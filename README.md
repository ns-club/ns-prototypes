# ns-prototypes

用于存放 `ns-club` 各业务线 HTML 原型的仓库，按产品域进行分类管理。

## 目录说明

- `wms/`：WMS 相关原型
- `erp/`：ERP 与后台相关原型
- `oms/`：OMS 相关原型
- `tms/`：TMS 与物流相关原型
- `shared/`：跨系统复用或公共能力原型

## 建议约定

每个原型单独建一个目录，例如：

```text
wms/
  inbound-receiving-v1/
    index.html
    assets/
```

建议每个原型目录包含：

- `index.html` 作为入口文件
- 原型依赖的静态资源
- 如有需要，可补充一个简短的 `README.md` 说明背景和使用方式

## 发布方式

该仓库适合存放静态 HTML 原型，后续如有需要，可以直接接入 GitHub Pages 做在线预览。
