# WebTheme

Free, open-source website templates and themes, organized by technology and platform.

Explore reusable source code for websites, landing pages, blogs, portfolios, and online stores. Each published template includes setup instructions, preview images, and licensing information.

## Project Scope

WebTheme aims to cover the following technologies and platforms. Availability depends on published contributions; this list does not imply that templates are already available for every platform.

| Category | Technologies and Formats |
| --- | --- |
| Static Websites | HTML, CSS, JavaScript, Bootstrap, Tailwind CSS |
| React | React, Next.js |
| Vue | Vue, Nuxt |
| Svelte | Svelte, SvelteKit |
| Astro | Astro websites, blogs, and content-driven templates |
| WordPress | Classic themes, block themes, and child themes |
| Elementor | Page templates and template kits |
| Shopify | Liquid themes, sections, and snippets |
| Ghost | Handlebars themes |
| Other Platforms | Platform-specific themes added through contributions |

Templates may also be tagged by purpose, including landing pages, portfolios, blogs, business websites, dashboards, and eCommerce.

## Template Catalog

Published templates will be listed here with their source code, previews, demos, and licenses.

| Template | Technology | Preview | Live Demo | Source | License |
| --- | --- | --- | --- | --- | --- |
| Coming soon | — | — | — | — | — |

## Getting Started

### 1. Choose a Template

Browse the template catalog and select a template that matches your preferred technology.

### 2. Download the Source

Download the repository as a ZIP file, or clone it:

~~~bash
git clone https://github.com/02oai/webtheme.git
cd webtheme
~~~

Navigate to the selected template directory.

### 3. Follow the Template Instructions

Read the template's `README.md` for:

- Required software and supported versions
- Installation and development commands
- Configuration and environment variables
- Build and deployment instructions
- Platform dependencies
- Licensing and third-party asset requirements

Installation steps vary by template. Framework projects may require a build tool, while CMS themes may require installation through their respective platforms.

## Repository Structure

The repository follows this structure as templates are added:

~~~text
webtheme/
├── README.md
├── README.zh-CN.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── THIRD_PARTY_NOTICES.md
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows/
├── catalog/
│   └── templates.json
├── docs/
│   ├── getting-started.md
│   └── licensing.md
└── templates/
    ├── html/
    ├── react/
    ├── nextjs/
    ├── vue/
    ├── nuxt/
    ├── sveltekit/
    ├── astro/
    ├── wordpress/
    ├── elementor/
    ├── shopify/
    └── ghost/
~~~

Only categories containing published templates need to exist.

## Template Requirements

Each template should include:

- Complete source code
- A `README.md` with setup and usage instructions
- A `LICENSE` file identifying the applicable license
- A `template.json` file containing catalog metadata
- A representative preview image
- Dependency and compatibility information
- Attribution and licenses for third-party assets

Templates should work at common screen sizes, use semantic markup where applicable, and avoid including credentials or private configuration.

### Template Metadata

Example `template.json`:

~~~json
{
  "id": "html-starter-landing",
  "name": "Starter Landing",
  "version": "1.0.0",
  "category": "html",
  "stack": ["html", "css", "javascript"],
  "tags": ["landing-page", "responsive"],
  "license": "MIT",
  "demo": "",
  "preview": "preview.webp",
  "requires": {},
  "status": "stable"
}
~~~

Use an empty `demo` value when no live demo is available. Record required platform versions, plugins, or runtimes in `requires` and explain them in the template README.

## Usage and Licensing

Templates are available without a download fee. Your rights to use, modify, redistribute, or commercially deploy a template depend on its applicable license.

- The root `LICENSE` applies to original repository code unless otherwise specified.
- Templates with separate license notices are governed by those notices.
- Third-party dependencies retain their original licenses.
- Images, fonts, icons, and other assets may have different licensing terms.
- Demo content is included for reuse only when its license explicitly permits it.

Check the selected template's `LICENSE`, README, and attribution notices before use.

## Contributing

Contributions are welcome, including:

- Original website templates and themes
- Bug fixes and compatibility improvements
- Accessibility and responsive layout improvements
- Documentation and translations
- Preview images and working demo links

To contribute:

1. Open an issue to discuss substantial additions or changes.
2. Fork the repository and create a branch.
3. Add or update the template and its documentation.
4. Verify the relevant installation and build steps.
5. Submit a pull request describing the change and how it was tested.

Only submit code and assets that you have permission to distribute. Preserve all required copyright notices, licenses, and attribution.

## Issues and Template Requests

For bug reports, include:

- Template name and version
- Browser, runtime, or platform version
- Steps to reproduce the issue
- Expected and actual behavior
- Relevant screenshots or error messages

For template requests, describe the desired technology, use case, and essential features.

## Security

Do not include API keys, passwords, access tokens, customer data, or other sensitive information in templates or issue reports.

Follow the repository's security policy when one is available. Avoid disclosing exploitable vulnerabilities in public issues.

## Project Status

WebTheme is being developed incrementally. The template catalog is the reference for currently available templates.

Compatibility, maintenance status, and setup requirements are documented separately for each template.
