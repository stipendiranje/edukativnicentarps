<!DOCTYPE html>
<html lang="sr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stipendiranje Studenata - Podrška za Uspeh</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="hero">
        <h1>Podrška studentima!</h1>
        <p>Pomozimo mladima koji se školuju daleko od kuće i grade svetliju budućnost.</p>
        <a href="#prijava" class="button">Prijavi se za stipendiju</a>
    </header>

    <section id="opis">
        <h2>Zašto pružamo podršku?</h2>
        <p>
            Naša misija je da budemo oslonac studentima koji su daleko od svojih domova i porodica, 
            a ulažu izuzetne napore da ostvare svoje obrazovne ciljeve. Ova stipendija namenjena je 
            devojkama i momcima, kojima želimo da olakšamo put ka uspehu i pružimo 
            podršku tamo gde je najpotrebnija. 
        </p>
        <p>
            Ako verujete u snagu obrazovanja i želite da napravite promenu, pozivamo vas da nam se pridružite 
            i donirate sredstva. Vaš doprinos će pomoći da mladi ljudi ostvare svoje snove i stvore svetliju budućnost 
            za sve nas.
        </p>
    </section>

    <section id="uslovi">
        <h2>Ko može da se prijavi?</h2>
        <ul>
            <li>Studenti fakulteta koji ne studiraju u svom gradu</li>
            <li>Minimalni prosek ocena: 8.5</li>
            <li>Studentkinje i studenti koji nisu obnovili godinu</li>
            <li>Kandidati sa nižim porodičnim primanjima ili oni koji su izgubili jednog roditelja</li>
        </ul>
    </section>

    <section id="prijava">
        <h2>Obrazac za prijavu</h2>
        <form action="mailto:edukativnicentarps@gmail.com" method="post" enctype="text/plain">
            <label for="ime">Ime i prezime:</label>
            <input type="text" id="ime" name="ime" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="fakultet">Naziv fakulteta:</label>
            <input type="text" id="fakultet" name="fakultet" required>

            <label for="prosek">Prosek ocena:</label>
            <input type="number" step="0.01" id="prosek" name="prosek" required>

            <label for="motivacija">Zašto vam je potrebna stipendija?</label>
            <textarea id="motivacija" name="motivacija" rows="4" required></textarea>

            <button type="submit">Pošalji prijavu</button>
        </form>
    </section>

    <footer>
        <p>Kontakt: <a href="mailto:edukativnicentarps@gmail.com">edukativnicentarps@gmail.com</a> | Telefon: +381 11 1234567</p>
    </footer>
</body>
</html>
