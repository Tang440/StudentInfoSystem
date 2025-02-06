📌 学生信息管理系统
一个基于 C++ 和 C# 的学生信息管理系统，采用 二叉排序树（BST） 作为核心数据结构，并结合 C# 界面 提供友好的用户交互。

📖 项目简介
本项目旨在构建一个高效、稳定、易用的学生信息管理系统，支持 增、删、改、查 以及多条件查询、数据统计等扩展功能。
采用 C++ 进行数据结构实现，C# 负责 UI 设计，并通过Git 进行团队协作开发。

🛠️ 技术栈
核心数据结构：C++（二叉排序树 BST）
用户界面：C#（Windows Forms / WPF）
文件存储：文本文件（.txt） 或 JSON
版本控制：Git + GitHub
🚀 主要功能
✅ 学生信息管理

添加学生信息（学号、姓名、性别、专业等）
删除/修改学生信息
按学号/姓名查找学生信息
遍历/导出所有学生信息
✅ 高级功能

条件查询（如按姓名模糊匹配、按专业筛选）
数据统计（统计各专业学生人数）
数据存储（支持文件读写）
✅ 用户界面

C# 界面（可选 Windows Forms / WPF）
命令行模式（支持基础操作）
🧑‍💻 团队分工
成员	负责模块	主要任务
A	数据结构设计	设计 & 实现 BST，封装插入/删除/查找操作
B	文件操作	读写学生数据，处理文件异常
C	UI & 主控	设计 C# 界面，处理用户输入，调用数据接口
D	功能扩展	实现高级查询、统计分析
E	测试 & 文档	测试系统功能，撰写技术文档 & PPT
🔧 安装 & 运行
📥 1. 下载代码
bash
复制
编辑
git clone https://github.com/your-team/StudentInfoSystem.git
cd StudentInfoSystem
🔨 2. 编译 & 运行
🔹 方式 1：使用 C++ 终端运行
bash
复制
编辑
g++ -o student_system main.cpp BST.cpp FileIO.cpp
./student_system
🔹 方式 2：使用 C# 界面
打开 Visual Studio
加载 C# 界面项目 (StudentInfoSystem.sln)
运行项目（F5）
📌 GitHub 贡献指南
欢迎贡献代码！请遵循以下开发流程：

Fork 本仓库
新建分支（如 feature-ui）
提交代码（git commit -m "实现 UI 界面"）
创建 Pull Request
代码审查后合并
📄 许可证
本项目遵循 MIT License，可自由修改和分发。

📌 联系我们
如有问题，请提交 Issues 🚀
🎯 希望大家一起打造一个高效的学生管理系统！ 🎯
