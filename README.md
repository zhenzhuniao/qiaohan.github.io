# README.md
```
# 乔韩博士学术主页 (Hugo + Wowchemy)

本项目是乔韩博士的个人学术主页，基于 **Hugo** 和 **Wowchemy** 构建，支持多语言、自动部署与自定义主题。

## 🔹 功能特色
- 中英文双语支持
- 研究方向、论文、项目、教学课程展示
- 个人简介和 CV 下载
- GitHub Pages 自动部署
- 自定义主题颜色和排版
- 支持日/夜间主题切换

## 📦 项目结构
```
config/            # Hugo 配置文件
content/           # 内容，包括主页、研究方向、论文、项目、教学等
static/files/      # 可下载文件（如 CV）
static/authors/admin/avatar.jpg  # 头像
.github/workflows/ # 自动部署 GitHub Pages 的脚本
```

## 🚀 本地运行
1. 安装 Hugo Extended: https://gohugo.io/installation/
2. 在项目根目录运行开发服务器:
```
hugo server -D
```
3. 构建生产版本:
```
hugo --gc --minify
```

## 🌐 GitHub Pages 部署
- 项目已配置 GitHub Actions 自动构建和部署
- 仓库分支 `main` 推送后自动生成网站
- 默认访问地址: `https://yourusername.github.io`

## 🌐 自定义域名
若有学校或个人域名，请修改 `static/CNAME` 文件:
```
your.custom.domain.edu
```
并确保 DNS 配置 CNAME 指向 `yourusername.github.io`。

## 📝 联系方式
- 姓名: 乔韩 博士
- 邮箱: qiaoh@psych.ac.cn
- 单位: 中国科学院心理研究所 · 人因与认知实验室
- GitHub: https://github.com/yourname
- LinkedIn: https://www.linkedin.com/in/yourname

## 🎓 教育经历
- 2011年9月——2015年7月: 哈尔滨工业大学能源科学与工程学院，学士学位
- 2016年9月——2019年6月: 中国科学院大学心理学研究所，硕士学位
- 2021年9月——2025年12月: 中国科学院大学心理学研究所，博士学位
- 2024年3月——2024年10月: 西澳大学心理科学学院，访问学生

## 💼 研究方向
- 人机界面设计 / Human–Machine Interface (HMI) Design
- 空中交通管制 / Air Traffic Control (ATC)
- 特殊岗位人员选拔与培训 / Personnel Selection & Training for High-Reliability Occupations

## 📚 学术论文
1. Qiao, H., & Zhang, J. (2023). Enhancing global thinking can reduce the misconception of accumulation: A potential way to mitigate climate change. *Environmental Science and Pollution Research*, 30(20), 58618–58629.
2. Qiao, H., Zhang, J., Zhang, L., Li, Y., & Loft, S. (2022). Exploring the peak-end effects in air traffic controllers’ mental workload ratings. *Human Factors*, 64(8), 1292-1305.
3. Xiao, Z., Liu, W., Yang, J., & Qiao, H*. (2022). Influence of psychological states on train drivers’ safety performance. *China Safety Science Journal*, 32(S2), 13-18.
4. Guo, T., Wang X., Gu, D., & Qiao., H*. (2022). Intervention strategies for sleep quality issues of shift workers. *China Safety Science Journal*, 32(S2), 236-242.
5. Qiao, H., Zhang, J., & Liu., M (2021). Exploring people’s hue ranking ability across the color ring: taking the categorization effect into consideration. In C. Stephanidis, M. Antona, & S. Ntoa (Eds.), *HCI International 2021-Posters* (pp. 153-157). Springer.
6. Qiao, H., & Zhang, J. (2023, October 20). A New Method to Predict Layout Appropriateness: Coherence of Multiplex Networks [Poster presentation], Annual Conference of Engineering Psychology, Xi’an, China.
7. Qiao, H., & Zhang, J. (2024, November 15). Predicting Perceived Visual Complexity and Search Performance under Varying Feature Conditions Using the Multiplex Cognitive Network Approach [Poster presentation], International Conference on Human Factors Engineering and Intelligent System Interaction, Shenzhen, China.

## 💡 申请/已获专利
- PCT/CN2022/126443, WO2023093390: LAYOUT METHOD, READABLE MEDIUM AND ELECTRONIC DEVICE, Liu, Mengdi; Zhang, Jingyu; Qiao, Han, Published on June 01, 2023.

## 🏆 研究项目
1. 国家自然科学基金重大项目子课题二: 面向人因安全的人机功能分配与人机交互界面研究 — 核心成员
2. 横向课题: 铁路行业机车乘务员心理健康标准研究 — 主持
3. 横向课题: 铁路行业机车乘务员睡眠干预方法研究 — 主持

## 🎖 获奖情况
- 中国科学院大学心理研究所 研究生奖学金 特等 — 2023
- 中国科学院大学心理研究所 研究生奖学金 一等 — 2024
- 中国科学院大学 三好学生 — 2023
- 中国科学院大学 三好学生 — 2024
- 中国科学院大学 博士研究生国际合作培养计划奖学金 — 2023
