Thoughts?
```yml
game: &default
  title: <TITLE>
  theme: <THEME>
  genres:
  - <GENRES>
games:
- <<: *default
  title: <placeholder>PICO-8 Game
  theme: Colony
  genres:
  - Idle
  - Incremental
```