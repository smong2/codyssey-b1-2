# 🎬 [2단계] 오버타임 광고 캠페인 스토리보드

# OVERTIME 광고 캠페인 스토리보드: "대한민국에서 살아남는 K-직장인의 우정"

## 1. 프로젝트 개요

- **컨셉:** 박카스 광고 패러디 ("대한민국에서 성실한 사람으로 산다는 것")
- **총 영상 길이:** 30초
- **대상:** 더 나은 미래를 위해 묵묵히 노력하는 모든 직장인, 학생, 성실한 사람들
- **사용 도구 체인:** * **이미지 생성:** GPT-5, Gemini Pro 3.1
  - **동영상 생성:** Gemini Pro 3.1 (컷 2-1~끝), Sora 2 (컷 1-1, 1-2)
  - **오디오/TTS:** TTS-1, Suno v4

---

## 2. 파이프라인 전략

- **최적화:** Sora 2(최대 4초) 및 기타 도구(10초 생성 후 컷 편집)를 활용하여 리듬감 확보.
- **몽타주 기법:** 롱테이크 시 발생하는 물리 법칙 왜곡을 방지하기 위해 8개의 정교한 3-4초 단위 컷으로 분할 생성.
- **소스 일관성:** 씬 이미지를 프롬프트로 변환하거나, 필요 시 외부 링크를 활용하여 일관성 유지.

---

## 3. 스토리보드 구성

### [Cut 1-1] 인물 초근접 클로즈업 - ok

- **길이:** 4초 | **목표 메시지:** 야근에 지친 K-직장인의 피로감 전달
- **화면 구성:** [구도] 익스트림 클로즈업 샷 / [피사체] 멍하니 노트북을 응시하는 개발자의 눈과 안경 / [배경] 불 꺼진 어두운 사무실 / [텍스트] 없음
- **내레이션:** "대한민국에서 성실한 사람으로 산다는 것."
- **사용 도구:** 이미지(GPT-5, 사실적 안경 반사광 구현), 영상(Sora 2, 미세한 눈 깜빡임)
- **입력 프롬프트(원문):** 
`A highly detailed, cinematic extreme close-up shot of a tired South Korean male software engineer in his late 20s, staring blankly at a laptop screen in a completely dark office at night. The cold blue light of the coding screen is intensely reflected on the lenses of his glasses, obscuring his eyes slightly and emphasizing his burnout. His head is supported by his hand, weary expression, dark circles under his eyes, realistic skin texture with sweat. The background is a vast, dark open-plan office with only distant, blurred LED indicators. Lighting is dark and moody with a dramatic contrast between the cold blue light and shadows. Shot on Sony A1, 16:9 aspect ratio, 8k resolution, ultra-photorealistic, shallow depth of field.`
- **동영상 프롬프트:**
`A highly detailed, cinematic extreme close-up shot of a tired South Korean male software engineer in his late 20s, staring blankly at a laptop screen in a completely dark office at night. The cold blue light of the coding screen is intensely reflected on the lenses of his glasses, obscuring his eyes slightly and emphasizing his burnout. His head is supported by his hand, weary expression, dark circles under his eyes, realistic skin texture with sweat. The background is a vast, dark open-plan office with only distant, blurred LED indicators. Lighting is dark and moody with a dramatic contrast between the cold blue light and shadows. Shot on Sony A1, 16:9 aspect ratio, 8k resolution, ultra-photorealistic, shallow depth of field. [Input Image: http://mong.or.kr/contents/cut01_01.png] CRITICAL DIRECTION: This video MUST be generated using the provided image URL as the strict, unalterable first frame (Frame 0). Do not change the identity of the person, clothing, or the environment. ANIMATION INSTRUCTION: Strictly lock the composition of the input image. Animate ONLY the fingers of the South Korean male developer, making them move in a natural, rhythmic typing motion on the mechanical keyboard. The rest of the scene, including the background, desk items, and lighting, must remain 100% consistent with the original image. Execute smooth motion blur for the hands while maintaining the exact cinematic low-light atmosphere from the source URL.`
- **결과 요약:** 안경에 코딩 화면이 반사된 지친 눈빛 확보
- **파일명:** `cut_01_01.png`, `cut_01_01.mp4`

### [Cut 1-2] 데스크 인서트 샷 - ok

