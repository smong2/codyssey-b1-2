# 🎬 [2단계] 오버타임 광고 캠페인 스토리보드

# 🎬 AI-Driven Advertising Storyboard: OVERTIME (30s)

> **캠페인명:** "지구에서 살아남는 K-직장인의 우정" (박카스 광고 오마주)
> **총 영상 길이:** 30초 (4초 생성 토큰 제약 최적화 버전)
> **최종 영상 스펙:** 1080p / 30fps / H.264 / AAC (권장)
> **사용 도구 체인:** GPT 모델(이미지) ➔ Gemini Pro 3.1(콘텍스트 조율) ➔ Sora 2(비디오 4초 컷 생성) ➔ TTS-1(음성) ➔ Suno v4(음악)

---

## 🛠️ 파이프라인 리스크 대응 및 의사결정 전략 (Token Saving Strategy)
* **현실적 제약:** Sora 2 비디오 생성 시 1회 최대 생성 분량이 4초로 제한됨.
* **해결 방안 및 의사결정:** 기존 4개 씬(7~8초)을 단일 롱테이크로 가져갈 경우 토큰 부족 및 물리 법칙 왜곡(시간이 길어질수록 AI 리소스 왜곡 심화) 리스크가 큼. 따라서 광고의 리듬감을 살리는 **몽타주 기법(Montage)**을 도입, 3~4초 단위의 정교한 8개 컷으로 해체 분할하여 생성 효율성과 시각적 다이내믹함을 동시에 확보함.

---

## 🎞️ Cut-by-Cut Details (컷별 상세 스토리보드)

### 🎬 Part 1: 대한민국에서 개발자로 산다는 것 (총 7초)

#### [Cut 1-1] 인물 초근접 클로즈업
* **컷 번호 / 길이:** Cut 1-1 / 3초 (00:00 ~ 00:03)
* **목표 메시지:** 야근에 지친 K-직장인의 무거운 피로감 전달
* **화면 구성:** * *구도:* 익스트림 클로즈업 샷 (Extreme Close-up)
  * *피사체:* 멍하니 노트북을 응시하는 2030 남성 개발자의 눈과 안경
  * *배경:* 불 꺼진 어두운 사무실
  * *텍스트:* 없음
* **내레이션 (TTS-1):** "대한민국에서 개발자로 산다는 것." (담담하고 지친 톤)
* **사용 도구 및 목적:** * `GPT 모델`: 모니터 반사광이 맺힌 사실적인 안경/눈빛 키 비주얼 생성
  * 이미지 생성 (gpt) :

* ** 수정 전 입력 프롬프트 (원문):**  `Extreme close-up of a tired South Korean male software engineer's eyes, cold blue laptop screen light reflecting deeply on his glasses, dark office background, subtle micro-movements, shallow depth of field, cinematic lighting, 4k.`

* ** 입력 프롬프트: ** `A highly detailed, cinematic extreme close-up shot of a tired South Korean male software engineer in his late 20s, staring blankly at a laptop screen in a completely dark office at night. The cold blue light of the coding screen is intensely reflected on the lenses of his glasses, obscuring his eyes slightly and emphasizing his burnout. His head is supported by his hand, weary expression, dark circles under his eyes, realistic skin texture with sweat. The background is a vast, dark open-plan office with only distant, blurred LED indicators. Lighting is dark and moody with a dramatic contrast between the cold blue light and shadows. Shot on Sony A1, 16:9 aspect ratio, 8k resolution, ultra-photorealistic, shallow depth of field.`

  * `Sora 2`: 정지 이미지에 미세한 눈 깜빡임 및 초점 흔들림 구현
* **출력 결과 요약:** 안경에 코딩 화면 푸른 빛이 반사된 채 미세하게 움직이는 지친 눈빛 확보
* **파일명:** `cut01_01_eyes_close.mp4`

#### [Cut 1-2] 데스크 인서트 샷
* **컷 번호 / 길이:** Cut 1-2 / 4초 (00:03 ~ 00:07)
* **목표 메시지:** 밤샘 코딩 노동의 시각적 시각화
* **화면 구성:** * *구도:* 매크로 로우앵글 샷 (Macro Low-angle)
  * *피사체:* 기계식 키보드 위에서 힘없이 코드를 타이핑하는 손가락들
  * *배경:* IDE 소스코드가 빽빽한 모니터 화면 하단부
  * *텍스트:* 없음
* **오디오/효과음:** 타닥타닥... 무겁고 느린 기계식 키보드 타건 소리 (SFX)
* **사용 도구 및 목적:** * `Sora 2`: 손가락의 타이핑 움직임을 사실적인 물리 법칙에 맞게 구현
* **입력 프롬프트 (원문):** `Close-up macro shot of hands slowly typing lines of code on a mechanical keyboard, glow from the monitor illuminating the fingers, shallow depth of field, cinematic dark office ambience, realistic finger joint movements, 4k.`
* **출력 결과 요약:** 어두운 조명 아래 기계식 키보드를 두드리는 손가락의 자연스러운 모션 생성
* **파일명:** `cut01_02_typing_hands.mp4`

