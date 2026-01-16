---
description: Thực hiện SEO audit toàn diện và đề xuất cải thiện ranking
---

# /seo-audit - Đánh Giá SEO

## Mục đích
Thực hiện SEO audit toàn diện cho website và đề xuất các cải thiện để tăng organic traffic. Workflow này cover cả Technical SEO, On-page SEO, và Content SEO.

## Input cần cung cấp
- Website URL
- Target keywords (optional)
- Competitor URLs (optional)
- Current traffic data (optional)

## Workflow

### Phase 1: Technical SEO Audit

#### Meta Tags Check
```
✅ Title tag: 50-60 characters, keyword trong đầu
✅ Meta description: 150-160 characters, compelling CTA
✅ Canonical tags: Properly set
✅ Robots meta: index, follow (unless intentional)
```

#### Site Structure
- URL structure clean và descriptive
- Breadcrumbs implementation
- Internal linking structure
- XML sitemap tồn tại và submitted
- Robots.txt configured correctly

#### Performance
- Page speed score (Core Web Vitals)
  - LCP (Largest Contentful Paint) < 2.5s
  - FID (First Input Delay) < 100ms
  - CLS (Cumulative Layout Shift) < 0.1
- Mobile responsiveness
- HTTPS implementation

#### Crawlability
- Broken links (404 errors)
- Redirect chains/loops
- Orphan pages
- Duplicate content issues

### Phase 2: On-page SEO Audit

#### Content Structure
```
✅ H1 tag: Một H1 duy nhất, chứa primary keyword
✅ H2-H6: Logical hierarchy, chứa secondary keywords
✅ Paragraph length: 2-3 sentences max
✅ Bullet points và numbered lists
```

#### Keyword Optimization
- Primary keyword trong:
  - Title tag
  - H1
  - First 100 words
  - URL
  - Meta description
- Secondary keywords
- LSI keywords (related terms)

#### Image Optimization
- Alt tags descriptive và keyword-rich
- File names optimized
- Image compression
- Next-gen formats (WebP)
- Lazy loading implemented

#### Internal Linking
- Contextual links trong content
- Related posts/products
- Anchor text optimization
- Link depth (3 clicks max to any page)

### Phase 3: Content SEO Audit

#### Content Quality
- E-E-A-T signals (Experience, Expertise, Authoritativeness, Trustworthiness)
- Content freshness
- Comprehensive coverage của topic
- Unique value proposition

#### Content Gaps
- Topics competitors rank for mà bạn không có
- Questions chưa được answer
- Long-tail keyword opportunities
- Featured snippet opportunities

#### User Intent Alignment
```
Informational: "how to", "what is", guides
Navigational: brand searches, specific pages
Commercial: "best", "review", comparisons
Transactional: "buy", "price", "discount"
```

### Phase 4: Competitor Analysis

#### Quick Wins
- Keywords đang rank #4-10 (push to top 3)
- Keywords rank #11-20 (push to page 1)
- Content gaps dễ fill

#### Long-term Opportunities
- High-volume keywords cần content mới
- Backlink opportunities
- Featured snippet targets

### Phase 5: Output

#### SEO Audit Report
1. **Executive Summary** - Overall health score
2. **Critical Issues** - Fix ngay lập tức
3. **High Priority** - Fix trong 30 ngày
4. **Medium Priority** - Fix trong 90 ngày
5. **Opportunities** - Growth potential

#### Priority Action Items
```
🔴 Critical (Fix Now):
- [ ] Broken links on homepage
- [ ] Missing meta descriptions

🟠 High (This Week):
- [ ] Optimize title tags
- [ ] Add internal links

🟡 Medium (This Month):
- [ ] Improve page speed
- [ ] Add schema markup
```

#### Implementation Checklist
- Step-by-step fixes
- Tools needed
- Expected impact
- Time estimate

## SEO Tools Recommendations
- **Keyword Research**: Ahrefs, SEMrush, Ubersuggest
- **Technical Audit**: Screaming Frog, Sitebulb
- **Page Speed**: Google PageSpeed Insights, GTmetrix
- **Rank Tracking**: Ahrefs, SERPWatcher

## Ví dụ sử dụng

```
User: /seo-audit
URL: https://example.com
Target keywords: "marketing automation", "AI marketing tools"
Competitors: competitor1.com, competitor2.com
```

## Related Workflows
- `/content-create` - Create SEO-optimized content
- `/marketing-campaign` - Content marketing strategy
