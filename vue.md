# vue源码分析

## vue源码的目录
```shell
// tree -aI ".git*|.vscode" -C -L 1
xxx/github/core/packages目录下为vue主要源码部分
.
├── compiler-core
├── compiler-dom
├── compiler-sfc
├── compiler-ssr
├── dts-built-test
├── dts-test
├── global.d.ts
├── reactivity
├── reactivity-transform
├── runtime-core
├── runtime-dom
├── runtime-test
├── server-renderer
├── sfc-playground
├── shared
├── size-check
├── template-explorer
├── vue
└── vue-compat
```
根据当前vue源码指导中，主要关注compiler-core,compiler-dom,runtime-core,runtime-dom 这四部分内容，分别对应一个编译状态和一个运行时处理
