# README
## MyPrettyJson

+ 快捷键 shift + cmd + j 格式化.
+ 快捷键 shift + cmd + u 压缩.
+ 快捷键 shift + cmd + r 美化，去掉json套json的转义
   key 加上 `[⭕️]` 表示原来是 字符串， 数组中  `[⭕️]` 表示下一个元素原来是字符串

```
{
    "l": 2,
    "v": "{\"l\":1,\"v\":\"{\\\"l\\\":0,\\\"v\\\":\\\"{\\\\\\\"a\\\\\\\":[{\\\\\\\"l\\\\\\\":2,\\\\\\\"v\\\\\\\":\\\\\\\"{\\\\\\\\\\\\\\\"l\\\\\\\\\\\\\\\":1,\\\\\\\\\\\\\\\"v\\\\\\\\\\\\\\\":\\\\\\\\\\\\\\\"{\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"l\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\":0,\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"v\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\":\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"{\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"value\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\":\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"AAAA\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"}\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"}\\\\\\\\\\\\\\\"}\\\\\\\"},{\\\\\\\"l\\\\\\\":1,\\\\\\\"v\\\\\\\":\\\\\\\"{\\\\\\\\\\\\\\\"l\\\\\\\\\\\\\\\":0,\\\\\\\\\\\\\\\"v\\\\\\\\\\\\\\\":\\\\\\\\\\\\\\\"{\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"value\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\":\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"BBBB\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\"}\\\\\\\\\\\\\\\"}\\\\\\\"}],\\\\\\\"value\\\\\\\":\\\\\\\"CCC\\\\\\\"}\\\"}\"}"
}
```




```
{
    "l": 2,
    "v[⭕️]": {
        "l": 1,
        "v[⭕️]": {
            "l": 0,
            "v[⭕️]": {
                "a": [
                    {
                        "l": 2,
                        "v[⭕️]": {
                            "l": 1,
                            "v[⭕️]": {
                                "l": 0,
                                "v[⭕️]": {
                                    "value": "AAAA"
                                }
                            }
                        }
                    },
                    {
                        "l": 1,
                        "v[⭕️]": {
                            "l": 0,
                            "v[⭕️]": {
                                "value": "BBBB"
                            }
                        }
                    }
                ],
                "value": "CCC"
            }
        }
    }
}
```

 

**Enjoy!**
