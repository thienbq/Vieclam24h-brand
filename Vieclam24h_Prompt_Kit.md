# Bộ prompt ảnh Vieclam24h — dành cho CTV

Tài liệu này giúp bạn tự tạo ảnh cho bài đăng Vieclam24h bằng ChatGPT (hoặc Gemini), đúng Brand Guideline 2026, không cần công cụ nội bộ.

Mỗi lần dùng, bạn nhận được **2 ảnh**:

- **Ảnh 1 — không chữ.** Ảnh người thật hoặc nền đồ hoạ (có Chớp nếu bạn cần). Đội thiết kế dùng ảnh này để tự đặt chữ và logo.
- **Ảnh 2 — design hoàn chỉnh có chữ.** Dùng để duyệt ý nhanh, hoặc đăng luôn nếu đội thiết kế đồng ý.

---

## 0. FOR THE AI — read this first (khi file này được đính kèm vào chat)

If you are an AI assistant and this file was attached together with a brief (text or images), follow these rules for EVERY request in the chat:

1. Read the brief, fill the fields of section 2 yourself, pick prompt type A (real people) or B (brand background graphic), and add the matching blocks of section 4 (job cards, job list, event details, expressive typography). Use the size / ratio asked in the brief.
2. Always generate TWO separate images: IMAGE 1 without any text, IMAGE 2 the finished design with the exact text of the brief (correct Vietnamese diacritics, nothing invented).
3. Mascot Chớp AI is OPTIONAL. Add Chớp ONLY when a Chớp reference image is attached or the user asks for Chớp. Then copy it exactly (suitcase-shaped head, face, colors, hands only — no arms, no legs), change only pose / expression / prop, and make it interact with the person or the content. Otherwise do NOT add Chớp, any mascot or any character.
4. Logo: if a logo image file is attached, place THAT logo in IMAGE 2, top-left inside the safe margin, exactly as the file (white version on purple), only one logo. If no logo file is attached, leave that area empty and never draw a logo.
5. Follow the brand guideline summary in section 8 (colors, fonts, margins, one CTA, text ≤ 30% of the frame) and the hierarchy & accent rules in section 9 (one focal point, max 3 text levels, headline ≥ 2× sub line, only ONE colored accent word or number).
6. Never draw, retype or invent the Vieclam24h logo. Only place the attached logo file; if there is none, leave the logo area empty.
7. After the images, write the caption of section 5.

---

## 1. Cách dùng (5 bước)

**Cách nhanh:** kéo file này + brief (ảnh hoặc chữ) + **file logo PNG** (+ **ảnh mẫu Chớp** nếu bài cần Chớp) vào ChatGPT, gõ `Làm theo file prompt-kit cho brief này` (cần Chớp thì thêm: `có Chớp, Chớp …[làm gì]`). AI đọc mục 0 và tự làm hết.

**Cách chắc tay** (kiểm soát từng chữ):

1. **Điền phiếu bài đăng** ở mục 2. Mỗi ô chỉ cần một câu ngắn.
2. **Chọn kiểu hình** ở mục 3: kiểu A (ảnh người thật) hoặc kiểu B (nền đồ hoạ). Bài cần Chớp thì giữ dòng "Mascot" trong prompt; không cần thì xoá dòng đó.
3. **Copy prompt** của kiểu đã chọn, thay mọi chỗ `[…]` bằng thông tin trong phiếu. Nếu có, dán thêm một khối tuỳ chọn ở mục 4 vào cuối prompt.
4. **Mở ChatGPT:**
   - Bài cần Chớp: kéo **ảnh mẫu Chớp** (file PNG gốc do đội thương hiệu gửi) vào khung chat.
   - Muốn AI đặt luôn logo: kéo thêm **file logo PNG gốc** (prompt tự đặt logo khi có file).
   - Dán prompt, rồi bấm Enter.
   - Nếu ChatGPT chỉ ra 1 ảnh, gõ: `tiếp ảnh 2`.
5. **Kiểm nhanh** theo mục 7. Chưa đạt thì dùng câu sửa ở mục 6, gõ ngay trong cùng đoạn chat. Đạt rồi thì gửi cả 2 ảnh và caption (mục 5) cho đội thiết kế.

> **Logo:** có kéo file logo vào chat thì AI đặt logo; không có thì AI chừa chỗ để ghép sau. AI hay vẽ lại logo sai nét, sai dấu, nên luôn soát kỹ (xem mục 4.6).
> Không gửi tài liệu nội bộ, số liệu hay thông tin khách hàng cho AI. Chỉ dùng thông tin công khai của bài đăng.

