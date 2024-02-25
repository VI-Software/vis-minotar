# Minecraft Go API

This repository is based on [Minotar](https://github.com/minotar/minecraft) but has been changed to use VI Software Authentication Services

~~~ go
package main

import "github.com/minotar/minecraft"

func main() {
  uuid, _ := minecraft.GetUUID("Benson")

  skin, _ := minecraft.FetchSkinUUID(uuid)
}
~~~

Install the package (**go 1.1** and greater is required):
~~~
go get github.com/VI-Software/vis-minotar
~~~

## Features
* User fetching using the Minecraft API
* Skin fetching using AmazonS3
* Almost no actual functionality!


## License

This software is redistributed under the MIT License.
