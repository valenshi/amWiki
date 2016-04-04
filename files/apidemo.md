# 客户日志流水接口

### 请求地址
/cloud/customer-flow

### 请求类型
GET

### 请求参数
| 参数名 | 类型 | 必填 | 描述 | 默认值 |
| --- | :---: | :---: | --- | --- |
| customer_id | number | 是 | 客户id | - |
| type | number | 否 | 客户类型，0所有、1扩展、2报备、3成交 | - |

### 返回JSON示例
```javascript
{
	"state": {
		"code": 10200,
		"msg": "ok"
	},
	"data": {
		"id": 307,  //流水id
		"real_name": "Tevin",  //用户名称
		"mobile": "暂无",  //用户手机
		"origin": "暂无",  //用户来源
		"created_at": "2016-04-04 20:00:00",  //加入时间
		"log": []  //日志列表
	}
}
```

### 备注
无