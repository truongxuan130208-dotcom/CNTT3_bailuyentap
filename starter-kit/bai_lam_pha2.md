## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "SVT",
    "ngay_su_kien": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "FZ",
    "ngay_su_kien": "2027-01-05",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_ve": null,
    "ghi_chu": "hỗ trợ xe lăn"
  },
  {
    "ma_goi": "VIP",
    "ngay_su_kien": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_ve": "vip",
    "ghi_chu": "hỗ trợ tìm chỗ"
  }
]
```

**Link trò chuyện:*https://share.gemini.google/BNYPqqDQcWbd*

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**
Al tính đúng
```text
Tiền người lớn:
5 × 1.
200.000 = 6.000.000 đồng
Tiền trẻ em:
(2 × 1.
200.000 × 70%) + (1 × 0) = 1.680.000 đồng
Tiền vé:
6.
000.000 + 1.680.000 = 7.680.000 đồng
Giảm giá nhóm:
7.
680.000 × 5% = 384.000 đồng
Phụ thu:
1 × 300.
000 = 300.000 đồng
Tổng tiền:
(7.
680.000 - 384.000) + 300.000 = 7.596.000 đồng
```

**Link trò chuyện:*https://share.gemini.google/OCxz9gpsFxdO*

### b) Kiểm tra kết quả AI

Al tính đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_hiep_bi_anh_huong": 2,
  "tom_tat": "Khán giả bị xếp nhầm sang khu không mái che trong 2 hiệp đầu."
}
```

**Link trò chuyện:*https://share.gemini.google/oBHHN3U9qGcL*
