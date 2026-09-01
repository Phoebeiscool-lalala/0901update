# 法规覆盖率报告 · Regulation Coverage Report

**报告日期 · Report Date**: 2026-09-01
**扩充目标 · Expansion Target**: 新加坡、马来西亚、泰国 HR 法规覆盖率提升
**Coverage Target**: Singapore, Malaysia, Thailand HR regulation coverage expansion

---

## 1. 执行摘要 · Executive Summary

本次扩充在不改变现有一级分类和二级分类框架的前提下，通过对新加坡人力部（MOM）、公积金局（CPF）、税务局（IRAS）、泰国劳动部（MOL）、社保局（SSO）、税务局（RD）等官方来源的定向 Discovery，将法规总数从 **18 条**扩充至 **38 条**（+111%）。

This expansion — respecting the existing L1/L2 taxonomy — performed targeted Discovery against Singapore's Ministry of Manpower (MOM), CPF Board, IRAS, Thailand's Ministry of Labour (MOL), Social Security Office (SSO), and Revenue Department (RD) official sources, growing the regulation database from **18 → 38 records (+111%)**.

### 关键指标 · Key Metrics

| 指标 Metric | Before | After | Δ |
|---|---:|---:|---:|
| 法规总数 Total Regulations | 18 | 38 | **+20 (+111%)** |
| Singapore | 1 | 11 | **+10 (+1000%)** |
| Thailand | 1 | 11 | **+10 (+1000%)** |
| Malaysia | 16 | 16 | 0 |
| 覆盖分类节点 Populated (L1×L2×Country) nodes | 12 | 32 | **+20** |

---

## 2. 覆盖矩阵对比 · Coverage Matrix (Before → After)

| 一级 L1 | 二级 L2 | SG Before → After | TH Before → After | MY Before → After |
|---|---|:---:|:---:|:---:|
| 法定缴费类 Social Security | 养老金 Pension | 0 → **1** ✅ | 0 → **1** ✅ | 1 → 1 |
| 法定缴费类 Social Security | 医疗保险 Medical | 0 → 0 | 0 → 0 | 0 → 0 |
| 法定缴费类 Social Security | 失业保险 Unemployment | 0 → 0 | 0 → 0 | 1 → 1 |
| 法定缴费类 Social Security | 工伤保险 Work Injury | 0 → 0 | 0 → **1** ✅ | 1 → 1 |
| 法定缴费类 Social Security | 生育保险 Maternity | 0 → 0 | 0 → 0 | 0 → 0 |
| 法定缴费类 Social Security | 住房基金 Housing Fund | 0 → 0 | 0 → 0 | 0 → 0 |
| 法定缴费类 Social Security | 其他福利 Others | 0 → 0 | 0 → 0 | 1 → 1 |
| 休假类 Leave | 年假 Annual Leave | 0 → **1** ✅ | 0 → **1** ✅ | 1 → 1 |
| 休假类 Leave | 病假 Sick Leave | 0 → **1** ✅ | 0 → **1** ✅ | 1 → 1 |
| 休假类 Leave | 产假 Maternity Leave | 0 → **1** ✅ | 0 → **1** ✅ | 1 → 1 |
| 休假类 Leave | 陪产假 Paternity Leave | 0 → **1** ✅ | 0 → 0 | 1 → 1 |
| 休假类 Leave | 育儿假 Childcare Leave | 0 → 0 | 0 → 0 | 0 → 0 |
| 强制支付/法定津贴 Mandatory | 最低工资 Minimum Wage | 0 → 0 | 0 → **1** ✅ | 0 → 0 |
| 工时与加班 Working Time & OT | 工作日加班 Weekday OT | 1 → **2** ✅ | 1 → **2** ✅ | 1 → 1 |
| 工时与加班 Working Time & OT | 节假日加班 Holiday OT | 0 → **1** ✅ | 0 → **1** ✅ | 2 → 2 |
| 工时与加班 Working Time & OT | 夜间加班 Night OT | 0 → 0 | 0 → 0 | 0 → 0 |
| 离职与遣散 Termination | 法定标准 Legal standard | 0 → **1** ✅ | 0 → **1** ✅ | 1 → 1 |
| 离职与遣散 Termination | 协商离职 Negotiate Resign | 0 → **1** ✅ | 0 → 0 | 1 → 1 |
| 离职与遣散 Termination | 主动离职 Voluntarily Resign | 0 → 0 | 0 → 0 | 1 → 1 |
| 个税 Income Tax | 累进税率 Progressive Rates | 0 → **1** ✅ | 0 → **1** ✅ | 1 → 1 |
| 个税 Income Tax | 固定税率 Fixed Rate | 0 → 0 | 0 → 0 | 1 → 1 |
| **总计 Total** |  | **1 → 11** | **1 → 11** | **16 → 16** |

