goja
====
filebeat使用github.com/dop251/goja => github.com/andrewkroh/goja v0.0.0-20190128172624-dd2ac4456e20，导致无法使用最新版本的goja，所以重新fork一个新goja模块

# 修改内容
go.mod 中 module github.com/dop251/goja => github.com/chaolihf/goja 
全局替换
github.com/dop251/goja/为github.com/chaolihf/goja/