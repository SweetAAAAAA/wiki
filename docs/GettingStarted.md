# 开始了……

Mindustry的一切东西都很简单。这篇文章将会教您如何在不同的平台上安装Mindustry。

## 常规安装

这里将介绍几种可能是您最常用的安装方式。

### PC端

#### Steam 

直接[在Steam上购买](https://store.steampowered.com/app/1127400/)来支持开发者Anuke!

#### Itch.io

1. 访问游戏的[itch.io页面](https://anuke.itch.io/mindustry)以下载游戏。
2. 一旦`.zip`压缩文件下载完成，将它解压。一般来说解压过程是没有错误的。完成之后，进入解压到的文件夹里。
3. 
    1. **Windows**: 启动`desktop-release.exe`.
    2. **MacOS**: 运行`Mindustry.app.`
    3. **Linux**: 运行`Mindustry`. 

如果您安装了JRE（推荐安装一个！），你也可以直接运行`desktop-release.jar`。

### Android

#### Play商店

Play商店上提供两种版本——Mindustry和Mindustry Classic。如果您想玩最新的Mindustry，应下载**Mindustry**；或者玩旧版本的**Mindustry Classic**。

#### F-Droid

F-Droid是一个安全方便的开源应用市场。首先，在这里[下载F-Droid](https://f-droid.org/)。安装后可以在市场中下载到Mindustry。

注意：F-Droid中游戏版本更新一般会比Play商店中的版本慢一些。

### iOS

iOS设备在App Store中需要付费下载。

## 为代码的贡献者

如果您想为游戏源代码贡献自己的力量，那么最好的办法就是自己编译一个。方法如下：

1. 检查并安装最新的JRE和JDK 8。
2. 在代码的根目录打开命令窗口，运行如下命令：
    1. Windows:
        1. 运行命令行: `gradlew desktop:run`
        2. 编译: `gradlew desktop:dist`
    2. Linux:
        1. 运行命令行: `./gradlew desktop:run`
        2. 编译: `./gradlew desktop:dist`
    3. 若要编译服务器，将`desktop`替换成`server`即可，比如这样：`./gradlew server:run`
