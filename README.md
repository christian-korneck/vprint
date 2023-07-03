# vprint

alias for `fmt.Printf("%#v\n", v)`, nothing more

```
package main

import (
	"github.com/christian-korneck/vprint"
)

func main() {
	b := []byte{'g', 'o'}
	vprint.Vprint(b) // prints: []byte{0x67, 0x6f}

}
```
