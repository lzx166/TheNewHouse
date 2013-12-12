## 根据城市区id获得具体定位地市区
## 请求
### URL

+ 填写请求的URL

### POST /items

```json
{
    "urbanid": "纬度",
    "countyid": "经度"
}
```
### 必要项目

### 默认项目

### 备注

* urbanid,countyid二者有一个则可以返回对应的城市区县名

## 响应

```json
{
	"ResultStatus": 200,
    "urbanid": "城市id",
    "urbanname": "南京",
    "countyid": "区县id",
    "countyname": "江宁区"
}
```

### `200` - 添加成功(目前：200)


### `400` - 请求参数错误
+ 其他错误由web端定义

********************