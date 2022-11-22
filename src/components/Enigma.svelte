



<div class="enigma">
  <img class="enigma-img" src="./assets/enigma-lighter.png" alt="enigma reader">
  <div class="enigma-text">
    <p class="title">Enigma Reader</p>
    <div class="sub-text">The enigma braille reader is our signature device, which aims to be affordable and provide an expandable ecosystem for people who are blind to be able to plug and play new functionality into their braille device.</div>
  </div>
</div>





<style>
  .enigma {
    display: flex;
    align-items: center;
    padding: 50px;
    width: 75%;
    margin: 0 auto;
    background: hsla(282.2, 98.6%, 28.8%, 0.8);
    border-radius: 20px;
  }

  .enigma-img {
    width: 50%;
    border: 3px solid white;
    border-radius: 10px;
    margin: 24px 54px;
    z-index: 1;
    box-shadow: 0px 0px 10px 6px #292929;

  }
/* 
  .enigma-text {
    margin: 0 auto;
    padding: 40px;
    z-index: 1;
  } */

  .title {
    font-size: 3.5em;
    font-weight: bold;
    margin: 20px;
    line-height: 1em;
  }

  .sub-text {
    margin: 15px;
    font-size: 1.4em;
    line-height: 1.4em;
    text-align: center;
  }

@media (max-width: 1040px) {
    .enigma {
      flex-wrap: wrap;
      justify-content: center;
      border: none;
      background: none;
      box-shadow: none;
    }
    .title {
      margin: 0 auto;
    }
    .enigma-img {
      width: 275px;
    }
  }
 
  @media (max-width: 870px) {
    .title {
      font-size: 2em;
    }

    .sub-text {
      font-size: 1.2em;
    }
  }
</style>