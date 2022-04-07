# Operator Demo

## 目录
-   [Operator Demo](#operator-demo)
    -   [目录](#目录)
    -   [先决条件](#先决条件)
    -   [构建命令](#构建命令)

## 先决条件
go 1.17.8

operator-sdk v1.18.1

## 构建命令
```
mkdir operator-demo
cd operator-demo/
operator-sdk init --owner wangchanggan --project-name operator-demo --repo github.com/wangchanggan/operator-demo
operator-sdk create api --group demo --version v1 --kind OperatorDemo
make manifests
```