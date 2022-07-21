# dubbo-go-schema
这个项目为了更好的编写dubbo-go配置文件

## 怎么使用

## golang

> https://github.com/dubbogo/dubbo-go-schema/dubbo-go.json

![img.png](images/img.png)

## vs code

![vs-code](images/vs-code.png)

在 settings.json 文件添加
```json
{
  "yaml.schemas": {
    "https://github.com/dubbogo/dubbo-go-schema/dubbo-go.json": [
      "dubbo.yaml",
      "application.yaml",
      "dubbogo.yaml"
    ]
  }
}

```
## 效果图

![img_1.png](images/img_1.png)
