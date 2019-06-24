
# Changelog

-------------------------------------------------------------------------------------------------------------

## 0.0.1

### 新特性
* 【poi】          增加TableUtil
* 【http】        HttpRequest增加setCookieManager方法
* 【http】        改进url错误时的报错信息（感谢@【北京】thumb）

### Bug修复
* 【core】        修复ZipUtil.zlib压缩识别问题（感谢@【上海】 沙漏）
* 【log】           调整log模块层次结构，兼容slf4j的API（issue#IY8DX@Gitee）
* 【core】         Convert.toXXX带默认值换成convertQuietly实现，避免异常（issue#403@Gitee）
* 【log】           解决行号错误问题
* 【log】           修复decimalFormatMoney中整数丢失问题（issue#IY9OV@Gitee）
