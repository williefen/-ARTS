# 左耳听风ARTS第二周（2019年10月27日）
1.**Algorithm**
**链接：**一次面试题

求出 1！+2!+3!+..+n! 之和。
解：(1) #include<stdio.h>
		int main()
		{
			int i;
			int n = 0;
			int product = 1;
			scanf("%d" ,&n);
			for(i=1; i<=n; i++)
			{
				product *= i;
			}
			printf("%d", product);
			return 0;
		}
		(2)#include<stdio.h>
		int main()
		{
			int i;
			int sum = 0;
			int n = 0;
			int product = 1;
			printf("请输入数字：");
			scanf("%d",&n);
			for(i=1; i<=n; i++)
			{
				product *= i;
				sum += product;
			}
			printf("%d", sum);
			return 0;
		}

 在第一步的基础求阶乘上多定义一个变量sum,对每次求得的阶乘都加给sum并将sum返回到循环外部的sum中，在接下来的循环中的sum值就是外部sum的值；这样，就会求到
sum值。

2.review
本周主要是去面试了。总的来说现在的公司要求都比较高吧，对于技术和业务的要求也比较高，spring boot 和分布式微服务在项目中怎么样使用的这些问题一直在问，要好好复习！！
3.Tip
https://mijisou.com 秘籍搜索 一款比较好的搜索引擎 广告较少= =
现在公司也要求前端技术了，所以这块也要重视起来。
4.Share
推荐一下我经常学习的公众号 ‘Java极客技术’ 以及极客星球 由十年老兵纯洁的微笑创建。分享一下面试经历 技术和对萌新答疑 🙂

https://t.zsxq.com/bQ7mqJQ

















