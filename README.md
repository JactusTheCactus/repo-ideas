Thoughts?
```yml
game: &default
  title: <TITLE>
  theme: <THEME>
  genres:
  - <GENRES>
  software:
  - <SOFTWARE>
games:
- <<: *default
  theme: Colony
  genres:
  - Idle
  - Incremental
  software:
  - PICO-8
  - Linux
```