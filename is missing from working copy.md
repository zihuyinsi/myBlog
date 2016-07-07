# Blog

Xcode 下 报出 "xxx" is missing from working copy

在项目中提交过svn后，再在本机上删除不用的图片资源后，build后会有  "xxx" is missing from working copy 的警告。在网上找了些资料后，总结下。
    直接在终端下用svn命令删除missing的文件：（需要cd到提示你missing 文件的路径下）
    svn delete nameOfMissingFile
    或用Git（如果你用的是Git的话）
    git rm nameOfMissingFile

#end