- **길이:** 4초 | **목표 메시지:** 밤샘 코딩 노동의 시각화
- **화면 구성:** [구도] 매크로 로우앵글 샷 / [피사체] 기계식 키보드를 두드리는 손가락 / [배경] 코드 IDE 화면 하단 / [텍스트] 없음
- **내레이션:** (효과음)
- **사용 도구:** 이미지(GPT-5, 디테일한 손 피부 묘사), 영상(Sora 2, 물리 법칙에 따른 키보드 모션)
- **입력 프롬프트(원문):**  `Cinematic medium close-up shot focusing on the hands of the same South Korean male developer from the previous scene, actively typing on a sleek mechanical keyboard in the same dark office. The environment is dimly lit, with the bright blue coding interface from the laptop screen illuminating the hands and the desk surface. Scattered notes, a half-empty coffee mug, and various office supplies on the wooden desk, all in soft focus. The atmosphere is tense and focused, nighttime office vibe, professional cinematography, 8k, photorealistic, shallow depth of field. http://mong.or.kr/contents/cut01_01.png 이 링크에 있는 이미지를 참조해줘.  톤앤매너 맞춰서 만들어줘. 첫번째 이미지는 손이 너무 깨끗해서 피곤하다는 느낌이 안들어. 적당히 건조한 느낌이 들어가 있어야해.`
- ** 동영상 프롬프트:**
`Maintain the consistent appearance of the South Korean male developer's hands and clothing from the original image. The fingers should move naturally and rhythmically on the mechanical keyboard, performing a focused typing action. Add a subtle, realistic flickering light effect from the monitor onto the hands and the desk surface to enhance the dark office atmosphere. Ensure the motion is smooth, steady, and perfectly matches the focused mood.  참고 영상 url : http://mong.or.kr/contents/cut01_02.png 이미지 참고하고 톤앤매너 지켜서 영상 만들어줘.`
- **결과 요약:** 키보드를 두드리는 손가락의 자연스러운 모션 생성
- **파일명:** `cut_01_02.png`, `cut_01_02.mp4`

### [Cut 2-1] 캔 음료 미끄러짐 -ok

- **길이:** 4초 | **목표 메시지:** 예상치 못한 호의의 진입
- **화면 구성:** [구도] 책상 수평 트래킹 샷 / [피사체] 어두운 책상을 미끄러져 오는 캔 / [배경] 헝클어진 마우스 선 / [텍스트] 없음
- **내레이션:** "당신의 야근 회복제는..."
- **사용 도구:** 이미지(GPT-5, 캔의 하이퍼 리얼리스틱 질감), 영상(Gemini 3.1 pro, 슬라이딩 물리 엔진)
- **입력 프롬프트(원문):** `A close-up cinematic shot continuing the scene from http://mong.or.kr/contents/cut_01_02.png A cinematic, low-angle tracking shot at desk level in a dark, moody South Korean office. An upright, sleek silver metallic beverage can smoothly slides across the surface of a dark wooden desk, gradually decelerating to a gentle stop. The camera slightly tracks the sliding can. The bold, modern text "OVERTIME" is clearly printed on the side of the can. The background is intentionally out of focus (shallow depth of field), revealing a blurred mechanical keyboard, tangled mouse cords, and sticky notes illuminated by a cold blue monitor light. The metallic surface of the sliding can dynamically reflects the blue screen light as it moves. Ultra-photorealistic, 8k, realistic physics of sliding and friction. No hands are visible.`
- **동영상 프롬프트:** 
`[IMAGE ANCHOR] A highly detailed, photorealistic wide shot of a cylindrical brushed silver aluminum beverage can lying perfectly flat on its side on a dark wood-grain desk. The can has a clean, bare-metal finish with visible horizontal hairline texture. Printed boldly on the side facing the camera is the word "OVERTIME" in a stark, black, wide sans-serif font. The pull-tab end of the can is visible on the right side. The background features a dark, moody office environment at night, lit by the cold blue ambient glow of a computer monitor. An out-of-focus mechanical keyboard is visible behind the can, along with sticky notes on the monitor bezel. The lighting creates a dramatic contrast, with a strong cool blue highlight running along the top edge of the metallic can. [ACTION] A human hand briefly enters the frame from the top left and gives the can a swift push. The can then slides rapidly from left to right across the dark wooden desk. As it slides, the can rotates smoothly on its longitudinal axis, causing the "OVERTIME" text to spin around the cylinder. The sliding motion is fast at first, then gradually decelerates, coming to a smooth stop near the right side of the frame. [STYLE & CAMERA] Cinematic tracking shot. The camera follows the can as it slides across the desk. Shallow depth of field keeps the can in sharp focus while the background elements (keyboard, monitor) remain beautifully blurred with blue bokeh. Ultra-realistic physics of sliding and rolling. High resolution, 8k, photorealistic textures, moody cinematic lighting.`
- **결과 요약:** 프레임 안으로 들어오는 캔의 액션 확보
- **파일명:** `cut_02_01.png`, `cut_02_01.mp4`

