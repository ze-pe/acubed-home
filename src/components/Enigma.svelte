



<div class="enigma">
  <img src="./assets/enigma.png" alt="">
  <div class="enigma-text">
    <p class="title">Enigma Reader</p>
    <div class="sub-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Necessitatibus, nostrum? Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint asperiores est aliquid veniam eos! Eligendi repellendus in doloribus perferendis dolorem.</div>
  </div>
</div>





<style>
  .enigma {
    /* height: 360px; */
    display: flex;
    align-items: center;
  }

  @media (max-width: 900px) {
    .enigma {
      flex-wrap: wrap;
      justify-content: center;
    }
  }

  .enigma img {
    /* height: 88%; */
    width: 400px;
    border: 3px solid white;
    border-radius: 10px;
    margin: 2rem;
  }

  .enigma-text {
    margin: 0 auto;
    padding: 40px;
  }

  .title {
    font-size: 2.3em;
    font-weight: bold;
    margin: 20px;
    line-height: 1em;
  }

  .sub-text {
    margin: 20px;
    font-size: 1.4em;
  }
</style>