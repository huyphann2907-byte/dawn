# Decisions Log & Core Principles — Ashworn

**Mục đích file này:** ghi lại toàn bộ quá trình ideation — ý tưởng nào đã cân nhắc, vì sao loại bỏ — để không lặp lại phân tích cũ nếu sau này muốn quay lại 1 hướng đã bỏ, và để bất kỳ ai (hoặc Claude ở phiên sau) hiểu logic đằng sau quyết định cuối cùng.

---

## Cập nhật gần nhất (04/07/2026)

- **Quyết định: không dùng chất liệu/wash làm lý do mua hàng chính.** Giữ nguyên blank `RB0003-C001-V3` làm quyết định **final** — không pivot sang mã wash-sẵn khác (từng cân nhắc mã `RU0092` ở 1 phiên trước đó, nhưng đã loại hẳn — không cần thiết nữa vì không làm wash riêng).
- Lý do mua hàng cụ thể sẽ được xây dựng qua **1 câu chuyện brand riêng** (chưa chốt nội dung) — không dựa vào chất liệu/wash. `03-brand-voice-and-content.md` (phần Problem/Guide trong StoryBrand) **tạm giữ nguyên bản cũ**, sẽ cập nhật khi câu chuyện được chốt.
- Silhouette oversized/boxy có dữ liệu ban đầu xác nhận qua size chart Tapstitch: size M — chest width 61cm (chu vi ~122cm), shoulder 56cm, length 60cm. Ease so với cơ thể chuẩn ~20-25% (mức oversized rõ rệt), tỷ lệ length/width gần 1:1 (đúng tinh thần "boxy"). **Cần confirm:** ảnh size chart có minh hoạ áo tay ngắn (tee) — phải xác nhận đây đúng là chart của tank top `RB0003-C001-V3`, không bị nhầm sản phẩm, trước khi coi là final.
- Trọng tâm hiện tại chuyển hẳn sang vận hành: chốt sản phẩm → kết nối Tapstitch–Shopify → upload sản phẩm → code theme/settings → Facebook Ads → email marketing hướng storytelling.

## Câu chuyện brand & nguồn gốc — đã chốt (04/07/2026, tiếp tục cùng ngày)

- **Câu chuyện brand: "The Uniform Philosophy".** Brainstorm theo khung SONCAS + Maslow's Hierarchy (nguồn: content-creative-strategy framework), ra 3 hướng — Founder's Frustration (sizing/shipping), The Uniform Philosophy (decision fatigue), Quiet Proof (không logo). Đã chọn **The Uniform Philosophy**: khách hàng mệt vì phải quyết định mặc gì mỗi sáng; Ashworn bán "ít món đúng" thay vì "nhiều lựa chọn". StoryBrand SB7 đầy đủ (Character/Problem/Guide/Plan/CTA/Failure/Success) đã viết ở `03-brand-voice-and-content.md`. Toàn bộ email angles, content pillar chính, và các chỗ `[Cần chốt]` ở file `02` và `03` đã được điền theo hướng này.
- **Nguồn gốc brand: ẩn.** Quyết định kể Ashworn như 1 brand US thuần, không nhắc việc vận hành/sản xuất từ Việt Nam trong content/copy/ads công khai. Hệ quả cho production: ưu tiên creator phương Tây cho UGC/testimonial, native English review mọi script, AI avatar chỉ dùng test volume (không dùng cho asset hero/cảm xúc). Chi tiết đầy đủ ở `03-brand-voice-and-content.md` phần "Nguồn gốc brand & nguyên tắc production".

---

## Hành trình ý tưởng

