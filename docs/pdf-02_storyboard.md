# 🎬 AI-Driven Advertising Storyboard: OVERTIME (30s)

> **캠페인명:** "지구에서 살아남는 K-직장인의 우정" (박카스 광고 오마주)
> **총 영상 길이:** 30초 (몽타주 기법 활용)
> **최종 영상 스펙:** 1080p / 30fps / H.264 / AAC 
> **사용 도구 체인:** GPT 모델(이미지) ➔ Gemini Pro 3.1 ➔ Sora 2 ➔ TTS-1 ➔ Suno v4 ➔ 영상 편집 툴 

---

## 🛠️ 파이프라인 리스크 대응 및 의사결정 전략
* **현실적 제약:** Sora 2 비디오 생성 시 1회 최대 생성 분량이 4초로 제한됨.
* **해결 방안:** 광고의 리듬감을 살리는 몽타주 기법(Montage)을 도입하여 3~4초 단위의 컷으로 분할하여 생성 효율성과 시각적 다이내믹함을 확보함.

---

## 🎬 Part 1: 대한민국에서 개발자로 산다는 것 (총 7초)

### [Cut 1-1] 인물 초근접 클로즈업
* **컷 번호 / 길이:** Cut 1-1 / 3초 (00:00 ~ 00:03)
* **목표 메시지:** 야근에 지친 K-직장인의 무거운 피로감 전달
* **화면 구성:**
  * **구도:** 익스트림 클로즈업 샷 (Extreme Close-up)
  * **피사체:** 멍하니 노트북을 응시하는 2030 남성 개발자의 눈과 안경
  * **배경:** 불 꺼진 어두운 사무실
* **내레이션 (TTS-1):** "대한민국에서 개발자로 산다는 것." (담담하고 지친 톤)
* **사용 도구 및 목적:** 정지 이미지에 미세한 눈 깜빡임 및 초점 흔들림 구현
* **프롬프트 및 에셋:**
  * **원본(이미지) 생성 프롬프트:**
    ```text
    Extreme close-up of a tired South Korean male software engineer's eyes, cold blue laptop screen light reflecting deeply on his glasses, dark office background, subtle micro-movements, shallow depth of field, cinematic lighting, 4k.
    ```
  * **동영상 생성 프롬프트:**
    ```text
    A highly detailed, cinematic extreme close-up shot of a tired South Korean male software engineer in his late 20s, staring blankly at a laptop screen in a completely dark office at night. The cold blue light of the coding screen is intensely reflected on the lenses of his glasses, obscuring his eyes slightly and emphasizing his burnout. His head is supported by his hand, weary expression, dark circles under his eyes, realistic skin texture with sweat. The background is a vast, dark open-plan office with only distant, blurred LED indicators. Lighting is dark and moody with a dramatic contrast between the cold blue light and shadows. Shot on Sony A1, 16:9 aspect ratio, 8k resolution, ultra-photorealistic, shallow depth of field.
    ```
  * **파일명:** `cut_01_01.png`, `cut_01_01.mp4`

### [Cut 1-2] 데스크 인서트 샷
* **컷 번호 / 길이:** Cut 1-2 / 4초 (00:03 ~ 00:07)
* **목표 메시지:** 밤샘 코딩 노동의 시각적 묘사
* **화면 구성:**
  * **구도:** 매크로 로우앵글 샷 (Macro Low-angle)
  * **피사체:** 기계식 키보드 위에서 힘없이 코드를 타이핑하는 손가락들
  * **배경:** IDE 소스코드가 빽빽한 모니터 화면 하단부
* **오디오/효과음 (SFX):** 타닥타닥... 무겁고 느린 기계식 키보드 타건 소리
* **사용 도구 및 목적:** 손가락의 타이핑 움직임을 사실적인 물리 법칙에 맞게 구현
* **프롬프트 및 에셋:**
  * **원본(이미지) 생성 프롬프트:**
    ```text
    Close-up macro shot of hands slowly typing lines of code on a mechanical keyboard, glow from the monitor illuminating the fingers, shallow depth of field, cinematic dark office ambience, realistic finger joint movements, 4k.
    ```
  * **동영상 생성 프롬프트:**
    ```text
    Maintain the consistent appearance of the South Korean male developer's hands and clothing from the original image. The fingers should move naturally and rhythmically on the mechanical keyboard, performing a focused typing action. Add a subtle, realistic flickering light effect from the monitor onto the hands and the desk surface to enhance the dark office atmosphere. Ensure the motion is smooth, steady, and perfectly matches the focused mood.
    ```
  * **파일명:** `cut01_02.png`, `cut01_02.mp4`

