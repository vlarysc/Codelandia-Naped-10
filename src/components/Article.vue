<template>
  <article class="main-article">
    <div class="article-container">
      <section class="article-section">
        <div class="article-geral">
          <div class="pain">
            <div class="pain-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="deed-pool">
            <div class="deedpool-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="minecraft">
            <div class="minecraft-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="harry-potter">
            <div class="harry-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="super-natural">
            <div class="supernatural-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="dragon-ball">
            <div class="dragon-ball-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="one-piece">
            <div class="one-piece-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
          <div class="revisions">
            <div class="revisions-img"></div>
            <div class="description">
              <h4>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor...
              </p>
              <span>00/00/0000</span>
              <button class="btn-description">Ler notícias</button>
            </div>
          </div>
        </div>
        <div class="article-geral-1">
          <h2>Lorem ipsum dolor</h2>
          <hr />
          <div class="chihiro-img">
            <button id="btn-chihiro">Lorem</button>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
              eros tellus, malesuada et velit in, blandit molestie dolor.
            </p>
          </div>
          <div class="rede-social-img">
            <button id="btn-rede">Lorem</button>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
              eros tellus, malesuada et velit in, blandit molestie dolor.
            </p>
          </div>
          <div class="kratos-img">
            <button id="btn-kratos">Lorem</button>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
              eros tellus, malesuada et velit in, blandit molestie dolor.
            </p>
          </div>
        </div>
      </section>
    </div>
  </article>
</template>

<script>
export default {};
</script>

<style scoped>
.main-article {
  width: 100%;
  height: 200vh;
}

.article-container {
  padding: 2rem 4rem 0rem 4rem;
  max-width: 1440px;
  /* overflow: auto; */
  display: grid;
  grid-template-areas: "pain  deed  mine  harry  super dragon onde, revisions";
}

.article-section {
  display: flex;
}

.article-geral {
  width: 66%;
  height: 65%;
  overflow-x: hidden;
  overflow-y: scroll;
}

.article-geral::-webkit-scrollbar {
  width: 8px;
  border-radius: 4px;
  background-color: #282830;
}

.article-geral::-webkit-scrollbar-thumb {
  background-color: #8257e6;
  border-radius: 4px;
}

.pain-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/pain.png);
}

.pain {
  display: flex;
  grid-area: pain;
  width: 761px;
  height: 151px;
  box-sizing: border-box;
  margin-bottom: 40px;
}

.deedpool-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/deed-pool.png);
}

.deed-pool {
  grid-area: deed;
  width: 761px;
  display: flex;
  margin-bottom: 40px;
}

.minecraft-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/minecraft-vendas\ 1.png);
}

.minecraft {
  grid-area: mine;
  width: 761px;
  display: flex;
  margin-bottom: 40px;
}

.harry-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/harry-potter-wallpapers-desktop-86788224\ 1.png);
}

.harry-potter {
  grid-area: harry;
  width: 761px;
  display: flex;
  margin-bottom: 40px;
}

.supernatural-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/supernatural\ 1.png);
}

.super-natural {
  grid-area: super;
  width: 761px;
  display: flex;
}

.dragon-ball-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/dragon-ball.png);
}

.dragon-ball {
  grid-area: dragon;
  width: 761px;
  display: flex;
}

.one-piece-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/one-piece-luffy.png);
}

.one-piece {
  grid-area: one;
  width: 761px;
  display: flex;
}

.revisions-img {
  width: 200px;
  height: 151px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/revisions.png);
}

.revisions {
  grid-area: revisions;
  width: 761px;
  display: flex;
}

.description {
  display: flex;
  flex-direction: column;
  padding: 5px 20px 0px 20px;
}

.description > h4 {
  width: 72%;
  color: #fefbfb;
  font-family: "lexend deca", sans-serif;
  font-weight: 400;
  font-size: 0.8rem;
  margin-bottom: 10px;
}

.description > p {
  width: 52%;
  color: #c4c4c4;
  font-family: "inter", sans-serif;
  font-weight: 400;
  font-size: 0.6rem;
  margin-bottom: 10px;
}

.description > span {
  color: #c4c4c4;
  font-family: "inter", sans-serif;
  font-weight: 600;
  font-size: 0.6rem;
}

.btn-description {
  width: 100px;
  height: 25px;
  font-family: "inter", sans-serif;
  font-weight: 600;
  font-size: 0.8rem;
  border-radius: 3px;
  color: #fefbfb;
  background-color: #8257e6;
  border: none;
  margin-top: 10px;
}

.article-geral-1 {
  margin-left: 1.2rem;
}

.article-geral-1 > h2 {
  color: #fefbfb;
  margin-bottom: 10px;
  font-size: 1.5rem;
  font-weight: 400;
  font-family: "lexend deca", sans-serif;
}

.article-geral-1 > hr {
  width: 250px;
  border-color: #8257e6;
}

.chihiro-img {
  width: 338px;
  height: 250px;
  margin-top: 20px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/A-Viagem-de-Chihiro-chihiro-e-haku\ 1.png);
}

.chihiro-img > p {
  height: 2vh;
  width: 20vw;
  position: relative;
  color: #fefbfb;
  font-size: 0.8rem;
  font-weight: 400;
  font-family: "lexend deca", sans-serif;
  top: 150px;
  left: 1vw;
}

#btn-chihiro {
  position: relative;
  width: 4vw;
  height: 2.5vh;
  font-size: 0.6rem;
  font-family: "lexend deca", sans-serif;
  background-color: #8257e6;
  border-radius: 3px;
  border: none;
  color: #fefbfb;
  top: 5px;
  left: 1vh;
}

.rede-social-img {
  width: 338px;
  height: 250px;
  margin-top: 40px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/cena-do-filme-a-rede-social-2010-1547503577708_v2_1920x1204\ 1.png);
}

.rede-social-img > p {
  height: 2vh;
  width: 20vw;
  position: relative;
  color: #fefbfb;
  font-size: 0.8rem;
  font-weight: 400;
  font-family: "lexend deca", sans-serif;
  top: 150px;
  left: 1vw;
}

#btn-rede {
  position: relative;
  width: 4vw;
  height: 2.5vh;
  font-size: 0.6rem;
  font-family: "lexend deca", sans-serif;
  background-color: #8257e6;
  border-radius: 3px;
  border: none;
  color: #fefbfb;
  top: 5px;
  left: 1vh;
}

.kratos-img {
  width: 338px;
  height: 250px;
  margin-top: 40px;
  background: linear-gradient(360deg, #13131f 0%, rgba(19, 19, 31, 0) 100%),
    url(../assets/img/NarTrailer_Print09.max-1920x1200\ 1.png);
}

.kratos-img > p {
  height: 2vh;
  width: 20vw;
  position: relative;
  color: #fefbfb;
  font-size: 0.8rem;
  font-weight: 400;
  font-family: "lexend deca", sans-serif;
  top: 150px;
  left: 1vw;
}

#btn-kratos {
  position: relative;
  width: 4vw;
  height: 2.5vh;
  font-size: 0.6rem;
  font-family: "lexend deca", sans-serif;
  background-color: #8257e6;
  border-radius: 3px;
  border: none;
  color: #fefbfb;
  top: 5px;
  left: 1vh;
}

@media screen and (min-width: 1440px) {
  .article-container {
    padding: 2rem 11rem 0rem 11rem;
  }
}
</style>
