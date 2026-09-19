# 地铁购物屏幕变装

> 形态：首图生成 + 图生视频。人物均为明确成年人；重点锁定人物身份、车厢几何、邻座乘客、礼盒与购物界面的连续性。

## 首图提示词

```text
Vertical 24:43 photorealistic smartphone image inside a subway carriage. An adult woman with long straight dark hair and a slim build sits centrally on a deep red upholstered bench, her legs crossed with the upper foot extending toward screen left. She looks down at a gray triple-camera smartphone held in both hands. She wears a fitted white sleeveless collared button-front top, black shorts, white ribbed ankle socks, and reflective silver pointed-toe heels. A white rectangular gift box with a small dark DIOR wordmark rests across her lap. A pale shoulder bag hangs from a fine chain on her screen-left side; pale bracelets are visible at her wrist.

A large dark-edged phone held by a hand fills the lower-right foreground, tilted slightly inward. Its white shopping screen shows a black floral-lace bodysuit and a pair of long stockings arranged as a product set, with small controls along the bottom and a magenta button at bottom right. Two seated adult passengers flank the woman, partially cropped: blue top, long gray skirt and brown handbag on screen left; gray knitwear and a dark bag on screen right. Silver metal walls, dark windows, a straight chrome pole immediately to the woman's screen right, and a mustard-yellow speckled floor establish the carriage. Frontal, slightly low viewpoint, even cool indoor light, soft shadows and natural skin texture.
```

### 首图负面提示词

```text
minor, child, extra people, duplicate passenger, distorted subway geometry, incorrect bench layout, missing chrome pole, warped phone, unreadable shopping screen, malformed hands, extra fingers, body proportion changes, face drift, low resolution, illustration, cartoon, CGI look, strong beauty filter, text watermark, cropped main subject, sexual nudity, explicit pose
```

## 图生视频提示词

```text
Use the reference image as the initial visual state. Maintain the adult woman's face, long dark hair, body proportions, pale shoulder bag and wrist accessories, the seated neighbors, the red bench, chrome pole and carriage geometry, and the natural photographic lighting throughout. Keep all action non-explicit and preserve the completed outfit as a black floral-lace bodysuit with matching stockings.

Keep a single continuous shot lasting about 15 seconds, with subtle handheld sway. The framing stays nearly still at first. Around 13 seconds it gradually shifts upward as she rises; her hair briefly reaches the top edge before the framing settles into a head-to-below-knees view. The foreground shopping phone gradually leaves the bottom of the frame.

0–4.7 seconds: the foreground thumb swipes horizontally through the product pictures: the black lace set, a black slip dress on a model, a black bodysuit on a model, then back to the original lace set by about 2.4 seconds. The thumb settles onto the selected image and holds there. The seated woman continues looking at her own phone.

About 4.8–8.3 seconds: pale violet luminous arcs appear around the shoes and ankles and sweep upward in successive horizontal bands, first along both legs, then across the lap, waist and torso toward the shoulders. Behind the ascending bands, the silver heels turn black, the white socks disappear into black floral-lace stockings, and the lace pattern progressively reaches the thighs. The lower-body change is visible before the upper clothing changes. Around 7–8.3 seconds, the white top and black shorts continuously change into a matching black floral-lace bodysuit with vertical suspender straps and banded stocking tops. Keep the face, hands and body shape intact while the clothing changes; the violet light fades by about 8.3 seconds.

Around 6.9–8.8 seconds she raises her eyes from her phone, widens her eyes and opens her mouth in surprise. Around 8.6–9.7 seconds she looks down at her outfit, lowers her own phone out of clear view behind the lap area, uncrosses her legs and lowers her feet side by side. Around 9.5–10.4 seconds she looks toward screen left, then around 10.6–11.6 seconds toward screen right; she then smiles and looks down. The neighboring passengers remain seated with only small head turns.

Around 12–13.7 seconds she lifts a small black shopping bag by its handles from her screen-left side while steadying the white box. Around 13.7–14.5 seconds she rises from the seat, bringing the black bag and white package together in front of her lower torso. Preserve the DIOR wordmark on the white box and the small centered white DIOR lettering on the black bag. Finish with her standing in front of the same seat, smiling slightly and looking down while lightly adjusting the bag, still wearing the completed black lace outfit and stockings.

No cuts, no camera jump, no voyeuristic framing, no exaggerated body movement. Preserve adult identity, realistic fabric behavior, natural body proportions, the two seated passengers, the red bench, chrome pole, windows, floor and cool subway lighting.
```

### 视频负面提示词

```text
minor, nudity, explicit sexual activity, fetish framing, body exposure, lingerie removal, face swap, identity drift, hairstyle changes, hand or finger deformation, extra limbs, warped phone screen, disappearing passengers, changing subway geometry, broken bench, missing pole, extra bags, text garbling, incorrect DIOR spelling, flashing transformation, fast camera movement, cuts, camera jump, motion blur, cartoon, CGI, beauty filter, watermark, subtitles
```

## 建议参数

| 参数 | 建议 |
| --- | --- |
| 时长 | 15 秒 |
| 首图画幅 | `24:43` 竖构图 |
| 视频画幅 | 与首图保持一致的竖构图 |
| 镜头 | 单一连续镜头，轻微手持晃动 |
| 变装节奏 | 4.8–8.3 秒由鞋履向上连续变化 |
| 收尾构图 | 站立后从头部到膝下，前景购物手机退出画面 |
