# 配置文件参考

## 完整案例

```toml
# aiotieba.toml
[User]

# default是自定义的BDUSS_key，你可以改成你喜欢的标识
# 该设计是为了方便通过BDUSS_key快速调用BDUSS，这样你就不用每次都填一串很长的东西作为参数
[User.default]
# 把你的那一串长长的BDUSS放在这
BDUSS = "W5RNUVKai2LdUd5TTVHblhFeXoxdGyOVURGUE1OYzNqVXVRaWF-HnpGckRCNFJnRVFBQUFBJCQAAAAAAAAAAAEAAADiglQb0f3Osqmv0rbJ2QAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMN6XGDDelxgc"
# 可以不填，一些网页端接口会需要STOKEN
STOKEN = "b77bf99815618155cb661f8b78b06f4d91fd44fd83d8881b0fc279916e67cedb"

# 如果要另新增一个BDUSS_key为other的用户，参考如下配置
[User.other]
BDUSS = ""
STOKEN = ""

[Database]
host = "127.0.0.1"
port = 3306
user = ""                                 # 填用户名
password = ""                             # 填密码
db = "aiotieba"                           # 使用的数据库名，不填则默认为aiotieba
unix_socket = "/var/lib/mysql/mysql.sock" # 用于优化linux系统的本机连接速度，看不懂就不用填
pool_recycle = 3600                       # 填连接超时的秒数，需要与服务端保持一致，不填则默认为28800秒
```
