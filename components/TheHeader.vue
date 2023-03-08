<template>
  <header id="header" class="l-header">
    <div class="l-header_cont">
      <h1 class="l-header_logo"><nuxt-link to="/"><img src="~/assets/img/logo.svg" alt=""></nuxt-link></h1>
      <nav class="l-header_nav">
        <ul class="l-header_nav_list">
          <li class="l-header_nav_item"><nuxt-link to="/" class="l-header_nav_link is-active">Works</nuxt-link></li>
          <li class="l-header_nav_item"><nuxt-link to="/about/" class="l-header_nav_link">About</nuxt-link></li>
          <li class="l-header_nav_item"><nuxt-link to="/admin/" class="l-header_nav_link"><img src="~/assets/img/icon_login.svg" alt="">Login</nuxt-link></li>
        </ul>
      </nav>
    </div>
  </header>
</template>