---

## 2. Phiếu bài đăng (điền trước khi copy prompt)

| Ô | Điền gì | Ví dụ |
|---|---|---|
| `[KÊNH]` | Nơi đăng | Facebook feed |
| `[TỈ LỆ]` | 1:1 (post vuông) · 4:5 (post dọc Facebook, Threads) · 9:16 (Story, Reels, TikTok) · 1.91:1 (banner web, LinkedIn) · 16:9 (slide, YouTube) | 4:5 |
| `[NGƯỜI XEM]` | Ai sẽ xem, càng cụ thể càng tốt | Sinh viên 18–24 tìm việc làm thêm |
| `[CẢNH]` | Ảnh chụp cái gì: ai, đang làm gì, ở đâu | Bạn nữ barista đang rót latte ở quầy quán cà phê |
| `[CHỚP LÀM GÌ]` | (Chỉ khi cần Chớp) Chớp tương tác với người / nội dung thế nào | Chớp đứng trên quầy đưa ly cà phê cho bạn barista |
| `[HEADLINE]` | Chữ lớn, tối đa ~8 từ. Minigame thì headline là câu hỏi | Ca sáng, lương tuần |
| `[DÒNG PHỤ]` | Tối đa ~14 từ (có thể bỏ) | Quán gần trường, giờ linh hoạt |
| `[NÚT]` | Tối đa 4 từ | Ứng tuyển ngay |
| `[CHỮ NHẤN]` | 1 từ trong headline, viết bằng font tay (có thể bỏ) | sáng |

Viết chữ bằng tiếng Việt **có dấu đầy đủ**.

Tránh những câu hối thúc như "Đừng bỏ lỡ!" hay "Ứng tuyển ngay trước khi quá muộn". Nên ghi thông tin cụ thể như lương, ca làm, địa điểm.

---

## 3. Prompt chính

### Kiểu A — Ảnh người thật (+ mini Chớp nếu cần)

