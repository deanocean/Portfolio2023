<template>
  <ul class="c-cardList">
    <li v-for="n in 10">
      <nuxt-link class="c-card" to="/work-detail/">
        <!-- <img src="~/assets/img/xxx.jpg" alt=""> -->
        <img class="c-card_img" src="https://picsum.photos/300/300" alt="">
        <p class="c-card_info">学校・教育 / 採用サイト<br>Movable Type / SCSS / HTML</p>
      </nuxt-link>
    </li>
  </ul>
</template>