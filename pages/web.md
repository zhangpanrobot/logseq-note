- CMS
	- contentful
		- headless cms, for content
	- strapi
	- netlify
	- airtable
- Low Code
	- webflow
	- wix
	- bubble
- animation
	- framer motion
	- react motion
	- popmotion
		- animation library
- Architecture
	- Islands
		- Framework
			- Astro
			- Marko
			- Qwik
		- [Island Architecture | Maina Wycliffe](https://mainawycliffe.dev/blog/island-architecture/)
		- [Building JavaScript Frameworks to Conquer eCommerce](https://dev.to/this-is-learning/building-javascript-frameworks-to-conquer-ecommerce-3glc)
	- components
		- [Integrate Vuetify with Storybook | Storybook](https://storybook.js.org/recipes/vuetify)
- Evolution
	- [The Evolution of Frontend DX](https://uxplanet.org/the-evolution-of-frontend-dx-5b3597f58f1a)
	-
- Interview
	- [tech-interview-handbook](https://github.com/yangshun/tech-interview-handbook)
	- [system-design-primer](https://github.com/donnemartin/system-design-primer)
	- [leetcode](https://www.techinterviewhandbook.org/grind75a)
	- 面试题收集
		- 底层
			- [一看就懂的事件循环机制(event loop) - 掘金 (juejin.cn)](https://juejin.cn/post/7002037475874963493)
		- 框架
			- Vue
				- [花了一天的时间，地板式扫盲了vue3所有API盲点 - 掘金 (juejin.cn)](https://juejin.cn/post/7164159759619194893)
		- 网络
			- 缓存
				- [你知道304吗？图解强缓存和协商缓存 - 掘金 (juejin.cn)](https://juejin.cn/post/6974529351270268958)
			- refresh token
				- 并发请求5个，此时5个token都已过期(比如用户电脑sleep几天后在网页处理)，如何处理
				- 方案：[关于无感刷新Token，我是这样子做的 - 掘金 (juejin.cn)](https://juejin.cn/post/7170278285274775560)
			- 实现并发请求
				- 实现一个批量请求函数 multiRequest(urls, maxNum)，要求如下：
				  • 要求最大并发数 maxNum
				  • 每当有一个请求返回，就留下一个空位，可以增加新的请求
				  • 所有请求完成后，结果按照 urls 里面的顺序依次打出
				- 并发控制 https://juejin.cn/post/7052700635154219015
					- 同时发10个相同的请求，如果第一个请求成功，那么剩余的请求都不会发出，第一个请求结果作为剩余请求返回
					- 如果第一个请求失败了，那么接着发编号为2的请求，如果请求成功，那么剩余的请求都不会发出，编号为2的结果作为剩余请求结果
					- 如果第二个请求失败了，那么接着发编号为3的请求，如果请求成功，那么剩余的请求都不会发出，编号为3的结果作为剩余请求结果
					- `...`以此递推，直到遇到最坏的情况需要发送10个请求
		- 算法
			- 树
				- 扁平结构转成树 [面试了十几个高级前端，竟然连（扁平数据结构转Tree）都写不出来 - 掘金 (juejin.cn)](https://juejin.cn/post/6983904373508145189)
					- ```let arr = [
					    {id: 1, name: '部门1', pid: 0},
					    {id: 2, name: '部门2', pid: 1},
					    {id: 3, name: '部门3', pid: 1},
					    {id: 4, name: '部门4', pid: 3},
					    {id: 5, name: '部门5', pid: 4},
					  ]```
- Framework
	- Astro
		- [Astro 1.0 正式发布，给前端带来了什么？ - 掘金 (juejin.cn)](https://juejin.cn/post/7131928500373553160)
- The Top 10 Websites for Coding Practice:
	- 1. Hackerrank .com
	  2. Leetcode .com
	  3. Codewars .com
	  4. Exercism .org
	  5. Codeforces .com
	  6. Hackerearth  .com
	  7. Topcoder .com
	  8. Coderbyte .com
	  9. Projecteuler .net
	  10. Codechef .com
- Book
	- [权威指南中英对照](https://js.okten.cn/)
- Blog
	- [Ryan Carniato](https://dev.to/ryansolid)
- React
	- [immer](https://zhuanlan.zhihu.com/p/146773995)
	-