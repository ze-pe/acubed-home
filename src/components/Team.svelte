

<div class="a-container" id="team">
  <div>
    <div class="team-title">
      <h1 class="exec-team-heading"><span></span>Executive Team</h1>
    </div>
    <div class="cards">
      <div class="card">
        <div class="card-content">
          <img class="profile-pic" src="../../dist/assets/Garrett.png" alt="Garrett Carder">
          <h1>Garrett Carder</h1>
          <div class="job-title">CEO & Chief Engineer</div>
          <p>Graduating in 2023 from OSU with a Bachelor's in Computer Science, Garrett leads A Cubed Design in Business Development and Engineering Development</p>
          <div class="social-links">
            <a href="https://www.linkedin.com/in/garrettcarder317/" aria-label="garrett carder's linkedin page"><i class="fa fa-linkedin"></i></a>
            <a href="https://garrettcarder.com/" aria-label="garrett carder's website"><i class="fa fa-globe"></i></a>
            <a href="mailto:garrett@acubed.design" aria-label="garrett carder's email"><i class="fa fa-envelope"></i></a>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-content">
          <img class="profile-pic" src="../../dist/assets/Caroline.png" alt="Caroline Karbowski">
          <h1>Caroline Karbowski</h1>
          <div class="job-title">Chief Community Officer</div>
          <p>Graduate in 2022 of OSU with a Bachelor's in Biology, Caroline backs A Cubed Design with a Robust Community and Deep Knowledge of Blindness Accessibility</p>
          <div class="social-links">
            <a href="https://www.linkedin.com/in/caroline-karbowski-4a4073178/" aria-label="caroline karbowski's linkedin page"><i class="fa fa-linkedin"></i></a>
            <a href="https://see3d.org/" aria-label="see3d website"><i class="fa fa-globe"></i></a>
            <a href="mailto:caroline@acubed.design" aria-label="caroline karbowski's email"><i class="fa fa-envelope"></i></a>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-content">
          <img class="profile-pic" src="https://source.unsplash.com/random/100x102" alt="Enan Srivastava">
          <h1>Enan Srivastava</h1>
          <div class="job-title">Chief Operations Officer</div>
          <p>Graduate in 2022 of OSU with a Bachelor's in Economics, Enan is the driving force behind A Cubed Design's Strategy and Operations.</p>
          <div class="social-links">
            <a href="https://www.linkedin.com/in/enan-srivastava/" aria-label="enan srivastava's linkedin page"><i class="fa fa-linkedin"></i></a>
            <a href="https://enan.rocks/" aria-label="enan srivastava's website"><i class="fa fa-globe"></i></a>
            <a href="mailto:enan@acubed.design" aria-label="enan srivastava's email"><i class="fa fa-envelope"></i></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .a-container {
    background-color: rgb(35, 33, 133);
    box-sizing: border-box;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 3em;
  }

  .cards {
    display: flex;
    justify-content: center;
    gap: 2rem;
    height: auto;
    grid-template-columns: repeat(3, 1fr);
  }
  
  .card {
    background-color: rgb(28, 32, 94);
    border-radius: 10%;
    width: 300px;
    margin-bottom: 40px;
    font-size: 2em;
    display: flex;
    box-shadow: 0px 0px 5px #9cdffc;
  }

  .card-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem;
    flex: 1;
  }

  .exec-team-heading {
    font-size: 60px;
  }

  .profile-pic {
    width: 70%;
    border-radius: 50%;
    border: 5px solid;
  }

  h1 {
    font-size: 1.5rem;
    margin: 1.5rem 0;
  }

  span {
    padding: 70px;
    margin: 0px 20px;
    background-image: url('dist/assets/ACubedLogo.png');
    background-size: contain;
    background-position: 15%;
    background-repeat: no-repeat;
  }

  .job-title {
    padding: 0px 30px;
    font-size: 1rem;
    width: 100%;
    background-color: hsl(282 98% 29%);
  }

  p {
    margin: 1.5rem 0;
    font-size: 1rem;
    flex: 1;
  }

  .social-links {
    width: 60%;
    display: flex;
    justify-content: space-between;
  }

  a:hover {
    cursor: pointer;
  }

  @media (max-width: 950px) {
    .cards {
      flex-wrap: wrap;
      justify-content: center;
    }
  }
</style>