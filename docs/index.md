# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

[![ci](https://github.com/waseemofficial/documentation1/actions/workflows/ci.yml/badge.svg)][def]

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

```py title="name mkdocs"
name = "mkdocs"
def hello(name) {
	print("hi",name)
}
```
## vega-lite

```vega-lite
{
"mark":"line",
"data":{
	"url":"range.csv"
},
"encoding":{
"X":{
	"field":"resistance(ohm)",
	"type":"quantitative"
},
"y":{
	"field":"distance(cm)",
	"type":"quantitative"
}
}
}
```

```sequence {theme="hand"}
MCU->Senser:start
MCU->Senser: Slave address
Senser-->MCU:ACK
```

[def]: https://github.com/waseemofficial/documentation1/actions/workflows/ci.yml