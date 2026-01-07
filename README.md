# Detecting-Electric-Scooter

블랙박스 영상을 통한 YOLOv8 기반 불법 주정차 전동킥보드 객체 탐지 및 Kakao Map API를 활용한 최적 수거 경로 생성 
<br />   

연세대학교 사회기반시스템종합설계 (2조 - 박광서, 이○○, 송○○) 

<br />   
<br />   

# 📝 Description:
YOLOv8을 기반으로 블랙박스 영상을 분석하여 불법 주정차된 전동킥보드를 자동으로 탐지하고, 수거를 위한 최적의 경로를 제공하는 통합 시스템입니다. 인공지능 기반의 객체 탐지와 공간정보 기술을 결합하여 스마트 인프라 안전 관리 및 도시 미관 개선에 일조합니다. 

<br />   

▶ 객체 탐지 시스템 (Object Detection): Fine-tuning된 YOLOv8 모델을 활용하여 주행 영상 속 전동킥보드를 식별합니다. '탑승 중인 킥보드(PP)'와 '불법 주정차된 킥보드(NP)'를 구분하여 탐지하며, 오탐지를 최소화한 정밀한 분석을 수행합니다. 

▶ 자동 정보 추출 (OCR & Database): Tesseract-OCR 기술을 적용하여 영상 내의 시간, 위도, 경도 정보를 텍스트로 자동 변환합니다. 탐지된 킥보드의 정확한 위치와 발생 시각 데이터를 엑셀 형태로 정리하여 서버에 저장됩니다. 

▶ 최적 수거 경로 생성: 추출된 위치 정보를 활용하여 AWS 서버 상에서 Kakao Maps API 및 Directions API를 활용해 수거 차량의 최단 경로를 계산합니다. 여러 지점에 흩어진 킥보드를 가장 효율적으로 수거할 수 있는 동선을 시각화하여 제공합니다. 

▶ 통합 모바일 애플리케이션 영상 업로드부터 분석 결과 확인, 지도 기반의 경로 안내까지 모든 과정을 하나의 안드로이드 앱에서 처리합니다. AWS 클라우드 서버와 연동하여 무거운 연산 처리 중에도 사용자의 편의성을 보장합니다. 

▶ 기대효과: 
    - 시민 안전 강화: 보행을 방해하는 킥보드의 신속한 처리
    - 운영 효율성 증대: 수거 업체의 이동 동선 최적화 및 비용 절감
    - 스마트 인프라 정책 수립: 불법 주정차 다발 구역 파악 및 정책 수립 지원 

<br />    
<br />   

<img width="1939" height="942" alt="Image" src="https://github.com/user-attachments/assets/f631f594-e265-4cfb-b352-2ea8fd5f53b0" />

<br />   

<img width="2460" height="805" alt="Image" src="https://github.com/user-attachments/assets/48ec3864-29cf-4976-9792-1f354d6bf38e" />

<br />   

<img width="2214" height="810" alt="Image" src="https://github.com/user-attachments/assets/38b441e2-8ff0-4992-a6ed-7900e33c893b" />

<br />   

<img width="2420" height="790" alt="Image" src="https://github.com/user-attachments/assets/1e86b7ab-6cad-4524-bc5a-56c4e1bb4a11" />

<br />   

<img width="2490" height="789" alt="Image" src="https://github.com/user-attachments/assets/db326789-67f8-420f-b661-5a246aaf1684" />

<br />   

<img width="558" height="438" alt="Image" src="https://github.com/user-attachments/assets/0e65aa0a-d41f-46ea-bed8-a70c40419428" />

<br />      
<br />    

# 👨‍👩‍👧‍👦 Teamates: 
박광서, 이○○, 송○○ 

<br />   

- 박광서: 객체 탐지 모델 학습, OCR 데이터 처리, AWS 서버 연결, 안드로이드 앱 개발, 시스템 통합 
- 이○○: 데이터셋 구축 
- 송○○: 객체 탐지 모델 학습, 최적 경로 생성 API 연동 

<br />    
<br />   

# 📝 My Role 
객체 탐지 모델 학습, OCR 데이터 처리, AWS 서버 연결, 안드로이드 앱 개발, 시스템 통합 
<br />   

- 안드로이드 앱개발 & 시스템 통합
- 블랙박스 영상 파일 선택 및 업로드 UI 구현
- AWS EC2 서버와의 통신을 통한 영상 데이터 전송 및 처리 요청
  - 서버로부터 수신한 OCR 결과 데이터(위도, 경도, 시간, 주소) 파싱 및 앱 내 데이터 모델링
- Kakao Maps API, Kakao Navigations AIP 연동 및 지도 화면 개발 
  - 탐지된 불법 주정차 킥보드 위치 마커 표시 
  - 마커 클릭 시 해당 위치의 탐지 이미지(스냅샷) 및 주소 정보 표시창 표시 
  - 최적 수거 경로 안내 시스템 

<br />    
<br />   

# 💻 Development Environment / Tools
- Language: Kotlin, Python (AI Model) 
- IDE: Android Studio, Jupyter Notebook
- AI/ML: YOLOv8 (Object Detection), Tesseract-OCR
- Cloud & Server: AWS EC2, AWS Cloud
- Map & Location: Kakao Maps API, Kakao Directions API
- Database: Excel 

<br />    
<br />   

# 🤜🤛 Collaborations
Notion


<br />    <br />
