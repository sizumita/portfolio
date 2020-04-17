<template>
  <div>
    <div class="contents">
      <div class="content">
        <a href="https://www.youtube.com/watch?v=rW57i1ZSksA"><img src="~/assets/tea.png"></a>
        <div class="content-title"><a class="url-content" href="https://www.youtube.com/watch?v=rW57i1ZSksA">Tea</a></div>
        <p class="date">2019 / 11 / 13</p>
        <p class="text">未踏ジュニアで開発した、経済シミュレーションのためのPluginシステムと、それを使用したゲームです。</p>
      </div>
      <div class="content">
        <a href="https://github.com/sizumita/Aegis"><img src="~/assets/aegis.png"></a>
        <div class="content-title"><a class="url-content" href="https://github.com/sizumita/Aegis">Aegis</a></div>
        <p class="date">2019 / 11 / 22</p>
        <p class="text">多機能・高性能を目指したDiscord Botです。</p>
      </div>
      <div class="content">
        <a href="https://qiita.com/sizumita/items/b98f21c20793ff791ac0"><img src="~/assets/aimai.png"></a>
        <div class="content-title"><a class="url-content" href="https://qiita.com/sizumita/items/b98f21c20793ff791ac0">Aimai</a></div>
        <p class="date">2020 / 02 / 18</p>
        <p class="text">COTOHA APIのコンテストのために作成した、曖昧な構文でも書ける日本語プログラミング言語です。</p>
      </div>
    </div>
  </div>
</template>

<style>

.contents {
  display: -webkit-flex;
  display: flex;
  flex-wrap: wrap;
  padding-left: 50px;
  padding-right: 50px;
  justify-content: space-evenly;
}

.content {
  height: 400px;
  width: 300px;
  background: rgba(50, 205, 50, 0.2);
  margin-top: 50px;
  border: solid 2px limegreen;
  border-radius: 5px;
}

.content img {
  width: 100%;
  height: 150px;
}

.content-title {
  font-size: 30px;
  text-align: center;
  -webkit-transition: 0.3s ease-in-out;
  -moz-transition: 0.3s ease-in-out;
  -o-transition: 0.3s ease-in-out;
  transition: 0.3s ease-in-out;
}

.content-title:hover {
  background: rgba(255, 255, 255, 0.15);
  -webkit-transition: 0.3s ease-in-out;
  -moz-transition: 0.3s ease-in-out;
  -o-transition: 0.3s ease-in-out;
  transition: 0.3s ease-in-out;
}

.url-content {
  color: rgb(204, 204, 204);
  text-decoration: none;
  height: 100%;
  width: 100%;
  display: flex;
  -webkit-align-items: center; /* 縦方向中央揃え（Safari用） */
  align-items: center; /* 縦方向中央揃え */
  -webkit-justify-content: center; /* 横方向中央揃え（Safari用） */
  justify-content: center; /* 横方向中央揃え */
}

.date {
  color: gray;
  padding-left: 15px;
  padding-top: 5px;
  padding-bottom: 5px;
}

.content p {
  font-size: 18px;
}

.text {
  padding: 5px;
}

</style>
