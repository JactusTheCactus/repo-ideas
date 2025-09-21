```yml
- title : PICO-8 game
  genre : Idle
  theme : Colony
```
```hcl
resource "aws_instance" "web" {
  ami           = "ami-123456"
  instance_type = "t2.micro"
}
```