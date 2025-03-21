# 🎮 Star Roll-a-ball 3D 게임 프로젝트

## 📁 프로젝트 기간
2023.10.01 ~ 2023.11.27

## 💻 Languages
C#

## ⚒️ Tools
Unity

## 📌 프로젝트 개요
- **프로젝트 이름**: Star Roll-a-ball  
- **개발자**: 박채원 (20217145)  
- **게임 장르**: 캐주얼 액션  
- **개발 일정**: 2023.11.15 ~ 2023.12.08  
- **기획 의도**: 간단하고 누구나 즐길 수 있는 게임을 목표로 개발

## 🎯 목표
**게임 목표**:  
- 평평한 지형을 뛰어넘고, 굴러서 아이템을 먹으며 목표 지점에 도달하도록 한다.  
- 아이템을 먹으면 점수를 획득하며, 별을 먹으면 공의 색이 바뀌거나 추가 점수를 획득한다.

## 🔧 주요 기능
- **아이템 (Item)**: 게임 내 아이템을 먹으면 점수를 획득하고, 별을 먹으면 공의 색상 변화 및 추가 점수를 획득한다.  
- **플레이어 (Player)**: 플레이어는 공을 조작하여 아이템을 먹고 목표 지점으로 이동한다.  
- **결승점 (Point)**: 게임의 목표는 결승점에 도달하는 것이다.  
- **지형 (Floor)**: 게임에서 공이 이동할 평평한 지형이 제공된다.

## 🛠️ 게임 구현
- **게임 매니저 코드**:  
  - 게임의 재시작 버튼 (Restart Button)을 구현하고, UI 텍스트들을 화면에 출력하는 코드 담당
  - ![restart button code](https://github.com/user-attachments/assets/b2340820-ed1d-4199-b421-3df4d00730b8)
  
    
- **플레이어 코드**:  
  - 공의 움직임, 속도, 중력 등을 구현  
  - 아이템과 충돌 시 오디오 소스 재생 및 공 색상 랜덤 변경
![ball roll code](https://github.com/user-attachments/assets/53f5f937-b9a0-4ea9-aee3-1baa1efa94f2)


- **UI TEXT 코드**:  
  - 게임 매니저 로직 코드로 ui-Text들을 구현
  - 스테이지가 마지막 스테이지인지 확인하고, 클리어 시 "clear" 메시지가 나타나도록 구현
 ![ui text code](https://github.com/user-attachments/assets/2f3d4cab-fe43-4822-b376-8dbb0ee43bf4)
![text 2](https://github.com/user-attachments/assets/35f4df8e-f7b8-4712-bcc1-87ead9f3aec4)



 **카메라 코드**:  
  - 메인 카메라가 공을 따라 이동하는 시스템 구현
  - ![camera code](https://github.com/user-attachments/assets/c1e87efb-b849-4be0-9efe-59dbec919719)
 




## 🎬 시연 영상
- 시연 영상은 압축 파일로 별도로 제공됩니다.
