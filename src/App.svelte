<script>
import Hero from "./lib/Hero.svelte";
import Footer from "./lib/Footer.svelte";

</script>

<main>
<Hero />
<Footer />
</main>

<style>
  :root {
    --clr-primary:hsl(223,87%,63%);
    --clr-secondary-pale:hsl(223,100%,88%);
    --clr-light-red:hsl(354,100%,66%);
    --clr-gray:hsl(0,0%,59%);
    --clr-dark-blue:hsl(209,33%,12%);

    --ff:'Libre Franklin', sans-serif;
    --fs:1.25rem;
    --fw-300:300;
    --fw-600:600;
    --fw-700:700;


  }

  /* reset */

*,
*::before,
*::after {
  box-sizing: border-box;
}

  main {
    display: flex;
    flex-direction: column;
    align-items:center;
    margin: 0 auto;
    line-height: 1.6;
    text-align: center;
    /* padding: 1em; */
    /* margin: 0 auto; */
    height: 100vh;
  }

  img {
  max-width: 100%;
  height: auto;
  display: block;
}


.split {
  display: flex;
  flex-direction: row;
}

@media (min-width: 40rem) {


}



</style>
