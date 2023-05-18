- html
	- Semantic
		- source
			- [Semantic HTML (web.dev)](https://web.dev/learn/html/semantic-html/)
		- relating to meaning, 易读易懂易维护；统一标准，方便沟通
		- accessibility
			- [Accessibility Object Model (AOM) — Part 1 | by BIBOSWAN ROY | Beginner's Guide to Mobile Web Development | Medium](https://medium.com/beginners-guide-to-mobile-web-development/accessibility-object-model-aom-part-1-8dc257fdb2d2)
			- 方便相关AOM(Accessibility Object  Model)读取和检索，比如读屏器
- css
- js
	- Foundation
		- [let vs var](https://stackoverflow.com/questions/762011/what-is-the-difference-between-let-and-var)
			- Scoping rules
			- Hoisting
			- Creating global object property
			- Redeclaration
		- [Hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
			- Value hoisting
				- function
			- Declaration hoisting
				- var
			- Cause behavior changes in its scope before the line in which it is declared(Temporal dead zone)
				- let, const, class
				- ```
				  const x = 1;
				  {
				    console.log(x); // ReferenceError
				    const x = 2;
				  }
				  
				  ```
				-
			-
	- Vue
		- ref vs reactive
			- [vuejs3 - ref vs reactive in Vue 3? - Stack Overflow](https://stackoverflow.com/questions/61452458/ref-vs-reactive-in-vue-3)
				- `reactive()` only takes objects, **NOT** JS primitives *(String, Boolean, Number, BigInt, Symbol, null, undefined)*
				- `ref()` is calling `reactive()` behind the scenes
				- Since `reactive()` works for objects and `ref()` calls `reactive()`, objects work for both
				- BUT, `ref()` has a `.value` property for reassigning, `reactive()` does not have this and therefore CANNOT be reassigned
- Typescript
	- [dynamically assign properties to an object in TypeScript?](https://stackoverflow.com/questions/12710905/how-do-i-dynamically-assign-properties-to-an-object-in-typescript)
		- ```
		  // simple
		  let obj: Record<string,any> = {}
		  // or more
		  interface MyType extends Record<string,any> {
		      typesafeProp1?: number,
		      requiredProp1: string,
		  }
		  ```
- HTTP
	- [Head-of-Line blocking from HTTP/1 to HTTP/3](https://github.com/rmarx/holblocking-blogpost)
	- [一个故事讲完https](https://mp.weixin.qq.com/s?__biz=MzAxOTc0NzExNg==&mid=2665513779&idx=1&sn=a1de58690ad4f95111e013254a026ca2&chksm=80d67b70b7a1f26697fa1626b3e9830dbdf4857d7a9528d22662f2e43af149265c4fd1b60024&scene=21)
- 安全
	- [数字签名是什么？](http://www.ruanyifeng.com/blog/2011/08/what_is_a_digital_signature.html)
- Interview其它人
	- JS
		- Promise
		- TS
	- Library
		- Vue
		- React
	- CSS
		- Flex
	- Http
	- New Tech
		- WebAssembly
	- Backend
		- Nodejs
		- SQL
	- CI/CE
		- webpack
	- Coperation
		- Git
		- Eslint
	- 项目经历
		- rxjs
		- puppeteer
		- jest
		- express
		- mongoose
	- Tech加分
		- Tailwind
		- 用户地址栏输入网址到页面渲染完整过程
	- 非Tech加分项
		- 英语
		- 学习渠道
		- 沟通
			- 理清业务逻辑
		- 合作