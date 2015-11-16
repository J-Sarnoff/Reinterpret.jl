# Reinterprets
extends reinterpret to work with Unsigned, Signed, AbstractFloat

```julia
julia> reinterprets(Signed,1.0)
4607182418800017408

julia> reinterprets(Signed,Float32(1.0))

1065353216

julia> reinterprets(Unsigned,Float16(1.0))
0x3c00

julia> reinterprets(AbstractFloat,ans)
Float16(1.0)
```
