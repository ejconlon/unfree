# unfree

Simplistic free monad with deriving through `UndecidableInstances`

Why does this exist when `free` is ubiquitous? Sometimes you just want to easily derive `Eq` without having to define `Eq1` for your functor, or maybe you just want a `Hashable` instance. (Maybe someday the situation will improve with quantified constrant superclasses.)
