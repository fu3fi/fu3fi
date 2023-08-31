```go
package fu3fi

import (
  p "people"
)

type Skills interface {
  Coffee() Error
  Exploit() Error
  Program() Error
} 

func main() {
  var fu3fi Skills = p.NewWorker() 
}
```
