FSQuestion
=====

## 项目内容

整理StackOverFlow，整理出精华。

## 为什么要创建这个项目

1. 平时实践碰到的问题(或者问题少，或者问题难度低，或者没精力去提出一个好问题，或者...)，已远远不能挑战你的能力;
2. 微博、RSS、Github、文档、书籍等信息，已远远不能满足你的脑容量;
3. 厌恶无力感，更想要以一种 碾压、粉碎、独孤求败的姿态去扫荡面前的障碍;
4. 在慢慢研究一些难题，无聊之余可以刷刷题来解解闷;
5. 枯燥的工作之余，打发时间的同时也能刷刷心情；
6. 在更短的时间内，碰到更多的问题。

另：

>
#### Don’t Repeat Don’t Repeating Yourself.



## 如何使用和参与项目

>
做最好的自己，坚持下去。

#### 分支管理

基本的分支分为两个，一个是master，另外一个是develop。其中master表示这些问题和解答是靠谱的，稳定版本。develop还包括有些问题和回答还在丰富和修正中，完成后会合并到master分支上去。

从master分支和develop分支相互切换命令：
		
	git checkout develop
	git checkout master


如果你不是很熟悉git，请看[git - 简易指南](http://rogerdudler.github.io/git-guide/index.zh.html)。

#### 目录管理

比如说当前只有iOS开发的资料，所以最外面的文件夹只有一个iOS Dev（如果你是另外方向的，你可以添加新的文件夹），还有README.markdown文件。下面以iOS Dev举例，iOS Dev下分为两块内容，一块是专门放置问题解读的Questions文件夹(这类似于原材料库)，另外一块是放置专题内容的Topics文件夹(总结某块内容等)。

在Questions文件夹下，attending.markdown文件表示正在准备的内容，Tags_xx表示某个tag（stackoverflow的tag）下的内容，这个文件夹下以xxxx-xxxx.markdown命名，表示xxxx-xxxxx的问题。

在Topics文件夹下，attending.markdown文件表示正在准备的内容，其他文件以专题的名字为文件名。

	▾ iOS Dev/
	  ▾ Questions/
	    ▾ Tags_iOS/
	        1-50.markdown
	        51-100.markdown
	        attending.markdown
	    ▸ Tags_Objective-C/
	    ▸ Tags_Xcode/
	  ▾ Topics/
	      attending.markdown
	  README.markdown
     
#### 问题格式

问题格式包括两个部分：一个是问题本身，另外一个是问题的精读。

如：

__问题 + 问题链接__

__精读__
 
精读包括：

1. 对问题的简单中文描述(你可以直接翻译问题，但要更贴近阅读，不能太生硬)。
2. 解读问题中提到的方案(结合自己的经验，如果你也有疑问可描述出你的疑问)。
3. 相关拓展的资料。
4. 思考有没有更深层次的点可以挖掘。

#### 使用Markdown

如果你对Markdown还没有了解，可以参看[daringfireball](http://daringfireball.net/projects/markdown/)上的相关内容。Markdown的中文语法说明，请[戳这里](http://wowubuntu.com/markdown/)。你可以使用支持Markdown语法的[Mou](http://mouapp.com/)进行文字编辑。


