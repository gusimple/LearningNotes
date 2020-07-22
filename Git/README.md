# Git内容学习
## 开发中使用的过
### git导出版本之间的差异文件
git diff 456bcb 93593a --name-only | xargs tar -czvf ../update.tar.gz  
说明 456bcb,93593a 为两个版本号,后面是打包的文件名
