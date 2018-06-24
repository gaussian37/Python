### 1.프로젝트 만들기
- django-admin startproject [프로젝트 이름] . <br>
(마지막에 .을 붙여 주어야 현재 디렉토리에 생성됨)

- 이상적인 디렉토리 구조
djangogirls
├───manage.py
└───mysite
        settings.py
        urls.py
        wsgi.py
        __init__.py
        
- 설정 변경하기 ([링크 참조](https://tutorial.djangogirls.org/ko/django_start_project/))

### 2.어플리케이션 만들기
- python manage.py startapp [app 이름]