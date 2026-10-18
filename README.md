# NAT10 Evidence Atlas / NAT10 文献证据地图

中文交互文献地图。2026-10-18 PubMed `NAT10[Title]` 检索330条，按六类研究证据分类。

在线阅读：https://zjl-bujiaban.github.io/nat10-evidence-atlas/

全文获取与审阅层级、分类边界请阅读 [METHODOLOGY.md](METHODOLOGY.md)。正文结构化核对不等于全部逐段人工精读。

## 使用

- 搜索题名、PMID、疾病和机制。
- 按主分类或多标签、全文状态、疾病、年份及选题重点筛选。
- 点击文献查看分类依据、简短摘录、人工复核说明及原文链接。
- 下载 [Excel](nat10-evidence.xlsx)、[CSV](nat10-evidence.csv) 或 [JSON](data.json)。

## 本地预览

无需构建或安装依赖，在此目录运行 `python -m http.server 8000`，访问 `http://localhost:8000`。直接以file协议打开时浏览器可能阻止JSON加载。

## 文件

`index.html`、`style.css`、`app.js`为静态网站；`data.json`为公开分类数据；`acquisition-manifest.json`记录获取状态与来源，不包含全文。

## 权利说明

论文权利归原作者与出版社。本站不分发论文全文或PDF，仅发布书目、简短证据摘录与分类解读。未标注为经过完整的系统综述、全文精读或风险偏倚评价。
