## 简介

基于[**aiotieba**](https://github.com/Starry-OvO/aiotieba)实现的百度贴吧高弹性吧务审查框架

+ 类型注解全覆盖，方法注释全覆盖，类属性注释全覆盖，内部命名统一
+ 支持获取用户主页信息（包括个性签名、发帖量、吧龄、成长等级、ip归属地、虚拟形象信息...）、历史发帖、关注吧、关注用户、粉丝列表...
+ 支持富文本解析，获取图片信息、at用户id、链接内容、投票帖、转发帖...
+ 支持针对多条相互关联的内容的审查
+ 支持二维码识别、相似图像查找
+ 支持用户黑白名单、图片黑白名单
+ 使用本地缓存避免重复检测，极大提升性能
+ 优先使用websocket接口，节省带宽

## 安装 (beta)

```shell
git clone https://github.com/Starry-OvO/aiotieba-reviewer.git --depth=1 -b develop
cd ./aiotieba-reviewer
pip install .
```

## 教程

[**云审查教程**](https://review.aiotieba.cc/tutorial/reviewer/)

## 客户名单

*2023.03.04更新*

|      吧名      | 关注用户数 | 最近24天日均访问量 | 日均主题帖数 | 日均回复数 |
| :------------: | :--------: | :----------------: | :----------: | :--------: |
|    抗压背锅    | 4,760,658  |     1,071,694      |    2,217     |   69,622   |
|    原神内鬼    |  562,195   |      770,760       |    1,679     |   57,184   |
|     孙笑川     | 3,453,405  |      598,735       |    5,070     |  174,086   |
|    逆水寒ol    |  799,730   |      177,566       |     891      |   18,412   |
|      嘉然      |   60,025   |      146,865       |      89      |   1,292    |
|      贝拉      |   21,840   |      145,211       |      29      |    559     |
|      乃琳      |   17,352   |      142,812       |      20      |    267     |
|      向晚      |   30,804   |      142,357       |      36      |    459     |
|    lol半价     | 2,035,056  |      141,536       |    1,686     |   75,269   |
|    新孙笑川    |  587,910   |       31,124       |     409      |   10,447   |
|      宫漫      | 1,534,603  |       29,072       |     111      |   1,753    |
|     vtuber     |  222,857   |       16,997       |      93      |   1,230    |
| vtuber自由讨论 |   17,277   |       1,391        |      2       |     34     |

## 友情链接

+ [TiebaManager（吧务管理器 有用户界面）](https://github.com/dog194/TiebaManager)
+ [TiebaLite（第三方安卓客户端）](https://github.com/HuanCheng65/TiebaLite/tree/4.0-dev)
+ [贴吧protobuf定义文件合集](https://github.com/n0099/tbclient.protobuf)
