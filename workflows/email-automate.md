---
description: Tự động hóa email marketing với sequences, templates và best practices
---

# /email-automate - Email Marketing Automation

## Mục đích
Tự động hóa email marketing end-to-end. Workflow này cung cấp email sequences hoàn chỉnh, templates theo từng mục đích, và best practices để tối đa hóa deliverability và conversions.

## Input cần cung cấp
- Business type (E-commerce, SaaS, Service, B2B)
- Email marketing goal (onboarding, nurture, sales, retention)
- Target audience description
- Current email list size (optional)
- ESP đang sử dụng (Mailchimp, Klaviyo, ConvertKit, etc.)

## Workflow

### Phase 1: Email Strategy Setup

#### Segmentation Framework
```
Demographic Segments:
- Location/Timezone
- Industry/Job title
- Company size

Behavioral Segments:
- Purchase history (first-time, repeat, high-value)
- Email engagement (active, dormant, at-risk)
- Website activity (pages visited, time on site)
- Lead source (organic, paid, referral)

Lifecycle Stages:
- Subscriber → Lead → MQL → SQL → Customer → Advocate
```

#### Email Types Matrix
| Type | Frequency | Purpose | Open Rate Target |
|------|-----------|---------|------------------|
| Welcome | 1x | Onboard | 50%+ |
| Newsletter | Weekly | Nurture | 20-30% |
| Promotional | 2-4x/month | Convert | 15-25% |
| Transactional | Triggered | Inform | 60%+ |
| Re-engagement | Triggered | Win-back | 10-15% |

### Phase 2: Email Sequences

#### Welcome Sequence (5-7 emails)

**Email 1: Welcome (Day 0, immediate)**
```
Subject: Chào mừng đến [Brand]! 🎉
Preview: Đây là những gì bạn sẽ nhận được...

Hi [Name],

Cảm ơn bạn đã join [Brand] community!

Đây là những gì bạn có thể mong đợi:
✅ [Benefit 1] - mỗi [frequency]
✅ [Benefit 2] - exclusive cho subscribers
✅ [Benefit 3] - được gửi đến inbox

🎁 Để cảm ơn, đây là [welcome gift]:
[CTA Button: Claim Gift]

Có câu hỏi? Reply email này - tôi đọc tất cả!

[Your name]
[Company]

P.S. Thêm [email] vào danh bạ để không bỏ lỡ email!
```

**Email 2: Value Delivery (Day 1)**
```
Subject: [Số] điều bạn cần biết về [Topic]
Preview: Đây là những insights quan trọng nhất...

Hi [Name],

Hôm qua bạn đã join - hôm nay tôi muốn chia sẻ 
những insights quan trọng nhất về [topic]:

1. [Insight 1 + brief explanation]
2. [Insight 2 + brief explanation]
3. [Insight 3 + brief explanation]

💡 Quick win: Hãy thử [actionable tip] ngay hôm nay.

Ngày mai, tôi sẽ chia sẻ về [teaser for next email]...

[Your name]
```

**Email 3: Story/Case Study (Day 3)**
```
Subject: Cách [Customer] đạt được [Result]
Preview: Từ [problem] đến [outcome]...

Hi [Name],

Hãy để tôi kể bạn nghe về [Customer name]...

Trước đây: [Pain point description]
Sau khi áp dụng [solution]: [Specific results]

Đây là 3 bước họ đã làm:
1. [Step 1 with detail]
2. [Step 2 with detail]
3. [Step 3 with detail]

Bạn cũng có thể làm điều tương tự.
[CTA: See How / Start Now]

[Your name]
```

**Email 4: Social Proof (Day 5)**
```
Subject: Đây là lý do [số] người chọn [Brand]
Preview: Reviews thật từ customers thật...

Hi [Name],

Đừng chỉ tin lời tôi. 
Đây là những gì customers nói:

"[Testimonial 1]" - [Name, Title]
"[Testimonial 2]" - [Name, Title]
"[Testimonial 3]" - [Name, Title]

Join [number]+ người đang sử dụng [Product]
[CTA: Get Started]

[Your name]

P.S. Rating trung bình của chúng tôi: ⭐⭐⭐⭐⭐ [4.9/5]
```

