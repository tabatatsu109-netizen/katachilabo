# カタチラボ 業種別イメージ画像 生成プロンプト集

LPの「設計図（ブループリント）」トーンに合わせた共通スタイルを冒頭に付け、
各業種で「困りごと → システム」への変化を1枚の構図で表現するプロンプトです。
Midjourney / DALL-E / Stable Diffusion など、お使いのツールにそのまま貼ってください。

---

## 共通スタイル指定（毎回コピペする部分）

```
Isometric technical blueprint illustration style.
Thin ink-navy (#1B2A41) linework on warm paper background (#FAFAF7).
Subtle hairline grid in the background, like drafting paper.
Dimension lines with small tick marks connecting the two halves of the scene.
One accent color used sparingly: deep red-ochre (#9A3324, Japanese bengara red),
applied only to a single highlight line, stamp mark, or arrow.
Fine brass/gold (#A9895E) thin outline details.
Clean minimal line art, engineering-drawing aesthetic, no shading, no gradients.
No text, no Japanese characters, no numbers in the image.
4:3 aspect ratio, editorial illustration quality.
```

---

## 業種別プロンプト（上の共通スタイルに続けて追加）

### 1. スポーツクラブ運営
```
Left side: a wall whiteboard covered in handwritten, crossed-out match schedules and marker scribbles.
Right side: a tablet screen showing a clean grid of court assignments with soccer-ball line icon.
A dimension-line arrow connects the whiteboard to the tablet across the center.
```

### 2. 物流・配送
```
Left side: a stack of paper order slips and an old fax machine with curled paper.
Right side: a tablet screen showing a simple delivery route map with connected dots and a small van icon.
A dimension-line arrow connects the fax machine to the tablet across the center.
```

### 3. 小売・店舗
```
Left side: a handwritten monthly shift calendar with names crossed out and rewritten by hand.
Right side: a smartphone screen showing a clean digital shift grid with colored blocks.
A dimension-line arrow connects the calendar to the smartphone across the center.
```

### 4. 施設管理
```
Left side: a wall whiteboard with reservation time slots scribbled in marker, some erased and rewritten.
Right side: a monitor screen showing a clean booking calendar interface.
A dimension-line arrow connects the whiteboard to the monitor across the center.
```

### 5. 飲食店
```
Left side: a worn paper reservation notebook next to a small pile of paper receipts.
Right side: a tablet POS screen showing a table layout grid and a small ingredient stock bar.
A dimension-line arrow connects the notebook to the tablet across the center.
```

### 6. 美容室・サロン
```
Left side: a small filing box packed with handwritten paper customer cards.
Right side: a smartphone screen showing a clean client history timeline with small icons.
A dimension-line arrow connects the filing box to the smartphone across the center.
```

### 7. 建設・工務店
```
Left side: a rolled paper blueprint next to a camera and a scattered pile of printed site photos.
Right side: a tablet screen showing a site-report app with a photo grid layout.
A dimension-line arrow connects the blueprint roll to the tablet across the center.
```

### 8. 不動産
```
Left side: a thick ring binder overflowing with printed property listing photos.
Right side: a smartphone screen showing a simple property map with location pins.
A dimension-line arrow connects the binder to the smartphone across the center.
```

### 9. 医療・介護
```
Left side: a clipboard with a handwritten shift schedule and handover notes, pages curling.
Right side: a tablet screen showing a shared care-notes interface with simple timeline entries.
A dimension-line arrow connects the clipboard to the tablet across the center.
```

### 10. 士業（税理士・行政書士など）
```
Left side: a tall stack of paper case folders tied together with string.
Right side: a laptop screen showing a simple kanban-style case-progress board with cards.
A dimension-line arrow connects the folder stack to the laptop across the center.
```

### 11. 製造業
```
Left side: a hand-tally clipboard with checkmarks, standing next to stacked cardboard boxes in a warehouse.
Right side: a monitor screen showing a production dashboard with simple bar gauges.
A dimension-line arrow connects the clipboard to the monitor across the center.
```

### 12. 農業・直売所
```
Left side: a handwritten harvest ledger notebook resting on wooden vegetable crates.
Right side: a tablet screen showing a simple sales and inventory bar chart.
A dimension-line arrow connects the notebook to the tablet across the center.
```

### 13. 教育・塾
```
Left side: a stack of paper attendance sheets next to an old rotary telephone.
Right side: a smartphone screen showing a simple parent notification chat interface.
A dimension-line arrow connects the telephone to the smartphone across the center.
```

### 14. NPO・地域団体
```
Left side: a printed spreadsheet page covered in handwritten pen corrections and arrows.
Right side: a tablet screen showing a clean member roster list with a simple dues-tracking bar.
A dimension-line arrow connects the spreadsheet page to the tablet across the center.
```

### 15. ペット関連（トリミング・ペットホテル）
```
Left side: a worn paper pet record card with a small paw-print stamp mark.
Right side: a tablet screen showing a booking calendar with a simple pet profile card.
A dimension-line arrow connects the record card to the tablet across the center.
```

---

## 使い方メモ
- 共通スタイル＋各業種の本文をそのままつなげて1つのプロンプトにしてください。
- 「no text, no Japanese characters」を入れているのは、AIが生成する文字が崩れやすいためです。文字はLP側でCSS/HTMLで乗せる想定にしています。
- 統一感を出したいので、同じツール・同じシードやスタイル参照（Midjourngeyなら `--sref` など）を使い回すと15枚のトーンが揃いやすいです。