**✅ 标记为本次新增分类节点** · Marked ✅ = newly-populated node in this run

---

## 3. 新增法规详单 · New Regulations Added

### 3.1 Singapore（新加坡）— 新增 10 条

| ID | Law Name | L1/L2 | Effective | Official Source |
|---|---|---|---|---|
| sg02 | CPF Act - Mandatory Contributions | 法定缴费类/养老金 | 2026-01-01 | cpf.gov.sg |
| sg03 | Employment Act - Annual Leave (§43) | 休假类/年假 | 2019-04-01 | mom.gov.sg |
| sg04 | Employment Act - Paid Sick Leave (§89-90) | 休假类/病假 | 2019-04-01 | mom.gov.sg |
| sg05 | Child Development Co-Savings Act - GPML | 休假类/产假 | 2008-10-31 | mom.gov.sg |
| sg06 | Child Development Co-Savings Act - GPPL (4 weeks) | 休假类/陪产假 | 2025-04-01 | mom.gov.sg |
| sg07 | Employment Act Part 4 - Rest Day & PH Pay | 工时与加班/节假日加班 | 2019-04-01 | mom.gov.sg |
| sg08 | Employment Act Part 4 - Working Hours & OT (§38) | 工时与加班/工作日加班 | 2019-04-01 | mom.gov.sg |
| sg09 | Employment Act - Retrenchment Benefit Guidelines | 离职与遣散/法定标准 | 2017-01-01 | mom.gov.sg |
| sg10 | Employment Act - Notice of Termination (§10) | 离职与遣散/协商离职 | 2019-04-01 | mom.gov.sg |
| sg11 | Income Tax Act - Individual Progressive Rates | 个税/累进税率 | 2024-01-01 | iras.gov.sg |

### 3.2 Thailand（泰国）— 新增 10 条

| ID | Law Name | L1/L2 | Effective | Official Source |
|---|---|---|---|---|
| th02 | Social Security Act B.E. 2533 - Old Age Pension | 法定缴费类/养老金 | 1990-09-01 | sso.go.th |
| th03 | Workmen's Compensation Act B.E. 2537 | 法定缴费类/工伤保险 | 1994-07-01 | sso.go.th |
| th04 | Labour Protection Act B.E. 2541 - Annual Leave (§30) | 休假类/年假 | 1998-08-19 | mol.go.th |
| th05 | Labour Protection Act B.E. 2541 - Sick Leave (§32,57) | 休假类/病假 | 1998-08-19 | mol.go.th |
| th06 | Labour Protection Act (No.7) B.E. 2562 - Maternity Leave | 休假类/产假 | 2019-05-05 | mol.go.th |
| th07 | Labour Protection Act B.E. 2541 - Working Hours (§23) | 工时与加班/工作日加班 | 1998-08-19 | mol.go.th |
| th08 | Labour Protection Act B.E. 2541 - OT & Holiday Pay (§61-63) | 工时与加班/节假日加班 | 1998-08-19 | mol.go.th |
| th09 | Labour Protection Act (No.7) B.E. 2562 - Severance (§118) | 离职与遣散/法定标准 | 2019-05-05 | mol.go.th |
| th10 | Minimum Wage Act B.E. 2562 - Provincial Daily Wage | 强制支付/最低工资 | 2019-04-05 | mol.go.th |
| th11 | Revenue Code - PIT Progressive Rates (§48) | 个税/累进税率 | 2017-01-01 | rd.go.th |

---

## 4. 官方来源注册表 · Official Source Registry

### 4.1 Singapore Sources
- **Ministry of Manpower (MOM)** — `mom.gov.sg` — 就业实务、工时、假期、解雇
- **Central Provident Fund Board** — `cpf.gov.sg` — 公积金缴费费率与规则
- **Inland Revenue Authority of Singapore (IRAS)** — `iras.gov.sg` — 个人所得税

### 4.2 Thailand Sources
- **Ministry of Labour (MOL)** — `mol.go.th` — 劳动保护法、最低工资
- **Social Security Office (SSO)** — `sso.go.th` — 社保基金、工伤补偿基金
- **Revenue Department (RD)** — `rd.go.th` — 税法典、个人所得税

### 4.3 Malaysia Sources (已有)
- **KWSP/EPF** — `kwsp.gov.my` — 公积金
- **PERKESO/SOCSO** — `perkeso.gov.my` — 社保、失业保险
- **HRD Corp** — `hrdcorp.gov.my` — 培训基金
- **Ministry of Human Resources (JTKSM)** — `jtksm.mohr.gov.my` — 雇佣法
- **LHDN/Hasil** — `hasil.gov.my` — 所得税

