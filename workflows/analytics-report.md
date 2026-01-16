---
description: Phân tích và báo cáo hiệu quả marketing với dashboards và KPI tracking
---

# /analytics-report - Marketing Analytics & Reporting

## Mục đích
Tạo reports và dashboards phân tích hiệu quả marketing. Workflow này cung cấp templates báo cáo, KPI frameworks, và hướng dẫn data visualization để đo lường và tối ưu ROI marketing.

## Input cần cung cấp
- Channels đang sử dụng (Paid, Organic, Email, Social)
- Report period (weekly, monthly, quarterly)
- Stakeholder audience (Executive, Team, Client)
- Current tools (Google Analytics, Facebook Insights, etc.)
- Business goals và KPIs chính

## Workflow

### Phase 1: KPI Framework Setup

#### Marketing KPI Hierarchy
```
Level 1 - Business Impact:
├── Revenue Generated
├── Customer Acquisition Cost (CAC)
├── Customer Lifetime Value (CLV)
└── Marketing ROI

Level 2 - Channel Performance:
├── Paid Media ROAS
├── Organic Traffic Growth
├── Email Revenue Attribution
└── Social Conversion Rate

Level 3 - Tactical Metrics:
├── Click-through Rate (CTR)
├── Cost per Click (CPC)
├── Engagement Rate
└── Open Rate / Click Rate
```

#### KPI by Channel

| Channel | Primary KPI | Secondary KPIs |
|---------|-------------|----------------|
| Paid Ads | ROAS | CTR, CPC, CVR, CAC |
| SEO | Organic Traffic | Rankings, DA, Backlinks |
| Email | Revenue/Email | Open Rate, Click Rate, Unsubscribe |
| Social | Engagement Rate | Reach, Followers, Shares |
| Content | Leads Generated | Time on Page, Bounce Rate |

### Phase 2: Report Templates

#### Weekly Performance Report
```markdown
# Weekly Marketing Report
📅 [Date Range]

## 📊 Executive Summary
- Total Spend: $X,XXX (↑/↓ X% vs LW)
- Revenue Generated: $XX,XXX (↑/↓ X% vs LW)
- ROAS: X.Xx (Target: X.Xx)
- New Leads: XXX (↑/↓ X% vs LW)

## 🎯 Key Wins This Week
1. [Win 1 with specific numbers]
2. [Win 2 with specific numbers]
3. [Win 3 with specific numbers]

## ⚠️ Areas of Concern
1. [Issue 1 + action being taken]
2. [Issue 2 + action being taken]

## 📈 Channel Breakdown

### Paid Media
| Platform | Spend | Revenue | ROAS | CTR |
|----------|-------|---------|------|-----|
| Meta Ads | $X,XXX | $X,XXX | X.Xx | X.X% |
| Google Ads | $X,XXX | $X,XXX | X.Xx | X.X% |

### Organic
- Sessions: XX,XXX (↑/↓ X%)
- New Users: XX,XXX (↑/↓ X%)
- Top Pages: [Page 1], [Page 2], [Page 3]

### Email
- Campaigns Sent: X
- Total Opens: X,XXX (X.X% rate)
- Total Clicks: XXX (X.X% CTR)
- Revenue: $X,XXX

## 📋 Next Week Priorities
1. [Priority 1]
2. [Priority 2]
3. [Priority 3]
```

#### Monthly Performance Report
```markdown
# Monthly Marketing Report
📅 [Month, Year]

## 📊 Month at a Glance

| Metric | Actual | Target | vs LM | vs LY |
|--------|--------|--------|-------|-------|
| Total Spend | $XX,XXX | $XX,XXX | +X% | +X% |
| Revenue | $XXX,XXX | $XXX,XXX | +X% | +X% |
| ROAS | X.Xx | X.Xx | +X% | +X% |
| New Customers | XXX | XXX | +X% | +X% |
| CAC | $XX | $XX | -X% | -X% |

## 🎯 Goals Progress

### Q[X] Goals Status
| Goal | Target | Actual | Status |
|------|--------|--------|--------|
| [Goal 1] | [Target] | [Actual] | 🟢/🟡/🔴 |
| [Goal 2] | [Target] | [Actual] | 🟢/🟡/🔴 |

## 📈 Channel Deep Dive

### Paid Media Performance
[Detailed breakdown with trends]

### SEO Performance
[Keyword rankings, traffic, backlinks]

### Content Performance
[Top posts, engagement, leads]

### Email Performance
[Campaign stats, list growth, automation results]

### Social Media Performance
[Followers, engagement, top content]

## 💡 Key Insights
1. [Insight 1 with data support]
2. [Insight 2 with data support]
3. [Insight 3 with data support]

## 🔮 Next Month Focus
1. [Initiative 1]
2. [Initiative 2]
3. [Initiative 3]

## 📎 Appendix
[Detailed data tables]
```

