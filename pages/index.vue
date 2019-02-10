<template>
  <b-container class="container" bg-light bg-expand>
    <div>
      <b-navbar class="navbar" toggleable="md" type="dark" variant="dark" string="top">
        <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

        <b-navbar-brand navbar position="relative">
          <img class="logo" src="https://i.imgur.com/eAvQcvd.png">
        </b-navbar-brand>

        <b-collapse is-nav id="nav_collapse">
          <b-navbar-nav>
            <b-nav-item href="#">關於我</b-nav-item>
            <b-nav-item href="#">網頁設計</b-nav-item>
            <b-nav-item href="#">產品企劃</b-nav-item>
            <b-nav-item href="#">社群行銷</b-nav-item>
            <b-nav-item href="#">視覺設計</b-nav-item>
            <b-nav-item href="#">內容專欄</b-nav-item>
            <b-nav-item href="#">聯絡我</b-nav-item>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
        </b-collapse>
      </b-navbar>

      <div class="container-fluid px-0">
        <div
          class="d-flex flex-column text-center justify-content-center align-items-center bg-banner"
        >
          <p class="text-white subtitle">Hi, I‘m</p>
          <h1 strong class="text-white title">Kerwin Yen</h1>
        </div>
      </div>
      <div class="bg-line-left"></div>
      <div class="bg-line-right"></div>
      <div class="line">
        <hr class=".style-six">
      </div>

      <b-container>
        <div class="p-3 mb-2 align-middle text-center p-3 mb-2">
          <h1>關於我</h1>
        </div>
      </b-container>
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <div class="introdction-title strong" col="8">
          <h2>臺北教育大學的四年</h2>
        </div>
        <div class="introdction-subtitle text-success">Published May 16, 2017</div>
        <b-row>
          <b-col>
            <div class="introdction-text">
              <p class>
                臣亮言：先帝創業未半，而中道崩殂。今天下三分，益州
                疲弊，此誠危急存亡之秋也。然侍衛之臣，不懈於內；忠志之
                士，忘身於外者，蓋追先帝之殊遇，欲報之於陛下也。誠宜開
                張聖聽，以光先帝遺德，恢弘志士之氣；不宜妄自菲薄，引喻
                失義，以塞忠諫之路也。宮中府中，俱為一體，陟罰臧否，不
                宜異同。若有作姦犯科，及為忠善者，宜付有司，論其刑賞，
                以昭陛下平明之治，不宜篇私，使內外異法也。
              </p>
            </div>
            <div>
              <b-button
                href="https://medium.com/@kevinyan/%E9%96%B1%E8%AE%80-%E6%80%9D%E8%80%83-ux-design-%E5%88%9D%E5%AD%B8%E8%80%85%E5%AD%B8%E7%BF%92%E6%89%8B%E5%86%8A-%E7%AC%AC%E4%B8%80%E7%AB%A0-d618ecb17651"
              >Read more</b-button>
            </div>
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic" col="4">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>
      <b-container>
        <div class="p-3 mb-2 align-middle text-center p-3 mb-2">
          <h1>網頁設計</h1>
        </div>
      </b-container>
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <div class="introdction-title strong" col="8">
          <h2>自學、自學、自學</h2>
        </div>
        <div class="introdction-subtitle text-success">Published May 16, 2017</div>
        <b-row>
          <b-col>
            <div class="introdction-text">
              <p class>
                臣亮言：先帝創業未半，而中道崩殂。今天下三分，益州
                疲弊，此誠危急存亡之秋也。然侍衛之臣，不懈於內；忠志之
                士，忘身於外者，蓋追先帝之殊遇，欲報之於陛下也。誠宜開
                張聖聽，以光先帝遺德，恢弘志士之氣；不宜妄自菲薄，引喻
                失義，以塞忠諫之路也。宮中府中，俱為一體，陟罰臧否，不
                宜異同。若有作姦犯科，及為忠善者，宜付有司，論其刑賞，
                以昭陛下平明之治，不宜篇私，使內外異法也。
              </p>
            </div>
            <div>
              <b-button
                href="https://medium.com/@kevinyan/%E9%96%B1%E8%AE%80-%E6%80%9D%E8%80%83-ux-design-%E5%88%9D%E5%AD%B8%E8%80%85%E5%AD%B8%E7%BF%92%E6%89%8B%E5%86%8A-%E7%AC%AC%E4%B8%80%E7%AB%A0-d618ecb17651"
              >Read more</b-button>
            </div>
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic" col="4">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container>
        <div class="p-3 mb-2 align-middle text-center p-3 mb-2">
          <h1>攝影剪輯</h1>
        </div>
      </b-container>
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <div class="introdction-title strong" col="8">
          <h2>Youtuber 的夢想</h2>
        </div>
        <div class="introdction-subtitle text-success">Published May 16, 2017</div>
        <b-row>
          <b-col>
            <div class="introdction-text">
              <p class>
                臣亮言：先帝創業未半，而中道崩殂。今天下三分，益州
                疲弊，此誠危急存亡之秋也。然侍衛之臣，不懈於內；忠志之
                士，忘身於外者，蓋追先帝之殊遇，欲報之於陛下也。誠宜開
                張聖聽，以光先帝遺德，恢弘志士之氣；不宜妄自菲薄，引喻
                失義，以塞忠諫之路也。宮中府中，俱為一體，陟罰臧否，不
                宜異同。若有作姦犯科，及為忠善者，宜付有司，論其刑賞，
                以昭陛下平明之治，不宜篇私，使內外異法也。
              </p>
            </div>
            <div>
              <b-button
                href="https://medium.com/@kevinyan/%E9%96%B1%E8%AE%80-%E6%80%9D%E8%80%83-ux-design-%E5%88%9D%E5%AD%B8%E8%80%85%E5%AD%B8%E7%BF%92%E6%89%8B%E5%86%8A-%E7%AC%AC%E4%B8%80%E7%AB%A0-d618ecb17651"
              >Read more</b-button>
            </div>
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic" col="4">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container>
        <div class="p-3 mb-2 align-middle text-center p-3 mb-2">
          <h1>內容專欄</h1>
        </div>
      </b-container>
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <div class="introdction-title strong" col="8">
          <h2>書寫的樂趣</h2>
        </div>
        <div class="introdction-subtitle text-success">Published May 16, 2017</div>
        <b-row>
          <b-col>
            <div class="introdction-text">
              <p class>
                臣亮言：先帝創業未半，而中道崩殂。今天下三分，益州
                疲弊，此誠危急存亡之秋也。然侍衛之臣，不懈於內；忠志之
                士，忘身於外者，蓋追先帝之殊遇，欲報之於陛下也。誠宜開
                張聖聽，以光先帝遺德，恢弘志士之氣；不宜妄自菲薄，引喻
                失義，以塞忠諫之路也。宮中府中，俱為一體，陟罰臧否，不
                宜異同。若有作姦犯科，及為忠善者，宜付有司，論其刑賞，
                以昭陛下平明之治，不宜篇私，使內外異法也。
              </p>
            </div>
            <div>
              <b-button
                href="https://medium.com/@kevinyan/%E9%96%B1%E8%AE%80-%E6%80%9D%E8%80%83-ux-design-%E5%88%9D%E5%AD%B8%E8%80%85%E5%AD%B8%E7%BF%92%E6%89%8B%E5%86%8A-%E7%AC%AC%E4%B8%80%E7%AB%A0-d618ecb17651"
              >Read more</b-button>
            </div>
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic" col="4">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <b-container>
      <div class="p-3 mb-2 align-middle text-center">
        <h1 class>聯絡我</h1>
      </div>
    </b-container>
  </b-container>
