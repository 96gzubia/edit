# Lecture Studio

Local-first lecture editor. Export lecture continues to download a standalone HTML file without changing the published student app.

**Prepare publishing handoff** downloads a versioned JSON package containing the exact exported HTML, its SHA-256 checksum, and editor-entered catalog metadata. It does not publish or change `latest`.

Follow the [publishing guide](https://github.com/96gzubia/project-engineering-interactive/blob/main/PUBLISHING.md) to validate the package, review its deterministic destination, and explicitly publish from a clean student-app checkout. No GitHub credentials are requested by the editor.
