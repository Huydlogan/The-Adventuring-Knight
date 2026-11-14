# ⚔️ Hiệp Sĩ Phiêu Lưu

Game hành động đi cảnh 2D pixel art chạy hoàn toàn trên trình duyệt. Bạn vào vai hiệp sĩ của vương quốc **Lumeria**, vượt qua 6 vùng đất, chiêu mộ đồng đội và đánh bại **Quỷ Vương Malgor** — hoặc thử sức ở chế độ **Chiến Đấu Vô Tận**.

Game không cần cài đặt hay máy chủ: toàn bộ nằm trong **một file `index.html`**, hình ảnh đã được nhúng sẵn bên trong.

---

## 🎮 Cách chơi

- **Chơi ngay:** mở file `index.html` bằng Chrome, Edge, Firefox hoặc Safari.
- **Đưa lên GitHub Pages:**
  1. Tải file `index.html` (và `README.md`) lên repository.
  2. Vào **Settings › Pages**, chọn nhánh `main`, thư mục `/ (root)`.
  3. Sau khoảng 1 phút, game có mặt tại `https://<tên-tài-khoản>.github.io/<tên-repo>/`.
- **Tiến trình được lưu tự động** trong trình duyệt (localStorage): vàng, màn đã mở, nâng cấp, nhiệm vụ, nhân vật.

---

## 📖 Cốt truyện

Pháp Sư Bóng Tối đánh cắp **Ấn Phong Long** — báu vật phong ấn **Hỏa Long Ignarok** — rồi bẻ thành 4 mảnh, chia cho bốn kẻ phản loạn. Vua Aldric giao cho hiệp sĩ trẻ **Aren** sứ mệnh thu hồi các mảnh Ấn trước khi Hỏa Long thức tỉnh.

Khi Hỏa Long đã bị phong ấn, kẻ chủ mưu thật sự lộ diện: **Quỷ Vương Malgor**, người đã điều khiển Pháp Sư Bóng Tối từ đầu. Aren cùng các đồng đội tiến vào Lâu Đài Quỷ Vương để kết thúc mọi chuyện.

---

## 🗺️ Thế giới

6 vùng đất × 3 màn = **18 màn**. Mỗi màn có 2 điểm lưu và 3 viên ngọc ◆ ẩn. Màn giữa mỗi vùng có **quái tinh anh**, màn cuối có **trùm**.

| Vùng | Quái tinh anh | Trùm |
|---|---|---|
| I · Làng Biên Giới | Phù Thủy Băng Cướp | Thủ Lĩnh Băng Cướp |
| II · Hẻm Núi Đá Đỏ | Vua Thằn Lằn | Đội Trưởng Lính Đánh Thuê |
| III · Pháo Đài Đế Chế | Thủ Lĩnh Hắc Kỵ Sĩ | Tướng Quân Đế Chế |
| IV · Rừng Ma Ám | Ma Sói Đầu Đàn | Pháp Sư Bóng Tối |
| V · Núi Lửa Rồng | Chúa Quỷ Dung Nham | Hỏa Long Ignarok |
| VI · Lâu Đài Quỷ Vương | Thần Chết Tối Thượng | Quỷ Vương Malgor |

Địa hình có thang, dây đu, sàn di động, thùng gỗ đẩy được, tường thành và bẫy. Dọc đường có **hòm đồ** chứa bình thuốc, túi vàng hoặc thuốc nổ — đứng cạnh hòm (hoặc người bị trói) và **giữ F / nút 💬 trong 0,5 giây** để mở hay giải cứu; thả tay hoặc bị đánh trúng thì phải làm lại. Từ vùng IV xuất hiện **hòm bẫy**: quái vật chui ra, hạ nó để nhận thưởng gấp đôi.

---

## 🛡️ Nhân vật

Mỗi nhân vật có **nội tại** và bộ kỹ năng riêng. Aren và Aria dùng miễn phí. 5 chiến binh còn lại được mở khóa qua nhiệm vụ chiêu mộ, sau đó mua ở **Cửa hàng › ⚔ Chiến binh**.

