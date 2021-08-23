<template>
  <header class="header">
        <div class="header__search">
          <svg class="icon">
            <use xlink:href="~/assets/sprite.svg#search"></use>
          </svg>
          <input id="search" type="text" name="search" class="header__search--input" placeholder="Search...">
        </div>
        <div class="header__nav">
          <a href="#" class="header__nav--link">
            <svg class="icon header__nav--icon">
              <use xlink:href="~/assets/sprite.svg#notification"></use>
            </svg>
          </a>
          <a href="#" class="header__nav--link">
            <svg class="icon header__nav--icon">
              <use xlink:href="~/assets/sprite.svg#help"></use>
            </svg>
          </a>
          <a href="#" class="header__nav--link">
            <svg class="icon header__nav--icon">
              <use xlink:href="~/assets/sprite.svg#avatar"></use>
            </svg>
          </a>
        </div>
      </header>
</template>

