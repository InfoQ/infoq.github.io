---
layout: page
title: "如何为InfoQ撰写新闻"
description: ""
---
{% include JB/setup %}


以下内容部分翻译、整理自InfoQ英文站的新闻撰写指南：


##啥是新闻？

对于新编辑而言，分辨“何为新闻”和“什么不是新闻”是最大的难题之一，不过写着写着就好了。

简单来说，新闻就是**新的知识**，我们用千字以内的篇幅将其表述出来。这个新知识是技术社区所关心的。

记住，InfoQ的宗旨是“促进软件开发领域知识与创新的传播”，这是判定一篇新闻是否合适的核心标准。以下是一个简单的checklist：

1. 是不是有变化？
2. 是不是有创新？
3. 是不是有不同的思考？
4. 社区会觉得这个有意思吗？


## 新闻的类型

### 纪实类

* [线下活动的演讲纪实](news-event-takeaways.html)
* [新产品发布、版本更新纪实](news-new-product.html)
* [新鲜有创意的技术项目纪实](news-creative-projects.html)
* [战略发布纪实](news-strategy-announcement.html)
* [技术应用状态纪实](news-growth-summary.html)
* [事故纪实](news-failure.html)
* [新书、新文章、新文档发布纪实](news-new-book.html)
* 某人最近说了什么话纪实

### 二次记录型（讨论、观点整理类）

* [社区讨论纪实](news-discussions.html)

### 汇总整理型

* [细分领域的定期阅读列表](news-reading-list.html)
* 大会值得关注的议程预告




## 新闻的基本结构

[**![](http://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Inverted_pyramid_2.svg/300px-Inverted_pyramid_2.svg.png)**](http://www.google.com/url?q=http%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2Fc%2Fca%2FInverted_pyramid_2.svg%2F300px-Inverted_pyramid_2.svg.png&sa=D&sntz=1&usg=AFrqEzc2JrEhqCtTK4NZfCu78Ms7dT1ocg)

倒金字塔新闻撰写方式，强调将重要的信息放在前，补充信息放在后。

* 标题：简短、准确，包含新闻中最重要的信息
* 摘要：这篇新闻如果发140字以内的微博，该怎么写？当然是最能引发观众兴趣的信息
* 正文：一般千字以内
	* 第一段：发生了什么事？谁在什么时间什么地点做了什么事
	* 第二段：这件事是怎么回事，为什么会有这件事
	* 第三段：相关阅读素材，相关人员对该事件的讨论引用
	* 第四段：一句话总结

###注意事项

1. 针对素材的引用不得超过原素材内容的30%，并需要明确标注素材来源
2. 如果是对英文素材的完整翻译，需获取作者授权
3. 一篇新闻只说一件事
3. 写作中不要使用“我/你/他”等代词，而是以第三方直叙的方式记录
4. 超链接以暗链形式挂在文字上，文字跟链接地址相关。不要直接放URL到正文中
5. 超链接不要忘了http(s)://的前缀！
6. 同样的超链接不要重复添加，一篇新闻中添加一次即可
5. 引用部分使用blockquote的格式






## News writing design patterns, guidelines & best practices
News is a very different animal from typical online writing, and news on InfoQ is also different from typical media writing because we are a technical community and not a news organization. There are important **patterns **for how to write news:  
  

### Guidelines for single-source news items
Almost every time we've had a serious public complaint/incident about InfoQ news it's been something which relied too heavily on a single source, with complaints saying that either it was quoted too much, it was taken out of context, it was biased, or it felt like a sales pitch.  We don’t want to copy someone's blog, but we also don’t want to just do a very short post saying “go see this”.  The value InfoQ brings is in providing value in a quicker-summary read of key concepts that might be learned from the other source, and add more context (background info not in the source, links to related stuff, etc).

**Guidelines:**


1. Your summary should be at least 1/5th shorter (including quotes) than the source.  If the size of your write-up including quotes approaches the same size as the source article then this is leaning on copying.
1. Try to distill the key points, you don’t need to summarize everything.
1. Blockquote key sections that express an idea well, and use your own more succinct paraphrasing for areas where the original author was verbose.
1. News should rarely just quote one blogger – aggregating multiple viewpoints on a topic would be preferable.
1. The title of such news should not be significantly similar to any of the blog post titles quoted.
1. When using images from a post, do not directly use the blogger’s file URL in a post. Instead, copy the image to InfoQ, embed that in the news item, and link from the InfoQ image to the blogger’s original file.  


**Examples:**  
[Five Common Ajax Anti-Patterns](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2007%2F03%2Fcommon-ajax-anti-patterns&sa=D&sntz=1&usg=AFrqEzcKwn98zBayOQQPUdmlpfMwMFU5Wg)  
[Dependency Injection: New Ground or Solid Footing?](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F01%2Fdependency-injection&sa=D&sntz=1&usg=AFrqEzc2ju7t1YoLkSFSKnETxVFtOGjJFA)  
[Partitioned-Iterative More Appropriate for EA than Zachman, TOGAF?](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2007%2F07%2Fpartitioned-iterative&sa=D&sntz=1&usg=AFrqEzeqkUf-yaN1qoJBxt66NkyC-nPHrg)  
[TestNG Concluded More Suitable for Large-Scale Testing Than JUnit 4](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2FTestNG-VS-JUnit-4&sa=D&sntz=1&usg=AFrqEzcCEeq2d2Ghllslaou1CkxehjyIag)  
[Prefer Broad Design Skills over Platform Knowledge](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F01%2Fprefere-broad-design-skills&sa=D&sntz=1&usg=AFrqEzfkq8-26crHKMSYEVyqHQVOcqAerA)  



### **Make titles qualitative**
When thinking about titles for product releases, try to avoid 'ABC vX.Y released' and instead focus on something qualitatively interesting about the release, such as:  
 1) what the product DOES - this works well if the product is new (not announced before) or generally not well known in the community.  
     - eg: Esper: High Volume Event Stream Processing and Correlation in Java  
 2) some key aspect(s) of the new release  
     - eg: Seam 1.1.5: Now tested on all major appservers  
 3)  or if you are drawing blanks on the above two, and if the product is not well known, then try to add in some text about what it 'is'. For example:  
    -  eg: Continuous Integration Server QuickBuild 1.2 Released  
  
