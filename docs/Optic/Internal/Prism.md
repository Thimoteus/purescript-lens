## Module Optic.Internal.Prism

#### `Market`

``` purescript
data Market a b s t
  = Market (b -> t) (s -> Either t a)
```

##### Instances
``` purescript
Functor (Market a b s)
Profunctor (Market a b)
Choice (Market a b)
```

#### `MarketP`

``` purescript
type MarketP a = Market a a
```


