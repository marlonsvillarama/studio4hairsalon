<script>
    import Price from "../../components/price.svelte";
    import InputDate from "../../components/input_date.svelte";
    import InputText from "../../components/input_text.svelte";
    import Dropdown from "../../components/dropdown.svelte";

    let data = [
        { text: 'Option 1', value: 'option1' },
        { text: 'Option 2', value: 'option2' },
        { text: 'Option 3', value: 'option3' }
    ];
</script>

<div class="hero" id="book">
    <!-- <div class="mask"></div> -->
    <!-- <div class="wrapper content">
        <h1>Almost there...</h1>
        <p>We are still building our website, but you may now book your appointments here!</p>
        <a href="/book" class="btn cta">BOOK NOW</a>
    </div> -->
</div>

<section id="book-form" class="form">
    <h1>Booking Form</h1>

    <div class="col-2">
        <div class="summary">
            <h2>Permanent straightening</h2><br/>
            <p>Hair treatment to straigthen hair</p><br/>
            <p>Can take up to 2 hours</p>
        </div>

        <div>
            <div class="fieldgroup">
                <InputText id="firstName" label="First Name" required=true />
                <InputText id="lastName" label="Last Name" required=true />
                <InputDate id="bookDate" label="Appointment Date" />
                <!-- <InputText id="lastName" label="Preferred Time" /> -->
                <!-- <Dropdown id="options" label="Options" data={data} /> -->
            </div>
        </div>
    </div>

</section>

<style>
    #book-form {
        box-sizing: border-box;
        position: relative;
        margin: 4rem auto;
        width: 50%;
        min-width: 25rem;
        /* border: 1px solid red; */
        /* display: grid; */
        /* grid-template-columns: repeat(2, 1fr); */
        /* border: 1px solid red; */
        /* row-gap: 3rem; */
        /* column-gap: 6rem; */
        /* row-gap: 4rem; */
    }
    #book-form h1 {
        /* display: block; */
        color: var(--color-accent);
        font-size: var(--fs-2xl);
        font-family: var(--font-notosans);
        font-weight: 500;
        padding-bottom: 0.5rem;
        border-bottom: 2px solid var(--color-accent);
    }
    .summary {
        background-color: rgba(212, 173, 97, 0.1);
        border-radius: 0.5rem;
        border: 0;
        padding: 1.25rem 1.5rem;
    }
    .summary > h2 {
        font-size: var(--fs-lg);
        color: rgba(0, 0, 0, 0.7);
    }
    .summary > p {
        color: rgba(0, 0, 0, 0.5);
        font-size: var(--fs-sm);
        line-height: var(--fs-lg);
    }
</style>