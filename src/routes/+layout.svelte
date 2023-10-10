<script>
  import "../app.css";
  import { Navbar, Footer } from "../components/index";
</script>

<svelte:head>
  <title>My Personal Blog</title>
  <link rel="stylesheet" href="https://cdn.simplecss.org/simple.min.css" />
</svelte:head>
<Navbar />
<slot />
<Footer />
