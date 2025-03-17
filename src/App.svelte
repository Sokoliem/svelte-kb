<script>
      import Header from './lib/Header.svelte';
      import Footer from './lib/Footer.svelte';
      import Navigation from './lib/Navigation.svelte';
    </script>

    <Header />
    <Navigation />
    <main>
      <slot></slot>
    </main>
    <Footer />
