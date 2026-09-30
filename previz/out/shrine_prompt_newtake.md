# 신사 나무타기 · 뉴테이크 프롬프트 (3D 스타일라이즈드 버전)

## 레퍼런스

| 태그 | 파일 | 쓰는 것 | 쓰지 말아야 할 것 |
|---|---|---|---|
| @1 | 캐릭터 (가능하면 3D로 변환한 캐릭터 이미지, 없으면 캐릭터 시트) | 얼굴, 머리, 의상, 소품, 색 | 시트의 2D 그림체 |
| @2 | `previz_shaded.mp4` | 카메라 경로, 타이밍, 동선, 세트 배치 | 마네킹의 뻣뻣한 포즈, 회색 도형 질감 |
| @3 | `reference_landscape.mp4` | 3D 룩, 조명, 색감, 움직임의 자연스러움 | 레퍼런스 속 소녀의 외형(파란 셔츠, 반바지) |

설정: 16:9, 24fps, 10초(9.5초 분량, 끝 0.5초는 편집에서 자름), 사운드 끔.

---

## 메인 프롬프트

```
Silent 10-second continuous shot, 16:9, 24 fps. No audio, no music, no sound effects, no dialogue.

[REFERENCES]
@1 = the character. Copy her identity exactly: face, eyes, long blue-black hair with one thick braid over her right shoulder, oversized navy hooded coat, cream ribbed top, long camel pleated midi skirt, black chunky loafers, film camera on a neck strap, small black mini backpack. Render her as a fully 3D character, not as the 2D drawing on the sheet.
@2 = the previz. Follow ONLY its camera path, camera timing, framing, the girl's route and the set layout (stairs, torii, courtyard, maple tree on a stone platform). Do NOT copy the mannequin's stiff poses or the grey block look; re-animate her body naturally.
@3 = the look and motion reference. Match its stylized 3D rendering, lighting, color, atmosphere and fluid motion quality. Do NOT copy the girl in @3; the only character is @1.

[ACTION — timing from @2]
0.0–0.5s  Low angle at the foot of old stone shrine stairs looking up at a red torii; an orange tabby cat darts up through the gate.
0.5–2.6s  The girl from @1 dashes past the camera from lower left and races up the stairs two at a time, arms pumping, leaning forward; the camera follows close behind her, climbing with her.
2.6–3.3s  She crests the top step and runs through the torii; the camera passes between the red pillars.
3.3–5.0s  She chases the cat across the sunlit gravel courtyard toward a huge autumn maple on a stone platform; shrine hall on the right, tall cedars behind.
5.0–5.7s  She plants a hand and hops up onto the stone platform.
5.7–9.5s  She climbs the thick trunk and pulls herself onto a low branch: hands gripping the bark, loafers pushing off, her body hauling up with visible effort. The camera pushes in and tilts up. The cat watches from a branch above.

[MOTION QUALITY]
Fluid, weighted, motion-captured-feeling performance, never stiff: anticipation before each jump, clear weight shifts, real foot plants on each stair, hips and shoulders counter-rotating while running. Rich secondary motion with physics: the coat tails and hood flap, the braid swings with inertia, the pleated skirt swirls and catches air, the camera bounces on its strap, and the backpack jolts. Natural handheld follow-cam on top of the @2 camera path: gentle bob and sway, slight lag when she accelerates.

[LOOK — stylized 3D, like @3]
A high-end stylized 3D animated feature film. Everything has real volume and depth: fully three-dimensional forms, soft global illumination, ambient occlusion and contact shadows, warm midday autumn sun with soft falloff, and volumetric light shafts through the red-orange maple leaves. The skin is soft and stylized with gentle subsurface glow, not photoreal. Stone, bark and wood carry hand-painted texture detail. Anime-inspired face and large eyes from @1, sculpted in 3D with real shading across the cheeks, nose and hair volume. Hair is modeled in thick strands with specular sheen. There is strong parallax between foreground, midground and background, a shallow depth of field on the close climbing shots, and atmospheric haze in the distance. Deep blue sky with red, orange and yellow maple foliage.
```

## 네거티브 프롬프트

```
2D, flat shading, cel shading, toon shading, ink outlines, line art, hand-drawn animation, anime drawing, flat colors, watercolor, paper texture, limited animation, drawn on twos,
stiff mannequin movement, robotic motion, wooden limbs, T-pose, sliding feet, floating, frozen hair, rigid cloth,
photorealistic human, realistic skin pores, uncanny face,
the girl from @3, blue floral shirt, shorts,
audio, music, sound, dialogue, subtitles, text, watermark, logo,
camera cut, scene change, extra limbs, extra fingers, distorted hands, face changing, outfit changing, missing braid
```

## 결과가 여전히 뻣뻣할 때

```
Treat @2 as a rough layout only. Animate her like a real athletic girl: loose shoulders, arms swinging freely, springy knees, natural stride length, a little stumble of excitement at the top of the stairs.
```

## 결과가 여전히 2D로 나올 때

```
Rendered like a modern 3D CG animated film, not illustrated. Visible 3D depth, real light bouncing on surfaces, soft shadows wrapping around forms.
```
