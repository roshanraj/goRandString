# goRand 

goRand is a tiny help suite for generating random data such as

* number 
   * 35218040
* string 
   * kuahaqbG
* email
   * DTSeoEKn@yahoo.com

***random string generator has be picked up from http://stackoverflow.com/questions/22892120/how-to-generate-a-random-string-of-a-fixed-length-in-golang***

## Installation
  go get github.com/Pallinder/go-randomdata

## Usage
package main
```
import (
	"fmt"

	"github.com/roshanraj/goRandString/goRand"
)

func main() {
	for i := 1; i < 10; i++ {
		fmt.Println(goRand.RandNumber(8))
		fmt.Println(goRand.RandString(8))
		fmt.Println(goRand.RandEmail(8))
	}
	fmt.Println("random string generator")
}
```
