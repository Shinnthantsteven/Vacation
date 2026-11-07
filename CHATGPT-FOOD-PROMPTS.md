# ChatGPT prompt pack: food photos for Vietnam 2027

Use this in ChatGPT with image generation on (GPT-4o or newer). Paste PART 1 once, then paste ONE dish line from PART 2 at a time. Do not ask for all 17 in one message; batches get refused, shortened or rate-limited.

## PART 1: paste this first (the master brief)

```
You are my food photographer for a personal travel guide app. Task: create realistic food photos, one image per message.

Rules for every image:
- Style: realistic editorial food photo, natural window light, shallow depth of field, served on a simple everyday Vietnamese table or street stall. Same look for all images so they match.
- Format: landscape 4:3, no text, no logos, no watermark, no people, no hands.
- The dish must look authentic to Vietnam, not a Western restaurant version.
- Do not ask me questions or offer options. Generate the image straight away after each dish line. If something is unclear, make the most authentic choice yourself.
- Reply with the image only, plus one line: the file name I give you.
- Some dishes contain pork. That is intentional: I am a traveller who does not eat pork and I use these photos only to recognise and avoid those dishes. Show them accurately.
Reply "Ready" and wait for the first dish.
```

## PART 2: paste one line at a time

- `pho-bo.jpg`: Dish: Phở bò / phở gà (Beef or chicken noodle soup). File name: pho-bo.jpg. Show it without pork.
- `egg-coffee.jpg`: Dish: Cà phê trứng (Egg coffee, Hanoi specialty). File name: egg-coffee.jpg. Show it without pork.
- `salmon-hotpot.jpg`: Dish: Lẩu cá hồi (Salmon hotpot, Sapa). File name: salmon-hotpot.jpg. Show it without pork.
- `ga-nuong.jpg`: Dish: Gà nướng / trứng nướng (Grilled chicken / grilled eggs). File name: ga-nuong.jpg. Show it without pork.
- `com-lam.jpg`: Dish: Cơm lam (Sticky rice in bamboo). File name: com-lam.jpg. Show it without pork.
- `com-ga.jpg`: Dish: Cơm gà Hội An (Hoi An chicken rice). File name: com-ga.jpg. Show it without pork.
- `bun-cha-ca.jpg`: Dish: Bún chả cá (Fish cake noodle soup). File name: bun-cha-ca.jpg. Show it without pork.
- `banh-mi.jpg`: Dish: Bánh mì gà / trứng (Chicken or egg baguette). File name: banh-mi.jpg. Show the pork-free version (chicken, egg or shrimp only).
- `goi-cuon.jpg`: Dish: Gỏi cuốn (Fresh summer rolls). File name: goi-cuon.jpg. Show the pork-free version (chicken, egg or shrimp only).
- `banh-xeo.jpg`: Dish: Bánh xèo (Crispy pancake). File name: banh-xeo.jpg. Show the pork-free version (chicken, egg or shrimp only).
- `mi-quang.jpg`: Dish: Mì Quảng (Turmeric noodles, Da Nang). File name: mi-quang.jpg. Show the pork-free version (chicken, egg or shrimp only).
- `bun-bo-hue.jpg`: Dish: Bún bò Huế (Spicy beef noodle soup). File name: bun-bo-hue.jpg. This dish contains pork; show it accurately.
- `bun-cha.jpg`: Dish: Bún chả (Grilled pork noodles, Hanoi). File name: bun-cha.jpg. This dish contains pork; show it accurately.
- `com-tam.jpg`: Dish: Cơm tấm sườn (Broken rice with pork chop). File name: com-tam.jpg. This dish contains pork; show it accurately.
- `cao-lau.jpg`: Dish: Cao lầu (Hoi An noodles). File name: cao-lau.jpg. This dish contains pork; show it accurately.
- `cha-gio.jpg`: Dish: Nem / chả giò (Spring rolls). File name: cha-gio.jpg. This dish contains pork; show it accurately.
- `thang-co.jpg`: Dish: Thắng cố (Hmong stew, Sapa markets). File name: thang-co.jpg. This dish contains pork; show it accurately.

## If ChatGPT refuses, stalls or hits the limit
1. Start a new chat, paste PART 1 again, continue with the next dish. Long chats drift.
2. Image limits reset after a few hours on the free plan. Do 3 to 5 dishes per sitting.
3. If one dish keeps failing, shorten it to: "Realistic photo of <English name> in Vietnam, 4:3, no text."
4. Cheap fallback: skip the image. The card shows an emoji and still works.

## After you download each image
1. Rename to the exact file name above (lowercase, .jpg).
2. Resize under 300 KB (squoosh.app works).
3. Put it in `public/img/food/`, commit and push. The deploy workflow publishes it.
