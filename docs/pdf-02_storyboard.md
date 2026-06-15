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

### [Cut 1-1] 인물 초근접 클로즈업

- **길이:** 4초 | **목표 메시지:** 야근에 지친 K-직장인의 피로감 전달
- **화면 구성:** [구도] 익스트림 클로즈업 샷 / [피사체] 멍하니 노트북을 응시하는 개발자의 눈과 안경 / [배경] 불 꺼진 어두운 사무실 / [텍스트] 없음
- **내레이션:** "대한민국에서 성실한 사람으로 산다는 것."
- **사용 도구:** 이미지(GPT-5, 사실적 안경 반사광 구현), 영상(Sora 2, 미세한 눈 깜빡임)
- **입력 프롬프트(원문):** `Extreme close-up of a tired South Korean male software engineer's eyes, cold blue laptop screen light reflecting deeply on his glasses, dark office background, subtle micro-movements, shallow depth of field, cinematic lighting, 4k.`
- **결과 요약:** 안경에 코딩 화면이 반사된 지친 눈빛 확보
- **파일명:** `cut_01_01.png`, `cut_01_01.mp4`

### [Cut 1-2] 데스크 인서트 샷

- **길이:** 4초 | **목표 메시지:** 밤샘 코딩 노동의 시각화
- **화면 구성:** [구도] 매크로 로우앵글 샷 / [피사체] 기계식 키보드를 두드리는 손가락 / [배경] 코드 IDE 화면 하단 / [텍스트] 없음
- **내레이션:** (효과음)
- **사용 도구:** 이미지(GPT-5, 디테일한 손 피부 묘사), 영상(Sora 2, 물리 법칙에 따른 키보드 모션)
- **입력 프롬프트(원문):** `Close-up macro shot of hands slowly typing lines of code on a mechanical keyboard, glow from the monitor illuminating the fingers, shallow depth of field, cinematic dark office ambience, realistic finger joint movements, 4k.`
- **결과 요약:** 키보드를 두드리는 손가락의 자연스러운 모션 생성
- **파일명:** `cut_01_02.png`, `cut_01_02.mp4`

### [Cut 2-1] 캔 음료 미끄러짐

- **길이:** 4초 | **목표 메시지:** 예상치 못한 호의의 진입
- **화면 구성:** [구도] 책상 수평 트래킹 샷 / [피사체] 어두운 책상을 미끄러져 오는 캔 / [배경] 헝클어진 마우스 선 / [텍스트] 없음
- **내레이션:** "당신의 야근 회복제는..."
- **사용 도구:** 이미지(GPT-5, 캔의 하이퍼 리얼리스틱 질감), 영상(Gemini 3.1, 슬라이딩 물리 엔진)
- **입력 프롬프트(원문):** `A photorealistic tall aluminum can lying perfectly flat on its side on a dark wood-grain desk. The can has a brushed bare-metal silver finish with visible hairline texture — no label, no wrapper. The word "OVERTIME" is printed in bold italic black sans-serif capital letters, centered on the can body. The pull-tab faces right. The can slides from left to right. ROTATION IS ABSOLUTELY FORBIDDEN.`
- **결과 요약:** 프레임 안으로 들어오는 캔의 액션 확보
- **파일명:** `cut_02_01.png`, `cut_02_01.mp4`

### [Cut 2-2] 캔 정지 및 브랜드 노출

- **길이:** 4초 | **목표 메시지:** 제품명 'OVERTIME'의 시각적 각인
- **화면 구성:** [구도] 익스트림 매크로 샷 / [피사체] 멈춰 선 캔의 라벨 / [배경] 흐릿한 코딩 화면 / [텍스트] 'OVERTIME' 선명한 라벨링
- **내레이션:** "...무엇입니까?"
- **사용 도구:** 이미지(GPT-5), 영상(Gemini 3.1, Focus-in 모션)
- **입력 프롬프트(원문):** `Extreme macro shot. The cylindrical brushed silver aluminum can slides and comes to an abrupt, hard stop next to a laptop. Immediately upon stopping, the camera dynamically pulls focus onto the crisp, black 'OVERTIME' typography. The can is heavily encrusted with hyper-realistic ice crystals and condensation.`
- **결과 요약:** 포커스 인을 통한 제품명 각인 비주얼 완성
- **파일명:** `cut_02_02.png`, `cut_02_02.mp4`

