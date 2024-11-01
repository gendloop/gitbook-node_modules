# gitbook-node_modules

该仓库包含了 gitbook 运行时需要的所有包.

## 配对版本

* [gitbook-cli@2.3.2](https://github.com/users/gendloop/packages/npm/package/gitbook-cli)
* [gitbook v3.2.3](https://github.com/gendloop/gitbook)
* Node.js v22.9.0

## 使用方法

在 gitbook 的 root 目录下打开 Git Bash, 运行

```git
git clone --no-checkout https://github.com/gendloop/gitbook-node_modules
cd gitbook-node_modules
git archive --format=tar HEAD | tar -x -C .. --exclude='README.md'
cd ..
rm -rf gitbook-node_modules
```

