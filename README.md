
# 云锻开源|CloudForgeTech-Wiki

本项目是记录云锻开源社区的项目及文档的站点,采用[mdbook](https://rust-lang.github.io/mdBook/)

## 如何使用
**rust安装器下载 [rustup-init.exe](https://static.rust-lang.org/rustup/dist/x86_64-pc-windows-msvc/rustup-init.exe)**

**安装 Rust 后，可以使用以下命令，构建和安装 mdBook：**

**构建书籍**
```
cargo install mdbook
```

**构建文档**
```
mdbook build
```

**启动服务**
```
mdbook serve
```

**上传流程：**
**Fork库到本地 在修改后构建文档 并启动服务**
**本地debug后 提交Pull requests到team-CloudForgeTech/Wiki主库**