```go
package fu3fi

import (
  p "people"
)

type Skills interface {
  Coffee()
  Exploit()
  Program()
  English()
  Study()
} 

func main() {
  // knowing go, python, javascript, php, sql
  var fu3fi Skills = p.NewWorker()
}
```
