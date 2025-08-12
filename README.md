# re-R Lab Website (Jekyll + Data)

**Edit content without touching HTML.** Update YAML files in `_data/` via the GitHub web editor. Upload photos to `assets/uploads/`.

## Publish on GitHub Pages
1. Upload all files to your repository root.
2. Settings → Pages → Source: **Branch = main**, **Folder = /(root)**.
3. Open: `https://<your-id>.github.io/<repository-name>`.

## Edit content
- People: `_data/people.yml`
- Publications: `_data/publications.yml`
- News: `_data/news.yml`
- Projects: `_data/projects.yml`
- Research areas: `_data/areas.yml`
- Lab basics: `_data/lab.yml`
- Photos: `assets/uploads/` (e.g., `/assets/uploads/nam-profile.jpg`)

## Project site note
If your site is `https://<id>.github.io/re-R`, set `_config.yml` → `baseurl: "/re-R"`.
