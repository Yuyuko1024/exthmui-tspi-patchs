## [exTHmUI-11.0](https://github.com/exTHmUI-legacy/) for tspi phone patch-sets

泰山派 tspi phone 补丁集合

已集成 小海豚手机安卓V4.1扩展板补丁V1.2.0精简版（去除内置应用以缩减补丁大小）

对于内核补丁，请对报错的dtsi文件使用```dos2unix```命令转换格式后保存提交后再进行修补。

不定时更新补丁，请根据补丁所处的路径在SDK找到指定目录后使用 git am /path/to/patchs/*.patch 应用补丁。