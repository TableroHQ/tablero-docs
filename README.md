# Tablero Documentation

Static HTML/CSS architecture documentation for **Tablero - The operating system for modern restaurants**.

This folder is prepared as the root of the `tablero-docs` GitHub repository. It contains the C4 architecture documentation, service breakdown, role and flow matrix, database design notes, REST API reference, and Kafka/outbox event catalog.

## Open Locally

Open `index.html` directly in a browser. The site is static and does not require a build step or local web server.

## Pages

- [Overview](https://tablerohq.github.io/tablero-docs/index.html)
- [C4 Architecture](https://tablerohq.github.io/tablero-docs/c4.html)
- [Services](https://tablerohq.github.io/tablero-docs/services.html)
- [Roles & Flows](https://tablerohq.github.io/tablero-docs/roles.html)
- [Database](https://tablerohq.github.io/tablero-docs/database.html)
- [API](https://tablerohq.github.io/tablero-docs/api.html)
- [Events](https://tablerohq.github.io/tablero-docs/events.html)

## Publish With GitHub Pages

1. Push this folder to a GitHub repository named `tablero-docs`.
2. Open the repository on GitHub.
3. Go to **Settings**.
4. Go to **Pages**.
5. Set **Source** to **Deploy from a branch**.
6. Set **Branch** to `main`.
7. Set **Folder** to `/root`.
8. Save.

The published site will be available at:

`https://tablerohq.github.io/tablero-docs/`

## Notes

- All pages use `style.css`.
- Internal links use clean GitHub Pages-friendly filenames.
- Current implementation notes distinguish implemented services from planned architecture.
- Event delivery wording reflects local outbox publisher workers; Kafka/Debezium CDC can be added later.
