<template>
  <div class="payment">
        <header class="payment__header">
          <h2 class="payment__title">Payments</h2>
          <div class="left">
            <button class="payment__header__button">
              <svg class="icon payment--icon">
                <use xlink:href="~/assets/sprite.svg#filter"></use>
              </svg>
              <span>Filter</span>
            </button>
            <button class="payment__header__button">
              <svg class="icon payment--icon">
                <use xlink:href="~/assets/sprite.svg#export"></use>
              </svg>
              <span>Export</span>
            </button>
            <button class="payment__header__button payment__header__button--create">
              <svg class="icon payment--icon">
                <use xlink:href="~/assets/sprite.svg#create"></use>
              </svg>
              <span>Create payment</span>
            </button>
          </div>
        </header>
        <div class="payment__tabs">
          <button class="payment__tabs--item payment__tabs--item-first">All</button>
          <button class="payment__tabs--item payment__tabs--item-selected">Succeeded</button>
          <button class="payment__tabs--item">Refunded</button>
          <button class="payment__tabs--item">Uncaptured</button>
        </div>
        <div class="payment__table">
          <div class="payment__table__header">
            <input id="success" type="checkbox" name="success" class="payment__table__header--item payment-checkbox">
            <h4 class="payment__table__header--item payment-amount payment__table__header--item--amount">Amount</h4>
            <h4 class="payment__table__header--item payment-header-label"></h4>
            <h4 class="payment__table__header--item payment-description payment__table__header--item--description">Description</h4>
            <h4 class="payment__table__header--item payment-email">Customer</h4>
            <h4 class="payment__table__header--item payment-date">Date</h4>
          </div>
          <div v-for="doc in docs" :key="doc.description">
            <listComponent :email="doc.Email" :description="doc.Description" :date="doc.Date" :amount="doc.Amount" />
          </div>
        </div>
        <footer class="payment__footer">
          <h3 class="payment__footer--text">16 <span>results</span></h3>
          <div>
            <button class="payment__footer__button payment__footer__button--previous" disabled>
              Previous
            </button>
            <button class="payment__footer__button">
              Next
            </button>
          </div>
        </footer>
      </div>
</template>

<script>
import listComponent from '@/components/listComponent.vue';
import docs from '@/store/data.json'
  export default {
    components: {
    listComponent,
  },
  data() {
    return {
      docs,
    }
  }
  }
</script>

