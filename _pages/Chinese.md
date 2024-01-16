---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

 [English](./about.md)
# 📖 教育经历
- *09/2025-07/2026*, 爱尔兰高威大学, 计算机科学与技术
  核心课程: 数据分析编程、网络和网络科学、数据可视化、数据分析案例研究
- *07/2022-08/2026(预期)*, 南京农业大学, 工商管理 (兼读制)
  核心课程: 现代项目管理、数据建模和与决策制定、财务管理、企业商业战略、财务理论与实践实务
- *10/2019-12/2024 (预期)*, 南京航空航天大学, 软件工程（全日制）
  核心课程：离散数学，C++编程，Java编程，计算机系统架构，软件工程，操作系统
- *10/2019-12/2024 (预期)*, 南京航空航天大学, 计算机科学与技术
  核心课程：高等数学，离散数学，C++编程，计算机网络，计算机系统架构，数据结构，软件工程，操作系统
- *09/2018-07/2023*, 南通师范高等专科学校, 计算机应用与技术
  核心课程：Java编程，C编程，动态网页设计，数据库应用开发
    
# ⭐ 出版物
- &ensp;(2023). 《汽车行业数智化营销及运营模式研究》上海商业 ISSN1007-2845 中国知网 收录检索。
- &ensp;(2023). 《Deciphering Modern Customer Loyalty： A Machine Learning Approach》 第三届物联网与机器学习国际学术会议（IoTML 2023）EI Compendex，Scopus收录检索。 Doi：10.1117/12.3016467.

# 📚 证书
- *02/2023* &ensp;高级-注册数据分析师（中国金融分析协会）
- *11/2022* &ensp;中级-软件设计师（人力资源和社会保障部）
- *12/2022* &ensp;工业互联网平台开发工程师中级（工业和信息化部人才交流中心）
- *03/2019* &ensp;全国计算机等级考试一级（Office）
- *03/2023* &ensp;全国计算机等级考试二级（C语言）

# 🌎 文章
-&ensp;“基于XGBoost的北京移动用户体验影响因素研究”<br/>
&ensp;&ensp;这项研究专注于调查影响北京移动用户体验的因素。通过使用皮尔逊相关系数分析，该研究检查了影响用户满意度和评级的各种因素，为决策提供了基础。此外，基于相关影响因素开发了一个XGBoost预测模型，以准确预测客户评级。
<br/>关键词：影响因素；皮尔逊相关系数；满意度预测；机器学习；XGBoost。
<br/>成就： 2022年第三届MathorCup大数据竞赛本科组全国一等奖。

-&ensp;“基于多元线性回归对医药电商销售额的预测与经营研究”<br/>
&ensp;&ensp;这项研究专注于提高医药电子商务平台的运营效率。通过利用数据挖掘技术，分析各种条件下药物的销售表现以及影响总销售额的关键因素。建立了一个多元线性回归模型来预测天猫上维生素类药品未来三个月的销售总额。根据研究发现，提出了电子商务运营策略，以加快库存中药品的销售速度。
<br/>关键词：电子商务；销售收入；预测模型；多元线性回归。
<br/>成就：2022年全国大学生数据分析竞赛全国一等奖第一名。

-&ensp;“基于时间序列预测和库存管理的小批量物料的生产安排”<br/> 
&ensp;&ensp;本研究的重点是中国一家电子制造公司的材料生产计划。该研究首先确定了六种关键材料，并根据需求和累计销售额将它们分为ABC类别。ARIMA 模型用于每周预测，结果令人满意，尽管出现了一些错误。然后，该研究使用BP神经网络提高了预测准确性。在第 101 周到第 110 周计算一种选定物料的生产计划，达到 99.28% 的服务水平。于是，该研究使用 ABC 库存管理系统来解决考虑到价格波动的库存水平和服务水平之间的平衡问题。最后，通过训练模型建立广义生产计划方法，在必要时可以在一定程度上牺牲服务水平来降低库存成本。
&ensp;&ensp;在中国的电子产品制造公司中，有效的生产调度计划对于维持供需平衡、最小化中断以及减少材料浪费至关重要。本研究利用某公司的历史数据，为小批量材料制定生产计划。
<br/>关键词：自回归集成移动平均模型（AIRMA）；BP神经网络；库存管理；需求预测；生产调度。
<br/>成就：2022年全国大学生数学建模竞赛江苏区域二等奖。

