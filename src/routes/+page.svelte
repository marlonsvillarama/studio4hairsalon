<script></script>

<div class="hero">
    <div class="mask"></div>
    <div class="wrapper content">
        <h1>Where artistry meets precision</h1>
        <p>Indulge in the ultimate salon experience at <strong>Studio 4</strong> - where every moment is crafted just for you, every style is designed for your unique beauty, and you leave beaming with every visit.</p>
        <button class="cta">Book an appointment now</button>
    </div>
</div>

<section id="services" class="wrapper">
    <h1>Our Services</h1>
    <div class="tileset">
        <a href="/services#haircut">
            <div class="tile">
                <h1>Haircut</h1>
                <div id="haircut" class="bg-img"></div>
                <div class="mask"></div>
            </div>
        </a>
        <a href="/services#colours">
            <div class="tile">
                <h1>Colours</h1>
                <div id="colours" class="bg-img"></div>
                <div class="mask"></div>
            </div>
        </a>
        <a href="/services#treatment">
            <div class="tile">
                <h1>Treatment</h1>
                <div id="treatment" class="bg-img"></div>
                <div class="mask"></div>
            </div>
        </a>
        <a href="/services#other">
            <div class="tile">
                <h1>Other Services</h1>
                <div id="other" class="bg-img"></div>
                <div class="mask"></div>
            </div>
        </a>
    </div>
</section>

<section id="blurb">john profile</section>

<section id="reviews" class="wrapper">reviews/testimonials</section>

<style>
    .hero {
        background-image: url('/images/action-01.webp');
        background-size: cover;
        background-position: 0 -5rem;
        z-index: -10;
        height: 60rem;
        width: 100%;
        margin-top: -10rem;
        margin-bottom: 5rem;
        position: relative;
        display: flex;
        align-items: center;
        margin-bottom: 5rem;
    }
    .mask {
        background-color: rgba(0, 0, 0, 0.5);
        z-index: 0;
        height: 60rem;
        width: 100%;
        margin-top: 0rem;
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
    }
    .content {
        /* background-color: antiquewhite; */
        font-size: var(--fs-lg);
        color: white;
        /* border: 1px solid green; */
        margin: 0 auto;
        z-index: 10;
        /* align-self: center; */
    }
    .content h1 {
        font-family: var(--font-serif);
        color: white;
        font-weight: 400;
        font-size: var(--fs-3xl);
        /* font-style: italic; */
        letter-spacing: 1px;
        margin-left: -0.25rem;
        margin-bottom: 1rem;
        line-height: var(--fs-4xl);
    }
    .content p {
        /* border: 1px solid red; */
        font-family: var(--font-sans);
        /* width: 80%; */
        max-width: 60rem;
        justify-content: flex-start;
        letter-spacing: 0.25px;
        font-weight: 300;
        line-height: var(--fs-2xl);
        opacity: 0.75;
        margin-bottom: 2.5rem;
    }
    button.cta {
        background-color: var(--color-red-flag-lite);
        padding: 1.5rem 2.5rem;
        border: none;
        border-radius: 0.75rem;
        font-size: var(--fs-xl);
        color: white;
        letter-spacing: 0.25px;
        transition: all 150ms ease-in-out;
    }
    button.cta:hover {
        background-color: var(--color-red-flag);
        cursor: pointer;
    }
</style>