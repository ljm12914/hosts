# hosts
在国内网络环境下，很多没有被屏蔽的国外网站想访问也十分艰难，其中有一部分的艰难就来自于DNS服务器由于各种问题而缺失或错误的DNS记录，它们导致数据包发往了不该发的IP地址。

而通过修改Windows自带的本地自定义DNS文件——hosts，将这些网站的正确IP地址定死，即可绕过DNS查询过程直接访问正确IP，这样做可以有效提升访问效率和防止DNS故障。

LJM12914的hosts文件目前包括了一些LJM12914常去的网站。如有任何建议欢迎提issue，PR就算了。

备份：[Gitee](https://gitee.com/ljm12914/hosts/raw/master/hosts)　短链：Gitee`ljm.im/hosts`　Github`ljm.im/host`

## 注意
DNS问题只是访问国外网站诸多问题中的一个，修改hosts文件并不能保证该网站一定可访问或访问速度加快。

## 授权许可
MIT
