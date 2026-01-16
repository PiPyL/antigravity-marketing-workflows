---
description: Tối ưu hóa chiến dịch quảng cáo Meta Ads và Google Ads
---

# /ads-optimize - Tối Ưu Quảng Cáo

## Mục đích
Tối ưu hóa chiến dịch quảng cáo trên Meta Ads và Google Ads. Workflow này giúp tạo ad copy variants, targeting suggestions, và budget allocation recommendations.

## Input cần cung cấp
- Campaign objective (awareness, traffic, conversions, leads)
- Target audience information
- Current ad performance data (nếu có)
- Budget constraints
- Platform (Meta Ads, Google Ads, hoặc cả hai)

## Workflow

### Phase 1: Campaign Audit
- Review current campaign setup và structure
- Analyze targeting và placements
- Check conversion tracking implementation
- Evaluate ad creative performance

### Phase 2: Ad Copy Optimization

#### Headlines (5 variants)
```
Format: [Benefit] + [Action] + [Urgency/Social Proof]

Ví dụ:
1. "Tăng 300% Leads với AI Marketing Automation"
2. "10,000+ Marketers Đang Dùng Tool Này"
3. "Tiết Kiệm 20 Giờ/Tuần với Marketing AI"
4. "Free Trial: AI Marketing Assistant"
5. "Được Tin Dùng bởi Fortune 500 Companies"
```

#### Descriptions (5 variants)
```
Format: [Problem] → [Solution] → [CTA]

Ví dụ:
1. "Mệt mỏi với manual marketing tasks? AI automation giúp bạn scale 10x. Dùng thử miễn phí."
2. "Từ lead gen đến conversion, tự động hóa toàn bộ funnel. Bắt đầu trong 5 phút."
```

#### CTAs phù hợp
- Awareness: Learn More, Discover, Explore
- Consideration: Get Started, Try Free, See Demo
- Conversion: Buy Now, Start Trial, Sign Up

### Phase 3: Creative Recommendations

#### Image Ads
- Format: 1:1 cho feed, 9:16 cho stories
- Elements: Product, Face, Text overlay (<20%)
- Colors: Contrast với platform UI

#### Video Ads
- Length: 15s cho awareness, 30-60s cho consideration
- Hook: First 3 seconds critical
- Captions: Always on (85% watch without sound)

#### Carousel Ads
- 3-5 cards optimal
- First card = strongest hook
- Each card = standalone value

### Phase 4: Targeting Refinement

#### Audience Segmentation
```
Cold Audience:
- Interest-based targeting
- Lookalike audiences (1-3%)
- Broad targeting với good creative

Warm Audience:
- Website visitors (30/60/90 days)
- Video viewers (25%, 50%, 75%)
- Engagement audiences

Hot Audience:
- Add to cart abandoners
- Past purchasers (upsell)
- Email list custom audiences
```

#### Exclusions
- Recent purchasers (7-14 days)
- Irrelevant interests
- Low-quality placements

### Phase 5: Budget Allocation

#### Testing Phase (Week 1-2)
- 70% budget cho proven audiences
- 30% budget cho testing new audiences
- $5-10/day per ad set minimum

#### Scaling Phase (Week 3+)
- Double budget mỗi 3-4 ngày nếu ROAS tốt
- Cut losers fast (sau 500-1000 impressions)
- Horizontal scaling > Vertical scaling

### Phase 6: Output
1. **Ad Copy Matrix** - Headlines x Descriptions combinations
2. **Targeting Document** - Audience definitions và exclusions
3. **A/B Testing Plan** - What to test và success metrics
4. **Budget Calculator** - Allocation recommendations
5. **Performance Benchmarks** - Industry-standard KPIs

## KPI Benchmarks

| Metric | E-commerce | SaaS | Lead Gen |
|--------|-----------|------|----------|
| CTR | 1-2% | 0.5-1% | 1-3% |
| CPC | $0.5-2 | $2-10 | $1-5 |
| CVR | 2-4% | 1-3% | 5-10% |
| ROAS | 3-5x | N/A | N/A |
| CPL | N/A | $50-200 | $20-100 |

## Ví dụ sử dụng

```
User: /ads-optimize
Platform: Meta Ads
Objective: Lead Generation
Audience: B2B SaaS, Marketing teams
Budget: $3,000/month
Current CPA: $80 (want to reduce to $50)
```

## Related Workflows
- `/marketing-campaign` - Overall campaign strategy
- `/content-create` - Ad creative content
- `/lead-generate` - Post-click optimization
