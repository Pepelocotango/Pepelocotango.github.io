# Portal de Projectes de Pepelocotango

Aquest repositori conté la web personal del portafoli de projectes de **Pepelocotango**. Aquesta web funciona com un centre d'índex per a tots els repositoris de GitHub, proporcionant informació, enllaços als repositoris i accés directe a les últimes versions publicades (*releases*).

## Tecnologies utilitzades

- **[Astro](https://astro.build/)**: Framework web d'alt rendiment per a contingut estàtic.
- **[Tailwind CSS](https://tailwindcss.com/)**: Disseny modular i modern per a una interfície ràpida.
- **[GitHub Pages](https://pages.github.com/)**: Allotjament gratuït i fiable.

## Estructura del Portal

El portal està organitzat per mostrar targetes amb informació rellevant de cada projecte:
- **Títol i descripció**: Context de l'eina o aplicació.
- **Enllaç a GitHub**: Accés al codi font.
- **Enllaç a Releases**: Accés directe a la descàrrega de l'última versió estable.
- **Web Oficial**: (Opcional) Enllaç a la pàgina web dedicada del projecte.

## Desenvolupament

Per treballar en aquest portal localment:

1.  **Instal·lar dependències**:
    ```bash
    pnpm install
    ```

2.  **Iniciar el servidor de desenvolupament**:
    ```bash
    pnpm dev
    ```

3.  **Compilar per a producció**:
    ```bash
    pnpm astro build
    ```

## Desplegament

Aquest projecte es desplega automàticament a GitHub Pages mitjançant **GitHub Actions** cada vegada que es realitza un *push* a la branca `main`.
## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)
