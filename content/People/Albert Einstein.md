---
title: Albert Einstein
tags:
  - science
  - physics
infobox:
  supertitle: Historical Figure
  title: Albert Einstein
  subtitle: Theoretical Physicist
  images:
    - label: Portrait
      image: einstein-portrait.svg
      caption: Photograph from [[1921]]
    - label: Lecture
      image: "[[einstein-lecture.svg]]"
      caption: Einstein giving a lecture
  tags: [science, physics]
  showTags: true
  fields:
    - section: Personal
    - Born: March 14, 1879
    - Died: April 18, 1955
    - Nationality: "[[Germany|German]] / [[United States|American]]"
    - section: Career
    - Field: Theoretical physics
    - Known for: "[[General Relativity]] | [[Special Relativity]] | [[Photoelectric Effect]]"
    - Awards: Nobel Prize in Physics (1921)
    - Aliases: |
        #### Codenames
        - Black King
        - Iron God

        #### Nicknames
        - Armored Avenger
        - [[Golden Boy]]
---

Albert Einstein developed the theories that reshaped modern physics. This note uses the same `infobox` frontmatter an Obsidian vault would use with Omni Infobox: a supertitle, a tabbed gallery, tags, section dividers, and field values that mix dates, wikilinks, pipes, and a Markdown block scalar.

The portrait and lecture images are resolved by filename from `assets/`, the same way Obsidian resolves a wikilink to a file anywhere in the vault. Nationality keeps the slash between two aliased links, and the birth date stays on one line instead of becoming a comma-separated list.

Known for is a pipe-separated list of notes. The alias field is a YAML block scalar: each heading becomes a small divider inside the value, with a bulleted list underneath.
