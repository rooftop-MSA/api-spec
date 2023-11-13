# Api spec  <img src="https://avatars.githubusercontent.com/u/149151221?s=200&v=4" height = 100 align = left>

> `Api spec` of whole service

## Usage

How to get a class   

``` shell
protoc --proto_path={submodule-path}/ \
--{language}_out=src/main/kotlin {submodule-path}/**/*.proto
```

If the `submodule-path` is an `apispec` and `language` is `kotlin` you can enter it as follows.   

``` shell
protoc --proto_path=apispec/ \
--java_out=src/main/kotlin \
--kotlin_out=src/main/kotlin apispec/**/*.proto
```

