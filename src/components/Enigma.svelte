



<div class="enigma one">
  <img class="enigma-img" src="./assets/enigma.png" alt="">
  <div class="enigma-text">
    <p class="title">Enigma Reader</p>
    <div class="sub-text">The enigma braille reader is our signature device, which aims to be affordable and provide an expandable ecosystem for people who are blind to be able to plug and play new functionality into their braille device.</div>
  </div>
</div>





<style>
  .enigma {
    /* height: 360px; */
    display: flex;
    align-items: center;
    padding: 50px;
    width: 80%;
    margin: 0 auto;
    border-radius: 20px;
  }

  @media (max-width: 1000px) {
    .enigma {
      flex-wrap: wrap;
      justify-content: center;
    }
  }

  .enigma-img {
    /* height: 88%; */
    width: 400px;
    border: 3px solid white;
    border-radius: 10px;
    margin: 24px 54px;
    z-index: 1;
    box-shadow: 0 0 20px 15px #2929299a;

  }

  .enigma-text {
    /* margin: 0 auto; */
    /* padding: 40px; */
    z-index: 1;
  }

  .title {
    font-size: 3.5em;
    font-weight: bold;
    margin: 20px;
    line-height: 1em;
  }

  .sub-text {
    margin: 20px;
    font-size: 1.4em;
    line-height: 1.4em;
  }

  .one {
  /* background: rgb(78,6,111); */
  background: #8B85C1;
  box-shadow: inset  0px 0px 0px 8px #CDC392;
  position: relative;
}

.one::after,
.one::before {
  position: absolute; 
  content: '';
  width: 150px;
  height: 150px;
  background: #8B85C1;
  border-bottom: 4px solid #CDC392;
  bottom: -1em;
  z-index: 0;
}

.one::before {
  right: 50%;
  transform: skew(0, 20deg)
}

.one::after {
  left: 50%;
  transform: skew(0, -20deg)
}
</style>