**Email 5: Soft Pitch (Day 7)**
```
Subject: Một tuần rồi - bạn thấy sao?
Preview: Quick check-in + special offer...

Hi [Name],

Đã 1 tuần kể từ khi bạn join.
Tôi muốn check-in nhanh...

Bạn đã có cơ hội thử [specific action] chưa?

Nếu chưa, đây là cách bắt đầu đơn giản nhất:
→ [Simple first step]

Nếu rồi, tôi có tin vui:
[Special offer for new subscribers]

[CTA: Claim Offer - Valid 48 hours]

Có câu hỏi? Reply email này!

[Your name]
```

#### Abandoned Cart Sequence (E-commerce)

**Email 1: Reminder (1 hour after)**
```
Subject: Bạn quên gì trong giỏ hàng... 🛒
Preview: [Product name] vẫn đang đợi bạn

Hi [Name],

Có vẻ bạn bận và chưa kịp hoàn tất đơn hàng.

Đây là những gì trong giỏ:
[Product image + name + price]

[CTA: Complete Your Order]

💬 Cần giúp đỡ? Reply email này!

[Your name]
```

**Email 2: Urgency (24 hours)**
```
Subject: Giỏ hàng của bạn sắp hết hạn ⏰
Preview: Giữ lại [Product] trước khi quá muộn

Hi [Name],

Chỉ muốn nhắc bạn:
[Product name] trong giỏ hàng sẽ không được giữ mãi.

Stock có hạn và chúng tôi không muốn bạn bỏ lỡ.

[Product image]
[Original price → Current price]

[CTA: Complete Purchase]

[Your name]
```

**Email 3: Incentive (48 hours)**
```
Subject: Đặc biệt cho bạn: [X]% OFF 🎁
Preview: Exclusive discount để hoàn tất đơn hàng

Hi [Name],

Tôi thấy bạn vẫn chưa checkout...

Đây là một incentive nhỏ:
Use code [CODE] for [X]% OFF

Chỉ valid trong 24 giờ!

[Product image]
[Price with discount]

[CTA: Apply Discount & Checkout]

[Your name]

P.S. Free shipping cho đơn trên [amount]!
[Previous content...]

#### Weekly Newsletter Sequence (The "Curated" Model)

**Email 1: The Weekly Digest**
```
Subject: [Topic] trong tuần: 3 điều bạn không nên bỏ lỡ
Preview: Plus một tips hay ho về [sub-topic]

Hi [Name],

Chào buổi sáng thứ 2! ☕️

Đây là 3 articles/resources hay nhất tôi tìm thấy tuần qua về [Topic]:

1. **[Article Title 1]**
   → Tại sao hay: [1 sentence summary]
   → [Link]

2. **[Article Title 2]**
   → Tại sao hay: [1 sentence summary]
   → [Link]

3. **[Article Title 3]**
   → Tại sao hay: [1 sentence summary]
   → [Link]

💡 **Tip of the week:**
[Quick actionable advice, 2-3 sentences]

Tuần tới tôi sẽ viết sâu hơn về [Upcoming Topic]. Stay tuned!

[Your name]
```

#### Re-engagement Sequence (Dormant subscribers)

**Email 1: We Miss You (30 days inactive)**
```
Subject: Lâu rồi không gặp, [Name]! 👋
Preview: Đây là những gì bạn đã bỏ lỡ...

Hi [Name],

Nhận ra bạn chưa mở email gần đây.
Mọi thứ ổn chứ?

Đây là những updates bạn có thể đã bỏ lỡ:
• [Update 1]
• [Update 2]
• [Update 3]

Muốn tiếp tục nhận updates từ chúng tôi?
[CTA: Yes, Keep Me Updated]

Nếu không phù hợp nữa, no hard feelings.
[Link: Unsubscribe]

[Your name]
```

**Email 2: Win-back Offer (45 days)**
```
Subject: Một món quà cho bạn 🎁
Preview: Because we miss you...

