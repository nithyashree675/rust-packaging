# rust-packaging

1. package climate_crisis
2. package pollution (depends on [1])

create package:
```
cargo new climate_crisis
cargo new pollution
```

publish package:
```
cargo publish --allow-dirty --index https://git.XXXdomain/XXXorg/XXXrepo/ --token XXXtoken
```

build package:
```
CARGO_REGISTRIES_XXXregistry_INDEX=https://git.XXXdomain/XXXorg/XXXrepo/ cargo build
```

compile
```
cargo build
```

run
```
cargo run
```
