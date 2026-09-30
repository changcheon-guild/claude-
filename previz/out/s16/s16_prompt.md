# S16 · 경화역 철길 질주 — 뉴테이크 프롬프트 (시행 연습용)

## 레퍼런스 업로드 순서

| 번호 | 파일 | 역할 |
|---|---|---|
| @1 | 캐릭터 시트 (남색 코트·땋은 머리 소녀) | 외형 전부: 얼굴, 머리, 의상, 소품, 색 |
| @2 | 콘티 S16 컷 | 구도, 포즈(팔 벌리기), 속도감 |
| @3 | 프리비즈 `s16_shaded.mp4` | 카메라 경로, 타이밍, 달리는 동선 |

뉴테이크의 실제 태그 표기(@1, @이미지1 등)가 다르면 번호만 바꿔 쓰세요.
생성 설정: 5초, 16:9, 24fps, 사운드 끄기.

---

## 메인 프롬프트

```
Silent 5-second shot, 16:9, 24 fps. No audio, no music, no sound effects, no dialogue.

[REFERENCES]
@1 is the character. Use her face, eyes, hair, outfit, props, colors and proportions exactly, and keep them identical in every frame.
@2 is the storyboard. Match its composition: side-on view, the girl running left to right with both arms spread wide, and a background streaking with speed.
@3 is the previz. Follow its camera path, timing, framing and running path exactly. Replace the grey mannequin with the girl from @1.

[CHARACTER @1]
A teenage girl with long glossy blue-black hair: loose strands frame her face, and a single thick braid hangs over her right shoulder. She has large dark blue-grey eyes and warm light skin with a soft blush. She wears an oversized navy blue hooded coat, open, over a cream ribbed knit top, with a long camel pleated midi skirt and black chunky loafers. A silver-and-black film camera hangs on a black strap at her chest, and a small black mini backpack with a gold zipper sits on her back.

[ACTION]
She sprints along the railway track from left to right, stepping from sleeper to sleeper between the rails. Both arms are stretched out wide like airplane wings, and she laughs with an open mouth and eyes squeezed shut in joy, as in the laughing expression on @1. The running is energetic and natural: knees lifting high, a slight forward lean, loafers pushing off the wooden sleepers.
Secondary motion on every stride: the coat tails and hood flare and flap behind her, her braid swings and whips back, the pleated skirt ripples around her calves, the camera bounces on its strap against her chest, and the backpack jolts.
Timing follows @3. She enters from frame left in the first second, runs level with the camera, and in the final second pulls slightly ahead toward frame right. She never slows down or stops.

[CAMERA]
Handheld lateral tracking shot on a 35mm lens, at her chest height, with the operator running alongside her from left to right at her speed. The handheld feel is natural and organic: a gentle vertical bob in rhythm with the operator's footsteps, 1–2 degrees of roll drift, tiny framing lag and catch-up when she speeds up, and light micro-shake. The camera is never locked-off and never gimbal-smooth, but she always stays in frame. She stays crisp; the background streaks past with strong horizontal motion blur.

[BACKGROUND]
Gyeonghwa Station railway in Jinhae during the Jinhae Gunhangje cherry blossom festival. An old track with two steel rails and weathered wooden sleepers on grey gravel, with pink petals scattered on the ties. Behind the track runs a low wooden slatted fence, and beyond it a festival crowd strolls and takes photos under rows of cherry trees in full bloom. The far blossoms melt into a soft pink haze. A white "경화역" station sign slides past briefly. Petals drift through the air and swirl in her wake.

[STYLE]
A 3D toon-shaded animation that reads like a 2D anime drawing. Translate the 2D design of @1 into a cel-shaded 3D model while keeping its proportions and palette.
- Shading: flat color fills with hard-edged two-tone cel shading and no soft gradients. Shadows are cool blue-violet, not grey.
- Linework: clean dark outlines of varying thickness around the silhouette, hair clumps and clothing folds, like hand-inked lines.
- Face and hair: anime eyes with painted highlights, and hair rendered as sharp clumped locks with a single glossy highlight band.
- Lighting: a warm spring backlight rim along her hair and shoulders, and a soft bounce of pink light from the blossoms.
- Background: softer and more painterly than the character, with hand-painted blossom masses and speed-streaked brushwork, so the crisp cel-shaded girl pops against it.
- Color: pastel pink, warm cream and navy.
- Overall: the dimensional camera and depth of 3D, with the graphic flatness of 2D.
```

## 네거티브 프롬프트

```
audio, music, sound, dialogue, subtitles, text overlay, watermark, logo,
photorealistic, realistic skin texture, pores, PBR materials, glossy plastic CGI, soft Pixar-style gradient shading, uncanny 3D face,
locked-off static camera, gimbal-smooth camera, camera cut, zoom,
walking, slow jogging, stopping, running toward or away from camera, train on the track,
changing face, changing outfit, missing braid, missing camera, missing backpack, shorts, pants,
extra limbs, extra fingers, distorted hands, deformed face, night, winter
```

## 옵션: 2D 느낌을 더 세게 (결과가 너무 3D스러울 때 [STYLE] 끝에 추가)

```
Animate the girl on twos (character poses hold for 2 frames) while the camera and background move smoothly on ones, like 2D-inspired 3D animation. Add subtle hand-drawn smear frames on the fastest arm and leg swings.
```

## 짧은 버전 (글자 수 제한용)

```
Silent 5s shot, no audio. @1 character exactly, @2 composition, @3 camera path and timing. The girl from @1 sprints left to right along the Gyeonghwa Station railway at Jinhae Gunhangje, arms spread like wings, laughing; coat, braid, skirt and camera bounce with each stride. Handheld 35mm lateral tracking beside her, natural bob and drift. Fence, festival crowd and full-bloom cherry trees streak past in motion blur, petals in the air. 3D toon-shaded, 2D anime look: flat cel shading, hard shadows, ink outlines, painterly background.
```
