<template>
  <div id="app">
    <div class="nav">
      <img
        class="logo-left"
        src="https://nd95x20v95u1skvw616h3puj-wpengine.netdna-ssl.com/wp-content/uploads/2017/09/logo.png"
      >
      <ul class="nav-tabs">
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/about">About</router-link>
        </li>
      </ul>
      <div class="link-toggle">
        <i class="fas fa-bars"></i>
      </div>
    </div>
    <div class="content">
      <transition name="component-fade" mode="out-in">
        <router-view></router-view>
      </transition>
    </div>
  </div>
</template>

<style lang="scss" src="./assets/styles.scss" >
</style>
