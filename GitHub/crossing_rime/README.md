# 小鹤双拼定制

这个仓库里包含我的Rime配置文件。

我的运行环境：Mac OS X 10.11.2 EI Capitan / 鼠须管 0.9.26.1 

根据 [Rime 擴充詞庫](https://github.com/rime-aca/dictionaries)，以及 [安装及配置 Mac 上的 Rime 输入法——鼠鬚管 (Squirrel)](http://www.dreamxu.com/install-config-squirrel/)改造而成。

定制项目包括：

1 新建`default.custom.yaml`管理候选词数量、输入选单中的输入方案、输入选单切换键

2 新建`squirrel.custom.yaml`管理输入选单字体设置及配色方案选择。

3 新建`chinese_contain_english.schema.yaml`方案，配合双拼输入；

`chinese_contain_english.dict.yaml`字典，记得把use_preset_vocabulary改成false。在省略号下面写上自定义的字码，我们在这可以加上中英文、大小写甚至特殊字符混合输入。

4 之后建`*.dict.yaml`，*表示自己的方案名。在这里我们需要输入新增的词典，由于双拼不支持[Rime 擴充詞庫](https://github.com/rime-aca/dictionaries)中的英文词典,我们已经通过第三点支持了，所以这里只添加了其余几个词库。词库资源网路上有很多，可以自己再去找找。个人观点，够用就好，库大了，废的也多，还不如慢慢调教。

5 建立`*.custom.yaml`，载入朙月拼音扩充词库。

6 建立`*.schema.yaml`，加入emoji、chinese_contain_english等。。。

具体条目的意思在文件中都有注释。

再次声明，文档改自[Rime 擴充詞庫](https://github.com/rime-aca/dictionaries)，以及 [安装及配置 Mac 上的 Rime 输入法——鼠鬚管 (Squirrel)](http://www.dreamxu.com/install-config-squirrel/)，非常感谢各位大拿的分享！

由于很多东西并不了解，初衷也仅仅是为了分享一下我个人的配置，如果有不对的地方，欢迎指正！




