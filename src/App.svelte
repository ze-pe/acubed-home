<script>
  import Header from './components/Header.svelte';
  import Footer from './components/Footer.svelte';
  import Hero from './components/Hero.svelte';
  import ThreeA from './components/ThreeA.svelte';
  import Team from './components/Team.svelte';
  import Contact from './components/Contact.svelte';
</script>

<main>

  <Header />
  <Hero />
  <ThreeA />
  <Team />
  <Contact />
  <Footer />

</main>

<style>

  main {
    display: flex;
    flex-direction: column;
    min-height: 100vh;

    overflow-x: hidden;
  }
</style>