---

## 🎬 Part 2: 당신의 야근 회복제는 무엇입니까? (총 8초)

### [Cut 2-1] 캔 음료 미끄러짐 (액션 컷)
* **컷 번호 / 길이:** Cut 2-1 / 4초 (00:07 ~ 00:11)
* **목표 메시지:** 예상치 못한 동료의 호의가 들어오는 반전 시점
* **화면 구성:**
  * **구도:** 책상 표면과 수평을 이루는 트래킹 샷 (Low-profile Tracking Shot)
  * **피사체:** 어두운 목재 책상 위를 스르륵 미끄러져 오는 메탈릭 캔 음료
  * **배경:** 주변의 헝클어진 마우스 선과 서류들 (아웃포커싱)
* **내레이션 (TTS-1):** "당신의 야근 회복제는..."
* **사용 도구 및 목적:** 마찰력과 감속이 들어간 캔의 미끄러짐 물리 현상을 어색함 없이 구현
* **프롬프트 및 에셋:**
  * **원본(이미지) 생성 프롬프트:**
    ```text
    A cinematic, low-angle tracking shot at desk level in a dark, moody South Korean office. An upright, sleek silver metallic beverage can smoothly slides across the surface of a dark wooden desk, gradually decelerating to a gentle stop. The camera slightly tracks the sliding can. The bold, modern text "OVERTIME" is clearly printed on the side of the can. The background is intentionally out of focus (shallow depth of field), revealing a blurred mechanical keyboard, tangled mouse cords, and sticky notes illuminated by a cold blue monitor light. The metallic surface of the sliding can dynamically reflects the blue screen light as it moves. Ultra-photorealistic, 8k, realistic physics of sliding and friction. No hands are visible.
    ```
  * **동영상 생성 프롬프트:**
    ```text
    A photorealistic tall aluminum can lying perfectly flat on its side on a dark wood-grain desk. The can has brushed bare-metal silver finish with visible hairline texture — no label, no wrapper. The word "OVERTIME" is printed in bold italic black sans-serif capital letters, centered on the can body. The pull-tab faces right. Behind the desk: an out-of-focus keyboard and glowing monitor casting cool blue ambient light. Dark, cinematic, late-night gaming atmosphere.

    — MOTION RULES (CRITICAL) —

    The can slides from left to right at extreme speed across the desk.

    ROTATION IS ABSOLUTELY FORBIDDEN:
    - The can must NOT roll.
    - The can must NOT spin.
    - The can must NOT rotate on any axis.
    - The can must NOT wobble or tilt.
    - Imagine the can is FROZEN INSIDE A FLAT RECTANGULAR ICE BLOCK that slides across the desk. The ice block cannot roll — therefore the can cannot roll. The can's orientation is permanently locked as if welded to a flat tray.
    - The "OVERTIME" text must face the camera at the exact same angle in EVERY SINGLE FRAME from start to finish.

    TEXT PRESERVATION (CRITICAL):
    - The word "OVERTIME" must remain IDENTICAL in every frame.
    - Same font, same size, same position, same letter shapes.
    - No warping, no smearing, no morphing, no distortion.
    - The text is physically ENGRAVED into the metal — it cannot change shape or disappear.
    - Treat "OVERTIME" as a FIXED TEXTURE permanently baked onto the can surface. It never changes.

    — CAMERA AND BLUR —

    Camera tracks the can in perfect sync (follow-cam), keeping the can razor-sharp at all times. The entire background — desk, keyboard, monitor — becomes extreme horizontal motion blur streaks due to the speed. The dramatic contrast between the sharp can and violently blurred background is the hero visual.

    Blue monitor light streaks across the brushed metal surface during the slide. No hands, no people.

    8K, photorealistic, cinematic motion-blur, professional energy drink product commercial.
    ```
  * **파일명:** `cut_02_01.png`, `cut_02_01.mp4`

