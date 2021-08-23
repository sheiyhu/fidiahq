<template>
<div class="container">
    <header class="header">
      <img src="vector.png" alt="Spripr" srcset="">
    </header>
    <div class="signin">
      <h2 class="signin__title">Sign in to your account</h2>
      <form class="form">
        <div class="form__container">
          <label for="email" class="form__label">Email</label>
          <input id="email" type="email" class="form--input">
        </div>
        <div class="form__container">
          <label for="password" class="form__label">Password <a href="#" class="form__label--link">Forgot your
              password?</a></label>
          <input id="passsword" type="password" class="form--input">
        </div>
        <div class="form__checkbox">
          <input id="check" type="checkbox" class="form__checkbox--box">
          <label class="form__checkbox--label" for="check">Stay signed in for a week</label>
        </div>
        <button type="submit" class="form__btn">Continue</button>
      </form>
      <h4 center class="signin__alternative">Use single sign-on (SSO) instead</h4>
    </div>
    <footer class="footer">
      <h3 class="footer__text">Don’t have an account? <a href="#" class="footer__text--link">Sign up</a></h3>
        <ul class="footer__nav">
          <li class="footer__nav--item">&copy; Stripe</li>
          <li class="footer__nav--item">Contact</li>
          <li class="footer__nav--item">Privacy & terms</li>
        </ul>
    </footer>
  </div>
  </template>

  <style scoped>
  @import '~/assets/main.css';
  </style>
