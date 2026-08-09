[![Netlify Status](https://api.netlify.com/api/v1/badges/eb096afd-7cad-44d9-8916-b6c031763198/deploy-status)](https://app.netlify.com/sites/azurebootcamp/deploys)

# Azure Bootcamp Switzerland

Source content and configuration for the [Azure Bootcamp Switzerland](https://azurebootcamp.ch) website. Azure Bootcamp Switzerland is a community-driven, non-profit conference for the Microsoft Azure community.

The site is built with the [Hugo](https://gohugo.io/) static site generator, uses the [Congo](https://github.com/jpanther/congo) theme, and is deployed through [Netlify](https://www.netlify.com/).

## Prerequisites

- [Git](https://git-scm.com/)
- Hugo Extended 0.158.0 or later

The theme and gallery shortcode are Git submodules. Clone the repository with its submodules, or initialise them after cloning:

```sh
git submodule update --init --recursive
```

## Local development

Run the Hugo development server:

```sh
hugo server --buildDrafts
```

The site is available at the local URL shown by Hugo, typically `http://localhost:1313/`. Hugo rebuilds the site when content or configuration files change.

To create a production build, run:

```sh
hugo
```

The generated site is written to `public/`, which is intentionally not tracked by Git.

## Content and configuration

- `content/` contains pages, event archives, sessions, sponsor information, and other site content.
- `config/_default/` contains the Hugo configuration.
- `static/` contains files served without processing.
- `layouts/` contains site-level layout overrides.
- `themes/` contains the Congo theme and gallery shortcode submodules.

## Deployment

Netlify builds the site with `hugo` and publishes the `public/` directory. The configured Hugo version is 0.158.0.

## License

Unless explicitly stated otherwise, this site's content is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE).

Hugo is released under the [Apache License 2.0](https://gohugo.io/about/license/). The Congo theme is released under the [MIT License](https://github.com/jpanther/congo/blob/stable/LICENSE).
