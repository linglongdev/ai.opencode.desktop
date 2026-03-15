# ai.opencode.desktop

opencode桌面版

二进制依赖libc2.38，deepin 25还是2.37，所以从 ubuntu:24.04 容器复制

ll-builder需要添加--skip-strip-symbols参数，否则会剥离掉opencode cli（bun打包）的部分业务代码