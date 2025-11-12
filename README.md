```yml
- &entry
  label: !!str N/A
  href: !!str https://www.google.com
- <<: *entry
  label: elm
  href: https://elm-lang.org
- <<: *entry
  label: Twine
```