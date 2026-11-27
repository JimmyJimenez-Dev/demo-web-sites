# Demo Web Sites

**[English](#english) · [Español](#español)**

---

## English

Sample websites for small businesses and personal projects. Each folder is a complete, standalone demo of a different type of business.

> ⚠️ **All businesses in this repository are fictional.** These sites are demos to show my work. They are not real companies, and their forms do not send any data.

### Demos

| Demo | Type | Live site |
|------|------|-----------|
| [demo-alpine-ridge](demo-alpine-ridge/) | Residential HVAC company (bilingual EN/ES) | [View live](https://demo-web-site.jimmyjimenez.workers.dev/) |


### How the sites are built and hosted
- **Code:** static HTML, CSS and JavaScript, with no frameworks and no build step. Each site is a single `index.html` file.
- **Hosting:** Cloudflare Workers (free plan), connected to this repository. Every commit to `main` deploys automatically.
- **Cost for a real client:** hosting is free. The client only pays for their own domain (about $10–15 a year for a `.com`).

### Structure
```
demo-web-sites/
├── README.md
└── demo-alpine-ridge/
    ├── README.md
    └── index.html
```

### Built with AI
I build these sites with Claude (Anthropic) as a pair programmer. I define the business, the content and the requirements, then review, test and deploy every site myself.

---

## Español

Sitios web de muestra para pequeños negocios y proyectos personales. Cada carpeta es un demo completo e independiente de un tipo de negocio distinto.

> ⚠️ **Todos los negocios de este repositorio son ficticios.** Estos sitios son demos para mostrar mi trabajo. No son empresas reales y sus formularios no envían datos.

### Demos

| Demo | Tipo | Sitio en vivo |
|------|------|---------------|
| [demo-alpine-ridge](demo-alpine-ridge/) | Empresa de climatización residencial (bilingüe EN/ES) | [Ver en vivo](https://demo-web-site.jimmyjimenez.workers.dev/) |


### Cómo se construyen y se publican
- **Código:** HTML, CSS y JavaScript estáticos, sin frameworks ni proceso de build. Cada sitio es un solo archivo `index.html`.
- **Hosting:** Cloudflare Workers (plan gratis), conectado a este repositorio. Cada commit a `main` se publica automáticamente.
- **Costo para un cliente real:** el hosting es gratis. El cliente solo paga su propio dominio (unos $10–15 al año por un `.com`).

### Hecho con IA
Construyo estos sitios con Claude (Anthropic) como compañero de programación. Yo defino el negocio, el contenido y los requisitos, y después reviso, pruebo y publico cada sitio.