# 📌 工作经历
 <b>江苏霖承科技有限公司(南通市软件协会成员)</b>
     <br/>*10/2021–至今*
    <br/><i>法人代表、CEO</i> 
    <br/>●&ensp;成功获得多项国家软件著作权，包括2022年3月开发“基于数据挖掘和用户画像的智能职业规划系统2.1”、2022年8月开发“基于人工智能的人才匹配系统V1.0”、2022年11月开发“房车市场需求营销系统”。
    <br/>●&ensp;通过获得上述项目的国家认可，展示在软件开发和创新方面的专业知识。
    <br/>●&ensp;通过在智能职业规划和人才匹配领域创建创新软件产品来提供尖端解决方案。
    <br/>
    <br/>
    <b>南通盒木信息技术有限公司</b> 
     <br/>*05/2023-07/2023*
    <br/><i>软件工程师</i> 
    <br/>●&ensp;管理WMS和ERP系统的二次开发，根据特定要求定制化，增强系统功能和性能。
    <br/>●&ensp;编写高质量的代码，并进行彻底的代码审查和优化，以确保项目的可靠性和可维护性。
    <br/>●&ensp;制作教学视频课程，作为ERP专家讲解ERP系统，从而为公司的培训计划和开源知识共享做出贡献。 GitHub: https://github.com/Joe-2002/sweettalk-django4.2
    <br/>
    <br/>
    <b>南通师范高等专科学校 </b> 
     <br/>*04/2023–06/2023*
    <br/><i>管理学院企业外聘讲师 </i>  
    <br/>●&ensp;完成跨境电商、网店运营管理等三个班两门课的教学职责。
    <br/><每周 教学12 课时的工作量，有效地提供课程材料并让学生参与学习。
    <br/>●&ensp;研发电子商务数据分析课程，展示了强大的教学技巧，有效地传达了复杂的概念，获得了学生的积极反馈和学术成功。
    <br/>
    <br/>
    <b>海安市教师发展中心附属小学</b>
    <br/>*04/2022–05/2022*
    <br/><i>教师 </i>  
    <br/>●&ensp;为学生设计并执行全面的软件编程教学方案，使学生沉浸于编程语言中，并培养对算法概念的深刻理解。
    <br/>●&ensp;设计及推动互动编码挑战和项目，营造一个充满活力的学习环境，磨练学生解决问题的能力，并培养他们在软件开发方面的创造力。
    <br/>
    <br/>
    <b>北京知未智能科技有限公司</b>
    <br/>*07/2022–11/2022*
    <br/><i>软件工程师 </i>  
    <br/>●&ensp;开发数据集导入、综合数据内容显示、查询信息、修改删除信息等关键功能的数据标注软件。
    <br/>●&ensp;实现了用户特定的文本注释功能，允许用户为分配的文本进行注释，以便进行后续的自然语言处理任务。
    <br/>
    <br/>
    
# 💻 项目经历
<br/>-<b>基于主成分分析和最邻近节点算法的中药材分类问题</b>
 <br/>●&ensp;概述:基于中药材的近红外和中红外光谱，该项目旨在确定中药材的类型，来源和类别，并分析其特征和差异。
    <br/>●&ensp;职责:数据预处理、特征选择、特征降维。建立了多个分类模型（K-means，KNN，SVM）。最终确定KNN为分类模型，准确率超过90%。
    <br/>●&ensp;成就:2021年全国大学生数学建模竞赛江苏区域一等奖。
    <br/>
    <br/>
    <b>-基于数据挖掘的智能职业规划系统</b>
    <br/>项目负责人:产品架构和团队管理。2021年江苏省大学生创新创业培养计划（202114493020Y）。
    <br/>●&ensp;概述:本项目利用数据挖掘技术，评估用户的职业规划能力，提供科学合理的职业规划策略和工具，帮助用户发展自主的职业规划能力。
    <br/>●&ensp;职责:组织团队完成商业计划、PowerPoint 演示文稿和现场路演。主导项目技术架构完成了多次产品迭代。
    <br/>
    <br/>
    <b>-基于LLM（大语言模型）与向量数据库构建的数智化企业智能助理系统</b> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;<b>GitHub:</b> https://github.com/Joe-2002/LinChance_GPT
    <br/>项目负责人:系统架构。
    <br/>●&ensp;成就: Datawhale“AI暑期营（第二版）”一等奖，开源学习卓越奖和最佳创新奖，Datawhale开源学习。
    <br/>●&ensp;概述: 该项目旨在打造具有数据驱动平台的智能人机交互产品，利用LangChain、向量数据库、大型模型和NLP等先进技术，提高知识检索效率，并扩展到企业和个人的个人知识系统。
     <br/>●&ensp;职责: 进行市场调研和竞争对手分析，确定目标用户。使用矢量数据库实现知识库数据的高效存储、检索和匹配。利用 GPT 模型进行快速全文搜索和精确的结果匹配。使用 Django 开发安全后端，使用 Vue.js 开发视觉上吸引人的前端。与 LangChain的 API和其他技术集成，以增强数据处理。利用 LangChain 和GPT模型，通过智能回复改善用户体验。

