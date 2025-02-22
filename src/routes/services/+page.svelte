<script>
    import Price from "../../components/price.svelte";
</script>

<div class="hero" id="services">
    <!-- <div class="mask"></div> -->
    <div class="wrapper content">
        <h1>Our Services</h1>
        <!-- <p>Indulge in the ultimate salon experience at <strong>Studio 4</strong> - where every moment is crafted just for you, every style is designed for your unique beauty, and you leave beaming with every visit.</p> -->
        <!-- <a href="/book" class="btn cta">BOOK NOW</a> -->
        <!-- <a href="/services" class="btn">Our Services</a> -->
    </div>
</div>

<section id="service-grid" class="wrapper content">
    <div class="service">
        <h1>Haircut</h1>
        <Price label="Under 16 years old" price="25" />
        <Price label="Men/Women (Gold Card Holder)" price="30" />
        <Price label="Men's Haircut" price="35" />
        <Price label="Women's Haircut with blowdry" price="40" />
        <Price label="Hair wash (additional)" price="10" />
        <Price label="Hair iron (additional)" price="30" />
    </div>
    <div class="service">
        <h1>Colours</h1>
        <Price label="Root Colour" price="110" />
        <Price label="Hair Colour" price="110" />
        <Price label="With full head foils" price="220" range="true" />
        <Price label="With Keratin treatment" price="270" range="true" />
        <Price label="Root Colour" price="110" />
    </div>
    <div class="service">
        <h1>Treatment</h1>
        <Price label="Hair Spa" price="60" />
        <Price label="Keratin" price="170" />
        <Price label="No yellow Keratin" price="180" />
        <Price label="Kerabond" price="250" />
        <Price label="Permanent straightening" price="250" range="true" />
    </div>
    <div class="service">
        <h1>Other Services</h1>
        <Price label="Hair & Make-up" price="150" />
        <Price label="Hair & Make-up (Bride)" price="200" />
        <Price label="Hair styling" price="60" />
        <Price label="Eyebrow tattoo" price="200" />
        <Price label="Eyeliner tattoo" price="150" />
    </div>
</section>

<style>
    #service-grid {
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