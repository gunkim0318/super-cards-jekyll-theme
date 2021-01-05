# [cards](http://webjeda.com/cards)테마를 커스텀한 나만의 테마

# Screen-Shot
![image](https://user-images.githubusercontent.com/45007556/103618886-0befd600-4f74-11eb-8a16-0fd3fa5d59ef.png)
![image](https://user-images.githubusercontent.com/45007556/103619014-4ce7ea80-4f74-11eb-86de-d1c43bc3f866.png)
![image](https://user-images.githubusercontent.com/45007556/103619071-6ab54f80-4f74-11eb-87bf-12746d33ec80.png)
![image](https://user-images.githubusercontent.com/45007556/103620327-9cc7b100-4f76-11eb-8efc-97fec315fe39.png)
![image](https://user-images.githubusercontent.com/45007556/103619109-7ef94c80-4f74-11eb-932c-58ac0a544d13.png)

# 카테고리 내비게이션 바에 추가하기
***_config.yml***
```yml
nav:
  Home:
    - "/"
  About:
    - "/about/"
  Think:
    - "/categories?categoryName=Think"
  Dev:
    Spring:
    Java:
    JavaScript:
    Python:
    Other:
    "Error Log":
  Basic:
    Algorithm:
    "Data Structure":
```
카테고리가 필요한 경우 해당 파일에 추가로 작성해주게 되면 자동으로 내비게이션 바에 나타나게 된다.

# 주요 기능
cards테마 디자인을 그대로 썻고, 한국인 입맛에 맞는 각종 기능들을 모두 추가했다.

- 카테고리
  - 카테고리에 이동하면 그 카테고리에 해당하는 글만 보임(지킬 테마는 이런 테마 드물다)
- 태그
  - 카테고리와 마찬가지로 태그에 해당하는 글만 보이도록 했음.
- 목차
  - 해당 글의 목차가 보이도록 했음.