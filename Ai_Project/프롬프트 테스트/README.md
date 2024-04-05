

---
![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00059-1580354914.png?raw=true)

parameters

prompt
```
Cute happy fluffy white puppy facing forward, full body, watercolor, intricate details, hd clarity, white background
```
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1580354914, Size: 512x512, Model hash: 6ce0161689, Model: v1-5-pruned-emaonly, Version: v1.8.0

---



![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00079-2838435814.png?raw=true)

ADetailer 적용 전

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00080-2838435814.png?raw=true)

ADetailer 적용 후

parameters
```
girl 1girl, forest spirit, Stream, Moss, small pebble, Forest, shorts, Happy , Wisps, fireflies, night, flower field
Negative prompt: aid291 bad-artist-anime bad-hands-5 bad_pictures bad_prompt_version2 BadDream easynegative EasyNegativeV2 epiCNegative, Blurry, ugly, tiling, poorly drawn hands, poorly drawn feet, poorly drawn face, out of frame, extra limbs, disfigured, deformed, body out of frame, bad anatomy, watermark, signature, cut off, Low quality, Bad quality, Long neck
```
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2838435814, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Version: v1.8.0


---

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00016-4223243398.png?raw=true)

인페인트 사용전

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00061-424445079.png?raw=true)

인페인트 사용후


parameters

1 old man , (long hair:1), school palace, medium window, hogwarts legacy, palace, hogwarts school uniform, 4k, arstation, intricate, elegant, highly detailed, bring magic wand

Negative prompt: worst quality, low quality, normal quality, unclear architectural outline, duplicate, missing_body, (missing_face:1.4), (missing_eyes:1.4), nsfw
Steps: 20, Sampler: Euler a, CFG scale: 7, Seed: 4223243398, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Version: v1.8.0


---

i2i 생성 테스트

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B7%B8%EB%A6%BC1.png?raw=true)

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00028-1068468216.png?raw=true)

parameters

Negative prompt: (painting by bad-artist-anime:0.9), (painting by bad-artist:0.9), watermark, text, error, blurry, jpeg artifacts, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, artist name, (worst quality, low quality:1.4), bad anatomy, watermark, signature, text, logo
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1068468216, Size: 352x528, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Denoising strength: 0.45, Mask blur: 4, Inpaint area: Only masked, Masked area padding: 32, Masked content: fill, Version: v1.8.0



---

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/5f5edfc82f1fddb04333f5a23cdde8dc.jpg?raw=true)

Lineart 색 적용전

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00027-238572726.png?raw=true)

Lineart 색 적용후


parameters

sharp_two_hand_sword
Negative prompt: (painting by bad-artist-anime:0.9), (painting by bad-artist:0.9), watermark, text, error, blurry, jpeg artifacts, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, artist name, (worst quality, low quality:1.4), bad anatomy, watermark, signature, text, logo
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 238572726, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: lineart_standard (from white bg & black line), Model: control_v11p_sd15_lineart [43d4be0d], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.8.0


---

Scribble

lineart, white background, masterpiece, extremely detailed thick line drawing, 1girl , hoodie, animal gloves, skirt, sneakers
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 3082143404, Size: 512x704, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Denoising strength: 0.4, ADetailer model: face_yolov8n.pt, ADetailer confidence: 0.3, ADetailer dilate erode: 4, ADetailer mask blur: 4, ADetailer denoising strength: 0.4, ADetailer inpaint only masked: True, ADetailer inpaint padding: 32, ADetailer version: 24.3.2, ControlNet 0: "Module: scribble_pidinet, Model: control_v11p_sd15_scribble [d4ba51ff], Weight: 1, Resize Mode: Crop and Resize, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Mask blur: 4, Inpaint area: Only masked, Masked area padding: 32, Version: v1.8.0

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B7%B8%EB%A6%BC%202.png?raw=true)

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00012-3082143404.png?raw=true)


Depth

![image]()


Pixel

![image](https://github.com/HHyeongSeok/ai-project_3AB/blob/main/Ai_Project/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00002.png?raw=true)