Hi [Name],

Chúng tôi nhớ bạn và muốn tặng:
[Special offer - discount/free trial/bonus]

Offer này chỉ dành cho bạn.
Valid trong 72 giờ.

[CTA: Claim Your Gift]

Hope to see you back!
[Your name]
```

**Email 3: Last Chance (60 days)**
```
Subject: Đây là email cuối cùng... 😢
Preview: Chúng tôi sẽ dọn dẹp list

Hi [Name],

Đây là email cuối cùng trước khi chúng tôi 
remove bạn khỏi list.

Nếu bạn vẫn muốn nhận emails:
[CTA: Keep Me Subscribed]

Nếu không click, chúng tôi sẽ tự động 
unsubscribe bạn trong 7 ngày.

No hard feelings - chúng tôi chỉ muốn 
gửi email cho những ai thực sự muốn nhận.

[Your name]
```

### Phase 3: Subject Line Formulas

#### High-Converting Templates
```
Questions:
- "Bạn có đang mắc [common mistake]?"
- "[Name], bạn đã thử [action] chưa?"

Numbers:
- "[X] cách để [achieve result]"
- "Cách tôi [achieved X] trong [Y] ngày"

Urgency:
- "Chỉ còn [X] giờ: [offer]"
- "Cuối cùng: [limited offer]"

Curiosity:
- "Điều này đã thay đổi [topic] của tôi..."
- "Bí mật mà [industry] không muốn bạn biết"

Personal:
- "[Name], một câu hỏi nhanh"
- "Tôi cần ý kiến của bạn, [Name]"
```

#### A/B Testing Priority
1. Subject line (highest impact)
2. Send time
3. CTA button text/color
4. Email length
5. Personalization level

### Phase 4: Deliverability Best Practices

#### Technical Setup Checklist
- [ ] SPF record configured
- [ ] DKIM authentication set up
- [ ] DMARC policy implemented
- [ ] custom tracking domain
- [ ] Dedicated IP (if >100k emails/month)

#### List Hygiene
```
Monthly:
- Remove hard bounces
- Suppress spam complaints
- Flag inactive (90+ days no open)

Quarterly:
- Re-engagement campaign for inactives
- Remove unengaged after re-engagement fails
- Audit and merge duplicate contacts
```

#### Sending Best Practices
- Warm up new IPs/domains gradually
- Maintain consistent sending volume
- Avoid spam trigger words
- Text-to-image ratio: 60:40 or higher
- Always include unsubscribe link
- Use double opt-in when possible

### Phase 5: Output

1. **Email Sequence Package**
   - Welcome series (5 emails)
   - Post-purchase series (3 emails)
   - Re-engagement series (3 emails)

2. **Template Library**
   - 20+ subject line formulas
   - 10+ email body templates
   - 5+ CTA variations

3. **Automation Flowchart**
   - Trigger definitions
   - Branch logic
   - Timing recommendations

4. **Performance Dashboard**
   - KPI tracking template
   - Benchmark comparisons
   - Optimization checklist

## Email KPI Benchmarks

| Metric | Poor | Average | Good | Excellent |
|--------|------|---------|------|-----------|
| Open Rate | <15% | 15-25% | 25-35% | 35%+ |
| Click Rate | <1% | 1-3% | 3-5% | 5%+ |
| CTR (Click-to-Open) | <5% | 5-10% | 10-15% | 15%+ |
| Unsubscribe | >1% | 0.5-1% | 0.2-0.5% | <0.2% |
| Bounce Rate | >5% | 2-5% | 0.5-2% | <0.5% |

## Ví dụ sử dụng

```
User: /email-automate
Business: SaaS - Project Management Tool
Goal: Improve trial-to-paid conversion
Audience: Marketing teams, 10-50 employees
Current list: 5,000 subscribers
ESP: ConvertKit
```

## Related Workflows
- `/lead-generate` - Capture emails với lead magnets
- `/content-create` - Content cho newsletters
- `/marketing-campaign` - Overall campaign strategy
