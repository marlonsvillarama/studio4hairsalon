<header>
    <a href="/"><div class="logo">Studio 4</div></a>

    <nav>
        <a href="/services">Services</a>
        <a href="/contact">Contact Us</a>
    </nav>
</header>

<style>
    header {
        /* background-color: rgba(47, 49, 50, 0.7); */
        /* background-color: rgba(218, 165, 32, 0.5); */
        /* background-color: transparent; */
        /* border-bottom: 1px solid red; */
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0.5rem 5rem 0.5rem;
        /* width: 100%; */
        z-index: 999;
        position: relative;
    }
    /* header nav {
        position: absolute;
        top: 50%;
        left: 0;
    } */
    /* header > * {
        border: 1px solid red;
    } */
    header a {
        cursor: pointer;
        /* border: 1px solid red; */
    }
    .logo {
        /* position: absolute; */
        /* top: 0; */
        /* left: 5rem; */
        font-family: var(--font-logo);
        font-size: 6rem;
        text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.7);
        /* border: 1px solid green; */
        line-height: 6rem;
        height: 5rem;
        /* width: 15rem; */
        color: white;
        transition: all 150ms ease-in-out;
    }
    .logo:hover {
        text-shadow: 4px 4px 4px rgba(0, 0, 0, 0.7);
        transform: scale(1.02);
        /* color: goldenrod; */
        /* box-shadow: var(--box-shadow); */
    }
    /* nav {
        border: 1px solid red;
    } */
    nav a {
        color: white;
        margin-left: 0.5rem;
        padding: 1rem 2rem;
        /* border: 1px solid green; */
        transition: all 150ms ease-in-out;
        font-size: var(--fs-sm);
        font-weight: 300;
    }
    nav a:hover {
        cursor: pointer;
        background-color: rgba(0, 0, 0, 0.3);
        border-radius: 0.5rem;
        /* font-size: var(--fs-md); */
        /* font-weight: 500; */
        /* text-decoration: underline; */
    }
</style>