| # | Ý tưởng | Kết quả | Lý do chính |
|---|---|---|---|
| 1 | Desk mat (thuần trang trí) | ❌ Loại | Không giải quyết vấn đề cụ thể nào — thuần aesthetic/identity purchase, khó justify giá cao cho cold traffic chưa có trust với brand |
| 2 | Desk mat + sạc không dây | ⏸️ Không theo | Giải quyết được vấn đề "lý do trả giá cao" (có bằng chứng: brand JOURNEY bán $120-170), nhưng phức tạp hơn (không còn POD thuần, cần supplier điện tử, rủi ro compliance) — không hợp bối cảnh portfolio đơn giản |
| 3 | Quần áo occasion (dự tiệc/sự kiện) | ❌ Loại | Return rate ngành thời trang 20-40%, sizing phức tạp, và đặc thù "occasion" tạo áp lực thời gian giao hàng mà dropship khó đáp ứng |
| 4 | Costume Halloween | ❌ Loại | Y hệt vấn đề #3 nhưng nặng hơn — chỉ có 1 ngày cố định (31/10) cho tất cả khách, giao trễ = mất giá trị hoàn toàn |
| 5 | Halloween decor tối giản/gothic ("Gothmas") | ⏸️ Không theo | Là lựa chọn tốt thật (né được vấn đề sizing, có bằng chứng thị trường tốt, mùa bán kéo dài nhờ trend bắc cầu sang Giáng sinh) — nhưng user chuyển hướng sang tank top trước khi triển khai |
| 6 | Tank top với logo nhỏ ngay ngực | ❌ Loại | Cấp 1 (áo — cạnh tranh cực cao theo playbook). Giá trị phụ thuộc vào việc logo được nhận diện — brand mới không có sẵn điều đó. Lệch kênh: brand dựa vào logo thường cần build organic/community trước, không hợp cold Meta Ads |
| 7 | **Boxy tank top (silhouette-driven, không dựa logo)** | ✅ **Chốt** | Vẫn là Cấp 1 về mặt danh mục, nhưng giá trị đến từ silhouette (khó clone hơn logo), có bằng chứng supplier thật (Printify, Tapstitch), phù hợp cold ads vì visual đủ ấn tượng để dừng scroll |
| 8 | Wash/dye riêng làm differentiator chính | ❌ Loại (sau khi đã chốt sản phẩm) | Tapstitch xác nhận `RB0003-C001-V3` không hỗ trợ wash/dye riêng. Từng cân nhắc pivot sang mã `RU0092` (có wash sẵn) để giữ hướng này, nhưng sau đó quyết định không cần — không muốn dựa vào chất liệu/wash làm lý do mua hàng nữa |

---

## Quyết định naming & production (sau khi chốt sản phẩm)

| Hạng mục | Quyết định | Ghi chú |
|---|---|---|
| Tên brand | **Ashworn** | Đã check nhanh — không đụng brand thời trang nào đang hoạt động. Handle `@ashworn` trên IG/X đã có người dùng cá nhân (không liên quan) → dùng biến thể như `wearashworn`/`ashworn.co` cho social/domain |
| Chữ in trên sản phẩm | Wordmark **tên brand**, không phải khẩu hiệu | Lý do: khẩu hiệu không tích luỹ nhận diện qua nhiều đợt drop, còn tên thì có. Đúng quy ước các brand quiet-luxury tham chiếu (Essentials, Fear of God) — không ai dùng khẩu hiệu trên sản phẩm chính |
| Vị trí chữ | Giữa ngực, nhỏ (2-3 inch), màu tonal/gần-tonal | Ban đầu định để ở sườn/gấu sau, nhưng giữa ngực vẫn ổn NẾU giữ nhỏ/tonal — vấn đề cốt lõi là kích thước/độ nổi bật, không phải vị trí |
| Supplier blank | Tapstitch, mã `RB0003-C001-V3` — French Terry 340gsm, 87% cotton/13% polyester, gấu Frayed sẵn | **Final — không pivot sang mã khác.** Silhouette oversized/boxy đã có dữ liệu bước đầu xác nhận qua size chart (cần confirm nguồn ảnh đúng sản phẩm). Wash/dye riêng bị loại khỏi kế hoạch — không còn là blocker. Còn thiếu giá/MOQ chính thức |
| Kỹ thuật in | DTG nếu chữ tonal, DTF nếu chữ sáng màu hơn nền | Quyết định dựa theo tương quan màu chữ vs màu nền thực tế của từng colorway, không cố định 1 kỹ thuật cho tất cả |

---

## Nguyên tắc đã chốt — áp dụng xuyên suốt project

