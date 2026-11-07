# Utviklerens fremtid

En Slidev-presentasjon av Vegard Haugland om hvordan AI påvirker
utviklerhverdagen. Presentasjonen uttrykker hans egne tanker og meninger.

## Kom i gang

Krever [Bun](https://bun.sh/).

```sh
bun install
bun run dev
```

Åpne adressen som vises i terminalen.

## Bygg og publisering

```sh
bun run build
```

Nettstedet bygges til `dist/`, uten foredragsnotater.

### GitHub Pages

Workflowen i `.github/workflows/deploy-pages.yml` bygger med Bun og publiserer
`dist/` ved push til `main`. Den kan også startes manuelt fra Actions-fanen.

Velg **Settings → Pages → Build and deployment → Source → GitHub Actions**
i GitHub-repoet før første kjøring.

Presentasjonen publiseres på:
<https://v3gard.github.io/utviklernes-fremtid/>

YouTube-videoene krever internettilgang.

## Innhold

- `slides.md` – presentasjonen
- `components/` og `style.css` – komponenter og utseende
- `public/` – bilder og andre ressurser
