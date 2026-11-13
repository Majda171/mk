# MK fotoateliér — veřejná ukázka pro GitHub Pages

Toto je **samostatná statická ukázka** návštěvnické části webu, bez PHP, databáze a administrace.

## Jak zveřejnit na GitHub Pages

1. Na GitHubu založ nový repozitář, například `mk-fotoatelier-ukazka`.
2. Nahraj **obsah této složky** přímo do kořene repozitáře: `index.html`, ostatní `.html`, složky `assets/` a `media/`. Nenahrávej nadřazenou složku jako jedinou podsložku.
3. V repozitáři otevři **Settings → Pages**.
4. V části **Build and deployment** zvol **Deploy from a branch**, větev **main**, složku **/(root)** a ulož.
5. Odkaz bude mít tvar `https://TVE_UZIVATELSKE_JMENO.github.io/mk-fotoatelier-ukazka/` (podle skutečného názvu repozitáře).

## Co je připraveno

- 7 funkčních HTML stránek: Úvod, Focení, Ceník, Portfolio, Fotokabina, Pronájem ateliéru, Kontakt.
- Animované logo v hero, 100svh hero, připravená smyčka videa.
- Automaticky přepínaná fotografie v úvodní slideshow a odkazy do portfolia.
- Galerie a zvětšování fotografií, mobilní menu, klikací mapa na Kontakt.
- Klárčiny původní texty, ceník uvedený pouze jako pracovní návrh, její dodané fotografie ve WebP.
- Příjemná teplá bílá, Inter + Montserrat a zlaté logo bez kruhu v hlavičce i patičce.

## Úvodní video

Až bude od Klárky video, vlož optimalizovaný soubor `uvod.mp4` do složky `media/`. Web ho začne používat v hero; nastavte vhodný záběr pro mobil. Pro lepší načítání doporučujeme MP4/H.264 se zvukovou stopou odstraněnou, video cca 15–25 sekund, a velikost optimalizovat před publikací.

## Co je pouze ukázka a na GitHub Pages nefunguje

- Skutečné rezervace, správa termínů, potvrzování plateb a automatické e-maily: pro tyto části je potřeba WEDOS s PHP a databází.
- Kontaktní formuláře nemohou bez backendu odesílat zprávy. V této ukázce jsou místo nich odkazy na telefon a Instagram.
- Správa fotografií a textů přes administraci není na GitHub Pages dostupná. Tyto soubory jsou výhradně statickou kopií.
- Uvedené ceny jsou **návrh k odsouhlasení**, ne závazná nabídka. U speciálního balíčku „Od bříška k miminku“ v původním zadání nesouhlasí tvrzení o úspoře 400 Kč se součtem cen MINI balíčků; před publikací je třeba tuto část upřesnit.
- Video, některé galerie, reference klientů, kompletní údaje o fotokabině a schválené odpovědi FAQ zatím nebyly dodány.
- Záměrně je vloženo `noindex,nofollow`, aby se pracovní ukázka neindexovala ve vyhledávačích.

## Bezpečnost

Na GitHub **nenahrávej** `config.php`, PHP soubory administrace, databázové soubory, hesla ani skutečné přihlašovací údaje. Tento balíček je neobsahuje.
