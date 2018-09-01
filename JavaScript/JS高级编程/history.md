# JavaScript历史

Just before Netscape Navigator 2 was offi cially released, Netscape changed LiveScript’s name to JavaScript to capitalize on the buzz that Java was receiving from the press.

就在Netscape Navigator 2正式发布之前，Netscape将LiveScript的名称改为JavaScript，以充分利用Java从媒体上获得的嗡嗡声。

Because JavaScript 1.0 was such a hit, Netscape released version 1.1 in Netscape Navigator 3.

由于JavaScript 1.0如此受欢迎，Netscape在Netscape Navigator 3中发布了1.1版本。

Brendan Eich, who worked for Netscape at the time, began developing a scripting language called Mocha, and later LiveScript, for the release of Netscape Navigator 2 in 1995, with the intention of using it both in the browser and on the server (where it was to be called LiveWire).

当时为Netscape工作的Brendan Eich开始开发一种名为Mocha的脚本语言，以及后来的LiveScript，用于在1995年发布Netscape Navigator 2，目的是在浏览器和服务器上使用它（在那里它被称为LiveWire）。

Shortly after Netscape Navigator 3 was released, Microsoft introduced Internet Explorer 3 with a JavaScript implementation called JScript (so called to avoid any possible licensing issues with Netscape).

Netscape Navigator 3发布后不久，微软就推出了一个名为JScript的JavaScript实现Internet Explorer 3（所谓的避免Netscape可能存在任何许可问题）。

This major step for Microsoft into the realm of web browsers in August 1996 is now a date that lives in infamy for Netscape, but it also represented a major step forward in the development of JavaScript as a language.

1996年8月，微软进入Web浏览器领域的这一重要步骤现在已成为Netscape的耻辱日期，但它也代表了JavaScript作为一种语言发展的重要一步。

In 1997, JavaScript 1.1 was submitted to the European Computer Manufacturers Association (Ecma) as a proposal.

1997年，JavaScript 1.1作为提案提交给欧洲计算机制造商协会（Ecma）。

Technical Committee #39 (TC39) was assigned to “standardize the syntax and semantics of a general purpose, cross-platform, vendor-neutral scripting language”(www.ecma-international.org/memento/TC39.htm). Made up of programmers from Netscape,
Sun, Microsoft, Borland, NOMBAS, and other companies with interest in the future of scripting, TC39 met for months to hammer out ECMA-262, a standard defi ning a new scripting language named ECMAScript (often pronounced as “ek-ma-script”).

技术委员会＃39（TC39）被指定为“标准化通用，跨平台，供应商中立的脚本语言的语法和语义”（www.ecma-international.org/memento/TC39.htm）。
由Netscape，Sun，Microsoft，Borland，NOMBAS以及其他对脚本未来感兴趣的公司的程序员组成，TC39几个月来一直在敲定ECMA-262，这是一种标准定义为ECMAScript的新脚本语言（通常发音）作为“ek-ma-script”）。

Indeed, a complete JavaScript implementation is made up of the following three distinct parts (see Figure 1-1):
The Core (ECMAScript)
The Document Object Model (DOM)
The Browser Object Model (BOM)

ECMAScript, the language defi ned in ECMA-262, isn’t tied to web browsers.

ECMAScript是ECMA-262中定义的语言，与Web浏览器无关。

The different versions of ECMAScript are defi ned as editions (referring to the edition of ECMA-262 in which that particular implementation is described). The most recent edition of ECMA-262 is edition 5, released in 2009.

ECMAScript的不同版本被定义为版本（参考ECMA-262的版本，其中描述了该特定实现）。最新版的ECMA-262是2009年发布的第5版。

The first edition of ECMA-262 was essentially the same as Netscape’s JavaScript 1.1 but with all references to browser-specifi c code removed and a few minor changes: ECMA-262 required support for the Unicode standard (to support multiple languages) and that objects be platform-independent (Netscape JavaScript 1.1 actually had different
implementations of objects, such as the Date object, depending on the platform). This was a major reason why JavaScript 1.1 and 1.2 did not conform to the fi rst edition of ECMA-262.

ECMA-262的第一版基本上与Netscape的JavaScript 1.1相同，但删除了对浏览器特定代码的所有引用，并进行了一些小的更改：ECMA-262需要支持Unicode标准（支持多种语言）和对象与平台无关（Netscape JavaScript 1.1实际上有不同的对象实现，例如Date对象，具体取决于平台）。这是JavaScript 1.1和1.2不符合ECMA-262第一版的主要原因。

The second edition of ECMA-262 was largely editorial. The standard was updated to get into strict agreement with ISO/IEC-16262 and didn’t feature any additions, changes, or omissions. ECMAScript implementations typically don’t use the second edition as a measure of conformance.

第二版ECMA-262主要是编辑性的。该标准已更新，与ISO / IEC-16262达成严格协议，并未包含任何添加，更改或遗漏。 ECMAScript实现通常不使用第二版作为一致性的度量。

The third edition of ECMA-262 was the first real update to the standard. It provided updates to string handling, the definition of errors, and numeric outputs. It also added support for regular expressions, new control statements, try-catch exception handling,  and small changes to better prepare the standard for internationalization. To many, this marked the arrival of ECMAScript as a true programming language.

第三版ECMA-262是该标准的第一次真正更新。它提供了字符串处理，错误定义和数字输出的更新。它还增加了对正则表达式，新控制语句，try-catch异常处理和小更改的支持，以更好地为国际化准备标准。对许多人来说，这标志着ECMAScript作为一种真正的编程语言的到来。