#### Executive Dashboard Template
```
┌─────────────────────────────────────────────────────────┐
│                   MARKETING DASHBOARD                    │
│                     [Month, Year]                       │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  💰 REVENUE        📈 ROAS           👥 NEW CUSTOMERS   │
│  $XXX,XXX          X.Xx              XXX               │
│  ▲ 15% vs LM       ▲ 0.3x vs LM     ▲ 20% vs LM       │
│                                                         │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  SPEND BY CHANNEL          │  REVENUE BY CHANNEL       │
│  ┌──────────────────┐      │  ┌──────────────────┐     │
│  │ Meta    ████ 40% │      │  │ Meta    █████ 45%│     │
│  │ Google  ██  25%  │      │  │ Google  ███  30% │     │
│  │ Email   █   15%  │      │  │ Email   ██   15% │     │
│  │ Other   █   20%  │      │  │ Other   █    10% │     │
│  └──────────────────┘      │  └──────────────────┘     │
│                                                         │
├─────────────────────────────────────────────────────────┤
│                     TREND (12 MONTHS)                   │
│  Revenue  ──────────────────────/─────▲                 │
│  Spend    ─────────────────────/──────                  │
│           J  F  M  A  M  J  J  A  S  O  N  D           │
└─────────────────────────────────────────────────────────┘
```

### Phase 3: Attribution Models

#### Multi-Touch Attribution
```
First-Touch Attribution:
→ Credit 100% to first interaction
→ Best for: Understanding discovery channels

Last-Touch Attribution:
→ Credit 100% to last interaction
→ Best for: Understanding closing channels

Linear Attribution:
→ Equal credit to all touchpoints
→ Best for: Valuing full journey

Time-Decay Attribution:
→ More credit to recent touchpoints
→ Best for: Long sales cycles

Position-Based (U-Shaped):
→ 40% first, 40% last, 20% middle
→ Best for: Balanced view
```

#### UTM Parameter Framework
```
Campaign Naming Convention:
utm_source:   [platform] - facebook, google, linkedin
utm_medium:   [channel] - cpc, email, social, organic
utm_campaign: [campaign-name] - spring-sale-2024
utm_content:  [creative-id] - video-1, carousel-a
utm_term:     [keyword] - marketing-automation

Examples:
?utm_source=facebook&utm_medium=cpc&utm_campaign=spring-sale-2024&utm_content=video-1

?utm_source=email&utm_medium=newsletter&utm_campaign=weekly-digest-w12
```

### Phase 4: Data Visualization Best Practices

#### Chart Selection Guide
```
Comparing values:       → Bar Chart
Showing trends:         → Line Chart
Part-to-whole:          → Pie/Donut Chart
Correlation:            → Scatter Plot
Distribution:           → Histogram
Geographic:             → Map
Single metrics:         → Scorecard/KPI Card
Progress toward goal:   → Gauge/Progress Bar
```

#### Color Coding Standards
```
Performance Colors:
🟢 Green: Above target (+10%+)
🟡 Yellow: Near target (±10%)
🔴 Red: Below target (-10%+)

Trend Indicators:
▲ Up arrow: Increase
▼ Down arrow: Decrease
─ Flat: No significant change
[Previous content...]

#### Data Debugging Checklist
```
Khi số liệu không khớp (Discrepancies):

1. **GA4 vs CRM/Backend:**
   □ Timezone settings (đảm bảo cả 2 cùng múi giờ)
   □ Sampling (GA4 có bị sample không?)
   □ Bot filtering (CRM có lọc bot không?)
   → Chấp nhận sai số 5-10% là bình thường.

2. **Ad Platform vs GA4:**
   □ Attribution window (Click 1-day vs 7-day?)
   □ View-through conversions (Ads tính, GA4 không tính)
   □ UTM tagging (có thiếu tag không?)

3. **Missing Data:**
   □ Cookie consent banner (người dùng từ chối track)
   □ Ad blockers (chặn script)
   □ Cross-device journey (đứt đoạn tracking)
```

#### Report Design Principles
1. **Lead with insights**, not just data
2. **Compare to benchmarks** (LW, LM, LY, target)
3. **Use consistent formats** across reports
4. **Highlight anomalies** for attention
5. **Include actionable recommendations**

### Phase 5: Output

1. **Report Templates**
   - Weekly performance (1-pager)
   - Monthly deep-dive (5-10 pages)
   - Quarterly business review
   - Executive dashboard

2. **KPI Tracking Spreadsheet**
   - Daily/weekly data entry
   - Automatic calculations
   - Visual trend charts
   - YoY comparisons

3. **Attribution Setup Guide**
   - UTM naming conventions
   - Tracking implementation checklist
   - Attribution model recommendation

4. **Dashboard Wireframes**
   - Executive overview
   - Channel-specific views
   - Campaign performance

## Analytics Tools Stack

| Purpose | Free Tools | Paid Tools |
|---------|------------|------------|
| Web Analytics | GA4, Plausible | Adobe Analytics |
| Social | Native insights | Sprout Social, Hootsuite |
| Ads | Platform dashboards | Supermetrics, Funnel.io |
| All-in-one | Google Data Studio | Tableau, Looker, Databox |
| Email | ESP dashboards | Litmus, Klaviyo Analytics |

## Reporting Cadence

| Report Type | Frequency | Audience | Depth |
|-------------|-----------|----------|-------|
| Daily Pulse | Daily | Marketing team | Metrics only |
| Weekly Report | Weekly | Team + Manager | Metrics + insights |
| Monthly Report | Monthly | Leadership | Full analysis |
| Quarterly Review | Quarterly | Executive | Strategic |

## Ví dụ sử dụng

```
User: /analytics-report
Channels: Meta Ads, Google Ads, Email, Organic
Period: Monthly
Audience: CMO and Marketing Director
Tools: GA4, Meta Business Suite, Mailchimp
Goals: 20% revenue growth, CAC under $50
```

## Related Workflows
- `/marketing-campaign` - Campaign planning
- `/ads-optimize` - Paid media optimization
- `/seo-audit` - Organic performance
