# LSAIL GitHub Pages Site

The public site remains hosted by GitHub Pages. Content is stored in Jekyll
collections so it can be managed with CloudCannon without editing HTML.

## Content collections

- `_news`: announcements and updates
- `_people`: professor, current members, and alumni
- `_publications`: journal and conference publications
- `_patents`: patents and applications
- `_lectures`: courses
- `_albums`: gallery items

The editing interface is configured in `cloudcannon.config.yml`. CloudCannon
uploads images to `assets/uploads` and writes content updates back to this
repository. GitHub Pages then rebuilds the public website automatically.

## Connect CloudCannon

1. Create a CloudCannon account and choose **Create Site**.
2. Connect the GitHub repository `lsail-jnu/lsail-jnu.github.io`.
3. Select **Jekyll** as the static site generator.
4. Use the repository root as the source and `_site` as the output directory.
5. After the first build, open the **Website Content** collections to add or
   edit News, People, Publications, Patents, Lecture, and Album entries.

The existing GitHub Pages address and visual design do not need to change.