The fourth edition of ECMA-262 was a complete overhaul of the language. In response to the popularity of JavaScript on the Web, developers began revising ECMAScript to meet the growing demands of web development around the world. In response, Ecma TC39 reconvened to decide the future of the language. The resulting specifi cation defi ned an almost completely new language based on the third edition. The fourth edition includes strongly typed variables, new statements and data structures, true classes and classical inheritance, and new ways to interact with data.

第四版ECMA-262是对该语言的彻底改革。为了响应JavaScript在Web上的普及，开发人员开始修改ECMAScript以满足全球Web开发不断增长的需求。作为回应，Ecma TC39重新召开会议以决定该语言的未来。由此产生的规范定义了基于第三版的几乎全新的语言。第四版包括强类型变量，新语句和数据结构，真实类和经典继承，以及与数据交互的新方法。

As an alternate proposal, a specifi cation called “ECMAScript 3.1,” was developed as a smaller evolution of the language by a subcommittee of TC39, who believed that the fourth edition was too big of a jump for the language. The result was a smaller proposal with incremental changes to ECMAScript that could be implemented on top of existing JavaScript engines. Ultimately, the ES3.1 subcommittee won over support from TC39, and the fourth edition of ECMA-262 was abandoned before offi cially being published.

作为一个替代提议，一个名为“ECMAScript 3.1”的规范被TC39的一个小组委员会发展为该语言的一个较小的演变，他认为第四版对于该语言来说太大了。结果是一个较小的提案，对ECMAScript进行了增量更改，可以在现有的JavaScript引擎上实现。最终，ES3.1小组委员会赢得了TC39的支持，第四版ECMA-262在正式发布之前就被放弃了。

ECMAScript 3.1 became ECMA-262, fifth edition, and was officially published on December 3, 2009. The fifth edition sought to clarify perceived ambiguities of the third edition and introduce additional functionality. The new functionality includes a native JSON object for parsing and serializing JSON data, methods for inheritance and advanced property definition, and the inclusion of a new strict mode that slightly augments how ECMAScript engines interpret and execute code.

ECMAScript 3.1成为ECMA-262，第五版，并于2009年12月3日正式发布。
第五版旨在澄清第三版的含糊不清并引入其他功能。
新功能包括用于解析和序列化JSON数据的本机JSON对象，继承方法和高级属性定义，
以及包含稍微增强ECMAScript引擎解释和执行代码的新严格模式。

It was then that the World Wide Web Consortium (W3C), the body charged with creating standards for web communication, began working on the DOM.

就在那时，负责创建网络通信标准的万维网联盟（W3C）开始研究DOM。


## 总结
ECMAScript, which is defined in ECMA-262 and provides the core functionality
ECMAScript，在ECMA-262中定义并提供核心功能
The Document Object Model (DOM), which provides methods and interfaces for working
with the content of a web page

文档对象模型（DOM），它提供了处理网页内容的方法和接口
The Browser Object Model (BOM), which provides methods and interfaces for interacting
with the browser
浏览器对象模型（BOM），提供与浏览器交互的方法和接口

## 词汇
round-trip： 往还

metaprogramming：元编程

predicted：预料到的

gained：获得

popularity：声望

Netscape：网景

intention：意向
名词
意向, 意图, 打算, 用心, 用意, 意, 动机, 心术, 作用, 图

alliance：联盟

capitalize：利用

hit：
中文(简体)
击中

动词
击中, 击, 打击, 撞, 撞击, 敲, 触, 殴打, 拍, 擂, 掊, 揕, 殴

名词
击中, 揕, 轰动一时的人, 轰动一时的物

fledgling：雏鸟
雏鸟, 雏儿

realm：领域
名词
领域, 境界, 王国

infamy：骂名

criteria
中文(简体)
标准
名词
标准, 准则, 规范, 则, 准绳, 尺度, 准, 轨范

compliant
中文(简体)
兼容

fate
中文(简体)
命运
名词
命运, 命, 运气, 气数, 运, 死活, 阄, 气运
动词
缘份

comply
中文(简体)
执行
动词
执行, 应承, 实现

adical
中文(简体)
激进
名词
激进, 基, 部首, 根, 根号
形容词
急进

unprecedented
中文(简体)
史无前例
形容词
史无前例, 空前的

tremendous
中文(简体)
巨大
形容词
巨大, 很大, 庞大, 巨, 优秀, 盛大, 优, 庞, 硕大无朋, 优等, 非常的, 广大的, 禕

factions
中文(简体)
派系
名词
派, 阵营, 派别, 帮派, 宗派, 党派, 翼, 宗, 政治派別

exclusive
中文(简体)
独家
形容词
独家, 优, 优势, 独占的
副词
只, 仅仅, 独占地

the World Wide Web Consortium (W3C)
中文(简体)
万维网联盟（W3C）

Consortium
中文(简体)
联盟
名词
合伙, 会社

traversals
中文(简体)
遍历

Scalable Vector Graphics (SVG)
中文(简体)
可缩放矢量图形（SVG）

realistic
中文(简体)
实际
形容词
实际, 切实

dissipated
中文(简体)
消散
形容词
放荡, 浪荡, 糜烂, 宕, 薄行, 荒唐

Custom objects such as XMLHttpRequest and Internet Explorer’s ActiveXObject

descendant
中文(简体)
后裔
名词
后裔, 裔, 后人, 后嗣, 儿孙, 后辈, 晜, 后世子孙
形容词
起源的

spun
中文(简体)
告诉

evolution
中文(简体)
演化
名词
演化, 进化, 发展, 进程, 开方, 发达


###### 参考
- https://auth0.com/blog/a-brief-history-of-javascript/
- JavaScript高级编程





