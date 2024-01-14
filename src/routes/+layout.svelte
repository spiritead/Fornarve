<!-- här ska till att börja med header och footer läggas in  -->
<!-- behöver ordna global typsnitt -->
<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
    // import "../../style.css";
    import '$lib/style.css';
</script>

<Header/>

<slot>
    <main></main>
</slot>

<Footer />
<!-- <Footer/> -->