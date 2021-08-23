<template>
  <div class="sidebar">
      <div class="nav__main__item nav__main__item--store">
        <a href="#" class="nav__main__link">
          <div class="store-icon-box">
            <svg class="icon nav--icon store-icon">
            <use xlink:href="~/assets/sprite.svg#store"></use>
          </svg>
          </div>

          <span class="store-name">Store name</span>
          <svg class="chevron">
            <use xlink:href="~/assets/sprite.svg#chevron"></use>
          </svg>
        </a>
      </div>
      <nav class="nav">
        <div class="nav__main">
          <div class="nav__main__item nav__main__item--home">
          <a href="#" class="nav__main__link">
            <svg class="icon nav--icon">
              <use xlink:href="~/assets/sprite.svg#home"></use>
            </svg>
            <span>Home</span>
          </a>
          </div>
          <ul>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#payment"></use>
                </svg>
                <span>Payments</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>Reviews</span>
              </a>
            </li>
            <li class="nav__main__item mt-8">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>Disputes</span>
              </a>
            </li>
            <li class="nav__main__item mt-8">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>Top-ups</span>
              </a>
            </li>
            <li class="nav__main__item mt-8">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>Collected fees</span>
              </a>
            </li>
            <li class="nav__main__item mt-8">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>Transfers</span>
              </a>
            </li>
            <li class="nav__main__item mt-8">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>Payouts</span>
              </a>
            </li>
            <li class="nav__main__item mt-8">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                </svg>
                <span>All transactions</span>
              </a>
            </li>
            <li class="nav__main__item mt-24">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#balance"></use>
                </svg>
                <span>Balances</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#customer"></use>
                </svg>
                <span>Customers</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#connected"></use>
                </svg>
                <span>Connected accounts</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#product"></use>
                </svg>
                <span>Products</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#report"></use>
                </svg>
                <span>Reports</span>
              </a>
            </li>
          </ul>
        </div>
        <div class="nav__secondary">
          <ul>
            <li class="nav__main__item">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#developer"></use>
                </svg>
                <span>Developers</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#off"></use>
                </svg>
                <span>View test data</span>
              </a>
            </li>
            <li class="nav__main__item mt-12">
              <a href="#" class="nav__main__link">
                <svg class="icon nav--icon">
                  <use xlink:href="~/assets/sprite.svg#settings"></use>
                </svg>
                <span>Settings</span>
              </a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
</template>
