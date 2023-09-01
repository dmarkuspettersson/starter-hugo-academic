---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured


# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Latest paper
subtitle: '[**See all research** {{< icon name="angles-right" pack="fas" >}}]({{< ref "/research/index.md" >}} "Research")'

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how many pages you would like to display (0 = all pages)
  count: 1
  # Filter on criteria
  filters:
    author: ''
    category: ''
    publication_types: ['3', '9']
    tag: ''
  # Link to paper archive: enable (true) or disable (false) 
  archive:
    enable: false
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 3
---