### [Cut 2-2] 캔 정지 및 브랜드 노출
* **컷 번호 / 길이:** Cut 2-2 / 4초 (00:11 ~ 00:15)
* **목표 메시지:** 제품명 'OVERTIME'의 시각적 각인
* **화면 구성:**
  * **구도:** 익스트림 매크로 샷 (Extreme Macro Shot)
  * **피사체:** 주인공 노트북 바로 옆에 '탁' 멈춰 서는 캔 음료 (성에와 물방울 맺힘)
  * **배경:** 정지한 캔 뒤로 흐릿하게 보이는 코딩 화면
* **내레이션 (TTS-1):** "...무엇입니까?"
* **사용 도구 및 목적:** 표면에 차가운 물방울이 맺힌 캔의 하이퍼 리얼리스틱 질감 표현 및 선명한 텍스트 렌더링 고정
* **프롬프트 및 에셋:**
  * **원본(이미지) 생성 프롬프트:**
    ```text
    Extreme close-up macro shot of a metallic energy drink can stopping perfectly on a desk. The can has distinct embossed text "OVERTIME" on its label, covered in cold crisp condensation droplets. Neon blue and orange rim lighting, crisp sharp focus, 4k.
    ```
  * **동영상 생성 프롬프트:**
    ```text
    [SCENE CONTINUITY & ANCHOR] > This video is a direct continuation of the sliding can shown in the previous video (cut_02_01.mp4). The video must start exactly from the visual state of the reference image ([http://mong.or.kr/contents/cut_02_01.png](http://mong.or.kr/contents/cut_02_01.png)) where the tall silver aluminum can lies perfectly flat on its side on a dark wood-grain desk with the word "OVERTIME" centered. As it slides and settles, it transitions seamlessly into the highly-detailed, frosty, condensation-covered state of the reference image ([http://mong.or.kr/contents/cut_02_02.png](http://mong.or.kr/contents/cut_02_02.png)) at its final stopping point.

    [ACTION & STOP] > The metallic can slides rapidly from left to right across the desk and comes to a sudden, precise, and solid stop right next to an out-of-focus keyboard and glowing monitor.

    [PHYSICS & ROTATION LOCK] > ROTATION IS ABSOLUTELY FORBIDDEN: The can must NOT roll, spin, rotate on any axis, wobble, or tilt. It stays perfectly flat on its side the entire time. The "OVERTIME" text must face the camera at the exact same angle in EVERY SINGLE FRAME.

    [TEXT PRESERVATION] > The bold italic black sans-serif capital letters "OVERTIME" must remain IDENTICAL, razor-sharp, and completely undistorted in every single frame. Treat "OVERTIME" as an engraved, FIXED TEXTURE permanently baked onto the can surface. No warping, smearing, morphing, or disappearing.

    [CAMERA, BLUR, & LIGHTING] > A follow-cam tracks the can in perfect sync, keeping the can razor-sharp. The entire background (desk, keyboard, glowing monitor casting cool blue light) becomes extreme horizontal motion blur streaks due to the speed. Cool blue and ambient orange light streaks across the brushed metal surface and water droplets during the slide. No hands, no people.

    8K, photorealistic, cinematic motion-blur, professional energy drink product commercial.
    ```
  * **파일명:** `cut02_02.png`, `cut02_02.mp4`

---

## 🎬 Part 3: 좋아하는 코딩을 계속하려면 (총 8초)

### [Cut 3-1] 캔을 움켜쥐는 손
* **컷 번호 / 길이:** Cut 3-1 / 4초 (00:15 ~ 00:19)
* **목표 메시지:** 호의를 받아들이고 인지하는 주체적인 액션
* **화면 구성:**
  * **구도:** 주인공 시점 샷 (POV / Close-up)
  * **피사체:** 뻗어 나와 책상 위 오버타임 캔을 꽉 쥐는 남성의 손
  * **배경:** 블러 처리된 코딩 IDE 화면