Many of our readers are just scanning headlines when deciding to read our news and without more descriptive titles, there are likely to be people who may have been interested in your post that wouldn't have read it because they don't recognize the product name.  

### **Levels of abstraction**
News is made up of three parts: the title, the summary, and the body. When we write our news, we should write each of these three elements as though they were different levels of abstraction of the same piece of news, as opposed to one holistic piece. Specifically the:


* **body **of a news item should be a summary of the news itself (drawn from one or many sources). All the key points of the news item that your peers would be interested in should be in the body. Here is example [where very lengthy blog post was summarized into a few paragraphs](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F03%2Fterracotta-as-message-bus&sa=D&sntz=1&usg=AFrqEzfoMjHJ8sJVvydrcaMaft3YgfR6lg), and also [a lengthy technical presentation](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2007%2F05%2Fwcf-web-programming-model&sa=D&sntz=1&usg=AFrqEzcUeEUCxjC06x2yVVtLeH9kUzrvmQ).
* **summary **should be a summary of the body. Choose the super-key points from the story and put them in the summary, but don't include any new points in the summary that weren't in the body. The summary, is a summary of the body.
* **title** should be a summary of the summary, any key points from the summary should make it into the title. A title should be as descriptive as possible, it's important to think about a title as a summary of the news event as that leads to more factual titles, more developer friendly, and less sensationalism.

Since each of these three are often seen in isolation (titles in feed readers, summaries on the homepage/newsletters, body on the news article page itself), it is important to make each as descriptive as possible and also to make sure there aren't dependencies between them. Specifically, when you write your body, **don't assume people have read the summary. **The summary is based on the body, not the other way around. A common practice Floyd often did at TSS is write the summary first, then re-use the summary as the first paragraph of the body and then add additional details below it, or expand the body.

Examples:

                > > > 1) **GemStone Reveals Plans for MagLev Ruby VM at RailsConf 2008**

**summary:** At RailsConf on Friday, Avi Bryant and Bob Walker of GemStone revealed plans for the MagLev project. MagLev will run Ruby on Rails within GemStone's distributed object technology. The MagLev VM, although only partially implemented, so far outperforms MRI 1.8.

[Read the body too.](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F05%2FMagLevAtRailsConf&sa=D&sntz=1&usg=AFrqEzcnMgu7owXetKC-P2RMxgu4hRhH3A)

2) **Google 'simplifies web development' with AppEngine**

