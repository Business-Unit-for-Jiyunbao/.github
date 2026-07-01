# 集运宝业务线 / Jiyunbao

集运宝网站、产品入口和后续业务系统资产。

## Repository Map

| Repository | Visibility | Purpose |
|---|---:|---|
| [`jiyunbao-website`](https://github.com/Business-Unit-for-Jiyunbao/jiyunbao-website) | private | Jiyunbao company website deployed to Cloudflare Pages. |
| [`.github`](https://github.com/Business-Unit-for-Jiyunbao/.github) | public | 组织 profile 和仓库地图。 |

## Scope

适合放在本组织：

- 集运宝官网、产品入口、营销页和业务系统。
- 集运宝相关需求、部署和运营材料。

不适合放在本组织：

- MCN/KOL、Xinliang、BidScout 等其它业务。
- 集团级制度/组合管理，这些属于 President-Office。

## Governance

- 具体业务代码、部署、需求和数据资产留在本业务组织。
- 跨 BU 的战略、组合、制度和决策进入 `President-Office`。
- 通用工程底座、RuoYi/Yudao clone/codegen 能力进入 `Business-Unit-for-Platform`。
- AI 平台产品和 AI infra 子域进入 `Business-Unit-for-AI-Platform`。
- 生产部署默认按多机模式设计，数据库/缓存不以 `127.0.0.1` 作为生产默认。

---

_Last updated: 2026-07-01_