</template>

<script>
export default {
  data() {
    return {
      counter: 60,
      max: 100
    };
  },
  methods: {
    clicked() {
      this.counter = Math.random() * this.max;
      console.log("Change progress to " + Math.round(this.counter * 100) / 100);
    }
  }
};
</script>



<style>
hr.style-six {
  border: 0;
  height: 0;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  border-bottom: 3px solid rgba(255, 255, 255, 0.3);
}

.container {
  max-width: 100%;
  height: auto;
  margin: 0px;
  padding: 0px;
  z-index: -1;
}

.navbar {
  position: fixed;
  max-width: 100％;
  height: 40px;
  margin: 0px;
  padding: 0px;
  z-index: 99;
}

.background {
  max-width: 100%;
  height: 700px;
  margin: 0px;
  padding: 0px;
  z-index: -1;
  min-width: 30%;
}

.bg-line-left {
  position: absolute;
  height: 2px;
  width: 100px;
  margin: 0px;
  padding: 0px;
  z-index: 9;
  background-color: aliceblue;
  top: 363px;
  left: 400px;
}

.bg-line-right {
  position: absolute;
  height: 2px;
  width: 100px;
  margin: 0px;
  padding: 0px;
  z-index: 9;
  background-color: aliceblue;
  top: 363px;
  left: 780px;
}

.title {
  position: "absolute";
  top: 500px;
  left: 200px;
  z-index: 1;
  font-size: 300%;
}

.subtitle {
  position: "absolute";
  top: 800px;
  left: 400px;
  z-index: 1;
  font-style: italic;
}

.logo {
  hight: 30px;
  width: 30px;
}

.bg-banner {
  background-image: url("https://i.imgur.com/WCwXGbD.jpg");
  min-height: 100vh;
  background-size: cover;
}

.bg-color {
  background-size: cover;
  z-index: -5;
}

.introdction-pic {
  position: relative;
  height: 500px;
  width: auto;
}
</style>