* **내레이션 (TTS-1):** "좋아하는 코딩을 계속하려면,"
* **사용 도구 및 목적:** 물체를 인지하고 자연스럽게 손가락으로 감싸 쥐는 인간의 연동 모션 구현
* **프롬프트 및 에셋:**
  * **원본(이미지) 생성 프롬프트:**
    ```text
    Cinematic close-up shot of the same South Korean male software engineer in his late 20s from the previous scenes, sitting at his desk in a completely dark office at night. His weary hand reaches out to touch or pick up a sleek, tall aluminum beverage can resting on the dark wood-grain desk right next to his laptop. The brushed bare-metal can is perfectly upright, covered in cold, crisp condensation droplets and fine frost. The bold, sans-serif capital letters "OVERTIME" are precisely centered on the can's body, razor-sharp, perfectly legible, and undistorted. Dramatic neon blue and orange rim lighting highlights the condensation, the metallic texture of the can, and the contours of his hand. The background features a heavily blurred keyboard and a glowing monitor casting cool blue ambient light. Ultra-photorealistic, 8K resolution, dramatic late-night gaming office atmosphere, professional cinematic commercial aesthetic, shallow depth of field.
    ```
  * **동영상 생성 프롬프트:**
    ```text
    Extreme close-up macro shot. A brushed bare-metal silver aluminum can with visible hairline texture — no label, no wrapper — sits perfectly still on a dark wood-grain desk. The word "OVERTIME" is printed in bold italic black sans-serif capital letters, centered on the can body. The text is razor-sharp, fully legible, and perfectly undistorted.

    The can surface is covered in cold crisp condensation droplets that catch the light. Tiny water beads cling to the brushed metal, some dripping slowly.

    A male right hand grips the can from the side. The hand has:
    - Light ivory / pale beige skin tone, slightly cool-toned from blue monitor light
    - Subtle veins and tendons visible on the back of the hand
    - Clean, short-trimmed fingernails with no polish
    - Slim but not skinny fingers, natural masculine proportions
    - A dark charcoal / black long-sleeve shirt covering the wrist, with the sleeve edge just reaching the base of the palm

    The grip is firm but relaxed — fingers wrapped around the can naturally, thumb on one side, four fingers on the other, as if the person just grabbed it mid-work.

    Background: a coding screen with syntax-highlighted code (blue, green, orange text on dark background) is visible but heavily blurred (shallow depth of field, f/1.4 bokeh). Soft bokeh circles from small LED indicator lights float in the deep background. A dark office environment at night.

    Lighting: Cool blue ambient light from the monitor illuminates the hand and can from the left side. Subtle warm rim light (neon orange or amber) outlines the can edge and knuckles from the right, creating dramatic two-tone separation. Deep shadows fill the spaces between fingers.

    The can is PERFECTLY STILL. No motion. No blur. Static frame.
    The "OVERTIME" text must remain IDENTICAL, sharp, and fully readable — treat it as a fixed engraving on the metal surface.

    8K, photorealistic, hyper-realistic condensation texture, cinematic shallow depth of field, professional energy drink product commercial aesthetic.
    ```
  * **파일명:** `cut_03_01.png`, `cut_03_01.mp4`

### [Cut 3-2] 동료의 따뜻한 미소
* **컷 번호 / 길이:** Cut 3-2 / 4초 (00:19 ~ 00:23)
* **목표 메시지:** 지친 밤을 위로하는 K-직장인의 진한 연대감 전달
* **화면 구성:**
  * **구도:** 미디엄 샷 (Medium Shot)
  * **피사체:** 어두운 파티션 너머 서서 따뜻하게 미소 짓는 여성 동료
  * **배경:** 은은한 웜 앰버(Warm Amber) 조명이 감도는 사무실 통로