```text
Create TWO separate images (two separate generations, same scene, same person). Make IMAGE 1 first, then IMAGE 2. Do not combine them into one picture.

=== IMAGE 1 — talent photo (NO text, leave space for design) ===
A candid, unposed photo taken on a smartphone (main camera, 26 mm) — looks like a real moment someone snapped, not a stock photo and not an ad. Aspect ratio [TỈ LỆ], for [KÊNH].
Scene: [CẢNH]
People in the image: [NGƯỜI XEM] — ordinary-looking Vietnamese people, real faces, not models, wearing real work uniforms / using real tools of the job.
Output ONLY the photograph itself, full-bleed, filling the whole frame. Do NOT add any graphic design on top: no color overlay or tint, no cards, panels, boxes, placeholder bars, buttons, icons, frames, borders or UI elements. Text, logo and info cards are added later by the designer.
Light: bright, soft natural daylight with a gentle warm feel (window light or open shade), moderate contrast. No golden hour, no sun flare, no glow, no HDR, no dark or moody look.
Color: true-to-life and warm, natural white balance, clean and sharp image (no visible noise, no grain, no blur). A small touch of purple (#401F99) or cyan (#00CAFB) on a real object (apron, cup, notebook) is welcome — do not tint the whole image.
People: busy doing something, not posing, not looking straight into the camera, natural expressions; real skin texture, no retouching. If possible the movement goes from left to right.
Background: an ordinary, lived-in real workplace in Vietnam (real details, not a studio set), tidy enough to stay clear; normal depth of field.
Composition: the top third of the photo is naturally calm (plain wall, sky or out-of-focus background) — keep it as part of the photo, do NOT draw any box or empty panel there.
Mini mascot (ONLY if a Chớp reference image is attached — otherwise skip this line and add no character): add a SMALL version of the brand mascot Chớp AI from the ATTACHED reference image into the real scene — about 12–18% of the frame height. It MUST visibly interact with the person: the two share one moment and their attention connects (the person looks at or smiles toward the mascot). Interaction: [CHỚP LÀM GÌ]. Keep the person doing their real job while interacting. Copy the character EXACTLY: same suitcase-shaped head, face, colors and details, hands only (no arms, no legs). Render it like a small physical figure in the photo, with matching light, correct scale and a soft contact shadow. Keep it away from the top third and never covering faces.
Avoid: stock-photo look; staged forced smiles; plastic or airbrushed skin; oversaturated colors; dark, blurry, noisy or grainy images; color filters; golden glow or lens flare; everyone smiling; cinematic color grading; logos or brand marks; any text, letters, numbers or watermark; text on phone / laptop screens; color overlays; cards, boxes, buttons or placeholder shapes; a redesigned or different-looking mascot.

=== IMAGE 2 — finished design WITH text (same person and scene as image 1, same mini mascot if any) ===
Create a finished, ready-to-post social media design (a complete graphic, not just a photo). Aspect ratio [TỈ LỆ], for [KÊNH].
Use the photo of image 1 as the main visual (same person, and the same mini mascot if image 1 has one). Behind the text, a purple overlay (#401F99, 60–80% opacity, fading into the photo) so white text reads clearly.
Text on the design — render EXACTLY these Vietnamese words with correct diacritics, no other text anywhere:
- Headline (biggest, bold): "[HEADLINE]"
- Sub line (smaller, under the headline): "[DÒNG PHỤ]"
- Button (one only, cyan #00CAFB with purple #401F99 text, fully rounded): "[NÚT]"
Typography: Lexend style — clean geometric sans-serif, very readable on a phone. Headline bold; sub line regular. Max 3 text levels.
Hierarchy: ONE focal point that the eye hits first (the headline or one key number), then the sub line, then the button. Headline at least 2× the size of the sub line; sub line clearly smaller and lighter. Group headline + sub line tightly together, with more space before the button. Only ONE accent: one key word or number in brand cyan #00CAFB (on purple) — never several colored words.
Colors: Brand Purple #401F99, Brand Cyan #00CAFB, white, Ink #1B1530 for dark small text. Never cyan text on white.
Logo (required): IF a logo image file is attached in this chat, place that exact logo in the top-left corner inside the safe margin, about 22% of the image width — same symbol shapes, same lowercase wordmark "việclàm24h" with its exact letters, accents and spacing, same colors and proportions; do NOT redraw, retype, restyle, recolor, stretch, rotate, outline or add effects; on a purple background use the all-white version of the same logo; keep clear space around it equal to the symbol height; only ONE logo. IF no logo file is attached, keep that top-left area (22% of the width, 8% of the height) EMPTY and do not draw or invent any logo. Either way the headline starts BELOW the logo area.
Safe margins: keep all text, the button and the logo at least 8% away from every edge (80 px on a 1080 px wide post). For 9:16 stories also keep them out of the top 13% and the bottom 18% of the frame. Text covers at most 30% of the frame. Simple, uncluttered layout.
Every shape that holds information must contain real, readable text from the list above — never empty placeholder bars, grey lines or dummy icons.
Avoid: misspelled or invented text, extra words, invented or redrawn logos, more than one logo, watermarks, cluttered layout, more than one button, a redesigned mascot, arms or legs on the mascot.
```

### Kiểu B — Nền đồ hoạ (+ Chớp nếu cần)