# 📜 校园经历 
- <b>南通师范高等专科学校</b> 
    <br/>&ensp;科技创新社团 创始人、社长、团支书 (*01/2021-07/2023*):组织和管理社团，社团以学科竞赛为导向，如数学建模、创新创业和算法竞赛。取得了优异的成绩，受众人数达数百人，教学和指导各种比赛的参与者，促进他们的成长和成功。被评为五星社团和活力社团。
- <b> 南通师范高等专科学校</b> 
    <br/>&ensp;算法集训队 创始人、队长  (*12/2020-07/2023*):在我校无算法竞赛的背景下，创办算法集训队。组织管理、授课。辅导近百名同学，数十名同学获得省级以上奖项。·	带领团队获得中国高校计算机大赛-团体程序设计天梯赛 “沧海竞舟”组江苏省 团体一等奖、高校一等奖、特等奖。
- <b> 南京航空航天大学</b> 
    <br/>&ensp;数学建模协会 学术部部长(10/2023 – 至今)：·	组织和开展各种讲座和课程。提高学生的数学建模能力和学术素养。通过邀请专家学者、优秀参赛者等来分享他们的经验和见解，让学生们能够更深入地了解数学建模的原理和应用。·	参与学生竞赛的组织工作。组织了各种级别的数学建模比赛，如美赛、国赛等。带领团队成员为学生们提供系统的培训和指导，帮助他们更好地掌握数学建模的知识和技能。成功地组织了一系列高质量的讲座和比赛，并获评五星社团。
# 📝 著作权  
- *11/2022*&ensp;《基于数据挖掘与用户画像的智能职业规划系统》(2022SR1346851).       
- *08/2022*&ensp;《基于人工智能的人才匹配系统》 (2022SR1570163).           
- *03/2022*&ensp;《房车市场需求平台解决方案V1.0》 (2023SR0217158).         
- *08/2023*&ensp;《基于Django和Vue前后端分离的教学协作平台V1.0》(2021SR1494741).  - *08/2023*&ensp;《基于LLM（大语言模型）与向量数据库的数智化企业智能助理系统》(2023SR1583655).         

# 🎖 奖项和荣誉
- *12/2023* 2023百度搜索创新大赛 搜索答案组织赛道 全国Top10  
- *12/2023* 2023百度搜索创新大赛 设计一个解决搜索用户需求的AI原生应用赛道  全国冠军
- *05/2023* 2023年南通市三好学生
- *04/2023* 第十四届“蓝桥杯”C/C++程序设计大赛 本科组 国家优秀奖和省一等奖
- *01/2023* 2022年中国大学社会企业实践50强
- *12/2023* “马蹄杯”全国职业院校程序设计大赛 国家铜奖 
- *12/2022* 第五届“传智杯”全国大学生IT技能大赛云计算与大数据赛道 本科生一等奖
- *11/2022* 第十二届江苏省挑战杯大学生创业计划大赛 银奖
- *08/2022* 2022年RoboCom世界机器人开发者大赛 全国三等奖和江苏省二等奖
- *07/2022* 江苏省大学生创新创业训练计划项目（20214554） 主持结项
- *06/2022* 2022年南通市三好学生
- *05/2022* 第十三届“蓝桥杯”C/C++程序设计大赛 本科组 国家优秀奖和省一等奖 
- *05/2022* 中国大学生计算机竞赛 江苏省团队程序设计天梯赛 团队一等奖
- *12/2021* 第十七届“挑战杯”江苏省大学生课外学术科技作品竞赛 铜奖两项
- *07/2021* 江苏省大学生创新创业训练计划项目（20202718） 主持结项
- *06/2021* 第十二届“蓝桥杯”C/C++程序设计大赛 本科组 国家优秀奖和省一等奖
- *05/2021* 中国大学生计算机大赛江苏省“挑战者竞技场”团体编程天梯赛一等奖。
- *05/2021* 南通师范高等专科学校 三等奖学金 
- *05/2021* 南通师范高等专科学校 优秀学生干部
- *12/2020* 第十一届江苏省“挑战杯”大学生创业计划竞赛铜奖
- *11/2020* 第十一届“蓝桥杯”C/C++程序设计大赛本科组 国家三等奖、省一等奖
  

