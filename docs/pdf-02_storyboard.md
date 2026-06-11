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

## 🎬 RE: DESIGNED STORYBOARD (4s Constraint Optimized)
총 길이: 30초 (3+4+4+4+4+4+4+3)

* 전략: 하나의 프롬프트로 길게 뽑는 대신, 3~4초짜리 컷 8개를 컷 편집(CapCut 등)으로 이어 붙여 다이내믹한 연출 구현.

### 🎞️ 1단계: 대한민국에서 개발자로 산다는 것 (총 7초)
 * 기존: 지친 얼굴 하나로 7초 버티기 ➔ 변경: 인물과 환경을 나누어 템포 조절

 * 🎬 Cut 1-1 (3초) | 인물 클로즈업

> 화면: 노트북 모니터의 파란 불빛이 안경에 반사된 채, 멍하니 화면을 응시하는 개발자의 눈빛.
> 이미지 프롬프트: Extreme close-up of a tired South Korean male developer's eyes, cold blue screen light reflecting on his glasses, dark office, 4k.
> 내레이션: "대한민국에서 개발자로 산다는 것."

### 🎬 Cut 1-2 (4초) | 데스크 인서트 샷

> 화면: 어두운 책상 위, 코드가 빽빽한 화면과 키보드를 힘없이 두드리는 손가락.
> 이미지 프롬프트: Close-up shot of hands typing lines of code on a mechanical keyboard in a dark office at night, shallow depth of field, 4k.
> 오디오: 타닥타닥... 무거운 키보드 타건음 효과음(SFX).


## 🎞️ 2단계: 당신의 야근 회복제는 무엇입니까? (총 8초)
> 기존: 미끄러져서 멈추는 것까지 8초 ➔ 변경: 미끄러지는 역동적인 컷 + 멈춰서 로고를 보여주는 컷 분리

### 🎬 Cut 2-1 (4초) | 미끄러지는 모션 (액션)

> 화면: 누군가의 손이 에너지 음료 캔을 책상 위로 스르륵 미끄러뜨리는 역동적인 샷.
> 이미지 프롬프트: A hand sliding a sleek energy drink can across a dark wooden desk, fast sliding motion, low angle, dark background, cinematic lighting, 4k.
> 내레이션: "당신의 야근 회복제는..."

### 🎬 Cut 2-2 (4초) | 캔 정지 클로즈업 (브랜드 각인)

> 화면: 미끄러지던 캔이 주인공 노트북 바로 옆에 탁 멈추며, 캔에 새겨진 'OVERTIME' 브랜드명이 선명하게 포커스인(Focus-in)됨.
> 이미지 프롬프트: Extreme macro shot of a sleek energy drink can with "OVERTIME" text stopping perfectly on a desk. The can is covered in cold condensation droplets. Cinematic neon orange lighting, 4k.
> 내레이션: "...무엇입니까?"

## 🎞️ 3단계: 좋아하는 코딩을 계속하려면 (총 8초)
기존: 초점 이동(Rack Focus) 연출 ➔ 변경: 캔을 잡는 손(주인공 시점) + 미소 짓는 동기 컷 분리

### 🎬 Cut 3-1 (4초) | 캔을 쥐는 손

> 화면: 멍하니 있던 주인공이 눈앞의 캔을 깨달아 의아해하며 손으로 캔을 움켜쥐는 장면.
> 이미지 프롬프트: Close-up of a male developer's hand reaching out and tightly grabbing a cold energy drink can on an office desk. Warm ambient lighting starting to glow, 4k.
> 오디오: 캔을 쥐는 투박한 소리.

### 🎬 Cut 3-2 (4초) | 동료의 미소
> 화면: 고개를 들어 바라본 곳에, 멀리서 미소를 지으며 똑같이 에너지 음료를 들어 올리는 동기( colleague ).
> 이미지 프롬프트: Medium shot of a warm-smiling female colleague standing in the dark office hallway, slightly raising her own energy drink can in a cheering gesture. Friendly atmosphere, soft bokeh, 4k.
> 대사 (내레이션 오버랩): "동기야, 우리 이번에 퇴근하자."

## 🎞️ 4단계: 풀려라 야근! 풀려라 피로! (총 7초)
> 기존: 걸어가는 뒷모습 길게 줌아웃 ➔ 변경: 걷기 시작하는 컷 + 멀어지며 로고가 박히는 최종 엔딩 컷

### 🎬 Cut 4-1 (4초) | 퇴근길 시작
> 화면: 나란히 가방을 메고 회사 로비나 어두운 문을 열고 밤거리로 나서는 두 사람의 발걸음 또는 측면 샷.
> 이미지 프롬프트: Side view of two young office workers walking together through the exit of a modern building into the city night, looking cheerful and relieved, cinematic, 4k.
> 내레이션: "풀려라 야근! 풀려라 피로!"

## 🎬 Cut 4-2 (3초) | 뒷모습 줌아웃 & 최종 로고 (CTA)
> 화면: 비에 젖은 새벽 네온사인 거리를 나란히 걸어가는 두 사람의 뒷모습이 점점 멀어짐 (Sora 2의 3초 줌아웃). 화면 중앙에 브랜드 로고 타이포그래피 등장.
> 프롬프트: Wide shot, back view of two people walking down a wet Seoul street at dawn, neon reflection on asphalt. Slow dolly-out camera movement, wide angle, 4k.
> 자막/오디오: (화면 중앙 로고 등장) 우리의 퇴근은 오버타임과 함께.
