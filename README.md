# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm139选课排课系统的设计与开发+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T48XecE9G?p=134)


# 第1章  绪论
## 1.1  系统开发背景
机遇与挑战始终并存。在开放的互联网平台面前，选课排课系统的信息管理面临着巨大的挑战。传统的管理模式局限于简单数据的管理，无法适应不断变化的市场格局。在早期阶段，在将计算机技术和网络技术融入学生选课数据管理方法之前，所有管理方式都通过人工操作完成了管理信息的交换和处理，效率低，错误率高，导致严重浪费物质资源，人力资源和财政资源。

系统管理也都将通过计算机进行整体智能化操作，对于网上选课排课系统所牵扯的数据信息及数据保存都是非常多的，举例像所有的个人中心、公告信息、班级管理、学生管理、教师管理、课程名称管理、课程信息管理、课表信息管理、学生选课管理、退课信息管理等，为此开发了本选课排课系统，为用户提供一个网上选课排课系统的平台，同时方便管理员对学生和教师进行课程选课信息进行处理。该系统满足了不同权限用户的需求，即管理员、及用户，管理相关信息可以及时、准确、有效地进行系统化、标准化和有效的工作。
## 1.2  课题意义
由于现在的选课排课系统用户所负责的工作越来越多，所以涉及到的数据也是相应增多。传统的学生选课信息查询模式面对大量数据信息，再给用户提供数据的时候效率会慢，而且用户等待的时间也相应的比较长，所以这样既不能满足用户的需求，不能给用户提供更有效的数据信息的同时，对于学生选课和教师课程等信息，进行查看或编操作，管理人员的工作效率低，所以开发网上选课排课系统可以改变这些缺憾。

目前，网上选课排课系统是吸引很多人的注意，通过互联网来搭建网上选课排课系统可以给用户提供更好的服务而且对于用户可以更好的提高工作效率。也可以更好的为我们建造更多区域及数据信息。

传统的学生选课信息的统计都是采用人工检查与核实，信息量大，由于使用的是人手工统计数据工作量大，而且出错率高，当然还会存在很多数据存储及丢失的问题，对于查找某一条数据比较麻烦，耽误时间，影响工作效率，为了提高工作效率我们急需开发出这套选课排课系统，网上选课排课系统相关信息成为必然。
## 1.3  研究内容
选课排课系统采用JSP和开发环境所使用技术开发，实现了选课排课系统的系统化、高效化、科学化。

选课排课系统主要有用户通过登录进入到用户操作界面，方便用户对学生选课信息的查看及管理操作，对于管理员可以对数据信息的统计及管理操作，选课排课系统的实现主要是对整个系统想要实现的功能及功能的每一步实现、系统的整体的分析、设计、代码的编写等内容进行实现操作，最后完成整个智能化管理系统的操作。


# 第2章  系统需求分析

## 2.1可行性分析
1、技术可行性分析：

技术可行性主要取决于系统设计和开发中使用的软硬件配置是否能满足应用要求，相关技术是否能保证系统设计完成后的正常运行。本网站在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，使用比较成熟的MYSQL数据库进行对系统后台的数据交互，根据技术语言对数据库管理，结合需求进行修改维护，可以使得系统运行更具有稳定性和安全性，从而完成实现系统的开发。该系统目前采用比较成熟的JSP技术，它可以在普通文本编辑器上编辑而无需编译，它可以直接在服务器上执行。它易于学习和操作，使用B/S模型作为软件开发的基础是高度兼容和灵活的，从技术可行性上来分析系统开发时完全可行的。

2、经济可行性

选课排课系统的开发，第一步要考虑到所要开发的系统在开发完成所要使用的费用问题，把该系统作为毕业设计，所以在经济可行性是要必须分析的，系统的开发是否需要花钱购买其他的软件或作者硬件，还有一些接口的对接，如果开发整个系统需要费用去置办这些，肯定是行不通，当然，通过学生自己动手开发，遇到比较难解决的问题，可以通过寻找指导老师及一些同学，进行帮助解决问题，不需要其他费用的支出，所以说学生开发的选课排课系统在经济上是可行的。

