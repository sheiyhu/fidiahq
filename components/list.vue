<template>
   <div class="payment__table__body">
            <input type="ckeckbox" class="payment-checkbox" />
            <h4 class="payment-amount payment-amount-data">{{amount}}</h4>
            <button class="payment-label">
              <span>Succeeded</span>
              <svg class="icon payment-label-icon">
                <use xlink:href="sprite.svg#success"></use>
              </svg>
            </button>
            <h4 class="payment-description">{{description}}</h4>
            <h4 class="payment-email">{{email}}</h4>
            <h4 class="payment-date">{{date}}</h4>
            <h4 class="payment-icon">
              <svg class="payment-icon-icon">
                <use xlink:href="sprite.svg#more"></use>
              </svg>
            </h4>
          </div>
</template>

<template>

</template>

<script>
export default {
  props: {
    amount: {
      type: String,
      default: null,
    },
    description: {
      type: String,
      default: null,
    },
    date: {
      type: String,
      default: null,
    },
    email: {
      type: String,
      default: null,
    }
  },

}
</script>

<style>

</style>
