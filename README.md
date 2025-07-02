

## 👥 기록을 넘어 연결로, 연결을 넘어 네트워킹으로
![image](https://github.com/user-attachments/assets/dc285b7b-91c9-440a-a4a3-b0864e19be4d)

Synapse-X는 기록 기반 네트워킹 기능 중심 하이브리드 컨퍼런스 통합 운영 솔루션입니다. <br/>
온/오프라인에서의 참가 인사이트를 기록하고, 타 참가자 및 연사와 연결될 수 있는 네트워킹의 단초를 제공합니다.
<br/>
<br/>
<br/>

### 🛠️ 프로젝트 핵심 기능
---

1️⃣ 인사이트 노트 
- 나의 인사이트를 정리하고, 타 참가자의 인사이트를 보며, 연사와도 연결 가능합니다.
- 작성된 인사이트 노트들을 같은 세션, 전체 세션에서 확인
- 타 참가자들의 프로필에서 컨택 메일 주소, 직군/직업, 관심분야, 네트워킹 링크 확인
- 강연자의 답글을 받은 노트에는 뱃지가 주어져 작성 동기 유발
  
![image](https://github.com/user-attachments/assets/80e1182b-60a0-4a5f-925a-33fa1f86269f)
![image](https://github.com/user-attachments/assets/64d11e94-73c6-4ee2-bd08-66b1e208b685)

<br/>
<br/>
<br/>

2️⃣ 참가 신청
- 세션의 다양한 정보를 효율적으로 얻고 세션을 선택한 후 예약이 가능합니다.
- 시간대, 세션 요약, 연사, 장소, 참가 가능 인원 수를 파악
- 참가자 정보 입력과 카카오페이 결제를 한 페이지에서 해결
![image](https://github.com/user-attachments/assets/806eaacf-0298-4a4b-b1ae-f076f5275cc6)

<br/>
<br/>
<br/>

3️⃣ 회원 및 비회원 로그인/QR 인증
- 회원뿐만 아니라 비회원에게도 사용자 접근성을 높였습니다.
- 회원은 카카오/구글 소셜 로그인, 비회원은 이메일 인증 로그인 가능
- 서비스 사용 시 필요한 로그인과 컨퍼런스/세션 입장에 필요한 QR 인증을 한 페이지에서 가능
![image](https://github.com/user-attachments/assets/df11fb0f-ef12-453b-9e1e-e6fc63466622)


### 🛠️ 기술 스택
---
- **Next.js** <br/>
`pre-rendering`으로 SEO를 최적화하고, `client-side navigation`으로 사용자에게 매끄러운 페이지 간 이동을 제공하기 위해 채택했습니다. 
- **TailwindCSS** <br/>
빌드 타임에 stylesheet를 가져오기 때문에 SSR 환경에서 추가적인 설정이 필요 없으며, `atomic`한 특성으로 인해 프로젝트의 크기가 거대해져도 stylesheet 크기가 비례해서 늘어나지 않아 채택했습니다.
- **TypeScript** <br/>
코드 가독성 및 타입 안정성을 보장하기 위해 채택했습니다.
- **Tanstack Query(React-Query)** <br/>
서버 상태를 관리하기 위해 채택했습니다.
- **Vercel** <br/>
Next.js의 공식 호스팅 파트너로서 쉬운 지원 및 최적화를 진행해 주기 때문에 선택했습니다.