### [Cut 2-2] 캔 정지 및 브랜드 노출 - ok

- **길이:** 4초 | **목표 메시지:** 제품명 'OVERTIME'의 시각적 각인
- **화면 구성:** [구도] 익스트림 매크로 샷 / [피사체] 멈춰 선 캔의 라벨 / [배경] 흐릿한 코딩 화면 / [텍스트] 'OVERTIME' 선명한 라벨링
- **내레이션:** "...무엇입니까?"
- **사용 도구:** 이미지(GPT-5), 영상(Gemini 3.1, Focus-in 모션)
- **입력 프롬프트(원문):** `Extreme macro shot. The cylindrical brushed silver aluminum can slides and comes to an abrupt, hard stop next to a laptop. Immediately upon stopping, the camera dynamically pulls focus onto the crisp, black 'OVERTIME' typography. The can is heavily encrusted with hyper-realistic ice crystals and condensation.`
- **동영상 프롬프트:**
`A cinematic 8k single-take shot of a slender, horizontally elongated brushed silver aluminum can sliding extremely fast from the left across a dark wooden desk and coming to a sudden, hard stop. The can is covered in hyper-realistic frost, sharp ice crystals, and water condensation, with the bold black text 'OVERTIME' printed centered on its side. Immediately upon stopping, the camera executes a single, perfectly smooth, continuous zoom-in directly onto the 'OVERTIME' logo. The entire word 'OVERTIME' must remain 100% visible on the screen at all times, never getting cut off. The camera movement is perfectly steady with absolutely no zoom-out, bouncing, or stuttering. The background is a moody, heavily blurred dark office illuminated by the cool blue glow of a computer monitor, with photorealistic lighting and shallow depth of field.`
- **결과 요약:** 포커스 인을 통한 제품명 각인 비주얼 완성
- **파일명:** `cut_02_02.png`, `cut_02_02.mp4`

### [Cut 3-1] 캔을 움켜쥐는 손 - ok

- **길이:** 4초 | **목표 메시지:** 호의를 받아들이는 주체적 액션
- **화면 구성:** [구도] 주인공 POV 샷 / [피사체] 캔을 꽉 쥐는 손 / [배경] 키보드 / [텍스트] 없음
- **내레이션:** "대한민국에서 성실한 사람으로 산다는 것,"
- **사용 도구:** 이미지(GPT-5, 서리 질감), 영상(Gemini 3.1)
- **입력 프롬프트(원문):** `Extreme close-up macro shot. A brushed bare-metal silver aluminum can sits perfectly still. The word "OVERTIME" is printed in bold italic black sans-serif capital letters. A male right hand grips the can from the side. Fingers wrapped around naturally...`
- **동영상 프롬프트:** 
`A first-person perspective (POV) shot. A photorealistic, tall, slender brushed silver aluminum can stands perfectly upright on a dark wooden desk. The can is heavily covered in hyper-realistic frost, sharp ice crystals, and water condensation. The bold black text 'OVERTIME' is printed vertically on the can't surface. In the background, there is a heavily blurred, moody office setting with glowing blue computer monitors displaying lines of code.  A male right hand, wearing a dark black sleeve, enters the frame from the right side. The hand moves smoothly and realistically, reaching out and firmly gripping the cold can. The fingers wrap naturally around the metallic surface. The can and the 'OVERTIME' typography must remain perfectly sharp, static, and undistorted during the hand's movement. Cinematic lighting with a cool blue hue from the monitors, 8k resolution, photorealistic, shallow depth of field.`
- **프롬프트 수정 로그:** [전] 손과 캔의 부자연스러운 조화 -> [후] 캔의 비율과 고정된 텍스트 앵글을 강제하여 자연스러운 움켜짐 묘사
- **결과 요약:** 캔을 잡는 손의 안정적인 움켜짐 씬 확보
- **파일명:** `cut_03_01.png`, `cut_03_01.mp4`

