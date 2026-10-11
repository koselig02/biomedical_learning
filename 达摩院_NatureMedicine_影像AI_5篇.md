# 达摩院 Nature Medicine 影像 AI 研究(5 篇)

> 来源：微信公众号文章《从 5 篇 Nature Medicine 到 Science,看达摩院影像 AI 的研究路线》
> 链接：https://mp.weixin.qq.com/s/9X4Qd7q_78hfzHQQrphucg
>
> 这 5 篇按疾病依次为：胰腺癌、胃癌、急性主动脉综合征、肝脏恶性肿瘤、食管癌。其中一个鲜明特点是 **4 篇采用非增强（平扫）CT**(PANDA / GRAPE / iAorta / EAGLE),仅 LiON 使用增强 CT 与多期相信息。

---

## 1. PANDA —— 胰腺癌检测(非增强 CT)

- **论文标题**:Large-scale pancreatic cancer detection via non-contrast CT and deep learning
- **期刊/年份**:Nature Medicine,2023(29(12):3033–3043)
- **DOI**:10.1038/s41591-023-02640-w
- **要点**：用普通非增强(平扫)CT + 深度学习检测胰腺癌。训练集 3,208 例(单中心);多中心验证(6,239 例,10 个中心)病灶检出 AUC 0.986–0.996;敏感性比影像医生高 34.1%。真实世界 20,530 例连续患者中敏感性 92.9%、特异性 99.9%,并检出 31 例临床漏诊病灶。获 FDA"突破性医疗器械"认定。

## 2. GRAPE —— 胃癌筛查(非增强 CT)

- **论文标题**:AI-based large-scale screening of gastric cancer from non-contrast CT
- **期刊/年份**:Nature Medicine,2025(2025 年 6 月 24 日)
- **DOI**:10.1038/s41591-025-03785-6
- **合作方**：浙江省肿瘤医院 + 阿里达摩院
- **要点**：全球首个基于非增强 CT 的胃癌筛查 AI。近 10 万例、20 个中心数据训练。敏感性 85.1%(比影像医生高 21.8%)、特异性 96.8%;可在临床诊断前 2–10 个月发现胃癌迹象；将需胃镜精查的人群比例从传统筛查的 20–25% 降至约 6%。

## 3. iAorta —— 急性主动脉综合征诊断(非增强 CT)

- **论文标题**:AI-based diagnosis of acute aortic syndrome from noncontrast CT
- **期刊/年份**:Nature Medicine,2025(2025 年 8 月 20 日)
- **PubMed**:PMID 40835970
- **合作方**：浙大一院 + 阿里达摩院
- **要点**：从常规非增强 CT 直接识别急性主动脉综合征(AAS,48 小时未诊死亡率 40–50%)。多中心回顾(n=20,750)平均 AUC 0.958;真实世界(n=137,525)敏感性 0.913–0.942、特异性 0.991–0.993;前瞻性对照(n=13,846)将确诊时间从 219.7 分钟缩短至 61.6 分钟(约降 70%)。已在浙江 10 家医院试点部署。

## 4. LiON —— 肝脏恶性肿瘤诊断(增强 CT / 多期相)

- **论文标题**:Large-scale AI-guided liver malignancy diagnosis
- **期刊/年份**:Nature Medicine,2026
- **PubMed**:PMID 42618635
- **合作方**：盛京医院等 + 阿里达摩院(DAMO LiON)
- **要点**：面向肝脏恶性肿瘤诊断,**建立在增强 CT 与多期相信息之上**(是 5 篇中唯一不采用平扫的一篇)。真实世界试验中检出 15 例被医生漏诊的肝癌,性能可与影像医生媲美。

## 5. EAGLE —— 食管癌及癌前病变筛查(非增强/低剂量胸部 CT)

- **论文标题**:Large-scale esophageal cancer screening through noncontrast computed tomography and artificial intelligence
- **期刊/年份**:Nature Medicine,2026(2026 年 9 月 22 日)
- **DOI**:10.1038/s41591-026-04656-4
- **合作方**：四川省肿瘤医院、中山大学肿瘤防治中心等 + 阿里达摩院
- **要点**:EAGLE(Esophageal AI-Guided Lesion Evaluation)用非增强胸部 CT(含低剂量 CT)无创筛查食管癌与癌前病变。训练 6,813 例(2 中心);在 3 国 12 中心 80,612 例上验证。外部测试敏感性 90.0%、特异性 98.5%;低剂量 CT 敏感性 88.4%(可嵌入肺癌筛查流程);可提前 9–21 个月提示恶性病变。定位为内镜前的"分诊工具"。

---

## 附：第 6 项(Science,非 Nature Medicine)

- **RADAR —— 腹部 CT 通用诊断模型**(Science,2026)
- 视觉-语言对比学习模型；超 40 万例增强腹部 CT、约 150 万组 CT-报告配对，拆解出约 1500 万组按解剖结构划分的图文对；单一模型覆盖 **18 个解剖结构、146 种影像征象及疾病**。26 名来自 14 家机构的影像医生评估显示，RADAR 辅助后总体诊断敏感性提高约 10%。

---

