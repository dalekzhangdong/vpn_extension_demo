# vpn_extension_demo
一个用network extension 搭建的vpndemo

# demo使用说明：
1.下载后 cd到文件夹（和Cartfile 同目录） 执行 carthage update --no-use-binaries --platform ios  会生成Carthage文件夹（可能会因为commandline tool 不能编译，可以在xcode->prefrence->location->commandlinetool 选中当前版本，然后重新执行命令）

2.在extension的linkframework 添加framework ，添加->addother->Carthage/build/ios里面的framework 共十个framework

3.build 不出意外 就已经好了

vpn_demo相关： 简书：https://www.jianshu.com/p/dfd3960af5ac

