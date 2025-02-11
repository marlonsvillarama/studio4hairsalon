<header>
    <div class="logo">Studio 4</div>

    <nav>
        <a href="/services">Services</a>
        <a href="/contact">Contact Us</a>
    </nav>
</header>

<style>
    header {
        /* background-color: rgba(47, 49, 50, 0.7); */
        background-color: transparent;
        border-bottom: 0px solid red;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0.5rem 5rem 0rem;
        /* width: 100%; */
        z-index: 999;
        position: relative;
    }
    .logo {
        /* position: absolute; */
        /* top: 0; */
        /* left: 5rem; */
        font-family: var(--font-logo);
        font-size: 6rem;
        /* border: 1px solid green; */
        line-height: 6rem;
        height: 5rem;
        width: 15rem;
        color: white;
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