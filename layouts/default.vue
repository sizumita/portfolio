<template>
  <div>
    <header>
      <ul class="header-parent">
        <router-link tag="li" to="/" class="header-children"><a class="button_hover">Home</a></router-link>
        <router-link tag="li" to="/works" class="header-children"><a class="button_hover">Works</a></router-link>
        <router-link tag="li" to="/about" class="header-children"><a class="button_hover">About Me</a></router-link>
        <router-link tag="li" to="/contact" class="header-children"><a class="button_hover">Contact</a></router-link>
      </ul>
    </header>
    <nuxt/>
    <footer>
      <div class="end"></div>
    </footer>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  color: rgb(204, 204, 204);
  background-color: rgb(0, 0, 25);
  font-size: 16px;
}

.header-parent {
  text-align: center;
  width: 100%;
  height: 100px;
  display: flex;
  padding-left: 0;
}

.header-children {
  flex-grow: 1;
  list-style: none;
  height: 100px;
}

.header-children a {
  color: rgb(204, 204, 204);
  height: 100%;
  width: 100%;
  display: block;
  display: -webkit-flex;
  display: flex;
  -webkit-align-items: center; /* 縦方向中央揃え（Safari用） */
  align-items: center; /* 縦方向中央揃え */
  -webkit-justify-content: center; /* 横方向中央揃え（Safari用） */
  justify-content: center; /* 横方向中央揃え */
  font-size: 25px;
  text-decoration: none;
}

.button_hover {
  -webkit-transition: 0.3s ease-in-out;
  -moz-transition: 0.3s ease-in-out;
  -o-transition: 0.3s ease-in-out;
  transition: 0.3s ease-in-out;
}


.button_hover:hover {
  background: rgba(255, 255, 255, 0.15);
  -webkit-transition: 0.3s ease-in-out;
  -moz-transition: 0.3s ease-in-out;
  -o-transition: 0.3s ease-in-out;
  transition: 0.3s ease-in-out;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}


.link_button {
  height: 50px;
  width: 100px;
  border: solid 2px limegreen;
  border-radius: 10px;
  margin: 10px;
}

.link_button a {
  width: 100%;
  height: 100%;
  display: block;
  display: -webkit-flex;
  display: flex;
  -webkit-align-items: center; /* 縦方向中央揃え（Safari用） */
  align-items: center; /* 縦方向中央揃え */
  -webkit-justify-content: center; /* 横方向中央揃え（Safari用） */
  justify-content: center; /* 横方向中央揃え */
  text-decoration: none;
  color: rgb(204, 204, 204);
  font-size: 20px;
}

.end {
  height: 200px;
}
</style>

