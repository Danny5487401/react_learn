# npm(Node Package Manager)


随同NodeJS一起安装的包管理和分发工具，它很方便让JavaScript开发者下载、安装、上传以及管理已经安装的包。


## 命令使用

```shell
# 管理npm的配置路径
(⎈|sandbox:default)➜  ~ npm config list
; "builtin" config from /opt/homebrew/lib/node_modules/npm/npmrc

; prefix = "/opt/homebrew" ; overridden by user

; "user" config from /Users/python/.npmrc

prefix = "/opt/homebrew"

; node bin location = /usr/local/bin/node
; node version = v21.3.0
; npm local prefix = /Users/python
; npm version = 10.7.0
; cwd = /Users/python
; HOME = /Users/python
; Run `npm config ls -l` to show all defaults.

# 查看包的安装路径
(⎈|sandbox:default)➜  ~ npm root
/Users/python/node_modules
# 会自动 prefix + /lib/node_moduels
(⎈|sandbox:default)➜  ~ npm root -g
/opt/homebrew/lib/node_modules


```


## NVM（Node Version Manager）

旨在帮助开发者在同一台机器上管理多个 Node.js 的版本。

```shell
# 查看版本
(⎈|sandbox:default)➜  ~ nvm -v
0.39.7

# 查看目前已经安装的版本
(⎈|sandbox:default)➜  ~ nvm ls
->     v18.10.0
         system
iojs -> N/A (default)
unstable -> N/A (default)
node -> stable (-> v18.10.0) (default)
stable -> 18.10 (-> v18.10.0) (default)
lts/* -> lts/krypton (-> N/A)
lts/argon -> v4.9.1 (-> N/A)
lts/boron -> v6.17.1 (-> N/A)
lts/carbon -> v8.17.0 (-> N/A)
lts/dubnium -> v10.24.1 (-> N/A)
lts/erbium -> v12.22.12 (-> N/A)
lts/fermium -> v14.21.3 (-> N/A)
lts/gallium -> v16.20.2 (-> N/A)
lts/hydrogen -> v18.20.8 (-> N/A)
lts/iron -> v20.19.5 (-> N/A)
lts/jod -> v22.21.1 (-> N/A)
lts/krypton -> v24.11.0 (-> N/A)
```




## 参考

