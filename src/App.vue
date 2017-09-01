<template>
  <div id="app" class="mdl-layout mdl-js-layout is-upgraded">
    <header class="mdl-layout__header">
      <div class="mdl-layout__tab-bar-container mdl-layout--large-screen-only"></div>
      <div class="mdl-layout__drawer-button mdl-layout--small-screen-only">
        <!-- button for mobile nav -->
        <i class="material-icons">menu</i>
      </div>
      <div class="mdl-layout__header-row"></div>
      <div class="mdl-layout__header-row"></div>
      <div class="mdl-layout__header-row">
        <div class="person__block">
          <div class="block-img">
            <div class="block-img--photo block-img--shadow"></div>
          </div>
          <div class="person__data">
            <h3>Мадьяров Егор</h3>
            <div class="person__button-group">
              <button class="mdl-button mdl-js-button mdl-button--raised">
                Резюме
              </button>
              <button class="mdl-button mdl-js-button mdl-button--raised">
                Резюме 1
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="mdl-layout__header-row mdl-layout--small-screen-only"></div>

      <div class="mdl-layout__tab-bar-container mdl-layout--large-screen-only"></div>
      <div class="mdl-layout__tab-bar-container mdl-layout--large-screen-only">
        <div class="mdl-layout__tab-bar mdl-ripple-effect mdl-color--primary-dark">
          <a href="" class="mdl-layout__tab is-active">
            <i class="material-icons">account_circle</i> <span>Главная</span>
          </a>
          <a href="" class="mdl-layout__tab">
            <i class="material-icons">filter</i> <span>Блог</span>
          </a>
          <a href="" class="mdl-layout__tab">
            <i class="material-icons">pets</i> <span>Пече</span>
          </a>
          <a href="" class="mdl-layout__tab">
            <i class="material-icons">receipt</i> <span>Контакты</span>
          </a>
          <button class="mdl-button mdl-js-button mdl-js-ripple-effect mdl-button--icon">
            <i class="material-icons">more_vert</i>
          </button>
        </div>
      </div>
    </header>
    <div class="mdl-layout__header-row mdl-layout--small-screen-only transparent"></div>
    <div class="mdl-layout__header-row mdl-layout--small-screen-only transparent"></div>
    <!-- mobile nav -->
    <div class="mdl-layout__drawer mdl-layout--small-screen-only">
      <nav class="mdl-navigation mdl-typography--body-1-force-preferred-font">
        <a href="" class="mdl-navigation__link"><i class="material-icons">account_circle</i><span>Главная</span></a>
        <a href="" class="mdl-navigation__link"><i class="material-icons">filter</i><span>Блог</span></a>
        <a href="" class="mdl-navigation__link"><i class="material-icons">pets</i><span>Пече</span></a>
        <a href="" class="mdl-navigation__link"><i class="material-icons">receipt</i><span>Контакты</span></a>
      </nav>
    </div>

    <main class="mdl-layout__content">
      <div class="mdl-grid">
        <div class="mdl-cell mdl-cell--4-col mdl-cell--12-col-tablet mdl-cell--12-col-phone">

            <div class="mdl-cell mdl-cell--12-col mdl-card mdl-shadow--4dp">
              <div class="mdl-card__title">
                <div class="mdl-card__title-text">
                  <i class="material-icons material-icons--info">public</i><h6>Обо мне</h6>
                </div>
              </div>
              <div class="info-block">
                <div class="mdl-card__supporting-text text--black">Верстальщик, front-end разработчик</div>
                <div class="mdl-card__supporting-text">Тут еще какая-то информация ключевая</div>
                <div class="mdl-card__supporting-text">Тут еще какая-то информация ключевая</div>
              </div>
              <div class="mdl-card__actions mdl-card--border">
                <a href="" class="mdl-button mdl-button-colored mdl-js-button mdl-js-ripple-effect">Подробнее</a>
              </div>
            </div>

            <div class="mdl-cell mdl-cell--12-col mdl-card mdl-shadow--4dp photo-block">
              <div class="mdl-card__title">
                <div class="mdl-card__title-text">
                  <i class="material-icons material-icons--info">camera</i><h6>Фотографии</h6>
                </div>
              </div>
              <div class="photo-block__gallery">
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
              </div>
              <div class="mdl-card__menu">
                <button class="mdl-button mdl-button--icon mdl-js-button mdl-js-ripple-effect">
                  <i class="material-icons">keyboard_arrow_down</i>
                </button>
              </div>
            </div>

            <div class="mdl-cell mdl-cell--12-col mdl-card mdl-shadow--4dp photo-block">
              <div class="mdl-card__title">
                <div class="mdl-card__title-text">
                  <i class="material-icons material-icons--info">collections</i><h6>Портфолио??</h6>
                </div>
              </div>
              <div class="photo-block__gallery">
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
                <div class="photo-block__wrap">
                  <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
                </div>
              </div>
              <div class="mdl-card__menu">
                <button class="mdl-button mdl-button--icon mdl-js-button mdl-js-ripple-effect">
                  <i class="material-icons">keyboard_arrow_down</i>
                </button>
              </div>
            </div>
        </div>

        <div class="mdl-cell mdl-cell--7-col">
          <div class="mdl-cell mdl-cell--12-col mdl-card mdl-shadow--6dp">
            <div class="mdl-card__title topic-1">
              <div class="block-img--avatar">
                <div class="block-img--photo"></div>
              </div>
              <div class="mdl-card__subtitle-block">
                <div class="mdl-card__subtitle-text mdl-card__subtitle-text--author">
                  Мадьяров Егор Тимурович
                </div>
                <div class="mdl-card__subtitle-text">
                  28 августа в 13:49
                </div>
              </div>

            </div>
            <!-- использовать в Блоге на фотографии фоном -->
            <div class="mdl-card__media">
              <img src="https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg" alt="">
              <!-- <div class="overlay middle center">
                <div class="overlay-inside">
                  <div>
                    <div class="news-box--title ">Какое-то название</div>
                    <hr>
                    <div class="news-box--subtitle">драмматическое описание</div>
                    <hr>
                    <div class="news-box--copyright">какое-то авторство</div>
                  </div>
                </div>
              </div> -->
            </div>

            <div class="info-block">
              <h4>Какое-то эпическое название</h4>
              <div class="mdl-card__supporting-text text--black">Краткое описание эпической темы в нескольких предложениях. Да так, чтобы я смог проверить на нескольких строчках мог проверить. Тренирую свой десятипальцевый слепой набор на русской йцукен раскладке. Пальцы пока путаются.</div>
            </div>
            <div class="mdl-card__actions mdl-card--border">
              <a class="mdl-button mdl-button--colored mdl-js-button mdl-js-ripple-effect">
                Подробнее
              </a>
              <div class="mdl-layout-spacer"></div>
              <button class="mdl-button mdl-js-button icon-button">
                <i class="material-icons">mode_comment</i>
              </button>
              <button class="mdl-button mdl-js-button icon-button">
                <i class="material-icons">share</i>
              </button>
              <button class="mdl-button mdl-js-button icon-button">
                <i class="material-icons">thumb_up</i>
              </button>

            </div>
            <div class="mdl-card__menu">
              <button class="mdl-button mdl-button--icon mdl-js-button mdl-js-ripple-effect">
                <i class="material-icons">keyboard_arrow_down</i>
              </button>
            </div>
          </div>
        </div>

      </div>
    </main>
  </div>
