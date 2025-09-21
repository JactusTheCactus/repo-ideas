Thoughts? (These aren't being used in a script. This is just markup)
```toml
[pico-8_game]
genre = "Idle"
theme = "Colony"
```
```yml
- pico-8_game
  genre: Idle
  theme: Colony
```
```hcl
resource "game" "pico-8_game" {
	genre = "Idle"
	theme = "Colony"
}
```
```json
"pico-8_game": {
	"genre": "Idle",
	"theme": "Colony"
}
```