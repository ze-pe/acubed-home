

<div class="a-container">

  <h1 class="three-a-header">Three A's of A Cubed Design</h1>
  <div class="cards">
    <div class="card">
      <div class="card-header">Accessible</div>
      <img class="card-image" src="https://cdn-icons-png.flaticon.com/512/5273/5273859.png" alt="hand reading a braille book">
      <p class="card-text">We value accessibility first and foremost. We aim to provide a product, which will be easily usable and well documented.</p>
    </div>
    <div class="card">
      <div class="card-header">Affordable</div>
      <img class="card-image" src="https://cdn-icons-png.flaticon.com/512/3146/3146459.png" alt="two hands holding a coin">
      <p class="card-text">Our braille display is slated to become the most easily obtainable product on the market.</p>
    </div>
    <div class="card">
      <div class="card-header">Accelerated</div>
      <img class="card-image" src="https://cdn-icons-png.flaticon.com/512/619/619175.png" alt="a flying rocket ship">
      <p class="card-text">We aim to accelerate the way blind individuals interface with their environment by adding plug and play features to our device.</p>
    </div>
  </div>

</div>


<style>
  .a-container {
    background-color: #292929;
    padding: 3em;
    box-sizing: border-box;
  }

  @media (max-width: 900px) {
    .cards {
      flex-wrap: wrap;
      justify-content: center;
    }
  }

  .cards {
    display: flex;
    font-size: 2em;
  }
  
  .card {
    margin: 2rem;
  }

  .three-a-header {
    margin-top: 2rem
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
    margin: 1.5rem 0;
    font-size: 1.2rem;
  }
</style>