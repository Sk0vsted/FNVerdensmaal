Styleguide

/* Istedet for at bruge !important som følgende: */

        .visually-hidden {
            position: absolute !important;
            width: 1px !important;
            height: 1px !important;
            padding: 0 !important;
            margin: -1px !important;
            overflow: hidden !important;
            clip: rect(0,0,0,0) !important;
            white-space: nowrap !important;
            border: 0 !important;
        }

Så skal !important fjernes, da det er en dårlig ting at inkludere, og kan skabe forvirring i koden.


/* HUSK FLERE KOMMENTARER */

        Flere kommentarer kan skabe mere overskuelighed, og kan mindske navigationsbesværet


/* Farverne skal skrives i toppen til alle elementer, så det er nemmere at finde dem */


/* Ved f.eks. animationer, er det en god ide at skrive hvad de forskellige elementer i en animation linje gør */

        duration | timing-function | delay | iteration-count
        direction | fill-mode | play-state | name

        animation: 3s ease-in 1s 2 reverse both paused slidein;


/* Når man skal arbejde med media query, vil det være en god ide at inkludere det til telefonen før man inkluderer andre */


/* Lav mellemrum ved CSS'en på headers */

    Så f.eks. sådan her:

        h1,
        h2,
        h3 {
        font-family: sans-serif;
        text-align: center;
        }

    Istedet for sådan her:

        h1, h2, h3 {
        font-family: sans-serif;
        text-align: center;
        }