---

### 🎬 Part 2: 당신의 야근 회복제는 무엇입니까? (총 8초)

#### [Cut 2-1] 캔 음료 미끄러짐 (액션 컷)
* **컷 번호 / 길이:** Cut 2-1 / 4초 (00:07 ~ 00:11)
* **목표 메시지:** 예상치 못한 동료의 호의가 들어오는 반전 시점
* **화면 구성:** * *구도:* 책상 표면과 수평을 이루는 트래킹 샷 (Low-profile Tracking Shot)
  * *피사체:* 어두운 목재 책상 위를 스르륵 미끄러져 오는 메탈릭 캔 음료
  * *배경:* 주변의 헝클어진 마우스 선과 서류들 (아웃포커싱)
  * *텍스트:* 없음
* **내레이션 (TTS-1):** "당신의 야근 회복제는..."
* **사용 도구 및 목적:** * `Sora 2`: 마찰력과 감속이 들어간 캔의 미끄러짐 물리 현상을 어색함 없이 구현
* **입력 프롬프트 (원문):** `A sleek energy drink can sliding smoothly and swiftly across a dark office wooden desk, fast sliding motion showing dynamic energy, low angle tracking shot, blurry background of computer peripheral, cinematic office low-light, 4k.`
* **출력 결과 요약:** 책상 위를 부드럽게 미끄러지며 프레임 안으로 진입하는 캔의 액션 확보
* **파일명:** `cut02_01_can_sliding.mp4`

#### [Cut 2-2] 캔 정지 및 브랜드 노출
* **컷 번호 / 길이:** Cut 2-2 / 4초 (00:11 ~ 00:15)
* **목표 메시지:** 제품명 'OVERTIME'의 시각적 각인
* **화면 구성:** * *구도:* 익스트림 매크로 샷 (Extreme Macro Shot)
  * *피사체:* 주인공 노트북 바로 옆에 '탁' 멈춰 서는 캔 음료의 라벨
  * *배경:* 정지한 캔 뒤로 흐릿하게 보이는 코딩 화면
  * *텍스트:* 캔 표면에 선명한 **'OVERTIME'** 타이포그래피 라벨링
* **내레이션 (TTS-1):** "...무엇입니까?"
* **사용 도구 및 목적:** * `GPT 모델 & Sora 2`: 표면에 차가운 물방울이 맺힌 캔의 하이퍼 리얼리스틱 질감 표현 및 선명한 텍스트 렌더링 고정
* **입력 프롬프트 (원문):** `Extreme close-up macro shot of a metallic energy drink can stopping perfectly on a desk. The can has distinct embossed text "OVERTIME" on its label, covered in cold crisp condensation droplets. Neon blue and orange rim lighting, crisp sharp focus, 4k.`
* **출력 결과 요약:** 차가운 성에와 물방울이 맺힌 'OVERTIME' 캔이 포커스인되며 멈추는 비주얼 완성
* **파일명:** `cut02_02_can_focus_in.mp4`

---

### 🎬 Part 3: 좋아하는 코딩을 계속하려면 (총 8초)

#### [Cut 3-1] 캔을 움켜쥐는 손
* **컷 번호 / 길이:** Cut 3-1 / 4초 (00:15 ~ 00:19)
* **목표 메시지:** 호의를 받아들이고 인지하는 주체적인 액션
* **화면 구성:** * *구도:* 주인공의 시점 샷 (First-Person Perspective / POV)
  * *피사체:* 주인공의 손이 뻗어나와 책상 위 오버타임 캔을 꽉 쥐는 모습
  * *배경:* 노트북 키보드 주변부
  * *텍스트:* 없음
* **내레이션 (TTS-1):** "좋아하는 코딩을 계속하려면,"
* **사용 도구 및 목적:** * `Sora 2`: 물체를 인지하고 자연스럽게 손가락으로 감싸 쥐는 인간의 연동 모션 구현
* **입력 프롬프트 (원문):** `POV close-up shot of a male hand reaching out and tightly grabbing a cold, sweating metallic energy drink can on an office desk. Realistic hand grip, soft ambient light shifting to slightly warmer tones, shallow depth of field, 4k.`
* **출력 결과 요약:** 캔을 잡는 손의 안정적이고 매끄러운 움켜짐 씬 확보
* **파일명:** `cut03_01_hand_grab.mp4`

#### [Cut 3-2] 동료의 따뜻한 미소
* **컷 번호 / 길이:** Cut 3-2 / 4초 (00:19 ~ 00:23)
* **목표 메시지:** 지친 밤을 위로하는 K-직장인의 진한 연대감 전달
* **화면 구성:** * *구도:* 미디엄 샷 (Medium Shot)
  * *피사체:* 어두운 파티션 너머 서서 미소를 짓고 있는 여성 동료
  * *배경:* 은은한 오렌지빛 보조 조명이 켜진 사무실 통로
  * *텍스트:* 없음
