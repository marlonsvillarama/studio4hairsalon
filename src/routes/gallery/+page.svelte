<script>
    import Price from "../../components/price.svelte";
</script>

<div class="hero" id="services">
    <!-- <div class="mask"></div> -->
    <div class="wrapper content">
        <h1>Gallery</h1>
        <!-- <p>Indulge in the ultimate salon experience at <strong>Studio 4</strong> - where every moment is crafted just for you, every style is designed for your unique beauty, and you leave beaming with every visit.</p> -->
        <!-- <a href="/book" class="btn cta">BOOK NOW</a> -->
        <!-- <a href="/services" class="btn">Our Services</a> -->
    </div>
</div>

<section id="gallery-grid" class="wrapper content">
</section>

<style>
    #gallery-grid {
        box-sizing: border-box;
        position: relative;
        margin: 4rem auto;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        /* border: 1px solid red; */
        /* row-gap: 3rem; */
        column-gap: 6rem;
        row-gap: 4rem;
    }
    .service h1 {
        color: var(--color-accent);
        font-size: var(--fs-3xl);
        font-family: var(--font-notosans);
        font-weight: 700;
        border-bottom: 2px solid var(--color-accent);
    }
</style>