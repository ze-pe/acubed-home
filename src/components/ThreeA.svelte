

<div class="a-container">

  <h1 class="three-a-header">Three A's of A Cubed Design</h1>
  <div class="cards">
    <div class="card">
      <div class="card-header">Accessible</div>
      <img class="card-image" src="/assets/braille2.png" alt="hand reading a braille book">
      <p class="card-text">We value accessibility first and foremost. We aim to provide a product, which will be easily usable and well documented.</p>
    </div>
    <div class="card">
      <div class="card-header">Affordable</div>
      <img class="card-image" src="/assets/money2.png" alt="two hands holding a coin">
      <p class="card-text">Our braille display is slated to become the most easily obtainable product on the market.</p>
    </div>
    <div class="card">
      <div class="card-header">Accelerated</div>
      <img class="card-image" src="/assets/rocket2.png" alt="a flying rocket ship">
      <p class="card-text">We aim to accelerate the way blind individuals interface with their environment by adding plug and play features to our device.</p>
    </div>
  </div>

</div>


<style>
  .a-container {
    /* background-color: rgba(41, 41, 41, .8); */
    padding: 100px;
    box-sizing: border-box;
  }

  @media (max-width: 1270px) {
    /* .a-container {
      margin: 0 4em;
    } */
    .three-a-header {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
  }

  .cards {
    display: flex;
  }
  
  .card {
    margin: 2em;
  }

  .three-a-header {
    margin-top: 2rem;
    font-size: 3.5em;
  }
  
  .card-header {
    font-size: 2rem;
    font-weight: bold;
    margin: 1.5rem auto;
  }

  .card-image {
    width: 200px;
  }

  .card-text {
    margin: 1.2em auto;
    line-height: 1.2em;
    font-size: 1.3rem;
  }

  @media (max-width: 870px) {
    .three-a-header {
      font-size: 2em;
      width: 175px;
      margin: 0 auto;
    }

    .card-header {
      font-size: 1.4em;
    }

    .card-text {
      font-size: 1.2em;
    }
  }
</style>