| Nhân vật | Mở khóa | Giá | Nội tại |
|---|---|---|---|
| **Hiệp sĩ Aren** | Có sẵn | — | *Kiên Cường*: chặn đòn thành công hồi 3% HP; dưới 30% HP nhận ít hơn 25% sát thương |
| **Nữ hiệp sĩ Aria** | Có sẵn | — | *Thân Pháp*: chạy nhanh hơn 10%, hồi lướt nhanh hơn 33% |
| **Cung thủ Sylva** | Giải cứu Sylva (Lyra · màn 2-2) | 800 | *Mắt Ưng*: tên trúng mục tiêu xa hơn 6 ô thành chí mạng (+60%) |
| **Kiếm khách Kaito** | Đấu tay đôi (Hagen · màn 3-1) | 1000 | *Ám Sát*: đánh sau lưng +50%, 20% chí mạng, nhảy 3 lần |
| **Pháp sư Ignis** | Thu hồi 3 Trang Hỏa Thư (Elda · vùng IV) | 1200 | *Thiền Định*: đứng yên hồi MP, MP tối đa 140 |
| **Đấu sĩ Bjorn** | Đấu tay đôi (Gorm · màn 5-2) | 1400 | *Cuồng Chiến*: HP càng thấp càng mạnh (tới +50%), không bị đẩy lùi khi vung rìu |
| **Kị sĩ hắc ám Mordred** | Phá lời nguyền (Roland · màn 6-1) | 1800 | *Huyết Khế*: kỹ năng tốn máu thay MP, hút máu khi đánh, hạ địch hồi HP |

### Bộ kỹ năng

Tuyệt kỹ R cần đầy MP và có thời gian hồi chiêu (tính từ lúc kích hoạt): Aren/Aria 45 giây, Sylva/Kaito 42 giây, Ignis/Bjorn 50 giây, Mordred 55 giây.


| Nhân vật | Đánh thường | Q | E | R (đầy MP, có hồi chiêu) | Chặn |
|---|---|---|---|---|---|
| Aren / Aria | Liên hoàn kiếm 3 đòn | Lốc Xoáy | Kiếm Khí | Cường Hóa | Chặn khiên |
| Sylva | Bắn tên | Mưa Tên | Tên Xuyên Phá | Ưng Nhãn (3 tên đuổi) | Nhảy Lùi |
| Kaito | Tam liên trảm | Ảnh Bộ | Phi Tiêu Độc | Thiên Kiếm Loạn Vũ | Phản Đòn |
| Ignis | Cầu Lửa | Hỏa Trụ | Thiên Thạch | Hỏa Thần | Khiên Phép |
| Bjorn | Rìu nặng 2 đòn | Lốc Rìu | Nện Đất | Cuồng Nộ | Gồng Mình |
| Mordred | Hắc kiếm 3 đòn | Hắc Viêm Trảm | Xiềng Xích Bóng Tối | Hắc Ma Hóa | Khiên Máu |

---

## ⌨️ Điều khiển

### Máy tính (phím mặc định — đổi được trong **Cài Đặt Phím**)

| Hành động | Phím |
|---|---|
| Di chuyển | `A` `D` / `←` `→` |
| Nhảy (bấm 2 lần để nhảy đôi) | `W` / `↑` / `Space` |
| Leo xuống, rơi xuyên sàn | `S` / `↓` |
| Đánh thường | `J` / chuột trái |
| Kỹ năng Q | `U` / nút cạnh chuột trên |
| Kỹ năng E | `I` / nút cạnh chuột dưới |
| Kỹ năng R | `O` / `Q` |
| Lướt | `Shift` / `L` |
| Chặn (giữ) | `K` / chuột phải |
| Bình máu · Bình mana | `N` / `X` · `M` / `C` |
| Ném thuốc nổ | `B` |
| Nói chuyện với NPC · giữ để mở hòm / giải cứu | `F` |
| Bảng nhiệm vụ | `T` / `Tab` |
| Tạm dừng | `Esc` / `P` |
| Bật/tắt tự động đánh (Vô Tận) | `V` |

### Điện thoại

Cần điều hướng bên trái, nút nhảy và các nút kỹ năng bên phải. Trong menu tạm dừng có mục **Chỉnh Vị Trí Nút** để kéo, đổi cỡ và độ mờ của nút. Game hỗ trợ chơi toàn màn hình.

---

## ♾ Chiến Đấu Vô Tận

Chế độ giải trí mở từ menu chính:

