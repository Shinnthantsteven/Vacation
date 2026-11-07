# Food photos for the Vietnam 2027 plan

The Food tab shows a photo for each dish if a file with the right name exists in `public/img/food/`. If a file is missing, the card shows an emoji and still works.

How to fill it: ask ChatGPT to make a realistic photo for each prompt below, save it as JPG with the exact file name, put it in `public/img/food/`, then push to GitHub. Landscape 4:3 works best, under 300 KB each.

| File | Dish | Status | ChatGPT prompt |
|---|---|---|---|
| pho-bo.jpg | Phở bò / phở gà | safe | Realistic food photo of Phở bò / phở gà (Beef or chicken noodle soup) as served in Vietnam, top-down, natural light, no text, no pork |
| egg-coffee.jpg | Cà phê trứng | safe | Realistic food photo of Cà phê trứng (Egg coffee, Hanoi specialty) as served in Vietnam, top-down, natural light, no text, no pork |
| salmon-hotpot.jpg | Lẩu cá hồi | safe | Realistic food photo of Lẩu cá hồi (Salmon hotpot, Sapa) as served in Vietnam, top-down, natural light, no text, no pork |
| ga-nuong.jpg | Gà nướng / trứng nướng | safe | Realistic food photo of Gà nướng / trứng nướng (Grilled chicken / grilled eggs) as served in Vietnam, top-down, natural light, no text, no pork |
| com-lam.jpg | Cơm lam | safe | Realistic food photo of Cơm lam (Sticky rice in bamboo) as served in Vietnam, top-down, natural light, no text, no pork |
| com-ga.jpg | Cơm gà Hội An | safe | Realistic food photo of Cơm gà Hội An (Hoi An chicken rice) as served in Vietnam, top-down, natural light, no text, no pork |
| bun-cha-ca.jpg | Bún chả cá | safe | Realistic food photo of Bún chả cá (Fish cake noodle soup) as served in Vietnam, top-down, natural light, no text, no pork |
| banh-mi.jpg | Bánh mì gà / trứng | ask | Realistic food photo of Bánh mì gà / trứng (Chicken or egg baguette) as served in Vietnam, top-down, natural light, no text, no pork |
| goi-cuon.jpg | Gỏi cuốn | ask | Realistic food photo of Gỏi cuốn (Fresh summer rolls) as served in Vietnam, top-down, natural light, no text, no pork |
| banh-xeo.jpg | Bánh xèo | ask | Realistic food photo of Bánh xèo (Crispy pancake) as served in Vietnam, top-down, natural light, no text, no pork |
| mi-quang.jpg | Mì Quảng | ask | Realistic food photo of Mì Quảng (Turmeric noodles, Da Nang) as served in Vietnam, top-down, natural light, no text, no pork |
| bun-bo-hue.jpg | Bún bò Huế | avoid | Realistic food photo of Bún bò Huế (Spicy beef noodle soup) as served in Vietnam, top-down, natural light, no text (this dish contains pork; the photo is only so I can recognise and avoid it) |
| bun-cha.jpg | Bún chả | avoid | Realistic food photo of Bún chả (Grilled pork noodles, Hanoi) as served in Vietnam, top-down, natural light, no text (this dish contains pork; the photo is only so I can recognise and avoid it) |
| com-tam.jpg | Cơm tấm sườn | avoid | Realistic food photo of Cơm tấm sườn (Broken rice with pork chop) as served in Vietnam, top-down, natural light, no text (this dish contains pork; the photo is only so I can recognise and avoid it) |
| cao-lau.jpg | Cao lầu | avoid | Realistic food photo of Cao lầu (Hoi An noodles) as served in Vietnam, top-down, natural light, no text (this dish contains pork; the photo is only so I can recognise and avoid it) |
| cha-gio.jpg | Nem / chả giò | avoid | Realistic food photo of Nem / chả giò (Spring rolls) as served in Vietnam, top-down, natural light, no text (this dish contains pork; the photo is only so I can recognise and avoid it) |
| thang-co.jpg | Thắng cố | avoid | Realistic food photo of Thắng cố (Hmong stew, Sapa markets) as served in Vietnam, top-down, natural light, no text (this dish contains pork; the photo is only so I can recognise and avoid it) |

## Updating the private plan later
1. Edit `private/vietnam-plan.html` (it is git-ignored, so it never goes to GitHub).
2. Run `npm run lock` and choose a password.
3. Run `npm run build`, or just push: the deploy workflow builds and publishes.
