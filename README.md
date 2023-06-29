# mbti-insight
나와 같은 MBTI를 가진 사람들의 특징 공유 서비스

MBTI 특징 공유 서비스
---
- 기능
  1) 특징 추가기능 -> 나의 MBTI에 대한 특징을 작성할 때
  2) 특징 조회기능 -> 나와 같은 MBTI를 가진 사람들의 특징이 궁금할 때

- API 명세
  ![image](https://github.com/MinjeMun/mbti-insight/assets/122153602/e83ff157-bb57-4cbd-bd51-adb6ab9a5dc1)
  ![image](https://github.com/MinjeMun/mbti-insight/assets/122153602/0cca9723-f716-4da8-ae82-edcffe4d58c0)

  1) post로 전달하는 MBTI는 대소문자 관계없이 대문자로 DB에 저장됨
  2) DB에 없다면 "info": "MBTI"가 잘못되었거나 해당 mbti정보가 없습니다"로 반환
  3) CORS ERROR 문제 해결
  4) 현재 데이터가 들어있는 MBTI -> ENFJ, INFP
