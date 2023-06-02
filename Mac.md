- build

```shell
qmake -r prefix=my_brdf
make
```

- run
  - 进入 brdf/src 目录，确保当前目录具有 data, images, brdfs 等子目录
  - 执行 `./brdf/brdf`