## CHANGE LOG

### v2.2.2

2013-04-20 issue [#36](https://github.com/qiniu/c-sdk/pull/36)

- 增加 QBox_RS_PutPolicy_Token, QBox_RS_GetPolicy_Token (不建议继续使用 QBox_MakeUpToken)


### v2.2.1

2013-04-19 issue [#24](https://github.com/qiniu/c-sdk/pull/24)

- 增加 QBox_Client_InitNoAuth
- 增加 QBox_Io_PutFile, QBox_Io_PutBuffer
- 增加 QBox_RS_PutStream, QBox_RSCli_PutStream, QBox_RSCli_UploadStream (但不推荐，推荐 QBox_Io_PutXXX)
- 支持 Travis-CI，引入 CUnit 做单元测试