### [Cut 3-2] 동료의 따뜻한 미소

- **길이:** 4초 | **목표 메시지:** 지친 밤의 연대감 전달
- **화면 구성:** [구도] 미디엄 샷 / [피사체] 파티션 너머의 동료 / [배경] 앰버 조명 사무실 / [텍스트] 없음
- **내레이션:** "동기야, 우리 이번에 퇴근하자."
- **사용 도구:** 이미지(GPT-5), 영상(Gemini 3.1, 따뜻한 웜톤 라이팅)
- **입력 프롬프트(원문):**
`An over-the-shoulder shot in a dimly lit office at night. A young South Korean woman (late 20s, dark business blazer, long dark wavy hair) leans over a cubicle partition, smiling warmly at a seated male colleague seen from behind (wearing a dark navy knit sweater). In her right hand, she holds a sleek, brushed silver aluminum can with "OVERTIME" printed vertically in bold black text. Her left hand is open in a gentle, welcoming gesture. The scene features a cinematic lighting contrast: cool blue light from a computer monitor in the foreground against a heavily blurred background of warm amber hallway lights. 8k, ultra-photorealistic, shallow depth of field.`
- **동영상 프롬프트:**
`A cinematic over-the-shoulder video shot in a dark office at night. A South Korean woman in a dark blazer leans over a partition, warmly smiling and speaking to a seated male colleague seen from behind. She offers him a sleek silver aluminum can with "OVERTIME" printed vertically in black, making a gentle, encouraging hand gesture. The video captures lifelike, smooth micro-expressions and natural conversational movements. The lighting heavily contrasts the cool blue glow of the foreground computer screen with the deeply blurred, warm amber bokeh of the office background. 8k, photorealistic, seamless motion.`
- **결과 요약:** 동료의 따뜻한 미소와 격려 제스처 확보
- **파일명:** `cut_03_02.png`, `cut_03_02.mp4`

### [Cut 4-1] 함께 걷는 퇴근길

- **길이:** 8초 | **목표 메시지:** 해방감과 브랜드 최종 각인
- **화면 구성:** [구도] 하이 앵글 줌아웃 / [피사체] 나란히 걷는 두 동료 / [배경] 네온 젖은 새벽 거리 / [텍스트] 붓글씨 로고 레이어 합성
- **내레이션:** (남)"풀려라 야근! 풀려라 피로!" (여)"우리의 퇴근은, 오버타임!"
- **사용 도구:** 영상(Gemini 3.1), 오디오(Suno v4, 희망찬 오케스트라)
- **입력 프롬프트(원문):** `High-angle wide shot, two young office workers with backpacks walking side by side down a wet, neon-lit Seoul city street at dawn. The camera slowly zooms out as they walk away, capturing the reflections of city lights on the puddles. Cinematic, hopeful atmosphere, 4k.`
- **동영상 프롬프트:** 
`A cinematic 8k video featuring a seamless transition between two shots. It opens with a brief, photorealistic first-person close-up of a hand holding a frosty, brushed silver aluminum can with 'OVERTIME' printed on it, set against a blurred, neon-lit street background.  The scene then cuts to a cinematic, high-angle wide shot at dawn, showing a young South Korean man (wearing a dark navy knit sweater and a backpack) and woman (wearing a dark business casual blazer and a backpack) walking side-by-side away from the camera down a dark, wet, narrow alleyway. The man has his hand resting gently on the woman's shoulder. The camera slowly and smoothly zooms out as they walk forward. Vibrant neon signs and a warm streetlamp reflect beautifully on the rain-slicked asphalt, creating a shallow depth of field.  As the camera continues to pull back, a large, dynamic black-and-gold brush-calligraphy logo 'OVERTIME' fades in over the center of the screen, followed by smaller Korean text ("우리의 퇴근은, 오버타임! 풀려라 야근! 풀려라 피로!") appearing below it. The overall atmosphere is highly atmospheric, emotional, and hopeful.`
- **결과 요약:** 새벽 거리로 나서는 두 사람의 여운 있는 엔딩
- **파일명:** cut_04_01.png, `cut_04_01.mp4`

## 3. 최종 영상 스펙

- **파일명:** `OVERTIME_branding_final.mp4` | **길이:** 30초 | **인코딩:** H.264 / AAC | **통합 편집:** CapCut

