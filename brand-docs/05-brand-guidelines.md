# Brand Guidelines — Ashworn

**Mục đích file này:** consolidate các quyết định visual/design thành 1 nơi để dùng khi code theme, thiết kế ads, chụp sản phẩm. Tone of voice và câu chuyện brand đầy đủ vẫn ở `03-brand-voice-and-content.md` — file này chỉ tập trung phần **visual**.

**Nguyên tắc chọn:** mọi lựa chọn dưới đây bám theo định vị đã chốt — "quiet luxury/elevated basics", tối giản, không phô trương, tham chiếu Essentials/Fear of God — không phải màu/font mặc định chung chung.

---

## 🎨 Color Palette

| Tên | Hex | Vai trò |
|---|---|---|
| **Ink** | `#171614` | Neutral tối chính — text, wordmark trên nền sáng, nền cho colorway tối |
| **Bone** | `#EDE7DA` | Neutral sáng chính — background chính của site, wordmark trên nền tối |
| **Stone** | `#A8A196` | Neutral trung — text phụ, border/hairline, UI elements mờ |
| **Moss** | `#565645` | Accent mùa 1 — dùng cho tag "drop mới", nút CTA hover, hoặc màu áo signature 1 mùa |
| **Rust** | `#7A4632` | Accent mùa 2 — luân phiên với Moss, không dùng cùng lúc |

**Nguyên tắc dùng:** Ink/Bone/Stone là bộ 3 cố định, dùng cho toàn bộ UI (site, email). Moss/Rust chỉ dùng cho **màu sản phẩm/tag theo mùa** — mỗi thời điểm chỉ chọn 1 accent, không dùng cả 2 cùng lúc (đúng nguyên tắc "color story giới hạn 3-4 tone" đã chốt ở file `01`). Không thêm accent thứ 3 nếu chưa retire 1 trong 2 cái này.

---

## 🔤 Typography

**Typeface:** [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts, free, variable weight) — dùng 1 family duy nhất cho toàn bộ site, phân biệt bằng weight/case/tracking. Lý do chọn: grotesque sans trung tính, không có cá tính thừa — đúng tinh thần "để chất lượng tự nói" thay vì để font "nói hộ".

| Vai trò | Weight | Case | Tracking | Size (desktop) |
|---|---|---|---|---|
| H1 (hero) | Semibold 600 | UPPERCASE | +5% | 48-56px |
| H2 (section) | Semibold 600 | UPPERCASE | +4% | 32px |
| H3 (card/product name) | Medium 500 | Sentence case | 0 | 20-22px |
| Body | Regular 400 | Sentence case | 0 | 16px, line-height 1.55 |
| Caption/label/size chart | Medium 500 | UPPERCASE | +6% | 12-13px |

Mobile: giữ tỷ lệ, giảm ~30% (H1 ~34px, body giữ nguyên 16px để đảm bảo đọc được).

---

## 🏷️ Wordmark & Logo Usage

*(Chi tiết spec kích thước/in ấn trên sản phẩm đã có ở `01-brand-strategy-and-product.md` — mục dưới đây là quy tắc dùng wordmark trên digital/UI)*

- Wordmark = chữ "ASHWORN", set bằng Inter Semibold, uppercase, tracking +8%. Không dùng icon/symbol riêng — chỉ có wordmark, không cần logomark.
- **Trên sản phẩm (in ngực):** tonal — cùng value/gần-value với màu áo, gần như chìm vào vải.
- **Trên digital (site header, email header, social profile):** full-contrast — Ink trên Bone hoặc Bone trên Ink, tuỳ nền — vì digital cần dễ đọc/nhận diện, không cần hiệu ứng "quiet" như trên vải.
- Khoảng trống tối thiểu quanh wordmark: tối thiểu bằng chiều cao chữ "A" ở mọi phía.
- Không kéo giãn, không thêm hiệu ứng (shadow, gradient, outline) lên wordmark trong bất kỳ trường hợp nào.

---

## 📷 Photography & Imagery Style

- **Background:** phông neutral (studio grey/bone) hoặc ánh sáng tự nhiên ngoài trời — không dùng background nhiều chi tiết/màu sắc gây rối
- **Lighting:** ánh sáng mềm/tự nhiên, tránh shadow gắt
- **Color grading:** giảm sáturation nhẹ, tông ấm-trung tính khớp bảng màu Bone/Stone — không dùng filter/preset đậm
- **Styling người mẫu:** thoải mái, biểu cảm trung tính, không quá "posed" — khớp tinh thần "effortless" của câu chuyện Uniform Philosophy
- **Luôn có 1 ảnh cận cảnh chất liệu/construction** trong mỗi bộ ảnh sản phẩm — đây là bằng chứng chất lượng, hỗ trợ trực tiếp phần Guide trong StoryBrand
- **Casting người xuất hiện trong ảnh/video (UGC, lifestyle):** creator phương Tây, theo nguyên tắc production đã chốt ở `03-brand-voice-and-content.md`

---

## 📐 Layout & Spacing (dùng khi code theme)

- Khoảng trắng rộng, tối giản — đừng nhồi nhiều element trên 1 màn hình
- Section padding: ~96px desktop / ~48px mobile (trên-dưới)
- Border/divider: hairline 1px, màu Stone — không dùng box-shadow, không dùng border-radius lớn (giữ 0-4px, cạnh vuông/kiến trúc — khớp tinh thần "structured" của sản phẩm)
- Max content width: ~1200-1280px, margin 2 bên rộng rãi
- Grid-based, căn chỉnh nhất quán — mọi lệch pixel đều dễ bị nhận ra trong định vị minimalist (không có chi tiết trang trí để "che" lỗi layout)

---

## Tham chiếu chéo

- Tone of voice, StoryBrand, content pillar → `03-brand-voice-and-content.md`
- Spec wordmark trên sản phẩm, kỹ thuật in, chất liệu → `01-brand-strategy-and-product.md`
- Nguyên tắc production/casting (ẩn nguồn gốc VN) → `03-brand-voice-and-content.md` mục "Nguồn gốc brand & nguyên tắc production"