</template>

<script>
  require('material-design-lite')
  export default {
    name: 'app'
  }
</script>

<style src="material-design-lite/material.min.css"></style>
<style>
  @import url('https://fonts.googleapis.com/icon?family=Material+Icons');
  @import url('https://fonts.googleapis.com/css?family=Roboto');
</style>

<style lang="sass">
  body
    font-family: 'Roboto', sans-serif
  h3
    margin: 33px 0 15px
  h6, .mdl-card__subtitle-block
    margin: 0 0 0 10px
  img
    width: 100%
    height: 100%
  .icon-button
    min-width: auto
    width: 36px
    padding: 0
    & > i
      padding: 0
      color: rgba(48, 63, 159, .6)
  .text--black
    color: black
  .overlay
    position: absolute
    top: 0
    left: 0
    right: 0
    bottom: 0
    width: 100%
    height: 100%
    display: flex
    color: #fff
  .middle
    align-items: center
  .center
    text-align: center
    justify-content: center
  .overlay-inside
    margin: 0
    padding: 0
  .news-box
    &--title
      font-size: 36px
      line-height: 22px
    &--subtitle
      font-size: 21px
      line-height: 25px
    &--copyright
      margin-top: 10px
      font-size: 13px
      line-height: 18px

  .info-block
    padding: 0 16px
  .mdl-card
    margin: 8px auto
    &__media
      width: 100%
      padding-bottom: 66.8%
      position: relative
      overflow: hidden
      margin: auto
      img
        position: absolute
        top: 0
        bottom: 0
        width: 100%
        height: 100%
    &__supporting-text
      padding: 0 0 16px
    &__title-text
      align-items: center
    &__subtitle-text
      &--author
        font-weight: 600
        color: rgba(48, 63, 159,.8)
        margin-bottom: 5px
    &__actions
      display: flex
      align-items: center
      a
        color: rgba(48, 63, 159, .6)
        padding: 0 8px
    &__menu
      top: 21px
      i
        color: rgba(0,0,0,.44)

  .mdl-layout, .mdl-layout__content
    overflow: visible
  .mdl-layout
    margin: 0 auto
    max-width: 1280px
    &__content
      padding: 21px 21px 0px 21px
    &__header
      background: url(assets/bg.jpg) center no-repeat
      background-size: cover
      border-top: 4px solid #303f9f
    &__tab-bar
      height: 72px
      padding: 0
      overflow: visible
      position: absolute
      top: 35px
      right: 13%
      width: auto
      box-shadow: 0 2px 2px 0 rgba(0,0,0,.14), 0 3px 1px -2px rgba(0,0,0,.2), 0 1px 5px 0 rgba(0,0,0,.12)
    &__header-row
      background: rgba(101, 115, 242, .3)
    .transparent
      background: transparent
    &__tab-bar-container
      background: rgba(101, 115, 242, .3)
      overflow: visible
      height: 72px
      .mdl-button--icon
        position: relative
        top: 20px
        margin-right: 20px
    &__tab
      height: 100%
      line-height: 25px
      display: flex
      flex-direction: column
      padding: 0 38px
      i
        padding-top: 15px
    &.is-upgraded &__tab.is-active::after
      background: white
      height: 5px

  .person__block
    display: flex
    flex-direction: row
    z-index: 3
  .person__data
    margin-left: 25px
    .mdl-button
      margin-right: 15px
      &--raised
        background: rgba(255, 255, 255, 0.3)
        color: white
  .block-img
    width: 145px
    height: 145px
    &--avatar
      width: 45px
      height: 45px
    &--shadow
      box-shadow: 0px 11px 13px 1px rgba(0,0,0,0.14)
    &--photo
      width: 100%
      height: 100%
      border-radius: 50%
      background: url(assets/photo.jpg) center center no-repeat
      background-size: 150%


  .material-icons--info
    border: 7px solid #c9c9c9
    border-radius: 50px
    background: #c9c9c9
    color: white
    position: relative
    font-size: 28px
  .photo-block
    &__gallery
      display: flex
      flex-flow: row wrap-reverse
      padding-left: 2px
    &__wrap
      flex: auto
      width: 110px
      margin: 0 2px 2px 0
      img
        width: 100%
        height: auto
    &__image
      background: url(https://ep1.pinkbike.org/p6pb15019849/p6pb15019849.jpg) no-repeat
      background-position: center
      background-size: 200%
      width: 100%
      height: auto
    .mdl-grid
      padding: 0 0 0 2px
    .mdl-cell--4-col
      width: calc(33.3333333333% - 2px)
      margin: 0 2px 2px 0


  @media screen and (max-width: 1024px)
    .mdl-layout__header
      display: block
    .mdl-layout__header-row
      padding: 0
    .mdl-layout__drawer-button
      color: #fff
    .person__block
      flex-direction: column
      align-items: center
      margin: auto
      position: relative
      top: 10px // добавить теней фотографии

      h3
        color: black
        margin: 15px 16px 19px
    .person__data
      margin-left: 0
    .person__button-group
      display: flex
      justify-content: space-between
      .mdl-button
        margin-right: 0
        &--raised
          background: transparent
          color: #bfbfbf
          box-shadow: none
    .logo-img--photo
      box-shadow: 0px 11px 13px 1px rgba(0,0,0,0.14)

    .mdl-layout__content
      padding: 40px 0 0 0
</style>

