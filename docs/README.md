# docsify自动生成_sidebar.md文件

[docsify官网](https://docsify.js.org/#/zh-cn/)

## 使用方法

1. 下载仓库中的auto.js脚本
2. 将auto.js脚本置于docsify的文档目录下（如/docs）
3. 对于文档目录和其下的每一个子目录，修改文件夹名和文件名
    1. 对于每一个目录来说，所有要展示在sidebar里的文件和文件夹，都应以数字开头，例如“0-example”
    2. 对于每一个目录，“-”前面的数字代表其排序位置,按从小到大排列
    3. sidebar中只会写出“-”后的文件名
    4. 任何文件名为ignore的文件都会被忽略，例如“0-ignore”
    5. 所有的README.md文件会被默认忽略，排序时不计入
4. 文件改名完成后，使用node运行auto.js 
5. 本仓库文件结构即为示例，其中序号6的文件夹命名为ignore，生成时即会被忽略

