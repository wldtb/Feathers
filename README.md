修复刷屏崩服！！！！！

羽毛
Feathers 是一个耐力模组，可作为我所有未来项目的 API

安装
安装 Minecraft Forge 后，只需将从此处的文件部分下载的 mod 拖放到您的 mods 文件夹中。 mods 文件夹位于 。%appdata%/.minecraft/mods

开发商信息
向 Feathers 添加支持很容易。要导入它，只需将此行添加到文件的 .build.gradlerepositories

repositories {
     maven { url "https://www.cursemaven.com" }
}
这适用于项目的依赖项。

dependencies {
	implementation fg.deobf("curse.maven:feathers-699933:FILE_VERSION") 
}
要使用的版本的文件 ID 在哪里。您可以通过打开 Feathers 文件下载的 URL 并查看 URL 来找到它。末尾的数字是文件 ID。FILE_VERSION

然后只需像往常一样运行您的 gradle 设置命令，例如 然后。gradlew genEclipseRunsgradlew eclipse

您现在可以访问 Feathers API 和代码！该API是不言自明的，但如果您需要任何帮助，请随时在此处私信我！

贡献
欢迎拉取请求。对于重大更改，请先打开一个问题，讨论您想要更改的内容。

请确保适当地更新测试。

## License
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-nc-sa/3.0/)