```text
Create TWO separate images (two separate generations, same background). Make IMAGE 1 first, then IMAGE 2. Do not combine them into one picture.

=== IMAGE 1 — background graphic (NO text, NO people) ===
A clean, modern brand background graphic (not a photo), aspect ratio [TỈ LỆ], for [KÊNH].
Look: soft light gradient from very light lavender (#EFE4FF) to white, a few large soft rounded blob shapes and gentle curved ribbons in light tints of purple #401F99, violet #9A69FF and cyan #00CAFB, subtle depth and soft glow, small sparkles; bright, friendly, uncluttered.
Layout: keep the top-left area calm for the headline.
Mascot (ONLY if a Chớp reference image is attached — otherwise skip this line; the visual can be props like gifts, 3D numbers or icons that fit the brief): use the brand mascot Chớp AI from the ATTACHED reference image. Copy the character EXACTLY — same suitcase-shaped head, face, eyes, proportions, colors, materials and details; it has hands only (no arms, no legs). Do NOT redesign it and do NOT invent a different character. Only change its pose, expression and one small prop so it matches this post: [CHỚP LÀM GÌ]. Place it in the bottom-right area, turned toward the headline (top-left), at a size that feels like the hero of the post.
Avoid: people, any character other than the attached Chớp (none if no reference is attached), a redesigned or different-looking mascot, arms or legs on the mascot; any text, letters, numbers or logos; UI cards, buttons, placeholder bars; photos; dark or busy backgrounds.

=== IMAGE 2 — finished design WITH text (same background as image 1, same mascot pose if any) ===
Create a finished, ready-to-post social media design (a complete graphic, not just a photo). Aspect ratio [TỈ LỆ], for [KÊNH].
Background (and mascot, if any): exactly as image 1 — NO photo, NO people. Keep the mascot in the bottom-right.
Text on the design — render EXACTLY these Vietnamese words with correct diacritics, no other text anywhere:
- Headline (biggest, bold): "[HEADLINE]"
- Sub line (smaller, under the headline): "[DÒNG PHỤ]"
- Button (one only, cyan #00CAFB with purple #401F99 text, fully rounded): "[NÚT]"
Typography: Lexend style — clean geometric sans-serif. Headline in Brand Purple #401F99; sub line in Ink #1B1530. Max 3 text levels.
Hierarchy: ONE focal point that the eye hits first (the headline or one key number), then the sub line, then the button; the mascot (if any) supports the headline and never competes with it. Headline at least 2× the size of the sub line. Group headline + sub line tightly together, with more space before the button. Only ONE accent: one key word or number of the headline in Violet #9A69FF (large text only, never small text) — never several colored words.
Logo (required): IF a logo image file is attached in this chat, place that exact logo in the top-left corner inside the safe margin, about 22% of the image width — same symbol shapes, same lowercase wordmark "việclàm24h" with its exact letters, accents and spacing, same colors and proportions; do NOT redraw, retype, restyle, recolor, stretch, rotate, outline or add effects; on a purple background use the all-white version of the same logo; keep clear space around it equal to the symbol height; only ONE logo. IF no logo file is attached, keep that top-left area (22% of the width, 8% of the height) EMPTY and do not draw or invent any logo. Either way the headline starts BELOW the logo area.
Safe margins: keep all text, the button and the logo at least 8% away from every edge (80 px on a 1080 px wide post). For 9:16 stories also keep them out of the top 13% and the bottom 18% of the frame. Text covers at most 30% of the frame and never overlaps the mascot.
Every shape that holds information must contain real, readable text from the list above — never empty placeholder bars.
Avoid: misspelled or invented text, extra words, invented or redrawn logos, more than one logo, watermarks, more than one button, people, any other character, a redesigned mascot.
```

---

## 4. Khối tuỳ chọn (dán thêm vào cuối prompt, trong phần IMAGE 2)

### 4.1 Typo nổi bật (khuyên dùng cho bài truyền thông, minigame)

```text
Typography — expressive but on-brand: set the headline in Lexend ExtraBold/Black, ALL CAPS allowed, broken into 2–3 stacked lines with tight leading (about 0.9) and strong size contrast between lines, left-aligned like a poster. Most words in #401F99 (white on a purple background); one key word or line in a brighter brand tint (#9A69FF on light backgrounds, #00CAFB on purple). Write the word "[CHỮ NHẤN]" in Oooh Baby (handwritten script, lowercase, slightly rotated, smaller than the big lines but never below 24 px at 1080 px width, tucked beside them). If you use the colored key word, the Oooh Baby word stays in the same color as the main headline — only ONE colored accent in total. Sub line small in Lexend Regular. Max 3 text levels, readable on a phone, no outlines, no 3D or glossy text effects, no extra words.
```

### 4.2 Thẻ việc làm (tin tuyển dụng: tối đa 3 thẻ, luôn có lương và địa điểm)

Thay mỗi dòng `Card …` bằng một việc. Xoá dòng thừa nếu có ít hơn 3 việc. Ô vuông tím bên trái là chỗ đặt logo doanh nghiệp: AI chỉ để ô trống, designer đặt logo thật sau.

> AI vẽ thẻ không chắc đúng 100% (hay sai dấu tiếng Việt, lệch màu, lệch khoảng cách). Tin tuyển dụng cần chính xác thì cách chắc nhất: cho AI làm ảnh nền + chữ lớn, còn thẻ việc làm thì ghép từ file mẫu trong Figma/Illustrator.

