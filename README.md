# TradingwithAJay

Website hành trình trading cá nhân — giao diện đen trắng, tĩnh, sẵn sàng deploy lên GitHub Pages hoặc Cloudflare Pages.

## Cấu trúc thư mục

```
tradingwithajay/
├── index.html          # Trang chủ
├── sentiment.html      # Market Sentiment (Liquidation + Social + Events)
├── knowledge.html      # Kiến thức & Tâm lý
├── about.html          # Về mình
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## Cách đưa lên GitHub Pages (khuyến nghị)

1. Tạo tài khoản GitHub (nếu chưa có)
2. Tạo repository mới, đặt tên ví dụ: `tradingwithajay` (để public)
3. Upload toàn bộ nội dung trong thư mục này lên repository
4. Vào **Settings → Pages**
5. Source: chọn nhánh `main`, folder `/ (root)`
6. Save → đợi 1-2 phút
7. Website sẽ có dạng: `https://username.github.io/tradingwithajay`

## Cách đưa lên Cloudflare Pages

1. Đăng nhập Cloudflare → Workers & Pages → Create → Pages
2. Kết nối GitHub repo hoặc upload trực tiếp thư mục
3. Build settings: không cần build command (vì là static HTML)
4. Deploy

## Chỉnh sửa nội dung

- Mở các file `.html` bằng VS Code hoặc bất kỳ trình soạn thảo nào
- Thay các chỗ có dấu `—` bằng số liệu và nhận định thật
- Sau khi sửa, commit + push lên GitHub là website tự cập nhật

## Ghi chú

- Website hoàn toàn tĩnh, không cần database hay backend ở giai đoạn này
- Có thể thêm bài viết mới bằng cách tạo thêm file HTML hoặc mở rộng sau
- Phù hợp để phát triển dần lên membership trong tương lai
