---
description: Hệ thống hóa A/B testing cho marketing
---

# /ab-test - A/B Testing Framework

## Mục đích
Xây dựng quy trình thử nghiệm A/B (Split Testing) khoa học để tối ưu hóa conversion rate. Workflow này giúp loại bỏ "đoán mò" và đưa ra quyết định dựa trên dữ liệu.

## Input cần cung cấp
- Test Object (Landing page, Email subject, Ad copy, CTA button)
- Current Metric (Baseline conversion rate)
- Hypothesis (Giả thuyết)
- Traffic Volume (Để tính thời gian test)

## Workflow

### Phase 1: Hypothesis Generation

#### The PIE Framework (Prioritization)
Đánh giá ý tưởng test dựa trên 3 tiêu chí (thang 1-10):
1. **Potential (Tiềm năng):** Trang này có nhiều room để cải thiện không?
2. **Importance (Quan trọng):** Trang này có nhiều traffic/doanh thu không?
3. **Ease (Dễ dàng):** Test này có dễ triển khai kỹ thuật không?

**Score = (P + I + E) / 3**

#### Hypothesis Template
```
Bởi vì tôi nhận thấy [Data/Feedback/Observation],
Tôi tin rằng việc thay đổi [Element A] thành [Element B]
Sẽ làm tăng [Primary Metric]
Bởi vì [Reasoning/Psychology].
```

**Example:**
"Bởi vì heatmap cho thấy user không cuộn xuống dưới, tôi tin rằng việc đưa CTA lên đầu trang sẽ làm tăng Click Rate, vì user sẽ thấy nó ngay lập tức."

### Phase 2: Test Design

#### Element to Test
- **Headlines:** Impact lớn nhất (thay đổi Value Prop).
- **CTA:** Màu sắc, text ("Buy Now" vs "Get Started"), vị trí.
- **Images:** Hero image (Người vs Sản phẩm).
- **Layout:** Single column vs Multi-column.
- **Form:** Số lượng trường (Short vs Long).

#### Sample Size Calculation
Bạn cần bao nhiêu traffic để kết quả có ý nghĩa thống kê?
*Rule of thumb:* Cần khoảng 1,000 conversions (không phải 1,000 visits) để chắc chắn.

Sử dụng tool: [Optimizely Sample Size Calculator](https://www.optimizely.com/sample-size-calculator/)
- Baseline Conversion Rate: 2%
- Minimum Detectable Effect (MDE): 20% (muốn tăng từ 2% lên 2.4%)
- Statistical Significance: 95%

### Phase 3: Execution Checklist
- [ ] **Đảm bảo tracking:** Cài đặt Goal/Conversion trong GA4 chuẩn xác.
- [ ] **QA Test:** Check trên Mobile, Desktop, các trình duyệt khác nhau.
- [ ] **Split Traffic:** 50/50 randomly.
- [ ] **No Interference:** Không chạy các campaign lớn bất thường trong lúc test.
- [ ] **Duration:** Chạy ít nhất 1-2 tuần (để cover đủ các ngày trong tuần).

### Phase 4: Analysis & Learning

#### Statistical Significance
- **P-value < 0.05:** Kết quả đáng tin cậy (95% confidence).
- Nếu chưa đạt 95% mà traffic đã lớn → Kết luận là "Inconclusive" (Không khác biệt).

#### Test Card Template (Documentation)
```markdown
# Test ID: [WEB-001]
**Date:** [Start] - [End]
**Platform:** [Homepage]

## Hypothesis
Changing the headline from "Software for X" to "Increase Revenue by Y" will improve signups.

## Results
| Variation | Visitors | Conversions | Conv. Rate | Lift | Confidence |
|-----------|----------|-------------|------------|------|------------|
| Control A | 5,000    | 100         | 2.0%       | -    | -          |
| Variant B | 4,950    | 130         | 2.6%       | +30% | 98% (Win)  |

## Conclusion
Variant B chiến thắng áp đảo. Users phản hồi tốt hơn với benefit-driven headline.

## Next Steps
- Triển khai Variant B cho 100% traffic.
- Test tiếp sub-headline để support headline mới.
```

### Phase 5: Output

1. **Test Roadmap** (Danh sách các test được ưu tiên theo PIE).
2. **Hypothesis Document** (Chi tiết cho từng test).
3. **Execution Plan** (Design, Tech setup).
4. **Test Report** (Kết quả và bài học - xem Template trên).

## Common Mistakes to Avoid
1. **Dừng test quá sớm:** Thấy Variant B thắng trong ngày đầu tiên là dừng → Sai lầm (Sample size chưa đủ).
2. **Test quá nhiều thứ cùng lúc:** Thay đổi cả headline, ảnh, nút bấm → Không biết cái nào gây ra kết quả (Nên dùng Multivariate test nếu traffic cực lớn, còn không thì A/B từng cái).
3. **Bỏ qua Mobile:** Chỉ check trên Desktop mà quên Mobile (thường chiếm 70% traffic).

## Ví dụ sử dụng
```
User: /ab-test
Object: Landing page đăng ký khóa học
Metric: Sign-up rate
Current: 1.5%
Hypothesis: Video testimonial sẽ tăng trust hơn là text testimonial.
```

## Related Workflows
- `/analytics-report` - Setup tracking cho test
- `/lead-generate` - Tối ưu landing page
- `/ads-optimize` - A/B test ad creatives
