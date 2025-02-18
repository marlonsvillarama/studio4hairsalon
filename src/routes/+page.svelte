<script>
    import Contact from "../components/contact.svelte";
    import Map from "../components/map.svelte";
</script>

<div class="hero" id="cover">
    <!-- <div class="mask"></div> -->
    <div class="wrapper content">
        <h1>Where artistry meets <span class="accent">precision</span></h1>
        <p>Indulge in the ultimate salon experience at <strong>Studio 4</strong> - where every moment is crafted just for you, every style is designed for your unique beauty, and you leave beaming with every visit.</p>
        <a href="/book" class="btn cta">BOOK NOW</a>
        <!-- <a href="/services" class="btn">Our Services</a> -->
    </div>
</div>

<section id="services" class="wrapper tileset">
    <!-- <h1>Our Services</h1> -->
    <!-- <div class="tileset"> -->
        <a href="/services#haircut">
            <div class="tile">
                <div id="haircut" class="bg-img"></div>
                <h2>Haircut</h2>
                <div class="sep"></div>
                <p>Precision haircuts that suit your lifestyle and personality</p>
                <!-- <div class="mask"></div> -->
            </div>
        </a>
        <a href="/services#colours">
            <div class="tile">
                <div id="colours" class="bg-img"></div>
                <h2>Colours</h2>
                <div class="sep"></div>
                <p>Customised hair colouring to highlight your individuality</p>
                <!-- <div class="mask"></div> -->
            </div>
        </a>
        <a href="/services#treatment">
            <div class="tile">
                <div id="treatment" class="bg-img"></div>
                <h2>Treatments</h2>
                <div class="sep"></div>
                <p>Keratin treatments that leave your hair silky, smooth, and revitalised</p>
                <!-- <div class="mask"></div> -->
            </div>
        </a>
        <a href="/services#other">
            <div class="tile">
                <div id="other" class="bg-img"></div>
                <h2>Other Services</h2>
                <div class="sep"></div>
                <p>Personalised customer care to make every visit enjoyable and relaxing</p>
                <!-- <div class="mask"></div> -->
            </div>
        </a>
    <!-- </div> -->
</section>

<section id="john">
    <div class="wrapper content">
        <p>Led by <span class="emp name">John Fernandez</span>, a seasoned professional with over 20 years of international experience, we bring world-class expertise and creativity to every client.</p>
        <p>John’s journey spans the vibrant salons of Dubai, the dynamic multi-franchise networks of the Philippines, and the innovative hair industry of New Zealand.</p>
        <p>This extensive background combines diverse techniques, global trends, and a passion for excellence to ensure you receive a look tailored specifically to your unique style.</p>
        <a href="/book" class="btn cta">BOOK NOW</a>
    </div>
</section>

<!-- CONTACT -->
<Contact />

<!-- MAP -->
 <Map />

<section id="reviews">
    <div class="wrapper">
        <div class="review">
            <p>"It was my first time in here and I experienced excellent service from John.  I love supporting local and believe me, he is one of the best hairstylist out here! Highly recommended! Got the perfect cut I wanted!"</p>
            <span class="reviewer">Josephine</span>
        </div>
        <div class="review">
            <p>"Highly recommended hairdresser! His expertise and attention to detail are impressive. I walked out with a look that exceeded my expectations..."</p>
            <span class="reviewer">Elizah May</span>
        </div>
        <div class="review">
            <p>"One of the best hairdressers in Palmy. I would highly commend him for being approachable and friendly. Got the haircut and hair color I wanted. Thank you kuya John! Will definitely come back."</p>
            <span class="reviewer">Janella</span>
        </div>
    </div>
</section>

<style>
    /* .hero {
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
    } */
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
        margin-bottom: 0.5rem;
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
        margin-bottom: 4rem;
    }
    #services {
        margin: 8rem auto;
    }
    #john {
        background-image: url('/images/john-white.webp');
        /* height: 35rem; */
        background-size: cover;
        background-position: 0 -2rem;
        /* z-index: -10; */
        width: 100%;
        /* margin-top: -10rem; */
        /* margin-bottom: 5rem; */
        position: relative;
        /* display: flex;
        align-items: center; */
        padding: 4rem 0 6rem;
        /* margin-bottom: 5rem; */
    }
    #john p {
        box-sizing: border-box;
        /* border: 1px solid red; */
        font-family: var(--font-sans);
        width: 80%;
        max-width: 60%;
        justify-content: flex-start;
        letter-spacing: 0.25px;
        font-weight: 300;
        font-size: var(--fs-md);
        letter-spacing: 0.75px;
        line-height: var(--fs-2xl);
        /* opacity: 0.6; */
        color: rgba(255, 255, 255, 0.75);
        /* padding-bottom: 2.5rem; */
    }
    /* #john .content > p:last-child {
        margin-bottom: 3.5rem;
    } */
    span.emp {
        font-weight: 700;
    }
    span.name {
        color: white;
    }
</style>