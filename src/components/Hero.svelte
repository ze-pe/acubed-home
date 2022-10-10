<div class="background">

</div>

<div class="hero-container">

  <div class="content">
    <div class="hero-left">
      <h1>A Cubed Design</h1>
      <p>We're aiming to tackle the braille literacy crisis by making it easier for blind individuals to acquire screen readers.</p>
    </div>
    <div class="hero-right">
      <iframe src="https://www.youtube.com/embed/1rPE22she0Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>
</div>


<style>
  .background {
    background: url("./assets/pixabay-royalty-free-printer-2.jpg") no-repeat;
    background-size: cover;
    background-position: center;
    background-color: hsla(282 78% 8% / 0.4); 

    background-blend-mode: darken;
    height: 750px;
    width: 100vw;
    z-index: -1;

    position: fixed;
  }

  .hero-container {
    height: 650px;
    width: 1200px;
    position: relative;

    margin: 0 auto;
    margin-top: 96px;

    display: flex;
    flex-direction: column;
    justify-content: center;

  }

  .content {
    display: flex;
    justify-content: center;
    align-items: center;

    text-align: left;

    backdrop-filter: blur(9px);
    background-color: #0004;
    border-radius: 10px;
    gap: 12px;

    height: 50%;

    padding: 22px;
  }

  iframe {
    width: 550px;
    aspect-ratio: 16/9;

  }
  

  h1 {
    margin: 14px;
    font-size: 4em;
    margin: 26px 0;
    font-family: 'Open Sans', sans-serif;
  }  

  * {
    font-family: 'Open Sans', sans-serif;
  }

  p {
    font-size: 1.7em;
    margin: 12px;
    line-height: 106%;
  }
</style>