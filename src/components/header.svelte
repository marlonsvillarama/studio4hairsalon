<header>
    <div class="logo">LOGO</div>

    <nav>
        <a href="/services">Services</a>
        <a href="/contact">Contact Us</a>
    </nav>
</header>

<style>
    header {
        background-color: white;
        border-bottom: 1px solid red;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0rem 5rem;
        /* width: 100%; */
        z-index: 999;
        position: relative;
    }
    .logo {
        /* position: absolute; */
        /* top: 0; */
        /* left: 5rem; */
        border: 1px solid green;
        height: 5rem;
        width: 15rem;
        color: white;
    }
    nav {
        border: 1px solid red;
    }
    nav a {
        /* color: white; */
        margin-left: 2rem;
        padding: 0.5rem 1.5rem;
        border: 1px solid green;
        transition: all 150ms ease-in-out;
    }
    nav a:hover {
        cursor: pointer;
        background-color: antiquewhite;
    }
</style>