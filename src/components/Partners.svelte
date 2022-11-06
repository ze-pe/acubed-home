<div class="container bg-braille">
    <h2 class="md text-center my-2 shadow">
        Our Partners
    </h2>
    <div class="container flex">
        <div>
            <img class="logo-image" src="/public/assets/osu-logo.png" alt="osu keenen center for entrepreneurship logo">
        </div>
        <div>
            <img class="logo-image" src="/public/assets/gen-usa-logo.svg" alt="generation usa logo">
        </div>
        <div>
            <img class="logo-image" src="/public/assets/see3d-logo.png" alt="see3d logo">
        </div>
        <div>
            <img class="logo-image" src="/public/assets/innovation-studio-logo.svg" alt="innovation studio logo">
        </div>
        <div>
            <img class="logo-image" src="/public/assets/school-for-the-blind-logo.png" alt="ohio state school for the blind logo">
        </div>
    </div>
</div>

<style>
.container {
    /* background-color: #292929; */
    margin: 0 auto;
    padding: 40px 0;
    width: 100%;
}

.bg-braille {
    background-image: url('/public/assets/unsplash-royalty-free-braille.jpg');
    background-position: 0 40%;
    background-size: cover;
}

.flex {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

.text-center {
    text-align: center;
}

.md {
    font-size: 4rem;
}

.my-2 {
    margin: 1.5rem 0;
    line-height: 1em;
}

.shadow {
    text-shadow: 1px 4px #292929;
}

.logo-image {
    width: 230px;
}

@media (max-width: 900px) {
    .container {
      flex-wrap: wrap;
      justify-content: center;
    }

    .logo-image {
        margin: 20px;
    }
  }
</style>