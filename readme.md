# YYZ's registry

Some packages which are not registered in `General` but used in my project is registered in this registry since I don't include `Manifest.toml` file in a package, see: 

https://github.com/JuliaLang/Pkg.jl/issues/492

This package is managed by [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl), however hand-manipulating is still required in my opinion.

Usage:

```julia
] registry add https://github.com/yiyuezhuo/YYZRegistry.git
```
