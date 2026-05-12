<div align="center">

# Beomboos

사용자와 환경을 연결하는 서비스를 개발하는 팀입니다.

<br/>

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Spring](https://img.shields.io/badge/BackEnd-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 🌱 About Beomboos

**Beomboos**는 사용자가 주변 쓰레기통 위치를 쉽게 확인하고,  
매장과 사용자가 함께 참여할 수 있는 친환경 서비스를 만드는 팀입니다.

우리는 단순히 기능을 구현하는 것을 넘어,  
실제 사용자가 편하게 사용할 수 있는 앱과 서비스를 목표로 개발하고 있습니다.

---

## 🗑 Main Project: Throw

**Throw**는 주변 매장의 쓰레기통 위치와 분리수거 가능 정보를 제공하는 서비스입니다.

사용자는 지도 기반으로 주변 쓰레기통을 확인할 수 있고,  
매장은 직접 쓰레기통 정보를 등록하여 친환경 활동에 참여할 수 있습니다.

---

## 🎬 Demo Video

> Throw 앱의 주요 화면 흐름을 보여주는 시연 영상입니다.

<video src="https://github.com/user-attachments/assets/여기에_영상_URL_넣기" controls width="100%"></video>

---

## 📌 Repositories

| Repository | Description |
|---|---|
| [Throw_FrontEnd](https://github.com/Beomboos/Throw_FrontEnd) | Android 앱 클라이언트 |
| [Throw_BackEnd](https://github.com/Beomboos/Throw_BackEnd) | 서버 및 API |
| [Document](https://github.com/Beomboos/Document) | 프로젝트 기획 및 문서 |

---

## 🛠 Tech Stack

### FrontEnd

- Kotlin
- Android
- XML Layout
- MVVM
- Retrofit
- DataStore
- Firebase
- Kakao Map API
- ZXing QR Scanner

### BackEnd

- REST API
- Database
- Server Architecture

### Collaboration

- Git
- GitHub
- Notion
- Figma

---

## 🧱 System Overview

```mermaid
flowchart LR
    User[사용자] --> App[Android App]
    Store[매장 관리자] --> App
    App --> API[BackEnd API Server]
    API --> DB[(Database)]
    App --> Map[Kakao Map API]
    App --> Firebase[Firebase]