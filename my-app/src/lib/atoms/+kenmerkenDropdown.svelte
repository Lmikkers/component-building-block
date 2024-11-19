<script>

</script>

<details name="kenmerken">
    <summary>
        <img src="/assets/land-icon.svg" alt="icoon van wereldbol">
        Landherkomst
    </summary>
    <p>Nederland</p>
</details>


<details name="kenmerken">
    <summary>
        <img src="/assets/voeding-icon.svg" alt="Voeding icoon">
        Voeding
    </summary>
    <p>In de lente en zomer elke maand plantvoeding geven.</p>
</details>

<details name="kenmerken">
    <summary>
        <img src="/assets/temperatuur-icon.svg" alt="Voeding icoon">
        Temperatuur
    </summary>
    <p>In de winter minimaal 12 graden celsius en in de zomer maximaal 22°C.</p>
</details>

<details name="kenmerken">
    <summary>
        <img src="/assets/giftig-icon.svg" alt="Voeding icoon">
        Giftig
    </summary>
    <p>De Gynura is giftig voor huisdieren</p>
</details>

<details name="kenmerken">
    <summary>
        <img src="/assets/verpotten-icon.svg" alt="Voeding icoon">
        Verpotten
    </summary>
    <p>Ververs de aarde of verpot de Gynura elke 2 jaar in de lente. </p>
</details>

<details name="kenmerken">
    <summary>
        <img src="/assets/watergeven-icon.svg" alt="Voeding icoon">
        Watergeven
    </summary>
    <p>Een keer per week een goede scheut water; maar laat de grond wel licht opdrogen voordat je de volgende scheut geeft - zolang de grond maar niet helemaal uitdroogt. In de winter heeft de Gynura een stuk minder water nodig.</p>
</details>

<details name="kenmerken">
    <summary>
        <img src="/assets/zonlicht-icon.svg" alt="Voeding icoon">
        Zonlicht
    </summary>
    <p>Hoe meer zonlicht (maar niet direct in de zon!) de bladeren krijgen, hoe paarser ze kleuren.</p>
</details>

<details name="kenmerken">
    <summary>
        <img src="/assets/stekken-icon.svg" alt="Voeding icoon">
        Stekken
    </summary>
    <p>In de lente en zomer elke maand plantvoeding geven.</p>
</details>

<style>
    details {
        position: relative;
        width: 100%;
    }
    summary {
        display: flex;
        align-items: center;
       
        font-family: var(--sub-header-font);
        text-transform: uppercase;
        font-weight: 600;
        border-radius: var(--border-card);
       
        padding: 0.9375em;
        
        background-color: #fbc980;
        color: var(--main-color-brown); 
        transition: background-color 0.3s;
        cursor: pointer;
    }
    summary img {
        padding-right: 0.9375em;
    }
    summary:hover,
    details[open] summary,
    details[open] p {
      background-color: #f5c275;
    }
    details[open] summary {
        border-radius: 1em 1em 0 0 ;
    }

    details p {
        border-radius: 1em 1em 0 0 ;
        background-color: #fbc980;
        padding: 0.9375em;
        color: #000;
    }
    details[open] p {
        border-radius: 0em 0em 1em 1em ;
    }

    summary::after {
        content: "+";
        position: absolute;
        right: 0.9375em;
    }
    details[open] summary::after{
        content: "-";
    }
</style>