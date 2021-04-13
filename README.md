# Rime_luna_pinyin_simp_mac

mac squirrel luna pinyin simple 鼠须管 明月拼音简化版本 无脑配置

## 配置结果：

* 输出显示设置：横向输出
* 可选个数：9
* 中英文切换：control+shift+2(其实也可以用键盘自带中/英键切，但中文模式下按中/英键会清空输入，因为设置了clear。。。)
* 配色: mac系统默认暗夜模式
* 词库包括：en_cn（部分词语可以中英文连打）; poetry（古诗吧）;hanyu（一些词组）
* 效果展示：



![image](https://user-images.githubusercontent.com/46819870/114512409-ae061500-9c6b-11eb-99db-a4c0782e625d.png)

![image](https://user-images.githubusercontent.com/46819870/114512865-2371e580-9c6c-11eb-8d0e-2017cd58b7d5.png)


## 要求：
* mac os 10.15.7 +
* 已经安装了基于Rime的鼠须管squirrel 0.15.2
* 只使用luna_pinyin_simp, 别的输入模式啥也不用

## 配置方法：
* 进入鼠须管的用户设定文件夹/User/Library/Rime
* 把setting.zip下载到本地，解压到上述文件夹
* 在鼠须管中重新配置/deploy
* 完成

## 自定义建议：
* 任意想改的部分都可以自己编辑yaml文件更改，mac下推荐使用`macvim`作为编辑器，不要用mac自带的文件编辑器。前提是会用vim编辑语法，简单来说就是按i进入编辑模式，按esc退出编辑模式，按shift+ZZ保存更改并退出编辑器。
* extend.dict.yaml 里面可以自己加习惯的用语词组，格式参照已经添加的词组。
* 官网doc天下第一

## 仍有疑惑
* 提issue，佛系登上来看
