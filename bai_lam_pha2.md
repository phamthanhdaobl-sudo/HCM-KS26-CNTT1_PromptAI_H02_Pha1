# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 05
- **Họ tên:**Phạm Thành Đạo
- **Lớp:**HCM-KS26-CNTT1
- **Link repository Pha2:**https://github.com/phamthanhdaobl-sudo/HCM-KS26-CNTT1_PromptAI_H02_Pha1.git- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**Gemini

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xem phim ra JSON

**KET QUA AI**

```text
[
  {
    "loai_ve": "P2D",
    "ngay_chieu": "2026-12-24",
    "ve_nguoi_lon": 2,
    "ve_tre_em": 1,
    "loai_ghe": "thuong",
    "ghi_chu": null
  },
  {
    "loai_ve": "P3D",
    "ngay_chieu": "2027-01-01",
    "ve_nguoi_lon": 3,
    "ve_tre_em": 0,
    "loai_ghe": null,
    "ghi_chu": "Một người hay chóng mặt, cần ngồi gần lối ra"
  },
  {
    "loai_ve": "GOLD",
    "ngay_chieu": null,
    "ve_nguoi_lon": 4,
    "ve_tre_em": 0,
    "loai_ghe": "doi",
    "ghi_chu": "một bạn đi xe lăn"
  }
]
```

**Link trò chuyện:**https://share.gemini.google/4qZo6wzbzsmP
## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền vé người lớn:
Số lượng: 5 người lớn
Đơn giá vé P3D: 130.000 đồng/vé
Phép tính: 
5
×
130.000
=
650.000
 đ
o
ˆ
ˋ
ng
5×130.000=650.000 đ 
o
ˆ
 
ˋ
 ng
Tiền vé trẻ em:
2 trẻ em cao 1,1 m và 1,25 m (nằm trong khoảng từ 1 m đến 1,3 m) tính 70% giá vé người lớn: 
2
×
(
130.000
×
70
%
)
=
2
×
91.000
=
182.000
 đ
o
ˆ
ˋ
ng
2×(130.000×70%)=2×91.000=182.000 đ 
o
ˆ
 
ˋ
 ng
1 bé cao 0,9 m (dưới 1 m) ngồi cùng người lớn được miễn phí: 
1
×
0
=
0
 đ
o
ˆ
ˋ
ng
1×0=0 đ 
o
ˆ
 
ˋ
 ng
Phép tính tổng tiền vé trẻ em: 
182.000
+
0
=
182.000
 đ
o
ˆ
ˋ
ng
182.000+0=182.000 đ 
o
ˆ
 
ˋ
 ng
Tiền vé (trước giảm giá):
Phép tính: 
650.000
+
182.000
=
832.000
 đ
o
ˆ
ˋ
ng
650.000+182.000=832.000 đ 
o
ˆ
 
ˋ
 ng
Giảm giá nhóm:
Nhóm có 5 người lớn (đủ điều kiện từ 5 người lớn trở lên) nên được giảm 10% trên tiền vé.
Số tiền được giảm: 
832.000
×
10
%
=
83.200
 đ
o
ˆ
ˋ
ng
832.000×10%=83.200 đ 
o
ˆ
 
ˋ
 ng
Tiền vé sau giảm: 
832.000
−
83.200
=
748.800
 đ
o
ˆ
ˋ
ng
832.000−83.200=748.800 đ 
o
ˆ
 
ˋ
 ng
Tiền combo:
Số lượng: 3 combo bắp nước (không áp dụng giảm giá)
Đơn giá: 75.000 đồng/combo
Phép tính: 
3
×
75.000
=
225.000
 đ
o
ˆ
ˋ
ng
3×75.000=225.000 đ 
o
ˆ
 
ˋ
 ng
Tổng tiền:
Phép tính: 
748.800
+
225.000
=
973.800
 đ
o
ˆ
ˋ
ng
748.800+225.000=973.800 đ 
o
ˆ
 
ˋ
 ng
[RESULT: 973.800 đồng]
```

**Link trò chuyện:**https://share.gemini.google/qtjJ2ovaUhVZ

### b) Kiểm tra kết quả AI

Kết quả đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{"loai_su_co": "loi_ky_thuat", "so_khach": 4, "so_suat_bi_loi": 2, "tom_tat": "Gia đình 4 người xem 2 suất phòng 3 tối 02/11/2026 đều bị mất tiếng hơn 15 phút."}
```

**Link trò chuyện:**https://share.gemini.google/K2RUAZBHo4yV

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
