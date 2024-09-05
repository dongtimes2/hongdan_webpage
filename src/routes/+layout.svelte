<script>
  import Banner from '$lib/components/Banner.svelte';
  import Footer from '$lib/components/Footer.svelte';
  import Header from '$lib/components/Header.svelte';
  import '../app.css';
</script>

<div>
  <Header />
  <Banner />
  <main>
    <slot />
  </main>
  <Footer />
</div>
