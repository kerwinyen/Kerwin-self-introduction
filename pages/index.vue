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
            <b-nav-item href="#">平面設計</b-nav-item>
            <b-nav-item href="#">內容專欄</b-nav-item>
            <b-nav-item href="#">聯絡我</b-nav-item>
          </b-navbar-nav>

          <b-nav-form>
            <b-form-input size="sm" class="mr-sm-2" type="text" placeholder="Search" right/>
            <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
          </b-nav-form>

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
      <div class="line"></div>
      <div class="cta-down">
        <img src>
      </div>
      <div class="p-3 mb-2 align-middle">
        <h1 class>Get into my brain</h1>
      </div>

      <b-container class="skill-bar" p-3 mb-2>
        <b-row>
          <b-col>
            <div col="4" position="relative">
              <h2 strong>網頁設計</h2>
            </div>
            <div col="8" position="relative">
              <b-progress :value="counter" :max="max" show-progress animated></b-progress>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container class="bv-example-row introdction-colum" p-3 mb-2>
        <b-row>
          <b-col>
            <div class="introdction-title strong" col="8">
              <h2>關於我</h2>
            </div>
            <div class="introdction-subtitle text-success">Published May 16, 2017</div>
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
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <b-row>
          <b-col>
            <div class="introdction-title strong">
              <h2 href>網頁設計</h2>
            </div>
            <div class="introdction-subtitle text-success">Published May 16, 2016</div>
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
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <b-row>
          <b-col>
            <div class="introdction-title strong">
              <h2>攝影剪輯</h2>
            </div>
            <div class="introdction-subtitle text-success">Published May 16, 2017</div>
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
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>
      <b-container class="p-3 mb-2 bv-example-row introdction-colum">
        <b-row>
          <b-col>
            <div class="introdction-title strong">
              <h2>內容專欄</h2>
            </div>
            <div class="introdction-subtitle text-success">Published May 16, 2017</div>
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
          </b-col>
          <b-col>
            <div class="p-3 mb-2 introdction-pic">
              <img src="https://i.imgur.com/dfAIbLq.jpg">
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div class="p-3 mb-2 align-middle">
      <h1 class>Collection</h1>
    </div>

    <b-card-group columns class="p-3 mb-2">
      <div>
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="p-3 mb-2 border border-secondary>"
        >
          <p
            class="card-text"
          >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <b-button href="#" variant="primary">Read more</b-button>
        </b-card>
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="p-3 mb-2 border border-secondary>"
        >
          <p
            class="card-text"
          >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <b-button href="#" variant="primary">Read more</b-button>
        </b-card>
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="p-3 mb-2 border border-secondary>"
        >
          <p
            class="card-text"
          >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <b-button href="#" variant="primary">Read more</b-button>
        </b-card>
      </div>
    </b-card-group>
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

.cta-down {
  top: 200 px;
  left: 300 px;
  z-index: 1;
}

.bg-color {
  background-size: cover;
  z-index: -5;
}
</style>



