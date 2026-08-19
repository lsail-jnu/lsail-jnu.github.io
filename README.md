# LSAIL GitHub Pages Site

The public site remains hosted by GitHub Pages. Content is stored in Jekyll
collections so it can be managed with Pages CMS without editing HTML.

## Content collections

- `_news`: announcements and updates
- `_people`: professor, current members, and alumni
- `_publications`: journal and conference publications
- `_patents`: patents and applications
- `_lectures`: courses
- `_albums`: gallery items

The editing interface is configured in `.pages.yml`. Pages CMS writes content
and uploaded images directly to this repository. GitHub Pages then rebuilds
the public website automatically.

## Connect Pages CMS

1. Install the free [Pages CMS GitHub App](https://github.com/marketplace/pages-cms)
   and grant access only to `lsail-jnu/lsail-jnu.github.io`.
2. Sign in at [app.pagescms.org](https://app.pagescms.org/) with GitHub.
3. Select the `lsail-jnu/lsail-jnu.github.io` repository and the `main` branch.
4. Open News, People, Publications, Patents, Lecture, or Album to add, edit,
   or remove an entry.
5. Save the entry. Pages CMS commits the change to GitHub, and GitHub Pages
   publishes the updated website automatically.

Images selected in People and Album can be uploaded through the editor. New
uploads are stored under `assets/uploads`.

The existing GitHub Pages address and visual design do not need to change.
