##什么是CSS Hack?
　　一般来说是针对不同的浏览器写不同的CSS,就是 CSS Hack。
　　IE浏览器Hack一般又分为三种，条件Hack、属性级Hack、选择符Hack(详细参考CSS文档：css文档)。例如：
　　// 1、条件Hack
　　// 2、属性Hack
　　.test{
　　color:#0909; /* For IE8+ */
　　*color:#f00; /* For IE7 and earlier */
　　_color:#ff0; /* For IE6 and earlier */
　　}
　　// 3、选择符Hack
　　* html .test{color:#090;} /* For IE6 and earlier */
　　* + html .test{color:#ff0;} /* For IE7 */
