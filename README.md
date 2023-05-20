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

*2023.05.20更新*

|      吧名      | 关注用户数 | 最近24天日均访问量 | 日均主题帖数 | 日均回复数 |
| :------------: | :--------: | :----------------: | :----------: | :--------: |
|    抗压背锅    | 4,988,625  |      719,584       |    1,314     |   58,553   |
|     孙笑川     | 4,073,427  |      645,815       |    5,241     |  224,603   |
|    原神内鬼    |  594,645   |      376,348       |     787      |   28,587   |
|      憨批      |   17,165   |      125,894       |    3,699     |   62,855   |
|      禾野      |  363,088   |      106,555       |     966      |   8,602    |
|    lol半价     | 2,078,647  |       68,593       |     258      |   22,063   |
|      宫漫      | 1,597,685  |       18,857       |      70      |   1,110    |
|    天堂鸡汤    |  357,856   |       16,914       |     126      |   4,848    |
|     vtuber     |  224,576   |       15,538       |     108      |   1,982    |
|      嘉然      |   61,135   |       10,796       |      76      |    990     |
|    元气骑士    |  273,274   |       4,298        |      49      |    500     |
| vtuber自由讨论 |   17,214   |       1,053        |      1       |     13     |

## 友情链接

+ [TiebaManager（吧务管理器 有用户界面）](https://github.com/dog194/TiebaManager)
+ [TiebaLite（第三方安卓客户端）](https://github.com/HuanCheng65/TiebaLite/tree/4.0-dev)
+ [贴吧protobuf定义文件合集](https://github.com/n0099/tbclient.protobuf)
