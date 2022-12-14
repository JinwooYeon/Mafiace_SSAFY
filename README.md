# Mafiace

![MafiaceBanner](README.assets/MafiaceBanner.png)

<br>

[[_TOC_]]

<br>

---

## π€ νλ‘μ νΈ κ°μ

>  [**Mafiace**](https://i6a602.p.ssafy.io/)λ λ€μν μ§μκ³Ό μΌκ΅΄ κ°μ  μΈμ APIλ₯Ό νμ©ν **μ¨λΌμΈ λ§νΌμ κ²μ μλΉμ€**μλλ€.
>
>  λκ΅¬λ μ½κ² μ¦κΈΈ μ μλ μ κ°κ° μμ€λ£¨ κ²μ Mafiace!! μ§κΈ λ°λ‘ λ§λλ³΄μΈμ.



### νλ‘μ νΈ λͺ©ν

- μνν μ¨λΌμΈ λ§νΌμ κ²μ μλΉμ€ κ΅¬ν
- μ¬νμκ° μμ΄λ λͺ¨λκ° μ¦κΈΈ μ μλλ‘ κ²μμ μλν
- λΉλλ©΄ νκ²½μμ νμ, μΉκ΅¬, λλ£λ€κ³Ό μμ΄μ€λΈλ μ΄νΉμ ν΅ν΄ μ λκ°κ³Ό μΉλͺ©μ νμ±ν  μ μλ κΈ°ν λ§λ ¨
- νμ  μ μλΌλ μ°¨λ³μ μ λ΄μΈμ μλ€λ₯Έ κ²μ κ²½ν μ κ³΅



### μ£Ό μ¬μ©μ λμ

- COVID-19λ‘ μΈν΄ μμ£Ό λ§λμ§ λͺ»νλ 20λ
- μ¬λ¬ λͺμ΄ ν¨κ» νλ μ¨λΌμΈ κ²μμ μ¦κΈ°λ MZ μΈλ

<br>

## π» κ°λ° νκ²½

### μΌμ 

- 2022.01.10 ~ 2022.01.16: μμ΄λμ΄ κ΅¬μ, κΈ°ν, νμ κΈ°μ  μ€ν νμ΅
- 2022.01.17 ~ 2022.01.30: μΈλΆ κΈ°ν, μ μ /κ³΅μ§μ¬ν­/λ°© κ΄λ ¨ λ‘μ§, Frontend κΈ°λ³Έ ν
- 2022.01.31 ~ 2022.02.18: κ²μ κΈ°λ₯, Frontend κ°μ , νμ€νΈ/λλ²κΉ/μ΅μ ν, μλΉμ€ UCC μ μ



### κ°λ° ν: SIXMAN

- **κΉλν**: νμ₯, Frontend λ΄λΉ, μλΉμ€ λμμΈ μ λ°, CSS λ° React
- **μ°μ§μ°**: Frontend λ΄λΉ, μλΉμ€ λμμΈ μ λ°, Face API κ΄λ ¨ κΈ°λ₯
- **κ³΅μ€ν**: Backend λ΄λΉ, Frontend λ³΄μ‘°, μλ² κ΄λ¦¬, OpenVidu, Docker 
- **κΉμ’μ°**: Backend λ΄λΉ, νμ νν΄, μμ  κΈ°λ₯, μλΉμ€μ© κ·Έλν½ μ μ
- **μ‘°μμ΄**: Backend λ΄λΉ, νμ κΈ°λ₯, κ²μ λ‘μ§ μ λ°, WebSocket κ΄λ ¨ κΈ°λ₯
- **μ²μ¬μ**: Backend λ΄λΉ, κ²μ λ‘μ§ μ λ°, JPA λ° QueryDSL, κ²μ κΈ°λ‘ λ° μ μ , μμ μ μ



### κΈ°μ  μ€ν

- IDE
  - IntelliJ IDEA Community Edition 2021.3.1
  - Visual Studio Code 1.64.2
- Frontend
  - HTML5, CSS, JavaScript (ES6)
  - React 17.0.2
  - face-api-js 0.22.2
  - semantic-ui-react 2.1.0
  - slick-carousel 1.8.1
  - sockjs-client 1.5.2
  - recharts 2.1.9
- Backend
  - Java OpenJDK 1.8.0 
  - Spring Boot 2.4.5
  - Spring Data JPA
  - Hibernate 5.4.30
  - OpenVidu 2.20.0
  - QueryDSL 4.4.0
  - Lombok
  - Spring Security
- DB
  - MySQL 8.0.28-0ubuntu0.20.04.3
- Server
  - AWS EC2 (Ubuntu 20.04 LTS)
- νμκ΄λ¦¬
  - GitLab
- μ΄μ κ΄λ¦¬
  - Jira
- Tools
  - Mattermost 4.7.0
  - Sourcetree 3.4.7

<br>

## π’ νλ‘μ νΈ νμΌ κ΅¬μ‘°

>  Frontend

```
mafiace-frontend
βββ build
βββ node_modules
βββ public
βββ src
	βββ components
	β   βββ common
	β   βββ ingame
	β   βββ main
	|		βββ header
	|		βββ login
	|		βββ mypage
	|		βββ notice
	|		βββ record
	|		βββ room
	|		βββ rules
	|
	βββ pages
	β   βββ ingame
	β   βββ main
	β
	βββ config
```



> Backend

```
com
βββ mafiace
	βββ api
	|	βββ controller
	|	βββ request
	|	βββ response
	|	βββ service
	|
	βββ common
	|	βββ auth
	|	βββ model
	|
	βββ config
	βββ db
	|	βββ entity
	|	βββ repository
	|
	βββ game
		βββ honor
```

<br>

## π‘ νλ‘μ νΈ Wiki

- [νλ‘μ νΈ ERD](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/ERD)
- [νλ‘μ νΈ API](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/API)
- [μλΉμ€ κΈ°λ₯](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/%EC%84%9C%EB%B9%84%EC%8A%A4-%EA%B8%B0%EB%8A%A5)
- [Git λ° κ°λ° μ»¨λ²€μ](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/Git-%EB%B0%8F-%EA%B0%9C%EB%B0%9C-%EC%BB%A8%EB%B2%A4%EC%85%98)
- [JPAλ₯Ό μ¬μ©νμ¬ DB κ΅¬μΆνκΈ°](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/JPA%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-DB%EA%B5%AC%EC%84%B1%ED%95%98%EA%B8%B0)
- [OpenVidu λ―Έλμ΄ μλ² κ΅¬μΆ](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/openVidu-%EB%AF%B8%EB%94%94%EC%96%B4-%EC%84%9C%EB%B2%84-%EA%B5%AC%EC%B6%95)
- [WebSocketμ μ΄μ©ν μ±ν](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/wikis/websocket%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EC%B1%84%ED%8C%85)

<br>

## π νλ‘μ νΈ μ°μΆλ¬Ό

- [μ€κ° λ°ν μλ£](https://docs.google.com/presentation/d/1MGD5Phwqq-WI5f14q6P44MnWq7EZLTsd/edit#slide=id.g10be5616b1f_0_147)
- μ΅μ’ λ°ν μλ£
- [ν¬ν λ§€λ΄μΌ](https://lab.ssafy.com/s06-webmobile1-sub2/S06P12A602/-/blob/develop/exec/%EB%B0%B0%ED%8F%AC.md)
- μμ° μλλ¦¬μ€

