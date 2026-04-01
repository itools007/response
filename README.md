# response

用于测试返回http请求中的各种参数测试

## responseHeader

请求什么header，返回什么header，主要用于测试header返回，以及代理请求后请求和返回的情况

nginx场景

```text
测试nginx返回日志: upstream sent too big header while reading response header from upstream 的问题

经过测试，发现当 header 大小超过4k时，nginx会返回upstream sent too big header while reading response header from upstream
```

