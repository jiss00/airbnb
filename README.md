# School Facility Reservation System🏫📅

이 프로젝트는 학교 시설 예약과 관련된 서비스를 제공하는 웹 애플리케이션입니다. 이 애플리케이션은 예약 생성, 알림 설정, 예약 연장, 예약 반납 등의 기능을 제공합니다. 또한 시설물 관련 정보 및 리뷰, 검색 랭킹 정보를 제공하는 기능도 있습니다.

![Java](https://img.shields.io/badge/Java-11-blue?style=flat&logo=java)
![Spring Framework](https://img.shields.io/badge/Spring_Framework-5.3.9-green?style=flat&logo=spring)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-2.5.3-green?style=flat&logo=spring)
![Lombok](https://img.shields.io/badge/Lombok-1.18.20-orange?style=flat&logo=lombok)
![REST API](https://img.shields.io/badge/REST_API-implementation-yellow)
![Redis](https://img.shields.io/badge/Redis-6.2.5-red?style=flat&logo=redis)
![WebSocket](https://img.shields.io/badge/WebSocket-communication-orange)

## 🚀시작하기
1. **프로젝트 클론**

    ```shell
    git clone https://github.com/username/school-facility-reservation.git
    cd school-facility-reservation
    ```
2. **프로젝트 빌드 및 의존성 설치**

    ```shell
    ./gradlew build
    ```
3. **애플리케이션 실행**

    ```shell
    java -jar build/libs/school-facility-reservation.jar
    ```
    혹은 IDE를 통해 `ReservationApplication`클래스를 실행합니다.

## 📝사용법

1. **예약 생성**

   `createReservation()` 메소드를 사용하여 새로운 예약을 생성할 수 있습니다.
2. **알림 설정**

   `scheduleAlerts()` 메소드를 사용하여 예약에 대한 알림을 스케줄링할 수 있습니다.
3. **예약 연장, 반납**

   `extendTime()`, `returnReservation()` 메소드를 사용하여 예약을 연장하거나 반납할 수 있습니다.
4. **예약 내역 확인**

   `getReservation()`, `getReservation_no()` 메소드를 사용하여 예약 내역을 확인할 수 있습니다.
5. **시설물 관련 정보**

   `FacilityQueryServiceImpl`클래스를 통해 시설물 관련 정보를 조회할 수 있습니다.
6. **검색 랭킹 업데이트**

   `SearchRankService`클래스를 통해 검색 랭킹을 업데이트하고 저장할 수 있습니다.
7. **기타 기능**

   `LibraryService`클래스를 통해 학교 도서관의 상태를 조회할 수 있습니다.
8. **리뷰 점수 업데이트**

   `ReviewScoreService`클래스를 통해 리뷰 점수를 업데이트할 수 있습니다.

## 🛠️기능
- **예약 관리**: 학교 시설물의 예약을 생성, 관리, 확인할 수 있습니다.
- **알림 설정**: 예약한 시설물에 대한 알림을 설정하여 시간을 효율적으로 관리할 수 있습니다.
- **시설물 정보 제공**: 다양한 시설묤의 정보(이용 가능 시간, 예약 제약 사항 등)를 제공하여 사용자가 편리하게 예약할 수 있도록 합니다.
- **리뷰 및 평점 기능**: 예약한 시설물에 대한 리뷰를 작성하고 평점을 부여할 수 있습니다. 다른 사용자들의 리뷰를 확인하여 시설물을 선택할 때 참고할 수 있습니다.
- **시설물 검색 및 랭킹**: 특정 기준(인기순,평점순,최신순 등)으로 시설물을 검색하고 랭킹을 확인할 수 있습니다.

## 👥기여자
- 🧑‍💻[사용자1](https://github.com/user1)
- 🧑‍💻[사용자2](https://github.com/user2)
- 🧑‍💻[사용자3](https://github.com/user3)
