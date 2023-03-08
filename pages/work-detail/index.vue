<template>
    
    <article class="l-work">
      <div class="l-work_heading">
        <div class="l-work_heading_cont">
          <h1 class="l-work_ttl">関西大学　事務職員採用サイト</h1>
          <p class="l-work_date">2022.12.01</p>
        </div>
        <div class="l-work_info">
          <!-- <img src="~/assets/img/works/xxx.jpg" alt=""> -->
          <div class="l-work_mv">
            <img src="https://picsum.photos/1000/800" alt="">
          </div>
          <a class="l-work_sitelink" href="http://google.com" target="_blank" rel="noopener noreferrer">Visit Website<img src="~/assets/img/icon_outlink.svg" width="12"></a>
          <table class="l-work_table">
            <tr class="l-work_table_row">
              <th class="l-work_table_ttl">担当</th>
              <td class="l-work_table_cont">フロントエンド / CMS構築</td>
            </tr>
            <tr class="l-work_table_row">
              <th class="l-work_table_ttl">技術</th>
              <td class="l-work_table_cont">Movable Type / SCSS / HTML</td>
            </tr>
            <tr class="l-work_table_row">
              <th class="l-work_table_ttl">ジャンル</th>
              <td class="l-work_table_cont">学校・教育 / 採用サイト</td>
            </tr>
          </table>
          <div class="l-work_desc">
            関西大学の事務職員の採用サイトです。このサイトはMovable TypeでCMSの構築をさせていただきました。加えて、スクロールアニメーションなどを使い、より賑やかに感じにしました。
          </div>
        </div>
      </div>

      <div class="l-wrap">

      </div>

      <div class="l-work_video">
        <div class="l-wrap l-wrap--m">
          <div class="l-work_video_box">
            <iframe src="https://www.youtube.com/embed/3GE8B2XIRTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
        </div>
      </div>

      <div class="l-wrap l-wrap--m">
        <div class="l-work_pcCapture">
          <img src="https://picsum.photos/1000/2000" alt="">
        </div>
        <div class="l-work_spCapture">
          <img src="https://picsum.photos/1000/2000" alt="">
          <img src="https://picsum.photos/1000/2000" alt="">
          <img src="https://picsum.photos/1000/2000" alt="">
        </div>
      </div>

      <nuxt-link class="l-work_back" to="/">
        <span>←</span>
        <span>Back</span>
      </nuxt-link>
    </article>

</template>

<script>
export default {
  name: 'WorkDetail'
}
</script>
