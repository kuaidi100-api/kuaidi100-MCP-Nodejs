## 快递100 MCP Server (Node.js)
安装`node.js`，最低版本要求为18.0.0

### 获取快递100 API KEY
登录快递100获取： [快递100官方](https://api.kuaidi100.com/extend/register?code=d1660fe0390d4084b4f27b19d2feee02) （注意不要泄露授权key，以防被他人盗用！！！）

### 一、STDIO方式：在线获取快递100 MCP服务运行
通过`npx`命令一步获取kuaidi100_mcp并使用
```json
{
  "mcpServers": {
    "kuaidi100": {
      "command": "npx",
      "args": [
        "-y",
        "@kuaidi100-mcp/kuaidi100-mcp-server"
      ],
      "env": {
        "KUAIDI100_API_KEY": "<YOUR_API_KEY>"
      }
    }
  }
}
```

### 测试

#### 物流轨迹查询：
![trae_test_queryTrace.png](https://file.kuaidi100.com/downloadfile/DTjS9PHPonJXikObm8OTcEA3OnuWBw0livDDJc73jYGMQmcwqfJpKhTzSVA-UwVX9LJZE3Nnnw7iLRgmekijRw)
#### 快递预估时效：
![trae_test_estimateTime.png](https://file.kuaidi100.com/downloadfile/NL6vRCRVQkmvdavX19DISKf8uCvrj3q5NkSNl0ALv8GOOUufxrYRTRxoZJ20_uF-MGURmZRcKxS5XfAaz9t39Q)
#### 快递预估价格
![trae_test_estimatePrice.png](https://file.kuaidi100.com/downloadfile/mPv7xFAUbsY5yFbaQZn7Z0ihtIU781pksXTTj-L2wwVgZ3dH-OSvqEdm3IaJzimTF_xIWbtHD6OFP8w2i35xsQ)

### Tips
如需获取账号信息（如 key、customer、secret），或免费试用100单，请访问[API开放平台](https://api.kuaidi100.com/home?code=d1660fe0390d4084b4f27b19d2feee02)进行注册
