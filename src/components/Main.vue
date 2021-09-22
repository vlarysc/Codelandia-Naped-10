<template>
  <main class="main">
    <div id="main-container">
      <div id="main-background1">
        <section id="intro-section-1">
          <h1>Mundo nerd? Naped!</h1>
          <p>
            O Naped pode ser sua fonte de informações sobre o mundo nerd e
            outros assuntos relacionados.
          </p>
        </section>
      </div>
      <div id="main-background-2">
        <section class="intro-section-2">
          <div id="img-main-plus">
            <button id="btn-lorem">Lorem</button>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
              eros tellus, malesuada et velit in, blandit molestie dolor.
            </p>
          </div>
          <div class="imgs-pq">
            <div id="imgs-main-1">
              <button id="btn-imgs-1">Lorem</button>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </p>
            </div>
            <div id="imgs-main-2">
              <button id="btn-imgs-2">Lorem</button>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                eros tellus, malesuada et velit in, blandit molestie dolor.
              </p>
            </div>
          </div>
        </section>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style scoped>
.main-header {
  width: 100%;
}

#main-container {
  max-width: 100%;
  padding: 0rem 4rem 0rem 4rem;
  box-sizing: border-box;
}

#main-container {
    max-width: 1440px;
}

#main-background1 {
    max-width:1440px;

}

#intro-section-1 {
    max-width:1440px;
    width:18.8rem;
    margin-top: 6rem;
}

#intro-section-1 > h1{
    color: #fefbfb;
    font-size: 2.5rem;
    font-weight: 500;
    font-family: "lexend deca", sans-serif;
}

#intro-section-1 > p{
    width: 24.1rem;
    color: #c4c4c4;
    margin-top: 1.2rem;
    margin-bottom: 5rem;
    font-size: 1rem;
    font-family: "inter", sans-serif;
}

.intro-section-2{
    max-width: 1400px;
    max-width: 1440px;
    display: flex;
}

#main-background-2 {
    max-width: 1440px;
}

#img-main-plus{
    width: 761px;
    height: 350px;
    background-image:linear-gradient(360deg, #13131F 0%, rgba(19, 19, 31, 0) 100%), url(../assets/img/image01.png)
}

#img-main-plus > #btn-lorem {
    position: relative;
    width: 6vw;
    height: 4vh;
    font-family: "lexend deca", sans-serif;
    background-color: #8257e6;
    border-radius: 3px;
    border: none;
    color: #fefbfb;
    top: 20px;
    left: 30px;
}

#img-main-plus > p {
    width: 28vw;
    color: #fefbfb;
    position: relative;
    font-size: 1.2rem;
    font-weight: 400;
    font-family: "lexend deca", sans-serif;
    top: 224px;
    left: 30px;
}


.imgs-pq{
    display: flex;
    flex-direction: column;
    
}

#imgs-main-1 {
    width: 338px;
    height: 165px;
    margin-left: 1.3rem;
    margin-bottom: 1.2rem;
    background-repeat: no-repeat;
    background-size: contain;
    background-image:linear-gradient(360deg, #13131F 0%, rgba(19, 19, 31, 0) 100%), url(../assets/img/98677e90349dff1d04519b1cebc0d02a\ 1.png);
}

#imgs-main-1 > #btn-imgs-1{
    position: relative;
    width: 3vw;
    height: 2.5vh;
    font-size:0.6rem;
    font-family: "lexend deca", sans-serif;
    background-color: #8257e6;
    border-radius: 3px;
    border: none;
    color: #fefbfb;
    top: 15px;
    left: 2vh;
}

#imgs-main-1 > p{
    height: 2vh;
    width: 18vw;
    position: relative;
    color: #fefbfb;
    font-size:0.8rem;
    font-weight: 400;
    font-family: "lexend deca", sans-serif;
    top: 80px;
    left: 1vw;
}

#imgs-main-2{
    width: 338px;
    height: 165px;
    margin-left: 1.3rem;
    background-repeat: no-repeat;
    background-size: contain;
    background-image:linear-gradient(360deg, #13131F 0%, rgba(19, 19, 31, 0) 100%), url(../assets/img/ElTI-Q0UcAA3EFg\ 1.png)
}

#imgs-main-2 > #btn-imgs-2{
    position: relative;
    width: 3vw;
    height: 2.5vh;
    font-size:0.6rem;
    font-family: "lexend deca", sans-serif;
    background-color: #8257e6;
    border-radius: 3px;
    border: none;
    color: #fefbfb;
    top: 15px;
    left: 2vh;
}

#imgs-main-2 > p{
    height: 2vh;
    width: 18vw;
    position: relative;
    color: #fefbfb;
    font-size:0.8rem;
    font-weight: 400;
    font-family: "lexend deca", sans-serif;
    top: 80px;
    left: 1vw;
}

@media screen and (min-width: 1440px){
  #main-container {
  padding: 0rem 11rem 0rem 11rem;
}
}


</style>