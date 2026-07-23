# Campus Pages

WayUp campus career pages, hosted on GitHub Pages. Each school has one self-contained
HTML page that can be shared directly with that school's career center.

## Live links

- Landing page: https://wayup-campus.github.io/Campus-Pages/
- Per campus: https://wayup-campus.github.io/Campus-Pages/&lt;file&gt;.html

| School | Link |
| --- | --- |
| University of Arizona | https://wayup-campus.github.io/Campus-Pages/University-of-Arizona.html |
| Arizona State | https://wayup-campus.github.io/Campus-Pages/arizona-state.html |
| Georgia Tech | https://wayup-campus.github.io/Campus-Pages/georgia-tech.html |
| University of Houston | https://wayup-campus.github.io/Campus-Pages/houston.html |
| Indiana University | https://wayup-campus.github.io/Campus-Pages/indiana.html |
| Maryland | https://wayup-campus.github.io/Campus-Pages/maryland.html |
| Michigan | https://wayup-campus.github.io/Campus-Pages/michigan.html |
| Rutgers | https://wayup-campus.github.io/Campus-Pages/rutgers.html |
| Texas A&M | https://wayup-campus.github.io/Campus-Pages/texas-am.html |
| Texas Tech | https://wayup-campus.github.io/Campus-Pages/texas-tech.html |
| UCF | https://wayup-campus.github.io/Campus-Pages/ucf.html |
| Illinois | https://wayup-campus.github.io/Campus-Pages/uiuc.html |

## Enabling GitHub Pages

Repo → **Settings** → **Pages** → Source: **Deploy from a branch** → Branch: **main** / **/ (root)** → Save.
The site publishes at `https://wayup-campus.github.io/Campus-Pages/` within a minute or two.

The `.nojekyll` file disables Jekyll processing so every file is served exactly as-is.

## Adding or updating a campus

Drop the new `<file>.html` at the repo root, add a row to `index.html` (the `campuses` array)
and to the table above, then commit and push. No build step.
