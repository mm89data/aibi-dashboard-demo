# TPC-H Supply Chain Analytics

AI/BI dashboard built with Genie Code on `samples.tpch` data.

## Demo Flow

1. **Prompt 1** — Semantic model: 6 metric views + relationship graph
2. **Prompt 2** — Sales Overview page with KPIs, charts, and global filters
3. **Prompt 3** — Modify existing page + add Supplier Analysis page

Each prompt auto-commits via the `dashboard-git-versioning` skill.

## Data Source

`samples.tpch` (TPC-H benchmark): orders, lineitem, customer, nation, region, supplier

## Git Versioning

Each prompt commits changes via the `dashboard-git-versioning` skill.
Full audit trail: model → build → iterate.
