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
          <h3>Мадьяров Егор</h3>
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
      <!-- Colored FAB button -->
      <button class="mdl-button mdl-js-button mdl-button--fab mdl-button--colored">
        <i class="material-icons">add</i>
      </button>
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
  .mdl-layout__header
    background: url(assets/bg.jpg) center no-repeat
    background-size: cover
  .mdl-layout__header-row
    background: rgba(101, 115, 242, .3)

    h3
      margin-left: 25px
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
  
  .person__block
    display: flex
    flex-direction: row
  .logo-img
    width: 145px
    height: 145px
    z-index: 3
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

