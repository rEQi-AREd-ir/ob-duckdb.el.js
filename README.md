# paperfolio

<div align="center">

[![Preview](readme_preview/theme-preview.png)](https://example.github.io/paperfolio/)

**A calm, responsive theme for academic homepages — Jekyll powered.**

---

[![deploy](https://img.shields.io/badge/deploy-passing-brightgreen)](#)
[![Platforms](https://img.shields.io/badge/targets-linux%20%7C%20macOS%20%7C%20windows-blue)](#)
[![Runs on](https://img.shields.io/badge/runtime-ruby%20%2B%20node-9e363a)](#)

</div>

## Who uses it

The list keeps growing: researchers, lab groups and course pages all over the world run this theme for their landing pages, blogs, workshop sites and conference pages. Any of them can be added by opening a pull request.

<table>
<tr>
<td>Sample pages</td>
<td>
<a href="https://example.edu/~lab-a" target="_blank">★</a>
<a href="https://example.org/researcher-b" target="_blank">★</a>
<a href="https://example.net/group-c" target="_blank">★</a>
<a href="https://example.com/course-d" target="_blank">★</a>
<a href="https://example.io/workshop-e" target="_blank">★</a>
</td>
</tr>
</table>

## Speed

Bundled checks keep the Lighthouse score honest across releases:

- [lychee](https://lychee.cli.rs/) — broken-link sweep
- [Axe](https://github.com/dequelabs/axe-core) — accessibility pass, run by hand

The accessibility pass stays manual on purpose: most findings need judgement from someone familiar with web work.

## Index

* [Starting out](#starting-out)
* [Deploying](#deploying)
* [Shaping the site](#shaping-the-site)
* [What it ships with](#what-it-ships-with)
* [Common questions](#common-questions)
* [Sending patches](#sending-patches)
* [Star history](#star-history)
* [Licence](#licence)

## Starting out

Clone, install the ruby and node toolchains, drop your content into `_pages`, `_posts` and `_projects`.

## Deploying

Push to the default branch and let the bundled workflow publish, or run the build locally and copy the output.

## Shaping the site

Layout, colours and navigation live in `_config.yml`; social links and analytics keys sit beside them.

## What it ships with

### Light and dark

The theme follows the operating system preference out of the box, and the sun/moon control in the header flips it by hand.

<p align="center">
<img src="readme_preview/light.png" width=400>
<img src="readme_preview/dark.png" width=400>
</p>

---

### Curriculum vitae

Two sources feed the CV page. A structured JSON file following the public résumé schema wins when present; otherwise the older YAML file is used, which reads better by hand and is still supported.

So if no structured file is configured and loaded, the YAML fallback supplies the content.

[![CV Preview](readme_preview/cv.png)](https://example.github.io/paperfolio/cv/)

---

### Group pages

When more than one person needs a profile, the people page renders each one with a portrait, a short biography and a choice of side.

[![People Preview](readme_preview/people.png)](https://example.github.io/paperfolio/people/)

---

### Papers

Publication lists support filtering and per-entry badges.

## Common questions

Answers live in a dedicated FAQ file in the repository root.

## Sending patches

Patches are welcome. Read the contributing notes first.

Documentation fixes and small consistency changes can go straight to the default branch as a pull request. Anything bigger — a feature or a design change — should start as an issue so it can be discussed.

### Joining the maintainers

Contributors who stay active are invited onto the maintainer team; say so if that interests you.

<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="33%"><a href="https://example.org/maint-a"><img src="https://avatars.githubusercontent.com/u/2126561?v=4" width="100px;" alt=""/><br /><sub><b>A</b></sub></a></td>
      <td align="center" valign="top" width="33%"><a href="https://example.org/maint-b"><img src="https://avatars.githubusercontent.com/u/50144004?v=4" width="100px;" alt=""/><br /><sub><b>B</b></sub></a></td>
      <td align="center" valign="top" width="33%"><a href="https://example.org/maint-c"><img src="https://avatars.githubusercontent.com/u/32064808?v=4" width="100px;" alt=""/><br /><sub><b>C</b></sub></a></td>
    </tr>
  </tbody>
</table>

### Every contributor

<a href="https://contrib.rocks">
  <img src="https://contrib.rocks/image?repo=example/paperfolio&max=500&columns=24" />
</a>

## Star history

<a href="https://star-history.com/#example/paperfolio&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=example/paperfolio&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=example/paperfolio&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=example/paperfolio&type=Date" />
  </picture>
</a>

## Licence

Released under the MIT licence.

The layout grew out of an earlier minimal theme published under the same licence; little of that original remains after the rewrite of the styles and the added features.