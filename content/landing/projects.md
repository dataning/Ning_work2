---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

active: true

# Order that this section appears on the page.
weight: 2

title: Data Science Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Dashboard
    tag: Dashboard
  - name: Machine Learning
    tag: Machine Learning
  - name: Spatial Analysis
    tag: Spatial
  - name: Data Visualisation
    tag: Data viz
  - name: Time Series
    tag: Time Series
  - name: Text Mining
    tag: Text Mining
  - name: Bayesian
    tag: Bayesian
  - name: Choice Modelling
    tag: Choice
  - name: Risk Assessment
    tag: Risk
  - name: Social Media Analysis
    tag: Social media
  - name: Others
    tag: Others
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '5'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
