# MDTool
A tool which can transfer markdown to HTML.

## How it works?
Pull from Maven Central Repository:  
```xml
<dependency>
    <groupId>com.youbenzi</groupId>
    <artifactId>MDTool</artifactId>
    <version>1.2.1</version>
</dependency>
```
Or download from [here](download/).

Usage:
```java
MDTool.markdown2Html(new File(markdown_file_path));
```
or 
```java
MDTool.markdown2Html(markdown_content);
```

## Why use it?
1. Easy to use
2. Support basic markdwon syntax
3. Support table syntax
3. Support todo list
4. No other jar dependency

## Looks like
![Looks like](resource/example.jpg)

## Prepare to support the following functionality
```
好像不支下面这种格式
[msg][url]
[url]:https://www.example.com
```
## ready to resolve issues