# vscode-support
vscode-support

发布：

1.安装VSCE：npm install -g vsce
2.cd 进入目录
3.vsce package
4.登录marketplace 并上传vsix。https://marketplace.visualstudio.com


快速发布：

$ vsce publish
Publishing uuid@0.0.1...
Successfully published uuid@0.0.1!

登录
vsce login (publisher name)

自动增加扩展版本
vsce publish minor / vsce publish 2.0.1

取消发布扩展
您可以通过指定扩展名id使用vsce工具取消发布扩展publisher.extension。

vsce unpublish (publisher name).(extension name)

包装扩展
您可能希望打包扩展而不将其发布到商店。扩展名将始终打包到.vsix文件中。就是这样：

vsce package
