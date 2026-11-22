# 호환성 및 테스트 범위

2026-11-22

| 기기 | 연결 방식 | 검증 범위 |
|---|---|---|
| iGPSPORT iGS630S | BLE | 실기기 확인: iGS630S |
| Garmin Edge 530 | Connect IQ + iPhone | Edge 530은 사용자 연결 성공 보고가 있습니다. 펌웨어, 장시간 잠금 상태 및 FIT 내보내기는 검증이 필요합니다. |
| 기타 BLE 기기 | BLE | 다른 모델은 개별 검증이 필요합니다. BLE 지원만으로 실기기 호환성이 확인되지는 않습니다. |

강제 종료, 재시작, 손목에서 벗겨져 잠긴 상태, 일반 화면 꺼짐은 다른 상태입니다. iGS630S에서는 두 모드 모두 운동 기기 재시작 후 재연결과 iPhone 모드의 백그라운드 업데이트를 실기기로 확인했습니다. 다른 모델은 개별 검증이 필요합니다.

## Garmin Edge 530

Edge 530은 Connect IQ 데이터 필드를 사용합니다. 심박 센서 목록에서 SportHeart를 페어링하지 마세요.

Garmin Connect에서 기기를 페어링한 다음 Sport Heart Assistant / 설정 / Garmin 심박수 연결에서 기기를 선택하세요.

2. SportHeart를 설치하고 사이클링 화면에 데이터 필드를 추가하세요.

워치에서 휴대폰 중계를 선택하고 시작하세요. iPhone의 Garmin 심박수 연결 페이지에서 공유를 켜세요.

수신 확인은 심박 표시 완료를 뜻하지 않습니다. 사이클링 컴퓨터 화면을 확인하세요.

이 필드는 Garmin 기본 심박 센서를 대체하거나 훈련 부하 계산을 보장하지 않습니다.

## iGPSPORT iGS630S

iGS630S: 설정 → 센서 → 센서 추가 → 심박수.

iPhone 모드에서 초기 페어링을 위해 iPhone 앱을 열어두세요. 두 가지 모드는 서로 다른 송신 기기를 사용하며 별도의 저장된 센서 항목이 필요할 수 있습니다.

iGS630S 실기기 테스트에서는 운동 기기와 휴대전화의 연동 연결이 동시에 있을 때 센서에 연결되어도 심박수 데이터가 전달되지 않는 경우가 있었습니다. 해당 연동 연결을 끊고 저장된 심박수 센서를 삭제한 뒤 다시 페어링하면 복구되었습니다. 원인은 확인되지 않았으며 다른 모델의 동작은 다를 수 있습니다.

iPhone 모드에서는 운동 기기의 동반 앱 링크만 연결 해제하세요. iPhone Bluetooth와 Apple Watch 연결을 켜두세요.

App Store: https://apps.apple.com/app/id6827442593

Connect IQ: https://apps.garmin.com/zh-CN/apps/0b750e18-5b36-4cc7-9470-b8f996dfa94a

Support: support-ko.html
