### run test step
- install miniserve

``` shell

cargo +nightly install miniserve


```
- build test project

``` shell

wasm-pack build --target web --out-name wasm --out-dir ./static

```

- access page use miniserve

``` shell

miniserve ./static --index index.html

```