```text
Add [SỐ THẺ] job cards stacked vertically, under the headline area. Render the text exactly, character by character, Vietnamese accents included:
  Card 1 — position: "[Vị trí 1]" / company: "[Công ty 1]" / location: "[Địa điểm 1]" / salary: "[Lương 1]"
  Card 2 — position: "[Vị trí 2]" / company: "[Công ty 2]" / location: "[Địa điểm 2]" / salary: "[Lương 2]"
  Card 3 — position: "[Vị trí 3]" / company: "[Công ty 3]" / location: "[Địa điểm 3]" / salary: "[Lương 3]"
Each field goes on its own row inside its card — never join them on one line, never show the separator "/" or the words position/company/location/salary.
Job card style (follow exactly, same for every card): a horizontal white card, corner radius about 16 px at 1080 px width, thin 1 px border #E6E3EE, very soft light-purple shadow, inner padding about 24 px. LEFT: one square tile (1:1), solid brand purple #401F99, corner radius about 12 px, its height EQUAL to the height of the text block next to it, about 20 px gap to the text; the tile is plain, empty purple — no letters, no icon, no invented logo (the real company logo is placed later by the designer). RIGHT: a left-aligned text block in a Lexend-like geometric sans-serif, one item per row, in this order: 1) job position — bold, ink #1B1530, the largest text in the card; 2) company name — semibold, ink #1B1530; 3) location — regular, ink #1B1530, with a small round-ended line map-pin icon before it; 4) salary — bold, violet #9A69FF, at least 24 px at 1080 px width, with a small round-ended line coin icon before it. Icons: 2 px rounded strokes, same set. The card contains ONLY the tile and these rows: no buttons, no tags/chips, no save/heart icon, no job code, no extra lines. If a row is not given, leave it out and let the card shrink to fit; never draw empty placeholder bars.
All cards have the same width, the same left edge and equal vertical gaps.
```

### 4.3 Một việc nổi bật

```text
Add ONE job card, a little larger than the other text blocks. Render the text exactly, character by character, Vietnamese accents included:
  position: "[Vị trí]" / company: "[Công ty]" / location: "[Địa điểm]" / salary: "[Lương]"
Each field goes on its own row — never join them on one line, never show the separator "/" or the words position/company/location/salary.
Job card style (follow exactly, same for every card): a horizontal white card, corner radius about 16 px at 1080 px width, thin 1 px border #E6E3EE, very soft light-purple shadow, inner padding about 24 px. LEFT: one square tile (1:1), solid brand purple #401F99, corner radius about 12 px, its height EQUAL to the height of the text block next to it, about 20 px gap to the text; the tile is plain, empty purple — no letters, no icon, no invented logo (the real company logo is placed later by the designer). RIGHT: a left-aligned text block in a Lexend-like geometric sans-serif, one item per row, in this order: 1) job position — bold, ink #1B1530, the largest text in the card; 2) company name — semibold, ink #1B1530; 3) location — regular, ink #1B1530, with a small round-ended line map-pin icon before it; 4) salary — bold, violet #9A69FF, at least 24 px at 1080 px width, with a small round-ended line coin icon before it. Icons: 2 px rounded strokes, same set. The card contains ONLY the tile and these rows: no buttons, no tags/chips, no save/heart icon, no job code, no extra lines. If a row is not given, leave it out and let the card shrink to fit; never draw empty placeholder bars.
```

### 4.4 Danh sách tên vị trí

```text
Add a clean bulleted list of job titles under the headline, one line each, render exactly:
  • "[Vị trí 1]"
  • "[Vị trí 2]"
  • "[Vị trí 3]"
```

### 4.5 Sự kiện / livestream (thông tin đọc được từ xa)

```text
Add the event details as a small clear line under the sub line, render exactly: "[Ngày] · [Giờ] · [Địa điểm hoặc kênh phát]".
```

### 4.6 Logo

Prompt đã tự xử lý: **có kéo file logo PNG gốc vào chat** thì AI đặt logo vào góc trên trái. **Không kéo** thì AI chừa trống chỗ đó để ghép sau.

Nếu logo bị vẽ lại sai nét, sai dấu chữ hoặc bị méo, gõ:
`Logo bị vẽ lại sai. Đặt lại logo y hệt file đính kèm, không vẽ lại, không đổi màu, không hiệu ứng. Giữ nguyên mọi thứ khác.`
Sửa vẫn không đúng thì ghép logo thật bằng Canva / Photoshop / Figma (luôn đúng 100%).

---

## 5. Prompt viết caption

Dán vào cùng đoạn chat sau khi có ảnh:

```text
Viết caption đăng kèm bài này cho [KÊNH] của Vieclam24h:
- Tiếng Việt có dấu, giọng gần gũi nhưng không suồng sã, tích cực nhưng không hứa hẹn quá mức.
- 2–4 câu ngắn, mỗi câu một ý, động từ lên trước, có thông tin cụ thể (lương, ca, địa điểm nếu có).
- Một lời kêu gọi rõ ràng, không hối thúc (không dùng "Đừng bỏ lỡ", "trước khi quá muộn").
- Tối đa 1 emoji. 2–4 hashtag ở cuối, có #Vieclam24h.
- Chỉ trả lời caption, không giải thích.
```

---

## 6. Câu sửa nhanh (gõ trong cùng đoạn chat)

