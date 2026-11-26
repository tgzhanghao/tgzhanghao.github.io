# tgzhanghao.github.io

TG 账号批发单页站，模板结构参考 <https://bbtg.cc/>，已替换为本站品牌与域名。

## 文件

- `index.html` — 首页（单文件，样式与脚本内联，无外部依赖）
- `404.html` — 404 页，沿用同一配色
- `robots.txt` / `sitemap.xml` — 收录配置

## 页面结构

Header → Hero → 优势 → 账号套餐 → 规格对比 → 选购指南 → 购买流程 → 用户评价 → FAQ → 底部 CTA → Footer，移动端底部固定购买条。

## 上线前需要改的地方

1. 购买链接：目前所有「立即购买」指向 `https://cnmb.xxid.shop/`，换成自己的商城地址。
2. 品牌与域名：`TG账号批发网`、`TGZHANGHAO.GITHUB.IO`、canonical、JSON-LD 中的 URL。
3. 价格、库存、发货量、评分与用户评价为模板示例数据，按实际业务替换。
4. Google / Bing 站点验证码：`index.html` 头部注释位置。

## 本地预览

```bash
python3 -m http.server 8091
# http://127.0.0.1:8091/
```