* **대사 (TTS-1 오버랩):** "동기야, 우리 이제 퇴근하자." (위트 있고 다정하게 던지는 톤)
* **프롬프트 및 에셋:**
  * **원본(이미지) 생성 프롬프트:**
    ```text
      [STYLE REFERENCE - DO NOT GENERATE, USE AS STYLE GUIDE]
      Cinematic late-night office scene. East Asian male subject,
      warm beige skin tone, realistic photographic texture,
      cold blue monitor lighting mixed with warm amber accent.
      
      SHIRT: Deep navy blue knit sweater / long-sleeve top,
      color: #1a2340 ~ #1e2a4a, soft fabric texture,
      reflecting cold blue monitor light on surface. 4K, shallow DOF.
      
      CAN DESCRIPTION (MUST MATCH EXACTLY):
    - Standard aluminum energy drink can (not slim — regular proportion)
    - Surface: brushed silver-grey aluminum with realistic 
      condensation water droplets all over
    - Label text: "OVERTIME"
    - Font: Bold italic condensed sans-serif, 
      heavy weight, slightly right-leaning italic angle
      (similar to Impact Italic or Bebas Neue Italic style)
    - Letter color: pure black (#000000), flat, no gradient
    - Text placement: centered horizontally on can body, 
      large and dominant
    - Lighting on can: left side cold blue (#4a90d9), 
      right side warm amber (#c87941), 
      creating metallic gradient across surface

    [GENERATE THIS SCENE]

    Medium shot. South Korean female colleague, late 20s,
    business casual dark blazer, leaning over office partition at night.
    Warm genuine smile, subtle encouraging hand gesture.

    SKIN: match reference — warm beige, photorealistic texture.

    SHIRT REFERENCE (male subject in background or implied):
    Deep navy blue knit sweater (#1a2340),
    cold blue monitor light reflecting off fabric surface.

    LIGHTING: warm amber halo from hallway lights (#F5A623),
    residual cold blue from distant monitors — emotional warm transition.

    Background: blurred dark office corridor, amber bokeh,
    dark partitions. Cinematic 4K, Korean commercial film aesthetic,
    Sony A7IV quality. Mood: tired solidarity, late-night warmth.
    ```
  * **동영상 생성 프롬프트:**
    ```text
    Prompt: [IMAGE ANCHOR] Use the provided reference image (cut_03_02.png) strictly as the first frame. Maintain the exact over-the-shoulder composition, characters, clothing, and lighting.

    [ACTION & EMOTION] Medium shot. The South Korean female colleague leaning over the office partition smiles warmly and genuinely at the male developer. Her expression is full of empathy and comfort. She performs a very subtle, soft nod and a gentle, inviting movement with her open left hand, visually matching the comforting sentiment "let's go home." Her long dark hair shifts naturally with her delicate movements. In the foreground, the out-of-focus male colleague (back to camera) subtly lowers his shoulders, releasing his tension.

    [TEXT & OBJECT INTEGRITY] The female colleague is holding the silver beverage can. CRITICAL: The black text "OVERTIME" on the can must remain perfectly sharp, identical in font, and completely undistorted throughout the slight movements of her hand. It must not warp or morph.

    [LIGHTING & CINEMATOGRAPHY] Keep the camera relatively steady with only a slight, cinematic handheld breathing effect. Preserve the dramatic dual-lighting: the cold blue monitor light illuminating the foreground and the warm, comforting amber bokeh in the blurred background hallway. The warm light should beautifully highlight her face and the metallic can. Ultra-photorealistic, lifelike micro-expressions, 8k resolution, cinematic shallow depth of field.
    ```
  
  * **파일명:** `cut_03_02.png`, `cut_03_02.mp4`

---

## 🎬 Part 4: 심플 엔딩 (제품 컷 활용) (총 3초)

### [Cut 4-1] 브랜드 캠페인 슬로건 및 여운 마무리
* **컷 번호 / 길이:** Cut 4-1 / 3초 (00:23 ~ 00:26)
* **목표 메시지:** 캠페인 슬로건 각인 및 깔끔한 엔딩
* **화면 구성:**
  * **구도:** 제품 정물 컷 (Static Product Shot)
  * **피사체:** Part 2~3에서 등장한 성에 맺힌 'OVERTIME' 캔의 클로즈업 고정 컷 (`cut02_02.png` 이미지 활용)
  * **자막(타이포그래피):** 화면 하단 중앙에 신뢰감 있는 굵은 고딕 폰트로 슬로건 출력  
    `"좋아하는 일을 계속하려면, 이런 힘이 필요하니까"`