3、 操作可行性

可操作性主要是对选课排课系统设计完成后，用户的使用体验度，对于管理员可以通过系统随时管理相关的数据信息，并且对于管理员、学生、老师三个用户角色，都可以简单明了的进入到自己的系统界面，通过界面导航菜单可以简单明了地操作功能模块，方便用户信息需求和管理员管理数据信息，对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在系统的可操作性是完全可以的。
## 2.2非功能分析
对于性能分析，与传统的管理方式相比，传统的管理方式是使用人工通过用纸和笔进行数据信息的统计和管理，并且这种方式对于存储和查找某一数据信息都比较麻烦，随着计算机网络的到来，这种传统的方法很难适应当下社会的发展，不仅降低人们的办事效率，而且还需要很多的人力和物力，对于使用的时间和所要花费的费用都是比较高的，为了降低成本费用，提高用户的工作效率，进行开发一套基于计算机和网络技术的选课排课系统。

选课排课系统的开发设计时一个独立的系统，以MYSQL数据库进行数据的存储开发，主要是为了实现学生选课信息的处置和管理，并且系统采用B/S结构，进行搭建于JSP技术的选课排课系统平台，这样不仅不会出现传统的管理差异、低效率，而是跟传统的管理信息恰好相反，选课排课系统的实现可以节约资源，并且对于业务的处理速度也提高，速度快、效率高，功能性强大。
## 2.3 项目设计原则
1、关于选课排课系统的基本要求

（1）功能要求：管理员可以实现个人中心、公告信息、班级管理、学生管理、教师管理、课程名称管理、课程信息管理、课表信息管理、学生选课管理、退课信息管理等功能模块。

教师可以实现个人中心、公告信管理、课表信息管理、课程信息管理、学生选课管理、退课信息管理功能模块，进行相对应操作。

学生可以实际个人中心、公告信息管理、课表信息管理、课程信息管理、学生选课管理、退课信息管理等功能模块，进行相对应操作。

（2）性能：在不同操作系统上均能无差错实现在不同类型的用户登入相应界面后能不出差错、方便地进行预期操作。

（3）安全与保密要求：用户都必须通过身份验证才能进入系统，并且用户的权限也需要根据用户的类型进行限定。

（4）环境要求：支持多种平台，可在Windows系列、Vista系统等多种操作系统下使用。

2、开发目标

选课排课系统的主要开发目标如下：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现用户对信息的控制和管理。

（3）方便查询信息及管理信息等；

（4）通过网络操作，改善处理问题的效率，提高人员利用率；

（5）考虑到用户多样性特点，要求界面简单，操作简便。

3、设计原则

本系统采用JSP技术，Mysql数据库开发，充分保证了系统稳定性、完整性。

选课排课系统的设计与实现的设计思想如下：

1、操作简便、界面良好：简单明了的页面布局，方便查询相关信息

2、即时可见：对系统信息的处理将立马在对应地点可以查询到，实现了“即时发布、即时见效”的功能。

3、功能的完善性：可以对用户所能用到的各个方面的功能模块的添加、修改、维护操作。
# 3 关键技术简介
3.1 JSP技术介绍

JSP技术本身是一种脚本语言，但它的功能是十分强大的，因为它可以使用所有的JAVA类。当它与JavaBeans 类进行结合时，它可以使显示逻辑和内容分开，这就极大的方便了用户的需求。JavaBeans 可以对JSP技术的程序进行扩展，从而形成新的应用程序，而且JavaBeans的代码可以重复使用，所以就便于对程序进行维护。JavaBean 组件有内部的接口，可以帮助不同的人对系统进行访问。1999年，Sun微系统公司正式推出了JSP技术，这是一种动态技术，是基于整个JAVA体系和JavaServlet提出的，是具有普遍适用性的WEB技术，也是本系统设计的核心技术之一。JSP技术能够极大的提高WEB网页的运行速度。这些内容会与脚本结合，并且由JavaBean和Servlet组件封装。所有的脚本均在服务器端运行，JSP引擎会针对客户端所 提交的申请进行解释，然后生成脚本程序和JSP标识，然后通过HTML/XML页面将结果反馈给浏览器。因此，开发人员亲自设计最终页 面的格式和HTML/XML标识时，完全可以使用JSP技术。