- Chọn 1 trong 6 chiến trường nhỏ theo phong cách từng vùng đất — có bệ đất, mái nhà, dây leo hoặc bệ di động, không có bẫy hay vực.
- Quái tràn ra từ **hai bên bản đồ** theo từng đợt; quái đợt trước chưa diệt hết vẫn có đợt mới kéo tới.
- **Cứ 5 đợt** xuất hiện một quái tinh anh, **cứ 10 đợt** xuất hiện một trùm. Hết 6 trùm thì vòng lặp lại, quái càng về sau càng mạnh.
- Quái vẫn rơi vàng, pha lê mana, ngọc máu và có thể rơi **ngọc nâng cấp** chỉ có hiệu lực trong trận: ⚔ sát thương, 🛡 giáp, ❤ máu tối đa.
- **🤖 Tự động đánh** (nút cạnh thanh máu hoặc phím `V`): nhân vật tự tìm mục tiêu, dùng mọi kỹ năng, lướt, né, chặn; bình máu và mana vẫn do người chơi tự dùng. Mỗi **vé tự động** (mua ở Cửa hàng › Bình thuốc, 500 vàng, tối đa **3 vé mỗi ngày**) cho 10 phút; vé cộng dồn và tự nối tiếp, thời gian chưa dùng hết được giữ cho lần sau. Hết vé, game tạm dừng và hỏi muốn chơi thủ công hay mua thêm. Đang tự động vẫn có thể tự điều khiển — thả tay ra máy lại đánh tiếp; nếu chỉ bấm đánh thường thì kỹ năng vẫn được dùng tự động.
- Có đồng hồ tính giờ; khi gục ngã sẽ hiện thời gian trụ được, số đợt, số quái hạ gục và **kỷ lục** của từng chiến trường.

---

## 📜 Nhiệm vụ

- **Nhiệm vụ chính:** bắt buộc để qua màn — đánh đuổi kẻ địch, giải cứu, thu thập vật phẩm, rèn lại Ấn, hạ trùm.
- **Nhiệm vụ phụ:** nhận từ NPC có dấu **!** — thu thập, chế tạo, săn quái, né mưa tên / cầu lửa, chạy đua tới cờ đỏ, đấu tay đôi để chiêu mộ chiến binh.
- **NPC:** Trưởng làng Bram, cô bé Mira, lính gác Tom, thợ săn Lyra, thợ rèn Hagen, Đại úy Roland, pháp sư Elda, thợ rèn Gorm.

Phần thưởng nhận trong bảng nhiệm vụ khi đang chơi, hoặc trong **Sổ Nhiệm Vụ** ở menu chính.

---

## 🛒 Cửa hàng

- **Nâng cấp (riêng cho từng nhân vật):** máu tối đa, vũ khí, giáp, kỹ năng Q, kỹ năng E, tuyệt kỹ R (mỗi mục 30 cấp) và túi hút vàng. Mỗi vùng đất mở thêm 5 cấp: lúc đầu tối đa cấp 5, hạ trùm vùng I mở tới cấp 10… hạ Hỏa Long mở toàn bộ 30 cấp.
- **Bình thuốc:** bình máu, bình mana (mang tối đa 9).
- **Trang phục:** mỗi nhân vật có bộ trang phục riêng, đổi cả kiểu trang phục lẫn màu hiệu ứng kỹ năng — Aren: *Chiến Binh Thập Tự*, *Quốc Vương Lumeria*; Aria: *Nữ Thợ Săn Rừng Sâu*; Ignis: *Lôi Pháp Sư* (phép lửa hóa sét xanh), *Ảo Thuật Sư Bóng Đêm* (phép tím). Sylva: *Tiễn Thủ Lá Rừng*; Kaito: *Samurai Mặt Quỷ*, *Quyền Sư Phong Ba*, *Sát Thủ Phong Thần*; Bjorn: *Sidrug Sừng Trâu*, *Chiến Binh Khiên Rìu*; Mordred: *Hỏa Kỵ Sĩ*. Aren và Aria vẫn có thêm các bộ đổi màu giáp.
- **Chiến binh:** chiêu mộ nhân vật đã mở khóa.

🎁 Có ô nhập **giftcode** trong menu chính.

---

## ✨ Tính năng khác

- Nhạc nền và hiệu ứng âm thanh tạo bằng Web Audio, riêng cho từng vùng đất và trận trùm.
- Hội thoại có chân dung nhân vật, cảnh truyện bỏ qua được.
- Vật phẩm đã nhặt không xuất hiện lại khi hồi sinh ở điểm lưu.
- Âm lượng nhạc và hiệu ứng chỉnh riêng.

---

## 🎨 Nguồn hình ảnh

Sprite và tileset từ các gói pixel art miễn phí: Gothicvania / Legacy Collection (Ansimuz), LuizMelo (Martial Hero 1–3, Huntress, Huntress 2, Medieval Warrior Pack 2, Medieval King Pack 2, Wizard Pack), chierit (Elementals: Leaf Ranger, Wind Hashashin, Fire Knight), sanctumpixel (Viking Axe), bytebox (Viking – Sidrug), CraftPix (Free Wizard Sprite Sheets, Villagers, Blacksmith), Axe Warriors, Warped và các gói NPC khác. Bản quyền hình ảnh thuộc về tác giả gốc của từng gói.

---

## 🛠️ Công nghệ

HTML5 Canvas + JavaScript thuần, không dùng thư viện hay framework. Khung hình 960×540, tự co giãn theo màn hình.
