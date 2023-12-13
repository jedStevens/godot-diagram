# Overview

A program that makes mermaid class diagrams from Godot source code.

This is a fork of a prototype; it may not act how you think it should.

![Example Mermaid diagram](https://raw.githubusercontent.com/jotson/godot-diagram/main/example.png)

# Requirements

* Scenes are `.tscn` files
* Scene code written in GDScript

# Usage

```bash
cd <game folder or game subfolder>
go run /path/to/godot-diagram/diagram.go
```

A file `output.mmd` will be generated in the current directory. It is a MermaidJS diagram file that you can paste here: https://mermaid-js.github.io/mermaid-live-editor/
