# TODO


## In-Progress

* [x] Add "News" to main nav
  * [ ] Link to page that pulls down and parses the RSS feed for the
        announcement mail list
* [ ] Add colour highlights to books, authors, and genres
  * [x] Each should have it's own "theme colour"
  * [x] Menus should have a bar of colour above/below
  * [ ] Panoramic header images for each top-level page should be in matching colour
* [x] Only show side nav on main, books, genres, and authors pages
  * [ ] Create location path content for use above main content
    * http://getbootstrap.com/components/#breadcrumbs
  * [ ] Show path above main content for all non-main-pages


## Not-Started

* [ ] Change "active" background colour from grey to its theme colour
* [ ] Update to be responsive
* [ ] Create author template page
* [ ] Create book template page
* [ ] Add support for parsing RSS feeds
  * [ ] Create a library for RSS feeds
  * [ ] Create a library for XML parsing (wrapper for erlsom)
* [ ] Create genre template page
* [ ] Store content in Redis
  * [ ] Write code to pull content out of Redis
  * [ ] Support Markdown source and convert to HTML
  * [ ] Write a content editor front-end for Redis
* [ ] Add authentication
* [ ] Add user page


## Done

* [x] Add logging support
* [x] Centre subfooter content
* [x] Fill in subfooter
* [x] Add icomoon support
* [x] Add Twitter link
* [x] Separate top nav from side nav
* [x] Lighten footer background colour
* [x] Update routes to point to new pages
* [x] Add sticky bottom
  * [-] Add siloutette imagery (maybe later)
* [x] Fill in footer
  * [x] Convert footer menu to function in nav module
  * [x] Add links to footer menu
* [x] Fix mouse-over on main nav obscuring logo
* [x] Add real items to side nav
  * [x] Update routes to match
* [x] Add real items to top nav
  * [x] Update routes to match
  * [x] Set menus to expand when a link is active
  * [x] Change blue "active" colour to light grey
* [x] Rename some more general modules:
  * [x] cnbbsite-templates.lfe -> cnbb-tmpls.lfe
  * [x] cnbbsite-util.lfe -> cnbb-util.lfe
  * [x] cnbbsite-const.lfe -> cnbb-const.lfe
* [-] Fix background colour of top nav and main content area to match footers
  * This didn't get fixed, since it was a perceptual problem -- depending
  upon the monitor/display, greys of different darkness with the same
  values in r, g, and b, will seem to have blue, green, or red highlights
* [x] Move "data" of menus into dedicated module
* [x] On book/genre/author pages use title & subtitle
* [x] Rename rest of modules (except main one)
* [x] Make subtitle font smaller
* [x] Move background colours back to grey
