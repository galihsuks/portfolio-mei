# Mei Anggraini Portfolio

This repository contains the source code for **Mei Anggraini's personal portfolio website**, available at [novitameilina.my.id](https://novitameilina.my.id/).

The website is designed to showcase Mei's work as an **SEO Writer**, **Content Writer**, and **Digital Marketing professional**. It highlights personal branding, service offerings, selected projects, published articles, contact information, and digital music-related creative work.

## Overview

This is a lightweight **static website** built with:

- HTML
- CSS
- JavaScript
- Bootstrap via CDN

The project includes:

- An **English homepage** at `/`
- An **Indonesian homepage** at `/id/`
- Custom styling in `css/style.css`
- Media assets stored in `img/` and `audio/`

## Features

- Bilingual portfolio pages
- Responsive desktop and mobile layout
- Project showcase for brand and content work
- Published writing showcase
- Audio preview section for music projects
- Contact section with external links
- SEO-friendly metadata, structured data, `robots.txt`, and `sitemap.xml`

## Project Structure

```text
.
|-- index.html
|-- id/
|   `-- index.html
|-- css/
|   `-- style.css
|-- img/
|-- audio/
|-- robots.txt
`-- sitemap.xml
```

## Running Locally

Because this is a static website, you can open it directly in a browser or serve it with any simple local server.

Example using VS Code Live Server or any static server:

```bash
# Example with Python
python -m http.server 8000
```

Then open:

- `http://localhost:8000/`
- `http://localhost:8000/id/`

## SEO Improvements Included

This project includes several on-page SEO improvements, such as:

- Localized page titles and meta descriptions
- Canonical URLs
- `hreflang` support for English and Indonesian pages
- Open Graph and Twitter card metadata
- JSON-LD structured data
- Image alt text improvements
- `robots.txt` and `sitemap.xml`

## Deployment

This project is intended to be deployed as a static website under:

- English: `https://novitameilina.my.id/`
- Indonesian: `https://novitameilina.my.id/id/`

## Notes

- The project currently uses CDN-based dependencies instead of a package manager workflow.
- Large media assets may still be optimized further for performance if needed.

## License

This project is intended for personal portfolio use unless stated otherwise by the repository owner.
