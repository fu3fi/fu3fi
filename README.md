```go
package GoodEmployees

import (
  p "people"
)

type Programming interface {
  Go()
  Python()
  SQL()
  JS()
  PHP()
}

type Language interface {
  Russian()
  English()
}

type CyberSecurity interface {
  Web()
  ActiveDirectory()
  MalwareDevelopment()
  Network()
}

type Skills interface {
  Programming
  Language
  CyberSecurity

  Coffee()
  Study()
} 

func main() {
  var fu3fi Skills = p.NewEmployee()
}
```
