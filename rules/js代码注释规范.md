# js代码注释规范笔记

## **文件注释**

>文件注释位于文件的最前面，应包括文件的以下信息：

- 概要说明及版本（必须）
- 项目地址（开源组件必须）
- 版权声明（必须）
- 开源协议（开源组件必须）
- 版本号（必须）
- 修改时间（必须），以ISO格式表示（可使用Sublime Text的InsertDate插件插入）文件注释必须全部以英文字符表示，并存在于文件的开发版本与生产版本中。

```js
/*!
 * jRaiser 2 Javascript Library
 * waterfall - v1.0.0 (2013-03-15T14:55:51+0800)
 * http://jraiser.org/ | Released under MIT license
 */

 /*!
 * kan.56.com - v1.1 (2013-03-08T15:30:32+0800)
 * Copyright 2005-2013 56.com
 */

 /*!
 * jRaiser 2 Javascript Library
 * sizzle - v1.9.1 (2013-03-15T10:07:24+0800)
 * http://jraiser.org/ | Released under MIT license
 *
 * Include sizzle (http://sizzlejs.com/)
 */
```
## **文档注释**

```js
/**
 * 模块说明
 * @module 模块名
 */

/**
 * 类说明
 * @class 类名
 * @constructor
 */

/**
 * 类说明
 * @class 类名
 * @constructor
 */

/**
 * 方法说明
 * @method 方法名
 * @for 所属类名
 * @param {参数类型} 参数名 参数说明
 * @return {返回值类型} 返回值说明
 */


```