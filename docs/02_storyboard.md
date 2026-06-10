# 🎬 [2단계] AstroBrew 광고 캠페인 스토리보드

# 🎬 AI-Driven Advertising Storyboard: OVERTIME (30s)

> **캠페인명:** "지구에서 살아남는 K-직장인의 우정" (박카스 오마주)
> **총 영상 길이:** 30초
> **사용 도구 체인:** GPT 모델(이미지) ➔ Gemini Pro 3.1(프롬프트 최적화) ➔ Sora 2(비디오) ➔ TTS-1(음성) ➔ Suno v4(음악)

---
---

## 🎞️ Scene Details (씬별 상세 스토리보드)

### 🎬 Scene 1: 대한민국에서 개발자로 산다는 것
* **씬 번호 / 길이:** Scene 1 / 7초 (00:00 ~ 00:07)
* **목표 메시지:** 야근에 지친 K-직장인의 멘탈 붕괴 상황을 사실적으로 보여주어 깊은 공감대 형성
* **화면 구성:** * **구도:** 피사체 정면 클로즈업 샷 (Eye-level, Shallow Depth of Field)
  * **피사체:** 헝클어진 머리와 피로한 눈빛의 2030 남성 개발자
  * **배경:** 불이 모두 꺼진 어두운 사무실
  * **텍스트 유무:** 없음 (시각적 피로감에 집중)
* **내레이션 (TTS-1):** "대한민국에서 개발자로 산다는 것." (차분하고 약간 지친 듯한 담담한 톤)
* **사용 도구 및 목적:**
  * `GPT (DALL-E)`: 인물의 디테일한 표정과 모니터 불빛이 반사되는 질감을 정교하게 생성 (키 비주얼)
  * `Sora 2`: 정지된 이미지에서 미세하게 눈을 깜빡이거나 한숨을 쉬는 미세 텐션(Micro-expression) 모션 부여
* **입력 프롬프트 (GPT 원문):** `Cinematic close-up of a tired 20s South Korean male software engineer staring blankly, dark office at night. Subtle exhaustion, cold blue laptop screen light reflecting on his glasses. Highly detailed face, dark circles, realistic skin texture, shallow depth of field, 16:9, 8k.`
* **출력 결과 요약:** 모니터의 파란 빛이 안경에 반사된, 극도로 피곤해 보이는 개발자의 얼굴 클로즈업
* **결과 파일명:** `scene01_dev_exhausted.mp4`

---

### 🎬 Scene 2: 당신의 야근 회복제는 무엇입니까?
* **씬 번호 / 길이:** Scene 2 / 8초 (00:07 ~ 00:15)
* **목표 메시지:** 절망적인 순간, 동료의 따뜻한 호의가 다가오는 반전의 순간 묘사
* **화면 구성:** * **구도:** 책상 위 탑다운(Top-down)에서 측면으로 이어지는 트래킹 샷
  * **피사체:** 메탈릭 질감의 'OVERTIME' 캔 음료
  * **배경:** 키보드, 널브러진 케이블, 커피 자국이 있는 어지러운 책상
  * **텍스트 유무:** 캔 라벨에 'OVERTIME' 로고 노출
* **내레이션 (TTS-1):** "당신의 야근 회복제는 무엇입니까?" (질문을 던지듯 조금 더 또렷해진 톤)
* **사용 도구 및 목적:**
  * `Sora 2`: 물리 엔진의 강점을 활용해 캔이 책상 위를 미끄러지며 카메라 초점(Focus) 영역으로 정확히 들어오는 현실적인 감속 모션 생성
* **입력 프롬프트 (Sora 2 원문):** `Macro low-angle tracking shot. A sleek energy drink can sliding smoothly across a dark wooden desk filled with a mechanical keyboard and papers. The can elegantly slows down and stops perfectly in focus. Dark tech atmosphere with subtle neon orange and blue rim lighting. Realistic physics, smooth motion, 4k.`
* **출력 결과 요약:** 어두운 책상 위로 캔 음료가 부드럽게 미끄러져 들어와 멈추는 매크로 영상
* **결과 파일명:** `scene02_can_sliding.mp4`

---

### 🎬 Scene 3: 좋아하는 코딩을 계속하려면
* **씬 번호 / 길이:** Scene 3 / 8초 (00:15 ~ 00:23)
* **목표 메시지:** 각성을 넘어선 '정서적 연대감'과 동료애 전달
* **화면 구성:** * **구도:** 오버 더 숄더 샷(Over-the-shoulder) 및 랙 포커스(Rack Focus, 초점 이동)
  * **피사체:** (포그라운드) 캔을 쥔 개발자의 뒷모습 / (백그라운드) 캔을 들고 미소 짓는 동기
  * **배경:** 앰버(Amber) 오렌지색 보조 조명이 은은하게 켜진 사무실 통로
  * **텍스트 유무:** 없음