| Vấn đề | Gõ câu này |
|---|---|
| Ảnh nhìn "AI" quá | `Làm lại ảnh này cho giống ảnh chụp thật bằng điện thoại: ánh sáng ban ngày tự nhiên, sáng và hơi ấm, màu chân thực, da thật có lỗ chân lông, biểu cảm tự nhiên (không cười gượng), bối cảnh nơi làm việc thật ở Việt Nam. Ảnh sạch, rõ nét, không nhiễu hạt, không filter. Giữ nguyên bố cục, người và Chớp. Không thêm chữ, logo.` |
| Ảnh tối, mờ hoặc nhiễu | `Làm ảnh sáng hơn, rõ nét hơn, bỏ nhiễu hạt. Giữ màu chân thực, hơi ấm, không đổi bố cục.` |
| Ảnh 1 bị vẽ thêm khung, thẻ, lớp tím | `Làm lại ảnh 1: CHỈ giữ ảnh chụp thật (và Chớp), phủ kín khung hình. Bỏ hết khung/thẻ thông tin, ô trống, thanh placeholder, nút, icon, chữ, logo và lớp phủ màu. Màu tự nhiên, không filter.` |
| Chớp bị vẽ sai | `Chớp chưa giống ảnh mẫu. Vẽ lại Chớp y hệt ảnh mẫu đính kèm: đầu hình vali, mặt, mắt, màu và chi tiết giữ nguyên; chỉ có bàn tay, không có cánh tay, không có chân. Chỉ đổi tư thế. Giữ nguyên phần còn lại.` |
| Chớp không tương tác với người | `Cho Chớp và người tương tác rõ hơn: người nhìn hoặc cười về phía Chớp, Chớp [CHỚP LÀM GÌ]. Giữ nguyên mọi thứ khác.` |
| Sai chính tả / sai dấu | `Sửa chữ cho đúng chính xác từng ký tự: "[chữ đúng]". Không đổi gì khác.` |
| Thẻ việc làm sai mẫu | `Vẽ lại thẻ việc làm đúng mẫu: nền trắng, bo 16px, viền #E6E3EE; bên trái là ô vuông tím #401F99 trống, cao bằng khối chữ; bên phải mỗi thông tin một dòng: vị trí (đậm, to nhất), doanh nghiệp, địa điểm có icon ghim, lương màu #9A69FF có icon đồng xu. Bỏ nút, tag, mã số, icon tim. Giữ nguyên mọi thứ khác.` |
| AI tự vẽ logo | `Xoá logo vừa vẽ, để trống góc trên bên trái. Không vẽ bất kỳ logo nào.` |
| Chữ chạm mép / đè lên người hoặc Chớp | `Dời chữ, nút và logo vào trong, cách mép ít nhất 8% khung hình (story: tránh 13% trên và 18% dưới), không đè lên người và Chớp.` |
| Tô màu nhiều chữ quá | `Chỉ giữ màu nhấn cho đúng một từ/cụm "[từ nhấn]", các chữ còn lại về màu chính. Giữ nguyên mọi thứ khác.` |

---

## 7. Kiểm nhanh trước khi gửi

- [ ] (Nếu có Chớp) Chớp giống ảnh mẫu (đầu vali, mặt, màu; chỉ có bàn tay) và tương tác với người hoặc nội dung. Không cần Chớp thì ảnh không có nhân vật lạ nào.
- [ ] Ảnh 1 không có chữ, khung, thẻ hay lớp màu phủ lên.
- [ ] Chữ ở ảnh 2 đúng từng dấu, không có chữ thừa, chỉ một nút.
- [ ] Logo: góc trên trái còn trống cho logo, hoặc (nếu dùng mục 4.6) logo giống hệt file gốc, không méo, không đổi màu, chỉ có một logo.
- [ ] Người trông thật, không nhìn thẳng ống kính, không cười gượng. Ảnh sáng, rõ nét, màu chân thực, không nhiễu hạt.
- [ ] Chữ, nút, logo nằm trong lề an toàn (≥ 8% mỗi cạnh; story tránh 13% trên, 18% dưới).
- [ ] Tin tuyển dụng: có lương và địa điểm, tối đa 3 thẻ. Thẻ đúng mẫu: ô vuông tím bên trái cao bằng khối chữ, mỗi thông tin một dòng, không nút / tag / mã số trong thẻ, đúng từng dấu.
- [ ] Nheo mắt nhìn ảnh 2: thấy ngay **một** điểm nhấn (headline hoặc con số), rồi mới tới dòng phụ, rồi nút (xem mục 9).
- [ ] Chỉ 1 từ/cụm được tô màu nhấn; headline to gấp ít nhất 2 lần dòng phụ.
- [ ] Chữ màu Violet (từ nhấn, lương) đủ lớn (≥ 24px ở khung 1080); không có chữ cyan hay chữ trắng trên nền trắng/cam.