* **오디오 및 효과음:** * **내레이션 (TTS-1):** `"풀려라 야근! 풀려라 피로!"` (확신에 찬 박카스 톤)
  * **BGM (Suno v4):** 묵직하고 희망찬 오케스트라 또는 어쿠스틱 기반의 엔딩 사운드와 함께 페이드아웃
* **제작 방식 (스펙 변경 대응):** * Sora 2로 추가 영상 생성을 하지 않고, 기 확보된 선명한 제품 컷 정지 이미지(`cut02_02.png` 등)를 타임라인에 배치합니다.
  * 영상 편집 프로그램(프리미어 프로, 캡컷 등)에서 해당 이미지 위에 자막(텍스트 트랙)을 얹고, 오디오 소스들을 싱크에 맞게 올려 3~4초간 재생되도록 구성하여 간편하고 완성도 높게 마무리합니다.


---

## 📝 프롬프트 개선 로그 (Prompt Engineering Log)

* **대상 씬:** Cut 1-1 (인물 초근접 클로즈업)
* **수정 전 프롬프트:** `A South Korean developer crying and extremely stressed in a dark office, holding his head, very sad, 8k.`
* **발생한 문제점:** 'stressed', 'crying' 같은 감정 단어를 직접 사용하자 AI가 이를 지나치게 과장 연산하여, 마치 호러 영화의 괴물처럼 얼굴 근육이 일그러지며 기괴하게 통곡하는 얼굴을 출력함. 리얼리스틱 오피스 광고의 톤앤매너를 완전히 훼손함.
* **수정 후 프롬프트:** `Extreme close-up of a tired South Korean male software engineer's eyes, cold blue laptop screen light reflecting deeply on his glasses, dark office background, subtle micro-movements, shallow depth of field...`
* **의도 및 개선 효과:** 직설적인 감정 단어를 제거하는 대신 **'staring blankly(멍하니 응시)'**, **'subtle micro-movements(미세한 움직임)'**, **'screen light reflecting on glasses(안경에 반사되는 모니터 빛)'**와 같은 정교한 환경/시각적 묘사로 대체함. 그 결과, 근육 왜곡 없이 현대 직장인 특유의 세련되고 묵직한 '번아웃/피로감'을 시네마틱하게 연출하는 데 성공함.

---

## 🗂️ 도구 접근성 및 백업 도구 리스트 (Accessibility Plan)
특정 도구의 트래픽 마비, 크레딧 오링, 플랜 대기열 병목 현상 발생 시 파이프라인 중단을 방지하기 위해 상호 대체 체인을 명시합니다.

* **이미지 파트 (키 비주얼 고정):** GPT 모델(DALL-E 3) ➔ `대체:` Midjourney v6 (Style Reference `--sref` 활용)
* **비디오 파트 (4초 컷 스왑):** Sora 2 ➔ `대체:` Runway Gen-3 Alpha (Image-to-Video 모드) 또는 Kling AI
* **음성 파트 (내레이션/대사):** OpenAI TTS-1 ➔ `대체:` ElevenLabs (Korean Neutral Narrative voice)
----
----
이 이후는 폐기된 문서

## 1. 캠페인 개요 (Campaign Overview)
* **브랜드명:** 아스트로브루 (AstroBrew)
* **캠페인 슬로건:** "말하지 않아도 우주(宇宙)"
* **기획 의도:** 대한민국 국민에게 가장 친숙한 오리온 초코파이 '정(情)' 광고를 B급 감성으로 패러디. 최첨단 우주선 공간과 짠내 나는 K-직장인의 애환을 무중력 상태의 시각적 오류(엉성함)와 결합하여 대중적 인지와 웃음을 유발하는 숏폼 바이럴 광고 설계.
* **핵심 메시지:** "우주에서도 통하는 진한 우정, 아스트로브루."

---

## 2. 씬별 상세 설계 (Scene-by-Scene Design)

