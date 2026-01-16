# 📣 Marketing Workflows

Bộ **16 marketing workflows** cho **Antigravity IDE**, giúp tự động hóa quy trình marketing.

## ⚡ Quick Start

```bash
# Cài đặt marketing workflows vào project
npx @pipyl/antigravity-marketing-workflows init
```

Sau khi cài đặt, sử dụng các slash commands trong Antigravity IDE:

```bash
# Core Workflows
/marketing-campaign  # Lập kế hoạch campaign
/content-create      # Tạo content marketing
/ads-optimize        # Tối ưu hóa quảng cáo
/lead-generate       # Thu hút leads
/seo-audit           # SEO audit
/social-engage       # Social media engagement

# Tier 1 Workflows ✨
/email-automate      # Email marketing automation
/analytics-report    # Marketing analytics & reporting
/competitor-spy      # Competitor intelligence

# Tier 2 Workflows ✨
/influencer-collab   # Influencer marketing
/brand-identity      # Brand strategy & identity
/retention-nurture   # Customer retention

# Tier 3 Workflows 🚀
/video-launch        # Video strategy (YouTube/TikTok)
/ab-test             # A/B testing framework
/pr-launch           # PR & Media relations
/affiliate-partner   # Affiliate program setup
```

## 📦 Cài Đặt

### Cách 1: Dùng npx (Khuyến nghị)

```bash
cd your-project
npx @pipyl/antigravity-marketing-workflows init
```

### Cách 2: Install global

```bash
npm install -g @pipyl/antigravity-marketing-workflows
marketing-workflows init
```

## 🛠️ Commands

| Command | Mô tả |
|---------|-------|
| `init` | Cài đặt workflows vào `.agent/workflows/` |
| `list` | Xem danh sách workflows có sẵn |
| `update` | Cập nhật workflows (ghi đè tất cả) |
| `remove` | Xóa workflows khỏi project |
| `help` | Hiển thị trợ giúp |

## ⚙️ Options

| Option | Mô tả |
|--------|-------|
| `--force`, `-f` | Ghi đè workflows đã tồn tại |
| `--only=a,b,c` | Chỉ cài đặt các workflows cụ thể |
| `--dir=path` | Thư mục đích (mặc định: thư mục hiện tại) |

### Ví dụ

```bash
# Ghi đè workflows đã tồn tại
npx @pipyl/antigravity-marketing-workflows init --force

# Chỉ cài đặt một số workflows
npx @pipyl/antigravity-marketing-workflows init --only=content-create,seo-audit

# Xem danh sách workflows
npx @pipyl/antigravity-marketing-workflows list
```

## 📋 Danh Sách Workflows

| Command | Mô tả | Khi nào dùng |
|---------|-------|--------------| 
| `/marketing-campaign` | Lập kế hoạch campaign | Khi cần chiến lược marketing tổng thể |
| `/content-create` | Tạo content marketing | Khi cần tạo content cho nhiều platform |
| `/ads-optimize` | Tối ưu Meta/Google Ads | Khi cần tối ưu quảng cáo |
| `/lead-generate` | Thu hút leads | Khi cần tạo lead magnets, email sequences |
| `/seo-audit` | SEO audit toàn diện | Khi cần đánh giá và cải thiện SEO |
| `/social-engage` | Social media engagement | Khi cần tối ưu engagement |
| `/email-automate` | Email marketing automation | Khi cần setup email sequences, automations |
| `/analytics-report` | Marketing analytics | Khi cần báo cáo và phân tích KPIs |
| `/competitor-spy` | Competitor intelligence | Khi cần nghiên cứu và theo dõi đối thủ |
| `/influencer-collab` | Influencer marketing | Khi cần hợp tác với influencers |
| `/brand-identity` | Brand strategy | Khi cần xây dựng nhận diện thương hiệu |
| `/retention-nurture` | Customer retention | Khi cần giữ chân và upsell khách hàng |
| `/video-launch` | Video marketing | Khi cần chiến lược YouTube/TikTok |
| `/ab-test` | A/B Testing | Khi cần test để tối ưu tỷ lệ chuyển đổi |
| `/pr-launch` | Public Relations | Khi cần làm việc với báo chí/media |
| `/affiliate-partner` | Affiliate program | Khi cần xây dựng mạng lưới CTV |

## 📁 Cấu Trúc Sau Khi Cài Đặt

```
your-project/
└── .agent/
    └── workflows/
        ├── ab-test.md             # 🚀 Tier 3
        ├── ads-optimize.md
        ├── affiliate-partner.md   # 🚀 Tier 3
        ├── analytics-report.md    # ✨ Tier 1
        ├── brand-identity.md      # ✨ Tier 2
        ├── competitor-spy.md      # ✨ Tier 1
        ├── content-create.md
        ├── email-automate.md      # ✨ Tier 1
        ├── influencer-collab.md   # ✨ Tier 2
        ├── lead-generate.md
        ├── marketing-campaign.md
        ├── pr-launch.md           # 🚀 Tier 3
        ├── retention-nurture.md   # ✨ Tier 2
        ├── seo-audit.md
        ├── social-engage.md
        └── video-launch.md        # 🚀 Tier 3
```

## 🔗 Related Packages

- [@pipyl/antigravity-workflows](https://www.npmjs.com/package/@pipyl/antigravity-workflows) - Bộ workflows cho phát triển phần mềm

## 📄 License

MIT License

---

**Happy Marketing! 📣**