### [Cut 3-1] 캔을 움켜쥐는 손

- **길이:** 4초 | **목표 메시지:** 호의를 받아들이는 주체적 액션
- **화면 구성:** [구도] 주인공 POV 샷 / [피사체] 캔을 꽉 쥐는 손 / [배경] 키보드 / [텍스트] 없음
- **내레이션:** "대한민국에서 성실한 사람으로 산다는 것,"
- **사용 도구:** 이미지(GPT-5, 서리 질감), 영상(Gemini 3.1)
- **입력 프롬프트(원문):** `Extreme close-up macro shot. A brushed bare-metal silver aluminum can sits perfectly still. The word "OVERTIME" is printed in bold italic black sans-serif capital letters. A male right hand grips the can from the side. Fingers wrapped around naturally...`
- **프롬프트 수정 로그:** [전] 손과 캔의 부자연스러운 조화 -> [후] 캔의 비율과 고정된 텍스트 앵글을 강제하여 자연스러운 움켜짐 묘사
- **결과 요약:** 캔을 잡는 손의 안정적인 움켜짐 씬 확보
- **파일명:** `cut_03_01.png`, `cut_03_01.mp4`

### [Cut 3-2] 동료의 따뜻한 미소

- **길이:** 4초 | **목표 메시지:** 지친 밤의 연대감 전달
- **화면 구성:** [구도] 미디엄 샷 / [피사체] 파티션 너머의 동료 / [배경] 앰버 조명 사무실 / [텍스트] 없음
- **내레이션:** "동기야, 우리 이번에 퇴근하자."
- **사용 도구:** 이미지(GPT-5), 영상(Gemini 3.1, 따뜻한 웜톤 라이팅)
- **입력 프롬프트(원문):** `Medium shot. South Korean female colleague, late 20s, business casual dark blazer, leaning over office partition at night. Warm genuine smile, subtle encouraging hand gesture. Lighting: warm amber halo from hallway lights...`
- **결과 요약:** 동료의 따뜻한 미소와 격려 제스처 확보
- **파일명:** `cut_03_02.png`, `cut_03_02.mp4`

### [Cut 4-1] 함께 걷는 퇴근길

- **길이:** 8초 | **목표 메시지:** 해방감과 브랜드 최종 각인
- **화면 구성:** [구도] 하이 앵글 줌아웃 / [피사체] 나란히 걷는 두 동료 / [배경] 네온 젖은 새벽 거리 / [텍스트] 붓글씨 로고 레이어 합성
- **내레이션:** (남)"풀려라 야근! 풀려라 피로!" (여)"우리의 퇴근은, 오버타임!"
- **사용 도구:** 영상(Gemini 3.1), 오디오(Suno v4, 희망찬 오케스트라)
- **입력 프롬프트(원문):** `High-angle wide shot, two young office workers with backpacks walking side by side down a wet, neon-lit Seoul city street at dawn. The camera slowly zooms out as they walk away, capturing the reflections of city lights on the puddles. Cinematic, hopeful atmosphere, 4k.`
- **결과 요약:** 새벽 거리로 나서는 두 사람의 여운 있는 엔딩
- **파일명:** `cut_04_01.mp4`

## 3. 최종 영상 스펙

- **파일명:** `OVERTIME_branding_final.mp4` | **길이:** 30초 | **인코딩:** H.264 / AAC | **통합 편집:** CapCut

