# ๐งโ๐ป Django Pair Project 20221021

#### Who? 

> ์ด์ ์ค, ๊น์ง์ฐ, ๊นํ์ค

#### Used Tool?

> Python, Django, HTML, CSS

#### What?

> ์ง๊ธ๊น์ง ๋ฐฐ์ด ๋ด์ฉ์ ํ ๋๋ก ์ํ ๋ฆฌ๋ทฐ ์น ์๋น์ค๋ฅผ ๊ตฌํํ๋ค
>
> ๊ตฌํํ ๊ธฐ๋ฅ
>
> - `Review` CRUD (Create, Read, Update, Delete)
> - `Comment` Create, Read, Delete
> - `Accounts` Create, Read, Delete
> - 1:N ๊ธฐ๋ฅ

##### 1:N ๊ธฐ๋ฅ

- Review -> User
  - ์ด๋ค ์ ์ ๊ฐ, ํด๋น ๋ฆฌ๋ทฐ๋ฅผ ์ผ๋์ง
- Comment -> User & Review
  - ์ด๋ค ์ ์ ๊ฐ, ์ด๋ค ๋ฆฌ๋ทฐ์ ๋๊ธ์ ์์ฑํ๋์ง



#### ํ์๊ฐ์

> ํ์๊ฐ์ ์๋ฃ ํ, ๋ฐ๋ก ๋ก๊ทธ์ธ์ด ์๋์ผ๋ก ๋๋ฉฐ, ํํ์ด์ง๋ก ์ด๋์ ํ๋ค

![ํ์๊ฐ์](README.assets/ํ์๊ฐ์.gif)



#### ๋ก๊ทธ์ธ

![๋ก๊ทธ์ธ](README.assets/๋ก๊ทธ์ธ.gif)



#### ๋ก๊ทธ์ธ ํ ๋๊ธ ์์ฑ ํ์ด์ง

> ๋ฆฌ๋ทฐ ์์ฑ ํ์ด์ง, ๋ฆฌ๋ทฐ ํ์ด์ง, ๋๊ธ๊ธฐ๋ฅ ๋ฑ์ ๋ชจ๋ ๋ก๊ทธ์ธ์ ํด์ผ ๋ค์ด๊ฐ ์ ์๋ค
>
> ์ฆ ํด๋น ํ์ด์ง๋ฅผ ๋ค์ด๊ฐ๋ ค๋ฉด, ๋ก๊ทธ์ธ์ ํด์ผํ๊ณ , `request.GET.get('next')`๋ฅผ ํตํด, ๋ก๊ทธ์ธ ํ ์ฒ์์ ํด๋ฆญํ๋ ํ์ด์ง๋ก ๋ฐ๋ก ๋ค์ด๊ฐ ์ ์๋๋ก ๋ง๋ค์๋ค

![๋ก๊ทธ์ธ_๋๊ธ](README.assets/๋ก๊ทธ์ธ_๋๊ธ.gif)



#### ๋ฆฌ๋ทฐ ํ์ด์ง ๋ง๋ค๊ธฐ

![๋ฆฌ๋ทฐ](README.assets/๋ฆฌ๋ทฐ.gif)



#### ๋๊ธ ์ฐ๊ธฐ

![๋๊ธ ์ฐ๊ธฐ](README.assets/๋๊ธ ์ฐ๊ธฐ.gif)



#### ํ๋กํ ํ์ด์ง

![ํ๋กํ ํ์ด์ง](README.assets/ํ๋กํ ํ์ด์ง.gif)