Gửi cho đội thiết kế: **Ảnh 1 + Ảnh 2 + caption**, đặt tên file theo mẫu `[ngày]-[kênh]-[chủ đề]-1.png` và `…-2.png`.

---

## 8. Tóm tắt guideline (để tham chiếu)

- **Màu chính:**
  - Brand Purple `#401F99`: nhận diện, tiêu đề.
  - Brand Cyan `#00CAFB`: điểm nhấn, nút.
- **Màu mở rộng:** Violet `#9A69FF` · Orange `#FF8A3D` · Cyan Light `#D2FCFF`.
- **Màu trung tính:** Lavender `#EFE4FF` (nền phụ) · Ink `#1B1530` (chữ chính) · Grey `#5F5A75` (chữ phụ) · Line `#E6E3EE` (viền thẻ).
- **Tỷ lệ màu:** 50% nền sáng (trắng, lavender) · 30% Purple · 15% Cyan / Violet / Orange.
- **Font:**
  - Lexend cho tiêu đề, nội dung, nút.
  - Oooh Baby chỉ cho một câu nhấn ngắn (≤ 8 từ, ≥ 24px, không viết hoa toàn bộ).
- **Tương phản:**
  - Chuẩn, mọi cỡ chữ: Trắng / Tím · Cyan / Tím · Tím / Lavender · Tím / Cyan Light · Ink / Cyan · Ink / Orange.
  - Chỉ chữ ≥ 24px: Violet trên nền trắng, chữ trắng trên nền Violet.
  - Không dùng: chữ cyan trên nền trắng, chữ trắng trên nền cam.
- **Lề an toàn:**
  - Post vuông 1080×1080: 80px.
  - Post dọc 1080×1350: 80px.
  - Story 1080×1920: 96px; trên 250px, dưới 340px.
  - Banner 1200×628: 60px.
- **Kích thước chuẩn:** Post vuông 1080×1080 · Post dọc 1080×1350 · Story/Reels/TikTok 1080×1920 · Ảnh bìa Facebook 1640×624 · LinkedIn 1200×627 · Banner web 1200×628.
- **Logo:** luôn ở góc trên trái hoặc dưới trái, trong lề an toàn, luôn từ file gốc. AI chỉ được **đặt** file logo đính kèm, không được vẽ lại. Logo AI đặt sai thì đội thiết kế ghép lại bằng file gốc trước khi đăng.
- **Mạng xã hội:** mỗi bài một thông điệp; chữ ≤ 30% khung hình; tối đa 2 màu nền thương hiệu; một nút CTA.
- **Chớp AI:** giữ nguyên đầu vali, tỷ lệ mặt, màu. Bản số chỉ có bàn tay, không có cánh tay hay chân. Luôn đối chiếu với hình mẫu chuẩn.

---

## 9. Phân cấp thông tin & điểm nhấn (áp dụng cho post, story, banner)

> Làm **slide thuyết trình**: dùng file mẫu và làm theo `Vieclam24h_Slide_Guideline_2026.md`, không dùng thang chữ ở mục này.

### 9.1 Chính – phụ: mỗi khung hình chỉ có 1 thông điệp chính

| Cấp | Vai trò | Kiểu chữ | Màu |
|---|---|---|---|
| **Cấp 1: Chính** | Thông điệp người xem phải nhớ (headline, câu hỏi, con số lớn) | Lexend Bold/ExtraBold, to nhất | Brand Purple `#401F99` (trắng nếu nền tím) |
| **Cấp 2: Phụ** | Giải thích, tiêu đề nhóm, tên vị trí | Lexend Bold, nhỏ hơn cấp 1 | Ink `#1B1530` (trắng nếu nền tím) |
| **Cấp 3: Chi tiết** | Mô tả, chú thích, nguồn | Lexend Regular | Grey `#5F5A75` (Lavender `#EFE4FF` nếu nền tím) |
| **Hành động** | Nút CTA, QR, link | Lexend Bold trong khối cyan | Purple trên Cyan `#00CAFB` |

- Tối đa **3 cấp chữ** + 1 nút. Không thêm cấp thứ 4 bằng cách đổi màu hay in nghiêng.
- Phân cấp bằng **cỡ chữ và độ đậm trước**, màu sau cùng. Không phân cấp chỉ bằng màu.