* **동료 대사 (TTS-1 오버랩):** "동기야, 우리 이번에 퇴근하자." (위트 있고 다정하게 툭 던지는 목소리)
* **사용 도구 및 목적:** * `Gemini Pro 3.1 & Sora 2`: 이전 컷들의 어두운 블루 톤 콘텍스트를 이어받되, 조명을 웜 앰버(Warm Amber) 톤으로 전환하여 정서적 온도를 극대화
* **입력 프롬프트 (원문):** `Medium shot of a South Korean female colleague standing in the dimly lit office hallway, warm amber accent lights in background. She is smiling warmly and making a subtle cheering gesture. Soft cinematic bokeh, emotional contrast from cold to warm, 4k.`
* **출력 결과 요약:** 지친 주인공을 바라보며 따뜻하게 미소 짓는 동료의 안도감 섞인 표정 생성
* **파일명:** `cut03_02_colleague_smile.mp4`

---

### 🎬 Part 4: 풀려라 야근! 풀려라 피로! (총 7초)

#### [Cut 4-1] 사무실 탈출 및 퇴근길 시작
* **컷 번호 / 길이:** Cut 4-1 / 4초 (00:23 ~ 00:27)
* **목표 메시지:** 해방감과 퇴근의 발걸음 시작
* **화면 구성:** * *구도:* 측면 팔로잉 샷 (Side Tracking Shot)
  * *피사체:* 백팩을 메고 나란히 보폭을 맞춰 걷는 두 동료의 하반신 또는 측면 모습
  * *배경:* 현대적인 오피스 빌딩 유리 자동문을 나서는 순간
  * *텍스트:* 없음
* **내레이션 (TTS-1):** "풀려라 야근! 풀려라 피로!" (가장 에너제틱하고 확신에 찬 박카스 톤)
* **사용 도구 및 목적:** * `Sora 2`: 두 사람의 일관된 보행(Walking) 싱크와 자동문이 열리는 복합 물리 연산 처리
* **입력 프롬프트 (원문):** `Side tracking shot of two young office workers wearing backpacks, walking side by side out of a modern corporate building entrance into the city night. Relieved and light footsteps, cinematic glass reflections, sharp details, 4k.`
* **출력 결과 요약:** 빌딩을 탈출해 밤거리로 나서는 두 직장인의 홀가분한 보행 모션 확보
* **파일명:** `cut04_01_exit_building.mp4`

#### [Cut 4-2] 비 젖은 서울 거리 뒷모습 줌아웃 (최종 엔딩)
* **컷 번호 / 길이:** Cut 4-2 / 3초 (00:27 ~ 00:30)
* **목표 메시지:** 여운이 남는 동료애 서사 완성과 브랜드 슬로건 최종 각인
* **화면 구성:** * *구도:* 와이드 앵글 돌리아웃 샷 (Wide Angle Dolly-out Shot)
  * *피사체:* 멀어져 가는 두 사람의 나란한 뒷모습 (점점 작아짐)
  * *배경:* 비가 그친 뒤, 네온사인이 아스팔트에 아름답게 반사되는 새벽녘의 서울 거리
  * *텍스트:* 화면 하단 중앙에 크고 신뢰감 있는 서체로 카피 배치 (**"우리의 퇴근은 오버타임과 함께."**)
* **오디오 (Suno v4):** 묵직하고 희망찬 오케스트라 사운드와 함께 피크(Peak)를 찍으며 엔딩 효과음.
* **사용 도구 및 목적:** * `GPT 모델 & Sora 2`: 카메라가 인물로부터 부드럽게 멀어지며 광활한 서울의 새벽 풍경을 담아내는 완벽한 공간 줌아웃(Dolly-out) 구현
* **입력 프롬프트 (원문):** `Wide shot, back view of two colleagues walking side by side away into a wet, beautiful neon-lit Seoul city street at dawn. Camera smoothly dollies out, moving backwards to reveal the vast, cinematic street filled with amber and cyan puddles. Poetic and hopeful atmosphere, 4k.`
* **출력 결과 요약:** 네온사인 반짝이는 새벽 거리를 걸어가는 두 사람의 뒷모습이 멀어지는 감성적 엔딩 확보
* **파일명:** `cut04_02_walking_away_end.mp4`

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
3. **통합 편집 제약 준수:** CapCut 무료 버전을 이용하여 소스들을 컷 편집하고, 하단 자막 서체 통일, 원작 느낌의 BGM 오디오 레벨 믹싱, 엔딩 씬의 붓글씨 로고 레이어 합성만 제한적으로 수행하여 생성형 AI 소스의 순수성을 유지함.