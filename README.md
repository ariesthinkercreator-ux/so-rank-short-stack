# Sổ Range Short-Stack

Web app xây và luyện range poker preflop cho bàn 4–7 người, stack 25–50bb.

## Tính năng
- **Tô range** trên bảng 13×13: Raise, Limp, Call, 3-bet, 4-bet, All-in, tần suất 100/75/50/25%
- **Dán range** từ solver hoặc chart (`AKs:0.5`, `[50]AKs[/50]`, `77+, A5s+`…)
- **So với solver**: chart 6-max 40bb (RangeConverter, rake 500z) có sẵn, hiển thị độ khớp và các ô lệch
- **Tính equity** kiểu Equilab: cả bảng hoặc từng tay, ngưỡng pot odds, EV all-in, board tuỳ chọn
- **Luyện tập**: chấm theo range của bạn hoặc theo solver
- **Sao lưu**: copy/nhập toàn bộ range

## Chạy
Một file `index.html` duy nhất, không cần build. Mở trực tiếp bằng trình duyệt hoặc deploy dạng static site (Vercel, GitHub Pages).

Range người dùng được lưu trong `localStorage` của trình duyệt.
