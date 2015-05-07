# scorm
名称：IT学习网（基于SCORM标准的资源学习平台）<br/>
项目演示地址：<a href="http://v.youku.com/v_show/id_XNzg5MjUzOTc2.html" target="_blank">http://v.youku.com/v_show/id_XNzg5MjUzOTc2.html</a><br/>
产品功能:<br/>                                                      
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;本次开发的平台是一个包含网上教学和教学辅导、网上自学、网上师生交流、网上测试、个性化推荐学习以及质量评估等多种服务在内的综合教学服务支持系统。将系统用户分为学员、教师、管理员三类，学员通过平台可进行课程学习、课程推荐（热门课程，最新课程，待参加考试课程，个性化推荐课程）、随时记录、个性化学习、师生互动、参加考试、管理学习档案、资讯公告、在线讨论等，教师在学员功能的基础上还可上传SCORM标准课件、统计课程学习情况、学习互动、课件管理等，管理员则可进行用户管理、课程管理、统计评估、课件管理，课程信息导出等。<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
我们IT学源网就是采用O2O模式，利用scorm学习标准，针对培训机构和学校做的一个学习平台。从实际问题出发，基于创新实用、资源共享、专业高效的设计原则，主要应用Spring、Structs2、Hibernate三大框架对系统进行实现。在开发过程中，编写了XML文件对SCORM课件压缩包进行解析，将课件自动解压到预设的位置并将路径保存到数据库中；应用JS和ADL（Advance Distributed Learning）解析数据和课件章节内容，实现了课件播放和断点播放；应用Struts2+JSON进行数据传输，实现了轻量级的数据交换，提高了程序的效率；应用Ajax、JQuery等技术实现异步验证等功能，保证了操作界面的流畅性；应用FusionCharts对数据进行呈现，实现了相关统计数据的3D柱形图、直方图、饼图等个性化呈现方式；采用基于协同过滤规则算法对用户目前的状况进行相对应的个性化推荐学习课程；应用excel表的导入导出课程信息；采用MD5对登录注册进行加密。结合B/S架构和MVC模式的广泛性、跨平台、多样化、人性化的特性，我们致力于为IT行业学习者和教师提供一个人性化、网络化、信息化、高效化的行业学习平台。通过注册不同类型的用户，在不同类型浏览器下对系统进行测试，结果表明。该系统功能达到了预定的设计目标，界面布局合理美观、操作方便、系统运行流畅。<br/><br/>
用户体验:<br/>
- 1.沉浸式学习。课程观看是响应式的全屏设计，多样化趣味课件。
- 2.“User Generated Content(用户原创内容)” - UGC内容沉淀：增加笔记分享功能，学员添加的批注、参考资料等更是需要沉淀的UGC，”学而时习之不亦乐乎“，习的不再仅仅是自己的笔记，其他优秀的笔记内容也是他山之玉，甚至可以是多人协同的一份笔记。UGC内容沉淀也是网站壁垒的一个重要手段， 
- 3.p2p互动：增加在线交流模块，”独学而无友则孤陋而寡闻“，但社交绝对不要走火入魔！尤其是教育。所以在线交流模块互动为学员之间的提供切磋交流机会，都是对学习的促进。
- 4.个性化推荐：基于协同过滤规则算法”因材施教“是无数教育家总结的经验，是教育的内涵和规律，互联网教育更是应该天然地支持个性化。这里是过程学习动态建模，根据用户主动学习的内容，判断用户，为用户推荐课程。
- 5.跟踪式学习：身份认证，唯一学号。为实现终身学习跟踪做准备。档案模块对学员学习进行跟踪；学分榜，（同学学习情况），学员能够快速了解身边朋友的学习情况。

注：该平台并没有开发完全，有些功能并不完善，读者可以参考其中对自己有益的地方。特别注意的是：该代码以及立意都已经申请版权。