* **내레이션 (TTS-1):** "좋아하는 코딩을 계속하려면, 이런 동기가 필요하니까." + (효과음 겹침: "동기야, 우리 이번에 퇴근하자.")
* **사용 도구 및 목적:**
  * `Gemini Pro 3.1`: 앞선 1, 2씬의 콘텍스트(푸른빛, 지친 상태)를 입력받아 3씬의 분위기 전환(따뜻한 오렌지빛, 위로)을 위한 Sora 2 프롬프트 엔지니어링 수행
  * `Sora 2`: 전경의 캔에서 배경의 인물로 초점이 부드럽게 넘어가는 랙 포커스 카메라 워크 구현
* **입력 프롬프트 (Sora 2 원문):** `Over-the-shoulder shot from a seated person. Foreground: a hand holding an energy drink can. Rack focus smoothly transitions to the background: a female colleague standing in the dark office corridor, smiling warmly while holding her own can. Cinematic lighting shifting from cold blue to warm amber, soft bokeh, 16:9.`
* **출력 결과 요약:** 캔에서 동기의 미소로 초점이 이동하며 차가웠던 화면의 온도가 따뜻하게 변함
* **결과 파일명:** `scene03_colleague_smile.mp4`

---

### 🎬 Scene 4: 풀려라 야근! 풀려라 피로! (엔딩)
* **씬 번호 / 길이:** Scene 4 / 7초 (00:23 ~ 00:30)
* **목표 메시지:** 여운이 남는 퇴근길 비주얼과 함께 브랜드 슬로건 각인
* **화면 구성:** * **구도:** 와이드 샷(Wide Shot) & 돌리 아웃(Dolly-out, 줌아웃하며 멀어지는 카메라)
  * **피사체:** 함께 걸어가는 두 사람의 뒷모습
  * **배경:** 네온사인이 반사되는 새벽빛의 젖은 서울 거리 (우천 직후)
  * **텍스트 유무:** 중앙 하단에 굵고 명확한 타이포그래피 배치
* **내레이션/카피 (TTS-1 & Text):** "풀려라 야근! 풀려라 피로! / OVERTIME" (가장 힘차고 밝은 에너지의 톤)
* **사용 도구 및 목적:**
  * `GPT (DALL-E)`: 아름답고 감성적인 퇴근길 새벽 거리의 키 비주얼 생성
  * `Sora 2`: 뒷모습이 자연스럽게 멀어지는 안정적인 보행 모션과 카메라 줌아웃 효과 동시 적용
* **입력 프롬프트 (Sora 2 원문):** `Wide shot, back view of two colleagues walking side by side down a wet, neon-lit Seoul street at dawn. Smooth dolly-out camera movement tracking backwards. Cinematic lighting, rain reflections on the asphalt, moody but hopeful atmosphere. High quality, 4k.`
* **출력 결과 요약:** 비 온 뒤 새벽 거리를 나란히 걸어가는 두 사람의 뒷모습이 멀어지며 로고가 뜸
* **결과 파일명:** `scene04_walking_away.mp4`

---

## 🛠️ 프롬프트 개선 로그 (Prompt Engineering Log)

* **대상 씬:** Scene 1 (대한민국에서 개발자로 산다는 것)
* **수정 전 프롬프트 (의도):** `A Korean developer crying and extremely stressed in a dark office, holding his head, very sad.`
* **수정 전 결과/문제점:** AI가 '스트레스'와 '슬픔'을 지나치게 과장하여, 마치 공포 영화처럼 기괴하게 오열하거나 얼굴 근육이 일그러진 형태를 출력. 일상적인 오피스 브랜드 광고의 톤앤매너를 완전히 해침.
* **수정 후 프롬프트 (적용):** `Cinematic close-up... staring blankly... Subtle exhaustion, cold blue laptop screen light reflecting...` (감정 묘사를 'staring blankly(멍하게 응시하는)', 'subtle exhaustion(미세한 피로감)'으로 변경하고 조명/반사광 디테일 추가)
* **수정의 효과(의도):** 인물의 얼굴 근육 왜곡을 막고, 감정을 과도하게 표출하는 대신 **'차가운 모니터 블루라이트'**와 **'무표정 속의 지침'**만으로 피로감을 세련되게 연출함.



----

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