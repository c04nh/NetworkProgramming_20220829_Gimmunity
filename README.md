# Gimmunity
- 기숙사생들의 활발한 소통을 위한 커뮤니티
- 수민외3 (공도윤, 김수민, 전유리, 홍해인)
- 미림 스타트업 창업발표회 대상 수상작
- [기획서](https://bit.ly/3Tq5i80)
  - 미림 계정 로그인, 기숙사생 전용 질문을 통과해야 가입 가능
  - 게시물 조회
  - 게시물 추가
  - 댓글
  - 기숙사 공지사항, 생활 규칙 전달
---
1. startproject
   1. python -m pip install django~=3.2
   2. django-admin startproject Gimmunity .
   3. python manage.py runserver
2. startapp notice
   1. python manage.py startapp notice
   2. 'notice', in INSTALLED_APPS