# Hoforsgym – redesign

Statisk sajt: `index.html` + `style.css`. Inga beroenden, ingen build.

## Lägg upp på GitHub

```bash
cd hoforsgym
git init -b main
git add .
git commit -m "Redesign av hoforsgym.se"
gh repo create hoforsgym --public --source=. --push
```

Utan GitHub CLI: skapa ett tomt repo på github.com/new och kör sedan

```bash
git remote add origin https://github.com/DITT-ANVÄNDARNAMN/hoforsgym.git
git push -u origin main
```

## Publicera gratis

Repo → Settings → Pages → Branch: `main` / root. Sajten ligger då på
`https://DITT-ANVÄNDARNAMN.github.io/hoforsgym/`.

## Att göra

- Bilden hämtas just nu från den gamla sajtens server. Ladda ner den, lägg i `img/` och byt `src` i `index.html`, annars försvinner den om gamla sajten stängs.
- Sidorna Foton, Video, Hofors Atletklubb, Stadgar och Brukaravtal är inte med i denna version.
- Kontrollera priser och kontaktuppgifter mot ägaren innan lansering.
