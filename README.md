# picgo-plugin-custom-api-uploader

plugin for [PicGo](https://github.com/Molunerfinn/PicGo)

- 自定义 api 接口上传

## 使用

### 图床配置

- url: 图床上传API地址
- paramName: POST参数名
- jsonPath: 图片URL所在返回值的JsonPath(eg:data.url)
- customHeader: 自定义请求头 标准JSON(eg: {"key":"value"}
- customBody: 自定义Body 标准JSON(eg: {"key":"value"})
- prefix: `jsonPath` 返回值前缀拼接
