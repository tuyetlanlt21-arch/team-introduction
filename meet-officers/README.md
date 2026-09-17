# Meet The Team · Dự án Gây quỹ

Interactive locker wall → scrapbook profile.

## Changes in this version
- Font: Be Vietnam Pro + Fredoka + JetBrains Mono (hỗ trợ tiếng Việt đầy đủ)
- Bỏ Weaknesses & Fun fact
- Thêm **Slogan** cho mỗi thành viên
- Highlight rõ **Vị trí trong team** (role badge)
- Data members từ form dự án gây quỹ

## Run
```bash
cd meet-officers
python3 -m http.server 8080
# http://localhost:8080
```

## Edit members
Mở `index.html`, sửa mảng `members`:
- `name`, `username`, `role`
- `strengths[]`
- `note` — ghi chú sticky
- `slogan` — slogan cá nhân
- `photo` — `"assets/xxx.jpg"` hoặc `null`
