<script>
    // import KenmerkenDropdown from '../lib/atoms/+kenmerkenDropdown.svelte';
    import Kenmerken from '../lib/molecules/+kenmerken.svelte';

</script>

<main>
    <section>
        <article>
            <h1>Beschrijving</h1>
            <p>De honderden kleine haartjes op de bladeren zorgen ervoor dat deze plant fluweelachtig aanvoelt. Zodra de knopjes van de kleine gele (helaas onaangenaam ruikende) bloempjes verschijnen, kun je ze beter uit de plant knippen voor ze uitkomen. Op deze manier kan de plant zijn energie beter steken in de mooie bladeren. Sproei de bladeren nooit af, anders krijgen ze bruine vlekken.</p>
        </article>
        <Kenmerken/>
    </section>
</main>


<style>
    main {
        position: relative;
        background-color: var(--main-color-green);
        width: 100vw;
        height: 100vh;
        overflow: hidden;
        padding: 2rem;

        display: flex;
        justify-content: center;
        align-items: center;
    }

    section {
        display: grid;
        /* grid-template-columns: 1fr 1fr; */
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        grid-gap: 2rem;
        width: 100%;
        background-color: #f9e9c2;
        border-radius: var(--border-bigCard);
        padding: 2em;
    }

    h1 {
        color: var(--main-color-brown);
        font-family: var(--header-font);
        font-size: 2em;
    }
</style>