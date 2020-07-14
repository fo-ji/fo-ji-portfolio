<template>
  <div id="app">
    <div class="header-outer">
      <header>
        <h1 class="site-title">
          <router-link to="/">fo-ji's Portfolio</router-link>
        </h1>
      </header>
      <nav id="gnav" class="header-nav">
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/about">About</router-link></li>
          <li><router-link to="/skill">Skill</router-link></li>
          <li><router-link to="/work">Work</router-link></li>
          <li><router-link to="/contact">Contact</router-link></li>
        </ul>
      </nav>
    </div>
    <router-view/>
    <div class="sns-box">
      <a href="https://twitter.com/foji89872898" target="_blank" class="sns-link">
        <i class="fab twitter-icon"></i>
      </a>
      <a href="https://github.com/fo-ji" target="_blank" class="sns-link">
        <i class="fab github-icon"></i>
      </a>
      <a href="https://qiita.com/fumiya1753" target="_blank" class="sns-link">
        <i class="fab qiita-icon"></i>
      </a>
    </div>
    <footer>
      <div class="copyright-box">©️ 2020 fo-ji</div>
    </footer>
  </div>
</template>

<style></style>
