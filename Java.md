# 常见类
|类|说明|备注|
|----|----|----|
|URLEncoder.encode( URL, "UTF-8" )|对url进行编码|
|URLDecoder.decode( URL, "UTF-8" )|对url进行解码|
|org.springframework.web.util.HtmlUtils.htmlUnescape(str)|进行编码还原|
|org.apache.commons.lang.StringEscapeUtils.escapeHtml(str)|进行编码转义|
|org.apache.commons.lang.StringEscapeUtils.unescapeHtml(str)|进行编码还原|
|org.springframework.web.util.JavaScriptUtils.javaScriptEscape(js)|进行编码转义|
|org.apache.commons.lang.StringEscapeUtils.escapeJavaScript(js)|进行编码转义|
|org.apache.commons.lang.StringEscapeUtils.unescapeJavaScript(js)|进行编码还原|
|matcher.matches()|当且仅当整个区域都匹配才返回true|
|System.getProperty("line.separator")|获得当前系统换行符|


# 常用类特殊参数
## SimpleDateFormat 

日期格式化字母的含义
---
|字母|日期或时间元素|表示|示例|
|----|----|----|----|
|a|Am/pm标记|Text|AM|
|D|年中的天数|Number|150|
|d|月中的天数|Number|9|
|E|星期中的天数|Text|Tuesday,Tue|
|F|月份中星期|Number|3|
|G|Era标识符|Text|AD/BD(公元前/公元后)|
|H|一天中的小时数（0-23）|Number|0|
|h|am/pm中的小时数（1-12）|Number|12|
|K|am/pm中的小时数（0-11）|Number|0|
|k|一天中的小时数（1-24）|Number|24|
|M|年中的月份|Month|September,Sep,9|
|m|小时中的分钟数|Number|31|
|S|毫秒数|Number|990|
|s|分钟中的秒数|Number|50|
|W|月中的周数|Number|3|
|w|年中的周数|Number|27|
|y|年|Year|1994|
|Z|时区|RFC 822 time zone|-0800|
|z|时区|General time zone|Pacific Standard Time; PST; GMT-08:00|
