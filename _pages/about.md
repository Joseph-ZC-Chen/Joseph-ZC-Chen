---
layout: about
title: About
permalink: /
subtitle: Consultant Specialist, Payment Tech SME in HSBC Software Dev (GD) Ltd.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>+86 13049362776</p>
    <p>Room 1605, Building M4, Phase 1, Poly Xiyuewan, Liwan District</p>
    <p>Guangzhou, Guangdong, P.R. China</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a software engineering researcher with 5+ years of industrial experience in banking payment systems and fintech infrastructure. My research centers on automated software quality assurance, LLM-augmented software engineering, and reliability validation of large-scale financial systems, with extensive field validation in ISO 20022 migration and batch payment testing scenarios.<br/>Three core strands:<br/>1. Automated testing and quality assurance for large-scale enterprise payment systems, with particular emphasis on batch processing scenarios and ISO 20022 standard migration validation<br/>2. LLM-augmented software engineering pipelines, including automated requirements analysis, user story generation, end-to-end test case synthesis, and defect identification<br/>3. Industrial-scale SE method validation, bridging academic methodologies with real-world banking system constraints and compliance requirements<br/><br/>I am now pursuing a PhD to develop more rigorous, efficient, and reliable software engineering practices for critical enterprise systems.

## Research Projects:
- A Configurable Fault-Tolerant Automated Testing Framework for Large-Scale Payment Systems
时间：2025.09 – 2026.01 | 项目负责人 & 核心设计者<br/>Problem 传统银行端到端支付测试依赖人工发起交易，在大批量监管测试场景下面临三大瓶颈：人工操作吞吐量不足、异常中断后需全量返工、跨子系统结果校验成本高，无法满足ISO 20022迁移下的批量验证需求。<br/>Methodology 提出并实现一套三层自动化测试框架：<br/>• 多维度参数化调度模块：支持交易规模、发送速率、目标节点的灵活配置<br/>• 基于日志感知的容错续跑机制：非侵入式采集执行状态，异常中断后自动断点恢复，无需重复执行<br/>• 分层级结果校验引擎：覆盖执行状态、业务逻辑一致性、异常分级三级自动校验<br/>Results 支持单批次上万笔支付交易的全自动发送与校验；异常中断恢复耗时降低90%以上；端到端测试人力投入减少70%；已落地于某国家级银行行业合规测试项目。<br/><br/>

- BA Agent: An LLM-Powered Assistant for Software Requirements Analysis and User Story Generation
时间：2026.03 – 至今 | 项目负责人<br/>Problem 银行软件开发需求分析高度依赖资深BA经验，新人产出质量不稳定，且从需求到测试用例的全链路人工转换效率低。<br/>Methodology 设计并实现面向银行软件场景的智能需求分析Agent，基于VS Code与GitHub Copilot Chat构建，内置银行支付领域知识规范，自动将业务需求转化为符合标准的User Stories。<br/>Results 产出的User Story符合企业BA规范标准；需求文档到开发交付物的转换效率提升显著；后续将拓展至测试用例自动生成、缺陷自动复核的全链路覆盖。<br/><br/>

- LLM-Assisted Automated Trading Strategy Development for Hang Seng Index
时间：2024.8 – 2024.11 | 个人独立参赛项目<br/>Background 2024 HSBC Code Cup 编程竞赛，主题为GenAI赋能业务创新，无强制编程基础要求，考察快速应用AI工具解决复杂问题的能力。<br/>Methodology 基于大语言模型完成从策略设计到代码实现的全流程，对接比赛虚拟环境API，构建恒生指数自动化交易策略系统，包含行情读取、信号判断、订单执行模块。<br/>Results 从全公司参赛队伍中晋级Top 12；验证了无深厚编程基础下，通过AI辅助快速构建工程系统的可行性。<br/><br/>

## Professional Experience：
### HSBC Software Dev (GD) Ltd. | Guangzhou, China
Consultant Specialist, Payment Systems Engineering | Jan 2023 – Present<br/>
Senior Software Analyst | Sep 2021 – Jan 2023<br/>
• Led the technical design and end-to-end validation of the Australia & New Zealand ISO 20022 migration program, designed the overall testing architecture and acceptance criteria for payment message transformation systems.<br/>
• Developed performance testing methodologies and resilience verification schemes for core payment systems, ensuring compliance with stringent availability and latency SLAs in production environments.<br/>
• Innovated batch testing and fault recovery solutions for large-scale payment scenarios, reducing post-deployment issues and improving delivery efficiency of regulatory compliance projects.<br/>
• Received Best Team of GBGF 2024 for outstanding technical delivery in payment system modernization.

## Technical Skills：
• Software Engineering Methods：Automated Testing, Fault-Tolerant Systems, Requirements Engineering, End-to-End System Validation, Agile Development<br/>
• Domain & Systems：ISO 20022 Payment Systems, Banking Core Systems, Distributed Enterprise Systems<br/>
• AI-Assisted Engineering：LLM Prompt Engineering, AI-Assisted Programming, LLM-based Agents, Test Generation with GenAI<br/>
• Tools & Technologies：Python, SQL, Splunk, GitHub Copilot, VS Code, Jira, Confluence<br/>
• Languages：Native Mandarin, Fluent English, Cantonese

## Education：
• Pepperdine University - Master of Science, Mathematical Finance<br/>
Location: Los Angeles, United States<br/>
Year: 2015 - 2016<br/>
Courses: Financial Modeling, Applied Data Analysis, Quantitative Business Analysis<br/><br/>

• Jinan University - Bachelor of Management, Information Management System<br/>
Location: Guangzhou, China<br/>
Year: 2009 - 2013<br/>
Courses: Computer Science, Numerical Computing, Mathematical Modeling, Information Systems
