<script>
  import "../app.css";
  import Footer from "../lib/homePageComponents/Footer.svelte";
  import Header from "../lib/homePageComponents/Header.svelte";
</script>

<div>
  <Header />

  <main>
    <slot />
  </main>

  <Footer />
</div>
