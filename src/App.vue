<template>
  <div id="app" class="mdl-layout mdl-js-layout is-upgraded">
    <header class="mdl-layout__header">
      <div class="mdl-layout__drawer-button mdl-layout--small-screen-only">
        <!-- button for mobile nav -->
        <i class="material-icons">menu</i>
      </div>
      <div class="mdl-layout__header-row"></div>
      <div class="mdl-layout__header-row"></div>
      <div class="mdl-layout__header-row">
        <div class="person__block">
          <div class="logo-img">
            <div class="logo-img--photo"></div>
          </div>
          <div class="person__data">
            <h3>Мадьяров Егор</h3>
            <button class="mdl-button mdl-js-button mdl-button--raised">
              Резюме
            </button>
            <button class="mdl-button mdl-js-button mdl-button--raised">
              Резюме 1
            </button>
          </div>
        </div>
      </div>
      <div class="mdl-layout__header-row mdl-layout--small-screen-only"></div>

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
      <div class="mdl-card">
        <div class="mdl-card__title">
          <h2 class="mdl-card__title-text">Title</h2>
        </div>
        <div class="mdl-card__supporting-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sagittis pellentesque lacus eleifendinia...</div>
        <div class="mdl-card__actions mdl-card--border">
          <a href="" class="mdl-button mdl-button-colored mdl-js-button mdl-js-ripple-effect">Get Started</a>
        </div>
        <div class="mdl-card__menu">
          <button class="mdl-button mdl-button--icon mdl-js-button mdl-ripple-effect">
            <i class="material-icons">share</i>
          </button>
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
</style>

<style lang="sass">
  body
    font-family: 'Material Icons', sans, sans serif
  h3
    margin: 33px 0 15px
  .mdl-layout__header
    background: url(assets/bg.jpg) center no-repeat
    background-size: cover
    border-top: 4px solid #303f9f
  .mdl-layout__header-row
    background: rgba(101, 115, 242, .3)

  .mdl-layout__tab-bar-container
    background: rgba(101, 115, 242, .3)
    overflow: visible
    height: 72px
  .mdl-layout__tab-bar
    height: 72px
    padding: 0
    overflow: visible
    position: absolute
    top: 35px
    right: 20%
    width: auto
    box-shadow: 0 2px 2px 0 rgba(0,0,0,.14), 0 3px 1px -2px rgba(0,0,0,.2), 0 1px 5px 0 rgba(0,0,0,.12)

    .mdl-button--icon
      position: relative
      top: 10px
      margin-right: 25px
  
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
  .logo-img
    width: 145px
    height: 145px
    
  .logo-img--photo
    width: 100%
    height: 100%
    border-radius: 50% 
    background: url(assets/photo.jpg) center center no-repeat
    background-size: 150%

  .mdl-layout__tab
    height: 100%
    line-height: 25px
    display: flex
    flex-direction: column
    padding: 0 38px

    i
      padding-top: 15px

  .mdl-layout.is-upgraded .mdl-layout__tab.is-active::after
    background: white
    height: 5px

  main
    background: pink
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
        margin-left: 0
    
</style>