### 📌 Scene 1: 우주 직장인의 절망 (기)
* **씬 길이:** 10초
* **목표 메시지:** 최첨단 공간 속 짠내 나는 상황의 대조를 통한 흥미 유발
* **화면 구성:** 우주선 내 허름한 사무실. 와이셔츠 차림의 피곤에 찌든 직장인 남자 A가 무중력 상태로 허공에 **거꾸로 대롱대롱 매달린 채** 모니터를 보며 머리를 쥐어뜯고 있다. 그의 주변에는 결재 서류와 서류봉투들이 무중력 상태로 둥둥 떠다닌다.
* **자막/카피:** (화면 하단 자막) "야근 300시간 째... 지구에 가고 싶다."
* **사운드 (BGM/SFX):** 무겁고 우울한 분위기의 저음 패드 음악 / 기계적인 키보드 타자 소리 효과음
* **사용 도구 및 목적:** * 이미지: Gemini (키 비주얼 - 거꾸로 매달린 우주 직장인 생성)
  * 비디오: Luma Dream Machine (서류가 떠다니는 느린 모션 구현)
* **입력 프롬프트(원문 예시):** `Inside a futuristic spaceship office, zero gravity, floating papers and documents. A tired Korean office worker man wearing a messy white dress shirt and tie is hanging upside down in the air, looking stressed out at a computer monitor. Cinematic lighting, dramatic shadows, photorealistic, B-grade comedy tone.`
* **출력 결과 요약:** 웅장한 우주선 배경과 볼품없이 떠 있는 직장인의 대비가 확실한 컷 확보.
* **생성 파일명:** `scene01_upside_down_worker.mp4`

---

### 📌 Scene 2: 무중력 전우애의 건넴 (승)
* **씬 길이:** 10초
* **목표 메시지:** 원작의 핵심 클리셰인 '말없이 건네는 위로' 오마주
* **화면 구성:** 동기인 남자 B가 헝클어진 정장 차림으로 허공에서 개구리헤엄을 치며 엉성하고 우스꽝스럽게 다가온다. 아무 말 없이 남자 A의 어깨를 툭 치더니, 은쟁반 위 허공에서 영롱하게 보라색 성운 빛을 내며 회전하는 '아스트로브루 구슬(액체 구체)'을 손가락으로 툭 튕겨 A에게 보낸다.
* **자막/카피:** (대사 없음 - 진한 전우애와 위로의 눈빛 교환)
* **사운드 (BGM/SFX):** **♬ (원작 멜로디 오마주) "말하지 않아도 알~아~요~"** (코믹하고 아련한 오르골 리메이크 톤 버전)
* **사용 도구 및 목적:**
  * 이미지: Gemini (개구리헤엄을 치는 정장 남성과 떠다니는 보라색 액체 구슬 생성)
  * 비디오: Kling AI (액체 구슬이 스르륵 미끄러지듯 이동하는 모션 제어)
* **입력 프롬프트(원문 예시):** `A Korean man in a business suit is awkwardly swimming through the air in zero gravity inside a spaceship. He gently pushes a glowing, iridescent purple liquid sphere that sparkles like a nebula toward another man. Emotional and funny friendship tone.`
* **출력 결과 요약:** 코믹한 개구리헤엄과 극도로 영롱한 아스트로브루 제품의 대비 성공.
* **생성 파일명:** `scene02_floating_brew.mp4`

---

### 📌 Scene 3: 눈물 젖은 우주 (전)
* **씬 길이:** 12초
* **목표 메시지:** 무중력 고증을 개그로 승화시킨 펀치라인 (B급 감성 절정)
* **화면 구성:** 남자 A가 허공에 떠온 보라색 음료 구슬에 입술을 대고 '앙' 베어 문다. 입안에서 화려하게 성운 조각들이 터지는 연출이 지나간 후, 감동과 위로에 복받쳐 엉엉 오열한다. 이때 무중력 상태라 눈물이 흐르지 못하고, **A의 눈가에 거대한 투명 물풍선처럼 물방울이 덕지덕지 뭉쳐서 커지는** 슬프고도 웃긴 클로즈업 샷.
* **자막/카피:** (화면 중앙 궁서체 자막) "눈물 젖은 우주를 마셔봤는가."
* **사운드 (BGM/SFX):** 감동적인 오르골 음악이 피크를 찍다가 눈물이 뭉칠 때 '띠용~' 혹은 물방울 커지는 코믹한 뿅 효과음 삽입.
* **사용 도구 및 목적:**
  * 이미지: Gemini (눈가에 거대한 물방울이 뭉친 채 울고 있는 정장 남성 매크로 클로즈업)
  * 비디오: Luma Dream Machine (눈물 물풍선이 출렁거리며 커지는 특수 효과 모션 구현)