**summary:** At Campfire One on April 7th, 2008, Google introduced Google App Engine as a way to simplify the job of creating, running and scaling web applications, to make it 'easy.' In essence, Google App Engine allows you to build web applications locally using and then deploy them on Google's infrastructure.

[Read the body too.](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F04%2Fgoogle-app-engine-simplifies-web&sa=D&sntz=1&usg=AFrqEzf1WOC4L_vsaH2CpkaTxeKfTwXYfA)



  



### Product Announcements   

Cover a release if either the product (or people behind it) is widely popular or if the upgrade has important innovations that are pushing the whole market forward / filling a gap you know to be important to your community.   


Keep in mind all of the other best practices in this guide, such as **marketing free**, make **titles qualitative**, **coarse grained **(not minor releases).   
Where at all possible, increase quality by embedding q&a with the progenitors of the product, a described in the [embedding q&a tutorial](https://sites.google.com/a/c4media.com/editorial/Home/Advanced-News).  This gives you a chance to ask 'why and how' questions to make a post more interesting than your typical 'ABC new features of Z' type posts.  Product Managers and PR people are highly motivated to respond to your q&a fast.  **  
**

The way we account for concerns about end-user bias is to be careful in choosing news that is infact newsworthy, and to have a variety of references and viewpoints (in particular, ones which are well thought out or which act as counterpoints to other perspectives in the article), this makes the article a more solid and "reference-quality" piece of content. We also inform submitters of product stories that we have a quasi-volunteer system where editors self-select news they find interesting, so there should not be any pressure on any one editor to cover a product. If product person emails you personally and you're not interested in covering a post, feel free to pass on to the Chief editor to act as a friendly blocker. :)

**Training & Consulting is usually not news.**  In general we don't cover announcements about SPECIFIC consulting or training offerings (as opposed to general topics related to training, consulting, methodology which are ok) these are rearly actionable by the readers and in practice there is not usually a sufficient change/innovation truly unique about training and consulting offering that dozens of other service providers couldn't also claim.  The only exceptions may be if there is a political reason to cover some news.   


  



### Make sure your news answers more questions than it raises / self containment
When writing the body and summary (even paragraphs within them), you should make sure that each unit of writing is self contained in terms of the knowledge/data you are adding to it. What I mean is, try to write it so that the reader will get a feeling of completion/understanding of the writing, and not more confusion. We should be writing news that includes data that answers the most obvious questions a reader would have about a news item, and not in a manner that raises even more questions for them. Many writers like to litter their writing with questions or obscure references (that are not introduced) which can be annoying to readers. If you refer to something obscure, then make sure you introduce it.

If they leave feeling confused or having more questions, then we have not really helped them. For example, while making a passing reference to 'Websphere' is ok because everyone knows what it is, making a passing reference in a news body to "JFox" would raise the question "what is JFox?", so you should prefix it in your writing as follows "chinese [J2EE?](http://c4media.jot.com/WikiHome/Editorial/News%20How-to/J2EE?create=1&createFromLink=1&sourcePage=%2FWikiHome%2FNews+How-to) appserver JFox" or something like that.

Another way to think about the idea of making sure that your writing answers more questions than it raises is to make sure each unit of writing is self-contained.

  

### News is an event that occurs, not an idea or something abstract, unless you specifically mark it otherwise
News is supposed to have a key component, which is that is should be something "new", something that happened, something that indicates an action has occured. A technical article for example is not news, as knowledge is not an event that occured, it's just knowledge. However, there are ways to spin things that are not quite news into news. For example:Instead of:


* Ajax using XMLRequest and Struts Example, **write**: Ajax using XMLRequest and Struts Example "Online", or "Posted", or "Available"
* Hibernate 3.0, **write**: Hibernate 3.0 Released/is out/launched
* AOP Myths and Realities, **write**: AOP Myths and Realities Published

Also, recall that our news is not just about new releases and things that are traditionally news, it's also about new debates and ideas that are important to the community. So when you want to publish something that isn't clearly "an event that has occured", isn't clearly news that is, then prefix it with something to mark what it is, that way you are explaining why you are posting it. Examples:


* A question/debate: Instead of "SCRUM should be abandoned for CMMI", write: "Debate/Opinion/Scrum should be abandoned for CMMI", or you can add a question mark to it which also indicates it's not news, such as: "Should we abandon Scrum for CMMI?". [Example](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2006%2F12%2Fjson-vs-xml-debate&sa=D&sntz=1&usg=AFrqEzeVoKL3ZS0MALk2QTiSuXXQp1qe8w), and another example: [Does TDD Really Ensure Quality?](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F01%2Fdoes-tdd-mean-quality&sa=D&sntz=1&usg=AFrqEzfOF8V0pr0QppKIIHwpJ5hotBvRvA)
* A controversial opinion: Instead of "EJB Sucks", write "Opinion: EJB Sucks", or if the opinion was expressed by someone famous, that too makes it newsworthy, so you could write "Rod Johnson: EJB Sucks!"]. Real world example: [Richard Monson-Haefel: It's too late to save Java EE](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2FJava-EE-Demise-Report&sa=D&sntz=1&usg=AFrqEzdWY2P6JQ5OObVWFDUlMEPD8tiacA).


###   


### Marketing free
Make sure that your writing doesn't **smell **like marketing. In general, it should remove all 'adjectives' (fast, easy, mission critical, cheap, etc) and anything that seems unproven and instead be written factually. For example, once we go live you will be frequently contacted by vendors, open source project leaders, even friends, to post news about their press releases. When you write the news item, be sure to strip it of anything that smells like marketing before you put it live. For example, the following news item is BAD (some specific bad smells highlighted):

<table><tbody><tr><td>**Terracotta Clusters Apache Tomcat for Free**

Terracotta, Inc., developer of groundbreaking solutions for Java scalability, today announced Terracotta Sessions for Tomcat, the industry’s first drop-in clustering solution for the Apache Tomcat application server. The move gives organizations a free, clustering solution that meets their need for load-balanced Tomcat application servers.It also helps lower costs by eliminating performance tuning from the development life cycle.

</td><td> </td></tr></tbody></table>
and can be reworded to remove the marketese like this. Note the removal of marketese and insertion of technical facts:

<table><tbody><tr><td>**Terracotta releases free 4 node Tomcat Session Clustering**

JVM clustering vendor Terracotta has released for free use their Terracotta Sessions for Tomcat. The product is based on their distributed shared objects (DSO) product which uses a hub and spoke architecture and can synchronize changes across nodes at the field level (instead of serialization). The license allows projects with up to 4 nodes in their cluster to use it for free.

</td><td> </td></tr></tbody></table>
  

### Coarse grained
  
News topics should be **important, **and not focus on little, insignifcant things. This rule is highly subjective but it's just a guideline. For example, when announcing products / open source projects, the general rule of thumb is to never post a 3rd level point release (x.y.Z) announcement, who cares about it if it's such a minor point release? Also, we shouldn't be announcing the same project/project more than once every 2 months unless something really major has happened.

Editors need to use their judgement on this one, but be sure that news is fairly coarse grained in nature and not announcing minor things, or that devalues the site as it wastes peoples time. People should learn to rely on InfoQ as the goto place to track things that **matter **in enterprise software development.

  

### Emphasize the news, not the peripheral stuff
A difficult but important point is that when surfing articles, blogs, and interviews news, try emphasize the subject that is new, not the actual blog, article, or interview itself. For example, a new idea or technique is very relevant to the audience, not the blog it came from. Link to the blog but emphasize the actual new idea/technique in the summary and body instead of the blog. In this way we are providing value by extracting what's new instead of simply aggregating a blog. Examples:. 

[Custom MSBuild Tasks](http://www.google.com/url?q=http%3A%2F%2Fwww.infoq.com%2Fnews%2F2008%2F02%2Fcustom-msbuild-tasks&sa=D&sntz=1&usg=AFrqEzfWGt-K2dd7taZyfmyRcfPR7hn2gw). The news summarizes the content of two blog posts into a concise list of 8 steps to make when creating a custom task.

  



### Provide so much value that people don't need to click for more (opposite of writing teasers)
A common best practice in the media is to write titles and summaries that are teasers, giving people a taste of something but ultimately raising more questions in the readers mind than are answered, in hopes that they'll click through and drive page views. On InfoQ we take the opposite approach. Considering that the reader is the customer, we should write our titles and summaries to be summarative enough that someone will only click through to read the body if they are really interested in the subject or want to see the discussions. Similarly, the body of a news item should be informative enough to be self-contained and people should only click through to the sources of the news item if they are really keen to find out more and read through all the minutia.

  