所以结合物流管理系统的需求及功能模块的实现，使用JSP技术是最合适的，而且JSP的拓展性比较好，对于物流管理系统在后期使用过程中可以不断对系统功能进行拓展，是系统更完成，更方便的满足用户管理。

3.2 JAVA简介

Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterprise JavaBeans）的全面支持，java servlet API，JSP（java server pages），和XML技术。多进步。例如，当我在微软Word中写这篇文章时，我还打开了一个MP3播放器来播放音乐。偶尔，我也会编辑Word，让我的机器执行打印作业，我也喜欢通过IE。对我来说，这些操作是同时执行的，我不需要等待一首歌来完成我的论文编辑。似乎他们都在我的机器上同时为我工作。事实是，对于一个CPU，它只能在某个时间点执行一个程序。CPU在这些程序之间不断地“跳跃”。那么为什么我们看不到任何破坏呢？这是因为，与我们的感情相比，它的速度太快了。因此，尽管我们看到一些同步操作，实际上对于计算机来说，它只能在某个时间点执行一个程序，除非您的计算机是多CPU的。

Java是一种计算机编程语言，具有封装、继承和多态性三个主要特性，广泛应用于企业Web应用程序开发和移动应用程序开发。

Java语言和一般编译器以及直译的区别在于，Java首先将源代码转换为字节码，然后将其转换为JVM的可执行文件，JVM可以在各种不同的JVM上运行。因此，实现了它的跨平台特性。虽然这使得Java在早期非常缓慢，但是随着Java的开发，它已经得到了改进。

3.3 MyEclipse开发环境

MyEclipse支持广泛、兼容性高并且功能强大，是一个Eclipse 插件集合，普遍适应于JAVA和J2EE的系统开发，支持 JDBC，Hibernate，AJAX，Struts，Java Servlet，Spring，EJB3等市面上存在的几乎所有数据库链接工具和主流Eclipse产品 开发工具。 

MyEclipse在业内是所熟知的开发工具，该平台在开发的过程中运用的就是该工具。MyEclipse又被称之为企业级的工作平台，它是以Eclipse IDE为基础的。MyEclipse可以帮助我们进行数据库的研发和J2EE的使用，除此之外，还可以提高系统的运营能力，这突出表现在服务器的整合过程中。MyEclipse的功能相当完备，能够为J2EE的集成提供必要的环境支持，从而完成编码、测试、调试及发布等功能。它可以支持JSP，HTML，MYSQL，Javascript，Struts， CSS等。

3.4 Tomcat服务器

Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试JSP 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML 页面的运行提供技术支持，Tomcat 的任务则是运行Servle和JSP 页面。Tomca也具有一定的HTML页面处理功能。

3.5 MYSQL数据库

Mysql的语言是非结构化的，用户可以在数据上进行工作，并且学起来比较容易，功能大，储存量也大，Mysql主要应用于数据的查询、编辑，现在普遍存在的关系数据库有很多，并得到了普遍的应用。使用Mysql数据库在应用编辑中带来了方便，可以对数据进行广泛地查询，Mysql数据库的应用并不需要用户了解其存储的方式，更不用掌握数据存放的方法，Mysql数据库的灵活性较强，功能也较强大，多，在其他程序中实现某功能需要编写一大堆代码，而在Mysql数据库中只需要一小段代码就可以实现功能，所以，Mysql数据库的语言较简洁。
## 3.6 SSM三大框架
当今流行的“SSM组合框架”是Spring + SpringMVC + MyBatis的缩写，受到很多的追捧，“组合SSM框架”是强强联手、各司其职、协调互补的团队精神。web项目的框架，通常更简单的数据源。Spring属于一个轻量级的反转控制框架(IoC)，但它也是一个面向表面的容器(AOP)。SpringMVC常常用于控制器的分类工作模式，与模型对象分开，程序对象的作用与自动取款机进行处理。这种解耦治疗使整个系统的个性化变得更加容易。MyBatis是一个良好的可持续性框架，支持普通SQL查询，同时允许对存储过程的高级映射进行数据的优化处理。大型Java Web应用程序的由于开发成本太高，开发后难以维护和开发过程中一些难以解决的问题，而采用“SSM组合框架”，它允许建立业务层次结构，并为这个问题提供良好的解决方案。

