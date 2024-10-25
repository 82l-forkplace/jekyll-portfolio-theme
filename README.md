# From Jekyll-Uno-Timeline to Porfolio with projects as cards
Custom jekyll theme. Aimed at game devs and people with a lot of diverse projects.
Design is based on scalability: easy to add projects and categories.

Feel free to download it, use it, modify it, or request changes.

The template is very much alive has it got a few iterations over the years.
Basically every time I need to add a project 😓, and I do plan to keep expanding it.


## How does is look
[Demo (my Portfolio)](https://82l.github.io/)


## Installation/Setup
1. Install Jekyll https://jekyllrb.com/ (needs ruby)
2. Install bundle (gem install bundle)
3. Download or clone repo `git clone https://github.com/82l-forkplace/jekyll-portfolio-theme.git`
4. Enter the folder: `cd jekyll-portfolio-theme/`
5. Install plugins : `bundler install`
6. Start Jekyll server: `bundle exec jekyll serve`
7. Configure: `_config.yml` (May need to restart the server)
   * at least set `font_awesome` or download and add the font in `head.html`
8. Add your projects as .md file in folders
9. To install website using github pages, consider this doc to setup the CI https://jekyllrb.com/docs/continuous-integration/github-actions/

Access via: [http://localhost:4000/](http://localhost:4000/)

## Details/Features/Changes
* based on the [jekyll-uno-timeline](https://github.com/tzuehlke/jekyll-uno-timeline), but:
  * Removed the timeline
  * Simplified the menu system for adaptation to all screen sizes
  * Modernized the UI
  * Re added blog posts for more in depth presentation of project
  * Added photoswipe support to display image galleries
  * Added video support on page project
  * Added support of links to external sources for project or yourself
  * Remove analytics, as I don't want to mess with GDPR
  * Repaired the preview for social medias
  * Added sitemap and privacy policy
