# HomeAssistant Addon for Hillstate (Hyundai HT Wallpad + RS-485)
Home Assistant Add-on for communication with RS-485 based Wallpad (Hyundai-HT)

### Blog: https://yogyui.tistory.com

### E-Mail: lee2002w@gmail.com

---

## Fork / 유지보수: 루원시티 2차 SK 리더스뷰 (Lu1City SKLeadersView2nd)

이 포크는 **인천 루원시티 2차 SK 리더스뷰 아파트**의 Hillstate 월패드 환경에 맞춰 개발·검증되었습니다.

**Main features of this fork:**
- 거실 디밍등 실측 adaptation: 밝기 서브주소 `0x75` (8단계 그리드, byte = level×31) 사용 패드 지원
  - 원본의 `0x42` 방식은 이 세대 릴레이가 응답하지 않아 디밍이 동작하지 않음 — RS-485 버스 라이브 캡처/제어 테스트로 실증 후 수정
- ON 시 밝기 전송 단위 버그 수정, 8단계(`max_brightness_level: 8`) 매핑

**Maintainer:** Sojulab
**E-Mail:** soju@sojulab.com
**Repository:** https://github.com/Sojulab/homeassistant-addons-Lu1Sk2
**App source:** https://github.com/Sojulab/HomeNetwork-Lu1Sk2

원작자 YOGYUI님의 훌륭한 프로젝트에 깊이 감사드립니다. (Original project: [YOGYUI/homeassistant-addons](https://github.com/YOGYUI/homeassistant-addons))
