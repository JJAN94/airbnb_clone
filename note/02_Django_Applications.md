# applications

project는 애플리케이션의 집합(group of function)

애플리케이션을 일종의 폴더라고 생각하면 된다.

그러면 어떻게 애플리케이션을 만들고 프로젝트를 계획해야 할까?

기능별 CRUD를 하나의 폴더에 넣자. (한곳에 다 밀어넣으면 안된다.)

```
django-admin startapp
```



이제 필요한 apps를 만들어보자.

```
django-admin startapp rooms
django-admin startapp users
django-admin startapp reviews
django-admin startapp conversations
django-admin startapp lists
django-admin startapp reservations
```

그러면 이제 각각 애플리케이션(폴더)가 생성되는데 django의 경우 폴더명, 파일명, 삭제, 수정을 하면 안된다.

새로운 파일, 폴더 생성은 가능하다.