# Divina

A modern build system for assembly

```lua
-- Divina.lua

Package = {
  name = "example",
  version = "0.1.0",
  description = "A default Divina package that you can extend!",
  compile_options = {},
  minimum_divina_version = Divina.version,
  sources = {
    "example/Main.asm",
  },
  type = Divina.Type.Bin,
  arch = Divina.Arch.x64,
  license = "Unlicense",
}

return Package
```