第 35 页
本科生毕业设计(论文)![](/md/blog.004.png)


# 第4章  系统设计
## 4.1 系统功能需求
架构设计的目的是反映一个结构和其他元素之间的关系，抽象，通常用于指导大型软件系统。将一个巨大的任务细分为多个小任务的过程是系统架构的总体设计。完成小任务后，整个任务就可以完成了。具体的实现过程是分解系统，分析各部分的功能、接口和逻辑关系。信息传递的设计，最后一步是优化，系统页面是一个一个模块组建而成的，层次结构分明，思想运用的是面向对象，一个实体对应一个数据类型，还要对每个数据类添加一个实施类。

在进行程序开发时，不仅要考虑用户的功能需求，还要保证界面友好，所以功能板块的设计显得尤其重要。系统在设计伊始，立足于满足学生选课信息和教师课程信息的基本管理需求，具有一般实用性。因此，可将系统进行划分，对每个小模块进行细节的添加，管理员进入到系统进行对一级功能模块进行编辑维护，然后再根据需求进行下一级划分。

系统功能结构，如图4.1所示： 

![](/md/blog.005.png)

图4.1 学生功能模块图
## 4.2 系统E-R图
学习编程，我们都知道数据库设计是基于系统功能需要设计的，我们需要建立一个数据库关系模型，用来存储数据信息，这样当我们在程序中时，就没有必要了为程序页面添加了数据，从而提高了系统的效率。数据库存储了大量信息，可以说是信息管理系统的核心和基础，数据库还提供了添加，删除，修改和检查，使系统可以快速找到自己想要的信息，而不是在程序代码中查找。数据库中信息表的每个部分根据一定的关系精确地组合，排列和组合成数据表。

数据库是整个软件程序设计中最核心的环节，因此开发的首要问题就是确定数据库的数量以及结构式的创建。上面已经介绍，本论文将使用MYSQL技术实现对数据库的管理，以保证它的可用性、一致性、保密性和完整性。有些非法用户可能会对系统数据库进行攻击，以获取数据库中的资料，MYSQL可以起到很好的保护作用。

根据需求分析，本系统包括以下几个实体。

学生信息信息实体E-R图，如图4.3所示。

![](/md/blog.006.png)

图4.2学生信息E-R图

课程信息管理E-R图，如图4.3所示。

![](/md/blog.007.png)

图4.3课程信息E-R图

学生选课信息E-R图，如图4.5示。

![](/md/blog.008.png)

图4.5学生选课信息E-R图
## 4.3 数据库表的设计
我们可以根据数据结构的详细分析要求，我们根据输入和输出数据量的要求进行分析，确定什么表表，结构之间的关系，我们可以验证，调整和完善，查询和浏览过程，可以实现数据库，以使用户对数据和功能有更多要求。

基于系统使用的数据库管理系统的特点，对数据库的概念模型进行了转换和构建。但是，这个系统只需要充分考虑选课排课系统的功能，而且组织比较清晰。数据库设计如下：

表1：banji表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|bigint|11|PRIMARY KEY|
|banji|varchar|200|DEFAULT NULL|
表2：config表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|bigint|11|PRIMARY KEY|
|name|varchar|100|DEFAULT NULL|
|value|varchar|100|DEFAULT NULL|
表3：gonggaoxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|bigint|11|PRIMARY KEY|
|gonggaobiaoti\_|varchar|200|DEFAULT NULL|
|tupian|varchar|200|DEFAULT NULL|
`	`表4：jiaoshi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|jiaoshigonghao|varchar|200|` `DEFAULT NULL|
|mima|varchar|200|` `DEFAULT NULL|
|jiaoshixingming|varchar|200|` `DEFAULT NULL|
|xingbie|varchar|200|` `DEFAULT NULL|
|zhaopian|varchar|200|` `DEFAULT NULL|
|nianling|varchar|200|` `DEFAULT NULL|
|zhicheng|varchar|200|` `DEFAULT NULL|
|lianxidianhua|varchar|200|` `DEFAULT NULL|
表5：kebiaoxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|int|11|PRIMARY KEY|
|banji|varchar|200|` `DEFAULT NULL|
|xueqi|varchar|200|` `DEFAULT NULL|
|diyijie|varchar|200|` `DEFAULT NULL|
|dierjie|varchar|200|` `DEFAULT NULL|
|disanjie|varchar|200|` `DEFAULT NULL|
|disijie|varchar|200|` `DEFAULT NULL|
|diwujie|varchar|200|` `DEFAULT NULL|
	

