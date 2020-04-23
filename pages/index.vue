<template>
  <div class="container">
    <div class="big_blank"/>
    <img src="~/assets/icon.png" width="300" height="300"/>
    <div class="blank"/>
    <p class="title">Sumito Izumita</p>
    <div class="blank"/>
    <div class="headline">Nicknames</div>
    <div class="blank"/>
    <div class="columns">
      <div class="column">sizumita</div>
      <div class="column">Sumidora</div>
    </div>
    <div class="big_blank"/>
    <div class="headline">Self Introduction</div>
    <div class="blank"/>
    <p>新高校2年生になりました。</p>
    <p>長野県の安曇野市というところに住んでいます。</p>
    <p>最近はいろいろ、主にAtCoderに力を入れています。</p>
    <p>今後の目標は、AtCoderで水色になる・OCamlで言語を作ることです。</p>
    <div class="big_blank"/>
    <div class="headline">Skills</div>
    <div class="blank"/>
    <div class="columns">
      <div class="column">OCaml</div>
      <div class="column">Python</div>
    </div>
    <div class="big_blank"/>
    <div class="headline">Tools</div>
    <div class="blank"/>
    <div class="columns">
      <div class="column">PyCharm</div>
      <div class="column">WebStorm</div>
      <div class="column">Visual Studio Code</div>
    </div>
    <div class="columns">
      <div class="column">Mac Book Pro 2018</div>
      <div class="column">iPhone XR</div>
      <div class="column"> Apple Watch Series 5 (44mm)</div>
    </div>
    <div class="big_blank"/>
    <div class="headline">Links</div>
    <div class="blank"/>
    <div class="columns">
      <div class="link_button"><a href="https://github.com/sizumita">GitHub</a></div>
      <div class="link_button"><a href="https://qiita.com/sizumita">Qiita</a></div>
      <div class="link_button"><a href="https://twitter.com/sizumita">Twitter</a></div>
    </div>
  </div>
</template>

<style>
.container {
  text-align: center;
}

.title {
  font-size: 30px;
}

.headline {
  font-size: 50px;
  font-weight: bold;
}

.columns {
  display: -webkit-flex;
  display: flex;
  justify-content: center;
}

.column {
  text-align: center;
  padding: 15px;
  font-size: 20px;
  margin: 5px;
  background: rgba(0, 106, 119, 0.4);
  border-radius: 5px;
}

.blank {
  height: 30px;
}

.big_blank {
  height: 60px;
}
</style>


