# 中国历法与传统天文星象 · 科普稿预印本（镜像）

本仓库是「中国历法与传统天文星象」系列科普稿的**预印本镜像**，与发表在 **Zenodo** 上的预印本记录一一对应。写这些稿子，起因是一堆日常里被反复问到的问题：立春那天出生的孩子生肖该按哪个算、古人没有钟表怎么知道现在是几点、黄道和白道到底差在哪儿。这些问题看着零碎，底下其实是同一套历法与星象的知识，于是索性按顺序一篇篇写下来，写成一份可以按需查阅的整理稿。

**正式引用请使用各篇的 Zenodo DOI**（见下表；表内各号为 **concept DOI**，永久指向最新版本）。

**站点入口（本仓库 Pages 首页 · 篇目与 PDF 直链）**：<https://kuangchujia.github.io/kuangchujia-preprints/>

<!-- ANCHOR-BLOCK-BEGIN -->
## ★ 本项目在学术网络中的位置

| 项 | 地址 |
|:---|:---|
| **作者** | 邝楚嘉（Chujia Kuang） |
| **ORCID** | [0009-0002-7650-833X](https://orcid.org/0009-0002-7650-833X) |
| **个人主页 / 全部成果总入口** | <https://kuangchujia.com> |
| **数据集 DOI（Zenodo）** | [10.5281/zenodo.22788686](https://doi.org/10.5281/zenodo.22788686)（concept DOI，永久指向最新版本） |
| **配套数据集仓库** | <https://github.com/Kuangchujia/chinese-calendar-dataset> |
| **本仓库** | <https://github.com/Kuangchujia/kuangchujia-preprints> |
| **站点（本仓库 Pages 首页）** | <https://kuangchujia.github.io/kuangchujia-preprints/> |

**本仓库是什么**：本系列科普稿预印本的**镜像与备份入口**（PDF ＋ 书目元数据），与 Zenodo 上一一对应。本仓库提供同一批 PDF 的浏览与下载通道，每份 PDF 的内页题名块都已印有该篇 DOI。

**正式引用请以 Zenodo 记录为准。**

**配套数据集**：本系列所依据的历法公共数据集（二十四节气交节时刻、历代历法改革年表、干支纪日对照表）见 <https://github.com/Kuangchujia/chinese-calendar-dataset>，Zenodo concept DOI [10.5281/zenodo.22788686](https://doi.org/10.5281/zenodo.22788686)。该数据集由生成脚本自算而成，可复算、可核验，凡引用本系列任一预印本，如需追溯到具体的节气时刻或干支日序，请一并注明该数据集的 DOI。
<!-- ANCHOR-BLOCK-END -->

## 篇目（已发布 9／11）

| 篇号 | 标题 | Zenodo DOI | 状态 |
|:--:|:---|:---|:---|
| 002 | 立春换岁，还是正月初一换岁？ | [10.5281/zenodo.22803746](https://doi.org/10.5281/zenodo.22803746) | ✅ 已发布 |
| 003 | 三本历法·三种时间 | [10.5281/zenodo.22821576](https://doi.org/10.5281/zenodo.22821576) | ✅ 已发布 |
| 004 | 立春不是一整天，只有一秒钟 | [10.5281/zenodo.22837998](https://doi.org/10.5281/zenodo.22837998) | ✅ 已发布 |
| 005 | 正月本来不是一月 | [10.5281/zenodo.22851039](https://doi.org/10.5281/zenodo.22851039) | ✅ 已发布 |
| 006 | 古人的一天，从晚上十一点开始 | [10.5281/zenodo.22866122](https://doi.org/10.5281/zenodo.22866122) | ✅ 已发布 |
| 007 | 钟表上的出生时间，不等于你出生的时辰 | [10.5281/zenodo.22884370](https://doi.org/10.5281/zenodo.22884370) | ✅ 已发布 |
| 008 | 时间是怎么产生的？ | [10.5281/zenodo.22906313](https://doi.org/10.5281/zenodo.22906313) | ✅ 已发布 |
| 009 | 天上三条道：黄道、白道、赤道 | [10.5281/zenodo.22926807](https://doi.org/10.5281/zenodo.22926807) | ✅ 已发布 |
| 010 | 古人的星空：三垣与二十八宿 | [10.5281/zenodo.22797854](https://doi.org/10.5281/zenodo.22797854) | ✅ 已发布 |
| 011 | 没有指南针，古人怎么定方向 | — | 待发布 |
| 012 | 干支：从一棵树到二十二个字 | — | 待发布 |

> **同步规则**：PDF **只收录已正式发布（已分配 DOI）的篇目**。Zenodo 在发布时会用预保留 DOI 重出 PDF，故未发布的版本与正式版并不一致——与其先推一份「待替换」的，不如发布后一次到位。未发布篇目的书目数据仍见 metadata/。

## 目录结构

```
preprints/   已发布篇目的 PDF（文件名含篇号与标题，内页印有 DOI）
metadata/    各篇在 Zenodo 上的书目元数据（title / description / keywords / license）
index.html   本站 Pages 首页（publications 索引页，由 gh_preprints_sync.py 生成）
.nojekyll    令 Pages 不走 Jekyll，仓库文件按原样送出
```

## 内容性质

全部内容为**中国传统历法与传统天文星象的科普整理**，依公开文献与天文历算数据写成。凡涉及具体时刻、日期、星位的地方，都以可查的历算数据与传世文献为据，能给出来源的尽量给出来源；文献之间有分歧的，把分歧本身写出来，不替读者选边。**不含预测性论断，亦不涉个体测算。**

## 相关仓库

- [`chinese-calendar-dataset`](https://github.com/Kuangchujia/chinese-calendar-dataset) —— 本系列所依据的历法公共数据集（二十四节气交节时刻、历代历法改革年表、干支纪日对照表），Zenodo DOI [10.5281/zenodo.22788686](https://doi.org/10.5281/zenodo.22788686)（**concept DOI**，永久指向最新版本）。

## 许可

CC BY 4.0，见 `LICENSE`；引用格式见 `CITATION.cff`。

转载或引用时请保留作者署名与 DOI。