### 9.2 Thang cỡ chữ (mỗi cấp gấp khoảng 1,5–2 lần cấp dưới)

> Thang này dành riêng cho ấn phẩm truyền thông (post, story, banner), lớn hơn thang chữ giao diện trong Brand Guideline (Display 60 / H1 44 / Body 16…) vì người xem lướt trên điện thoại.

| | Post 1080 px | Story 1080×1920 |
|---|---|---|
| Cấp 1 | 72–96 px | 88–120 px |
| Cấp 2 | 36–44 px | 44–56 px |
| Cấp 3 | 26–30 px | 32–36 px |
| Nút / nhãn | 28–32 px | 36–40 px |

- Headline **≥ 2 lần** dòng phụ. Chênh lệch nhỏ hơn thì mắt không biết đọc gì trước.
- Dãn dòng: headline 0,9–1,0; nội dung 1,2–1,3.

### 9.3 Điểm nhấn: 1 nhấn chính, tối đa 1 nhấn phụ

Chọn **một** trong các cách sau làm điểm nhấn chính của khung hình. Có thể thêm **một** cách khác làm nhấn phụ, nhưng **chỉ một cách được dùng màu** (cách 1 hoặc 4).

1. **Từ khoá màu:** 1 từ/cụm trong headline đổi sang Violet `#9A69FF` (nền sáng) hoặc Cyan `#00CAFB` (nền tím).
2. **Con số lớn:** lương, %, số thứ tự… làm cấp 1, to gấp 2–3 lần phần chữ còn lại.
3. **Chữ tay Oooh Baby:** 1 câu ngắn ≤ 8 từ, viết thường, nghiêng nhẹ, đặt sát headline.
4. **Khối nổi:** 1 khối nền Purple đặc giữa các khối trắng. Riêng thẻ việc làm luôn giữ nền trắng; thẻ quan trọng nhất nổi lên bằng cách to hơn hoặc nhô lên.
5. **Chớp AI:** mascot chỉ vào hoặc cầm nội dung chính.

Quy tắc:
- Màu nhấn (Cyan / Violet / Orange) chiếm **≤ 15%** khung hình, khớp tỷ lệ 50 / 30 / 15 ở mục 8.
- Chỉ tô màu **1 từ/cụm** trong một khung hình. Nhấn mọi thứ thì không còn gì được nhấn.
- Orange chỉ dùng làm khối nền nhỏ với chữ Ink `#1B1530`, không dùng chữ cam hay chữ trắng trên nền cam.
- Chữ Violet chỉ dùng khi chữ ≥ 24px (ở khung 1080).
- Trong một nhóm thẻ ngang hàng, chỉ **1 thẻ** được làm nổi (to hơn hoặc nhô lên; khối tím chỉ dùng cho khối thông tin, không dùng cho thẻ việc làm). Các thẻ còn lại giữ nguyên.
- Điểm nhấn đặt ở nơi mắt bắt đầu đọc (trên trái) hoặc ở giữa trục chính, không đặt ở góc bị bỏ qua.

### 9.4 Khoảng cách & nhóm thông tin

- Khoảng cách **trong nhóm < giữa các nhóm** (tỷ lệ khoảng 1 : 2). Headline với dòng phụ đứng sát nhau, cách xa nút hơn.
- Căn trái cho nội dung. Chỉ căn giữa cho câu ngắn đứng một mình (câu hỏi lớn, câu kết).
- Thứ tự đọc chữ Z hoặc F: logo → cấp 1 → cấp 2 → hành động.

### 9.5 Logo trong bộ nhận diện

- **Post / banner:** logo ở góc trên trái, trong lề an toàn, rộng khoảng 22% khung (không nhỏ hơn 120px). Headline bắt đầu dưới logo.
- **Slide:** logo đã gắn sẵn trong file mẫu (trên trái ở bìa, dưới trái ở slide nội dung). Không xoá, không chèn thêm. Xem `Vieclam24h_Slide_Guideline_2026.md`.
- Logo luôn ghép từ file gốc, không vẽ lại. Chừa vùng trống quanh logo bằng chiều cao biểu tượng.

### 9.6 Kiểm nhanh phân cấp ("nheo mắt")

- [ ] Nheo mắt nhìn: thấy rõ **1** điểm đầu tiên, sau đó mới tới phần còn lại.
- [ ] Không quá 3 cấp chữ, chỉ 1 cụm tô màu nhấn.
- [ ] Trong nhóm thẻ, chỉ 1 thẻ nổi bật.
- [ ] Logo đúng vị trí, đúng file gốc.
