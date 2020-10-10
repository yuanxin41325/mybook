# Gitbook



安装gitbook遇到的坑



1.node.js与gitbook版本不匹配安装报错

解决方案：需要安装10.21.0版本node.js



2.gitbook报错

原因：gitbook 3.2.3有bug，需要修改.gitbook\versions\3.2.3\lib\output\website\copyPluginAssets.js

把 `confirm:true` 改为 `confirm:false`



3.C/windows/System32> 文件夹下具有权限问题可以给对应book修改权限