### Về chọn sản phẩm
- **Thứ tự đúng: Channel → Audience → Product**, không phải ngược lại
- Mỗi store chỉ 1 Acquisition Product — phải trả lời được upsell/cross-sell/downsell trước khi chốt
- Cấp 2 (ít phổ biến, có thị trường sẵn, chưa ai làm brand hẳn) tốt hơn Cấp 1 (áo/canvas/cốc phổ thông — tránh nếu có thể) cho người mới
- Sản phẩm tốt cần: ấn tượng ngay lần đầu nhìn, giải quyết vấn đề cụ thể HOẶC giá trị rõ ràng, có bằng chứng thị trường (Google Trends/Amazon), market size đủ lớn, có khả năng tăng AOV/LTV

### Về differentiation
- Sản phẩm blank/công khai trên Printify **không tự nó tạo lợi thế** — ai cũng access được y hệt
- Lợi thế thật đến từ: tỷ lệ silhouette cố định, chi tiết construction, câu chuyện brand, hoặc **thực thi đều đặn mà người mới thường không làm** (viết email/content mỗi ngày — "lợi thế thứ 4 cho newbie")
- Đừng dựa vào logo để tạo giá trị nếu brand chưa có nhận diện — logo chỉ có giá trị khi đã được công nhận
- **Không ép chất liệu/wash làm lý do mua hàng nếu supplier không hỗ trợ và bản thân không ưu tiên hướng đó** — lý do mua hàng có thể (và nên) đến từ câu chuyện brand, xây dựng riêng, không nhất thiết gắn với 1 đặc điểm vật lý của sản phẩm

### Về kênh & content
- **Product/visual hook** giải quyết "vì sao dừng lại khi lướt cold ads" — **Brand story** giải quyết "vì sao tin tưởng và quay lại". Hai vấn đề khác nhau, đừng dùng cái này thay cái kia
- Organic cần 8+ tuần đăng đều mới thấy kết quả — không phải giải pháp nhanh
- StoryBrand SB7: khách hàng luôn là hero, brand là guide — không kể "chúng tôi làm gì", kể "bạn sẽ trở thành/cảm thấy ra sao"

### Về pricing
- GPM mục tiêu ≥ 60%, dưới 50% là nguy hiểm
- Giá bán = Base cost / (1 − GPM target − Payment fee%)
- Bán đắt hơn (trong giới hạn hợp lý) luôn tốt hơn cho ecom hiện đại — tạo room cho upsell/promotion

### Về bối cảnh portfolio (riêng cho project này)
- Mục tiêu là luyện vận hành + có sản phẩm show trong portfolio, không nhất thiết cần lãi thật
- Vì vậy: ưu tiên độ hoàn thiện branding/store/flow hơn là tối ưu lợi nhuận tuyệt đối
- Không cần chạy ads thật để tránh tốn ngân sách không cần thiết — có thể làm mockup ads thay thế nếu muốn luyện phần creative
- Nhưng vẫn nên chọn sản phẩm/ngách "thực tế đủ" để bài học vận hành có giá trị thật (tránh chọn ngách quá rủi ro như apparel sizing phức tạp chỉ vì "không cần lãi")

---

## Rủi ro còn mở với hướng đã chọn (boxy tank top) — cần theo dõi

1. Aesthetic khá sát với ngôn ngữ thiết kế Rick Owens — cần giữ khoảng cách đủ để không trông như "dupe", đặc biệt trong content/copy công khai (không nhắc tên brand đó)
2. Vẫn là category apparel — return rate do sizing vẫn là rủi ro thật, cần size chart rõ ràng ngay từ đầu
3. Blank Tapstitch (`RB0003-C001-V3`) — đã xác nhận không hỗ trợ wash/dye riêng (không còn là vấn đề vì đã bỏ hướng này); silhouette oversized đã có dữ liệu ban đầu qua size chart, cần confirm nguồn ảnh đúng sản phẩm trước khi coi final; còn thiếu giá/MOQ chính thức từ Tapstitch để lên đơn thật — xem chi tiết ở `01-brand-strategy-and-product.md`
4. Lý do mua hàng cụ thể chưa chốt — cần xây dựng câu chuyện brand trước khi viết copy bán hàng/email flow chi tiết, nếu không sản phẩm sẽ thiếu 1 "hook" rõ ràng ngoài yếu tố hình ảnh
