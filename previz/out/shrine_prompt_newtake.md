# 신사 나무타기 · 뉴테이크 프롬프트 (캐릭터 시트 + 영상 2개)

## 업로드 순서

| 태그 | 파일 | 쓰는 것 | 쓰지 않는 것 |
|---|---|---|---|
| @1 | 캐릭터 시트 (남색 코트·땋은 머리 소녀) | 얼굴, 머리, 의상, 소품, 색 | 2D 그림체 |
| @2 | `previz_shaded.mp4` | 카메라 경로, 타이밍, 동선, 세트 배치 | 마네킹의 뻣뻣한 포즈, 회색 도형 질감 |
| @3 | `reference_landscape.mp4` | 3D 렌더링 느낌, 조명, 색감, 자연스러운 움직임 | 영상 속 소녀의 외형(파란 셔츠, 반바지) |

설정: 16:9, 24fps, 10초(끝 0.5초는 편집에서 자름), 사운드 끔.

---

## 메인 프롬프트

```
Silent 10-second continuous shot, 16:9, 24 fps. No audio, no music, no sound effects, no dialogue.

[REFERENCES]
@1 is the character sheet. It is a 2D drawing; use it ONLY for her design: face, large dark blue-grey eyes, long blue-black hair with one thick braid over her right shoulder, oversized navy hooded coat, cream ribbed top, long camel pleated midi skirt, black chunky loafers, silver-and-black film camera on a neck strap, small black mini backpack with a gold zipper. Rebuild her as a fully 3D character model with real volume and 3D lighting. Do not keep the 2D drawing style of @1.
@2 is the previz. Follow ONLY its camera path, camera timing, framing, the girl's route and the set layout (stone stairs, red torii, gravel courtyard, big maple on a stone platform). Do NOT copy the grey mannequin's stiff poses or the block-shape look; re-animate her body naturally.
@3 is the look and motion reference. Match its stylized 3D rendering, lighting, colors, atmosphere and fluid, weighted movement. Do NOT copy the girl in @3; the only character is the girl from @1.

[ACTION — timing from @2]
0.0–0.5s  Low angle at the foot of old stone shrine stairs looking up at a red torii; an orange tabby cat darts up through the gate.
0.5–2.6s  The girl dashes past the camera from lower left and races up the stairs, arms pumping, leaning forward; the camera follows close behind and climbs with her.
2.6–3.3s  She crests the top step and runs through the torii; the camera passes between the red pillars.
3.3–5.0s  She chases the cat across the sunlit gravel courtyard toward a huge autumn maple on a stone platform; shrine hall on the right, tall cedars behind.
5.0–5.7s  She plants a hand and hops up onto the stone platform.
5.7–9.5s  She climbs the thick trunk and pulls herself onto a low branch: hands gripping the bark, loafers pushing off, her body hauling up with effort. The camera pushes in and tilts up. The cat watches from a branch above.

[MOTION]
Fluid, weighted, motion-captured-feeling performance, never stiff: anticipation before each jump, clear weight shifts, solid foot plants on every stair, hips and shoulders counter-rotating while she runs. Physics-driven secondary motion: the coat tails and hood flap, the braid swings with inertia, the pleated skirt swirls and catches air, the camera bounces on its strap, and the backpack jolts. Natural handheld follow-cam on top of the @2 camera path: gentle bob and sway, with slight lag when she speeds up.

[LOOK — stylized 3D like @3]
A high-end stylized 3D animated feature film. Fully three-dimensional forms with soft global illumination, ambient occlusion and contact shadows. Warm midday autumn sun, with volumetric light shafts through red-orange maple leaves. Soft, stylized skin with a gentle subsurface glow, not photoreal. Hair modeled in thick strands with specular sheen. Stone, bark and wood carry hand-painted texture detail. Strong parallax between foreground, midground and background; shallow depth of field on the close climbing shots; atmospheric haze in the distance. Deep blue sky with red, orange and yellow foliage.
```

## 네거티브 프롬프트

```
2D, flat shading, cel shading, toon shading, ink outlines, line art, hand-drawn animation, anime drawing, illustration, flat colors, watercolor, paper texture, limited animation, drawn on twos,
stiff mannequin movement, robotic motion, wooden limbs, T-pose, sliding feet, floating, frozen hair, rigid cloth,
photorealistic human, realistic skin pores, uncanny face,
the girl from @3, blue floral shirt, shorts,
audio, music, sound, dialogue, subtitles, text, watermark, logo,
camera cut, scene change, extra limbs, extra fingers, distorted hands, face changing, outfit changing, missing braid
```

## 결과를 보고 붙이는 추가 문장

여전히 뻣뻣할 때:
```
Treat @2 as a rough layout only. Animate her like a real athletic girl: loose shoulders, arms swinging freely, springy knees, natural stride length, a small stumble of excitement at the top of the stairs.
```

여전히 2D로 나올 때:
```
Rendered like a modern 3D CG animated film, not illustrated. Visible 3D depth, light bouncing off surfaces, soft shadows wrapping around forms.
```