* **입력 프롬프트(원문 예시):** `Macro close-up of a crying Korean man's face in zero gravity. Because of zero gravity, his big tears do not fall but accumulate around his eyes, forming a wobbling, large transparent water balloon cluster on his face. Cinematic lighting, crying in emotion, funny B-grade comedy.`
* **출력 결과 요약:** 우주 고증과 B급 유머가 결합한 최고의 명장면 연출 소스 확보.
* **생성 파일명:** `scene03_space_tears.mp4`

---

### 📌 Scene 4: 우리들의 우주정(宇宙情) (결)
* **씬 길이:** 10초
* **목표 메시지:** 브랜드 슬로건 및 CTA 각인
* **화면 구성:** 감동한 두 직장인 아저씨가 서로를 꽉 부둥켜안고 무중력 사무실 한가운데서 우아하게 빙글빙글 돌고 있다. 주변의 서류들도 함께 춤추듯 돈다. 화면 중앙에 거친 붓글씨(캘리그라피) 형태로 브랜드 로고와 슬로건이 강렬하게 쾅 박힌다.
* **자막/카피:** "우주에서도 통하는 진한 우정. 아스트로브루 [AstroBrew]"
* **사운드 (BGM/SFX):** (반전) 갑자기 음악이 중후하고 장엄한 블록버스터급 승리의 오케스트라 사운드로 변환, 아주 비장하고 굵은 남성 성우의 내레이션(TTS).
* **사용 도구 및 목적:**
  * 이미지: Gemini (서로 껴안고 공중에 뜬 채 회전하는 두 정장 남성 및 메탈릭 브랜드 로고 플레이트)
  * 비디오: Kling AI (두 인물이 부드럽고 웅장하게 축을 돌며 회전하는 카메라 무빙 구현)
  * 오디오: CapCut TTS (비장한 남성 성우 보이스 탑재)
* **입력 프롬프트(원문 예시):** `Two Korean men in business shirts hugging each other tightly, slowly spinning in circles while floating in zero gravity inside a futuristic spaceship room. Epic and heroic lighting, dynamic camera spinning, triumphant atmosphere.`
* **출력 결과 요약:** 짠내 나는 브로맨스의 완성 및 브랜드 각인 장치 결합.
* **생성 파일명:** `scene04_epic_hug_logo.mp4`

---

## 3. 제약 사항 및 예산 방어 전략
1. **정지 이미지 + 패닝 기법 중심:** 인물의 격렬한 움직임은 AI 비디오 툴에서 왜곡(지그러짐) 현상이 강하므로, 인물은 포옹이나 정지 상태의 안정적 구도를 잡고 Luma/Kling 명령어로 `Slow camera pan left` 또는 `Slow orbital rotation`을 주어 크레딧 낭비를 최소화함.
2. **대체 도구 셋업:** Luma 대기열이 밀릴 경우를 대비해 1일 무료 크레딧을 주는 Kling AI 및 Runway Gen-2를 이미지-투-비디오(I2V) 대체 스택으로 상시 대기.
<<<<<<< Uㅍpdated upstream
3. **통합 편집 제약 준수:** CapCut 무료 버전을 이용하여 소스들을 컷 편집하고, 하단 자막 서체 통일, 원작 느낌의 BGM 오디오 레벨 믹싱, 엔딩 씬의 붓글씨 로고 레이어 합성만 제한적으로 수행하여 생성형 AI 소스의 순수성을 유지함.
=======ㅓ
3. **통합 편집 제약 준수:** CapCut 무료 버전을 이용하여 소스들을 컷 편집하고, 하단 자막 서체 통일, 원작 느낌의 BGM 오디오 레벨 믹싱, 엔딩 씬의 붓글씨 로고 레이어 합성만 제한적으로 수행하여 생성형 AI 소스의 순수성을 유지함.
>>>>>>> Stashed changes
