# Foundry-VTT-Macro-Collection | FVTT的公开宏收集

## Project Structure? | 项目结构？

### Macro File | 宏文件

每一个宏都是一段JavaScript代码，它们都存储在`<name>.js`中。

宏有两种分类：

- 聊天宏，存放在`/Chat`目录下

- 脚本宏，存放在`/Script`目录下

当然为了规范化存储，规定每一个宏的代码前需要带有一段特定格式的多行注释：

```js
/*
Name: 宏的名称
Version: 宏的版本（可选）
System: 宏工作的系统，这里需要和FVTT Game System的ID相符
Require: 宏依赖的模块名称，和FVTT Module的显示名称相符
Author: 宏的作者
Description: 宏的描述
*/
```

因为宏需要工作在特定的版本下，因此顶层文件夹`Vxx`标注了宏的工作版本。

## Contribution? | 贡献你的想法？

你可以直接向此仓库提交Pull Request 请求，只需要保证如上的项目结构即可。