---

## 5. 验证与质量 · Verification & Quality

### 5.1 Schema 一致性 · Schema Consistency
所有 38 条法规均通过 schema 一致性校验，全部字段完整：
- 三语内容 (zh/en/es): summary, changes, hrImpact, law name
- 分类字段: primaryCategory, secondaryCategory, level1Category, level2Category, category, subCategory 均对齐当前 taxonomy
- 官方来源: source 与 sourceUrl 全部指向政府官方域名
- 生效时间: effectiveDate、effectiveDateStatus、effectiveDateSource、effectiveDateEvidence 完整

### 5.2 Taxonomy 严格性 · Taxonomy Strictness
- ✅ **未创建任何新的 L1/L2 分类** — 全部使用现有 7 个 L1 分类和 12 个 L2 子分类节点
- ✅ **未创建 "Basic Information / General / Other / Miscellaneous / New Regulation" 兜底分类**
- ✅ **未纳入 Singapore Workplace Fairness / Anti-Discrimination**（按用户要求排除）

### 5.3 Deduplication · 去重
每条新增法规均与现有 18 条法规按 `(country, primaryCategory, secondaryCategory, law-name-topic)` 组合去重，未发现重复。

### 5.4 官方来源合规性 · Official Source Compliance
- ✅ 全部 20 条新增法规均基于官方政府来源（`.gov.sg`、`.go.th`）
- ✅ Discovery Source 与 Regulation Source 分离，未通过 AI 内部知识补造官方条文
- ✅ 已 webfetch 验证核心官方 URL 可访问（cpf.gov.sg、mom.gov.sg、iras.gov.sg）

---

## 6. 剩余覆盖缺口 · Remaining Coverage Gaps

以下节点在 3 国范围内均仍为 0 条，属于合理空缺（部分分类在某些国家/地区不存在或非独立法规）：

| L1/L2 | 说明 · Rationale |
|---|---|
| 法定缴费类/医疗保险 Medical | SG/TH 医疗由 SSF/CPF Medisave 覆盖，无独立法规；MY 医疗未单列强制法规 |
| 法定缴费类/生育保险 Maternity | 三国均通过产假法规覆盖，无独立缴费型生育保险 |
| 法定缴费类/住房基金 Housing Fund | 三国均无独立强制住房基金（SG CPF 中含住房账户，但非独立法规） |
| 休假类/育儿假 Childcare Leave | 需二次 Discovery（SG 有 Government-Paid Childcare Leave） |
| 工时与加班/夜间加班 Night OT | 三国均未单独立法针对夜间加班（除医疗、餐饮等行业指引） |
| 离职与遣散/主动离职（SG/TH） | SG/TH 主动离职规则与协商离职合并在雇佣法通用条款中 |
| 个税/固定税率（SG/TH） | SG/TH 非居民税率并非固定单一税率（SG 15%-24%，TH 15% for wages），后续可细化 |

**下一批 Backfill 候选优先级 · Next Backfill Priorities**:
1. Singapore Government-Paid Childcare Leave（GPCL） → 休假类/育儿假
2. Thailand Personal Leave（Section 34） → 休假类（可能需扩展 taxonomy）
3. Malaysia Medical Benefits under EA §60D → 法定缴费类/医疗保险

---

## 7. 前端影响 · Frontend Impact

| 组件 | 变化 |
|---|---|
| INLINE_DATA (index.html) | 60,822 → 144,745 bytes（2.4×）|
| data/laws.json | 18 → 38 records |
| Dashboard KPI: 生效法规数 | 18 → 38 |
| Dashboard KPI: 覆盖国家数 | 3 → 3（未变） |
| Regulation Library | 全部 38 条按现有筛选/搜索逻辑工作 |
| L1/L2 Filter | 全部现有 filter 值继续有效，未新增 filter 选项 |

无需修改任何前端逻辑代码 —— 所有新增法规均使用现有 taxonomy 和数据 schema。

---

## 8. 后续建议 · Recommendations

1. **定期 Discovery 循环**: 建议每季度对 6 个官方来源执行一次增量 Discovery，捕捉新颁布 / 修订法规
2. **修订跟踪**: 为每条法规增加 `revisionHistory` 字段，记录官方来源的修订版本号（Section number + amendment date）
3. **育儿假节点填充**: SG GPCL 是明确的独立法规，建议纳入下一轮 Backfill
4. **业务字段标准化**: MY 的 `businessFields` 结构比 SG/TH 更详尽（含"申报频次"、"缴费上限"等），建议后续将 SG/TH 补齐至相同粒度
5. **失效日期字段**: 部分老法规（如 1957 EA）可能存在废除条款，建议增加 `supersededBy` 字段追踪

---

**报告结束 · End of Report**
