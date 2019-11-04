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