protoc - Qt 中开发 Protobuf 自动脚本
===================================================
在 Qt 项目工程文件里面只要配置 PROTO_FILES += xxxx.proto 就可以让 Qt 项目工程一键构建运行。

为了引入 Protobuf 自动化脚步，请将下面几行加入到项目中：

    $ # Set protobuf pkg-config
    $ CONFIG += link_pkgconfig
    $ PKGCONFIG += protobuf
    
    $ # Set protoc config
    $ CONFIG += protoc
    $ PROTO_FILES = xxxx.proto

博客内容：
---------
https://blog.csdn.net/zzs0829/article/details/86657648