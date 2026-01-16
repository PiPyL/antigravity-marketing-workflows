# 📣 Marketing Workflows

Bộ **6 marketing workflows** cho **Antigravity IDE**, giúp tự động hóa quy trình marketing.

## ⚡ Quick Start

```bash
# Cài đặt marketing workflows vào project
npx @pipyl/antigravity-marketing-workflows init
```

Sau khi cài đặt, sử dụng các slash commands trong Antigravity IDE:

```bash
/marketing-campaign  # Lập kế hoạch campaign
/content-create      # Tạo content marketing
/ads-optimize        # Tối ưu hóa quảng cáo
/lead-generate       # Thu hút leads
/seo-audit           # SEO audit
/social-engage       # Social media engagement
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

## 📁 Cấu Trúc Sau Khi Cài Đặt

```
your-project/
└── .agent/
    └── workflows/
        ├── ads-optimize.md
        ├── content-create.md
        ├── lead-generate.md
        ├── marketing-campaign.md
        ├── seo-audit.md
        └── social-engage.md
```

## 🔗 Related Packages

- [@pipyl/antigravity-workflows](https://www.npmjs.com/package/@pipyl/antigravity-workflows) - Bộ workflows cho phát triển phần mềm

## 📄 License

MIT License

---

**Happy Marketing! 📣**