表6：kechengmingcheng表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|int|11|PRIMARY KEY|
|kechengmingcheng|varchar|200|` `DEFAULT NULL|
表7：kechengxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|int|11|PRIMARY KEY|
|kechengmingcheng|varchar|200|` `DEFAULT NULL|
|kechengleixing|varchar|200|` `DEFAULT NULL|
|tupian|varchar|200|` `DEFAULT NULL|
|banji|varchar|200|` `DEFAULT NULL|
|xueqi|varchar|200|` `DEFAULT NULL|
|jiaoshigonghao|varchar|200|` `DEFAULT NULL|
|jiaoshixingming|varchar|200|` `DEFAULT NULL|
表8：token表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|bigint|20|PRIMARY KEY|
|` ``userid|bigint|20|` `DEFAULT NULL|
|username|varchar|100|` `DEFAULT NULL|
|tablename|varchar|100|` `DEFAULT NULL|
|role|varchar|100|` `DEFAULT NULL|
|token|varchar|100|` `DEFAULT NULL|
表9：tuikexinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|bigint|20|PRIMARY KEY|
|kechengmingcheng|varchar|200|` `DEFAULT NULL|
|kechengleixing|varchar|200|` `DEFAULT NULL|
|banji|varchar|200|` `DEFAULT NULL|
|xueqi|varchar|200|` `DEFAULT NULL|
|xuankeriqi|varchar|200|` `DEFAULT NULL|
|tuikeshuoming|varchar|200|` `DEFAULT NULL|
|tuikeriqi|varchar|200|` `DEFAULT NULL|
|jiaoshigonghao|varchar|200|` `DEFAULT NULL|
|jiaoshixingming|varchar|200|` `DEFAULT NULL|
|xuehao|varchar|200|` `DEFAULT NULL|
|xueshengxingming|varchar|200|` `DEFAULT NULL|
|sfsh|varchar|200|` `DEFAULT NULL|
# 第5章 系统实现
## 5.1用户登录界面
用户后台登录，对于登录窗口是一个系统功能操作的安全门，如果没有这个登录安全门，任何人都可以进入到系统操作平台进行对功能模块的操作，那么系统的数据信息将会出现错乱，不同用户拥有不同的管理权限，所以对于登录窗口是系统实现的重要窗口，用户通过输入自己的用户名和密码，信息填写完成，系统对用户输入的信息进行在线匹配，匹配完成后登录成功，进入到系统操作界面，进行相对应的功能模块的修改维护等操作，如图5.1所示。

![](/md/blog.009.png)

图5.1 系统登陆页面设计
## 5.2管理员功能模块
管理员通过登录进入到系统操作界面，通过系统操作界面可以对个人中心、公告信息、班级管理、学生管理、教师管理、课程名称管理、课程信息管理、课表信息管理、学生选课管理、退课信息管理等模块进行查看管理等操作。

公告信息管理：通过列表可以查看公告标题、图片、发布日期等信息，进行查看详情、新增、修改或删除操作，或通过输入公告标题进行查询，如图5.2所示。

![](/md/blog.010.png)

5.2公告信息管理界面图



学生管理：通过列表可以查看学号、学生姓名、性别、头像、班级、手机、邮箱等信息，进行查看详情、修改或新增、删除操作，如图5.3所示。

![](/md/blog.011.png)

图5.3学生管理界面图

教师管理：通过列表可以查看教师名称、教师描述等信息，管理员可以进行查看或修改、删除、新增教师信息，如图5.4所示。

![](/md/blog.012.png)

` `图5.4教师管理界面图

课程管理：通过列表可以查看课程名称等信息，管理员可以进行查看详情、新增、修改或删除操作，如图5.5所示。

![](/md/blog.013.png)

图5.5课程名称管理面图

` `课表信息管理：通过列表可以查看班级、学期、星期、第一节、第二节、第三节、第四节、第五节等信息，管理员可以进行查看详情、新增、修改或删除操作，如图5.6所示。

![](/md/blog.014.png)

图5.6课表信息管理面图

` `课程信息管理：通过列表可以查看课程名称、课程类型、图片、班级、学期、发布日期、教师工号、教师姓名等信息，管理员可以进行查看详情、新增、修改或删除操作，如图5.7所示。

![](/md/blog.015.png)

图5.7课程信息管理面图

学生选课管理：通过列表可以查看课程名称、课程类型、班级、学期、选课日期、状态、教师工号、教师姓名、学号、学生姓名、备注、审核回复、审核状态等信息，管理员可以进行查看详情、审核、修改、删除操作，如图5.8所示。


![](/md/blog.016.png)

图5.8学生选课管理面图

## 5.3教师模块
老师通过登录窗口，进行输入自己的用名和密码，信息输入完成后进入到用户的操作界面，通过系统操作界面可与对个人中心、公告信管理、课表信息管理、课程信息管理、学生选课管理、退课信息管理等模块进行查看管理等操作。

课程管理，通过教师处理课程列表可以进行查看课程名称、课程类型、图片、班级、学期、发布日期、教师工号、教师姓名等信息，进行查看详情操作，如图5.9所示。

![](/md/blog.017.png)

图5.9课程信息管理界面图

课表信息管理：通过列表可以获取班级、学期、星期、第一节、第二节、第三节、第四节、第五届等信息，进行在线查看课表信息，如图5.10所示。

![](/md/blog.018.png)

图5.10课表信息管理界面图

学生选课管理：通过列表可以查看课程名称、课程类型、班级、学期、选课日期、状态、教师工号、教师姓名、学号、学生姓名、备注、审核回复、审核状态等信息，管理员可以进行查看详情、修改、删除操作，如图5.11所示。

![](/md/blog.019.png)

图5.11学生选课管理界面图

退课信息管理：通过列表可以查看课程名称、课程类型、班级、学期、选课日期、状态、教师工号、教师姓名、学号、学生姓名、审核回复、审核状态等信息，管理员可以进行查看详情操作，如图5.12所示。

![](/md/blog.020.png)

图5.12退课信息管理界面图

## 5.4学生模块
学生通过登录窗口，进行输入自己的用名和密码，信息输入完成后进入到用户的操作界面，通过系统操作界面可与对个人中心、公告信息管理、课表信息管理、课程信息管理、学生选课管理、退课信息管理等模块进行相对应操作。

课表信息管理：通过列表可以获取班级、学期、星期、第一节、第二节、第三节、第四节、第五届等信息，进行在线查看课表信息，如图5.13所示。

![](/md/blog.021.png)

图5.13课表信息界面图

` `课程信息管理：通过列表可以查看课程名称、课程类型、图片、班级、学期、发布日期、教师工号、教师姓名等信息，管理员可以进行查看详情、在线选课操作，如图5.14所示。

![](/md/blog.022.png)

图5.14课程信息界面图

学生选课管理：通过列表可以查看课程名称、课程类型、班级、学期、选课日期、状态、教师工号、教师姓名、学号、学生姓名、备注、审核回复、审核状态等信息，管理员可以进行查看详情、退课、删除操作，如图5.15所示。

![](/md/blog.023.png)

图5.15学生选课管理界面图

退课信息管理：通过列表可以查看课程名称、课程类型、班级、学期、选课日期、状态、教师工号、教师姓名、学号、学生姓名、审核回复、审核状态等信息，管理员可以进行查看详情、修改、删除操作，如图5.16所示。

![](/md/blog.024.png)

图5.16退课信息管理界面图












