# General

This file describes better code structure. 
Follow it guidelines or refactor code 6 hours in a row. You decide ^-^.

# SCSS File structure

- component folder
  - [settings] folder (component development)
    - **fonts**.scss (family, size, align, font-weight, text-transform, line-height)
    - **colors**.scss (color, background, border, box-shadow)
    - **spacing**.scss (margin, padding, width/max-width, height)
    - **display**.scss (display, flexbox) 
  - [configuration] (component build)
    - **component-name**.scss

## Recommendations

- Responsive is part of a design. Don't separate it.
  - Instead think in terms of it 
- One component = one folder 
  - Treat elements like a single component
  - thus elements = one component

## Working Example

[scss]:

- [base]
  - [settings]
    - colors.scss
    - fonts.scss
    

