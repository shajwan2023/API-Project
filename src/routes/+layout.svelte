<!-- Layout.svelte -->
<script>
  export let title;
  import Footer from "../components/footer.svelte";
  import Navbar from "../components/nav.svelte"
 import "./styles.css"
</script>

<main>
  <nav>
    <Navbar />
  </nav>

  <section>
    <slot></slot>
  </section>

  <footer>
   <Footer />
  </footer>
</main>


<style>

</style>