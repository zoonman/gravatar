# Gravatar Avatar generator

Generates Gravatar picture url from a given email with specified size

## Usage

```go
import (
       	"github.com/zoonman/gravatar"
       	"log"
       )

func main ()
{
	 log.Print(gravatar.Avatar("philipp@zoonman.com", 256))
}
```
