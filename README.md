<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:58A6FF&height=230&section=header&text=SuperBRS&fontSize=78&fontColor=ffffff&fontAlignY=36&desc=Удобно, быстро, красиво, с встроенным расписанием и ИИ-ассистентом&descSize=22&descAlignY=58&animation=fadeIn" alt="SuperBRS" width="100%" />
<br/>

![статус](https://img.shields.io/badge/%D1%81%D1%82%D0%B0%D1%82%D1%83%D1%81-%D0%B2_%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B5-F59E0B?style=flat-square) ![версия](https://img.shields.io/badge/%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F-0.0_%C2%B7_MVP-8957E5?style=flat-square)


<br/>

<img src="https://skillicons.dev/icons?i=react,vite,tailwind,cs,dotnet,docker,git,github,figma,vercel&theme=dark" alt="Стек технологий" />

<br/>

</div>

<br/>

> **SuperBRS** — единая цифровая витрина успеваемости и расписания с интеллектуальным ассистентом.
> Текущий сервис БРС ЮФУ морально устарел, неудобен не встроено расписание, поэтому мы разрабатываем удобный и современный веб-сервис, который объединит оценки и пары. Мы сделаем мгновенную загрузку за счет кэширования, чтобы последние данные открывались даже при сбоях
> встроим умного ИИ-ассистента для поиска аудитории в которой сейчас нужный преподаватель или сколько баллов не хватает до зачета.

## Быстрый старт

```bash
git clone https://github.com/Kingrane/SuperBRS.git
cd SuperBRS
```

**Бэкенд**

```bash
cd backend
dotnet restore
dotnet run
```

**Фронтенд**

```bash
npm install
npm run dev
```

<details>
<summary><b>Переменные окружения</b></summary>

<br/>

| Где | Переменная | Для чего |
|:--|:--|:--|
| frontend | `VITE_API_URL` | адрес нашего бэкенда |
| backend | `ALLOWED_ORIGIN` | домен фронтенда для CORS |
| backend | `LLM_BASE_URL`, `LLM_API_KEY`, `LLM_MODEL` | провайдер языковой модели |


</details>

<details>
<summary><b>Где взять токен для входа</b></summary>

<br/>

Войти в SuperBRS можно только с токеном из официального БРС ЮФУ: у университета вход устроен через почту, другого способа получить доступ к данным нет.

1. Войдите в официальный сервис БРС с университетской почтой.
2. Скопируйте свой токен (пошаговая инструкция со скриншотами появится здесь).
3. Вставьте его на странице входа SuperBRS.

</details>


## Команда

[![Conributors][contibutors-logo]](https://github.com/Kingrane/SuperBRS/graphs/contributors)

<br/>

<div align="center">

**Сделано командой MOGnit**

<sub>Проект не является официальным сервисом университета.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,50:1F6FEB,100:0D1117&height=120&section=footer&reversal=true" width="100%" alt="" />

</div>

[contibutors-logo]: https://contrib.rocks/image?repo=Kingrane/SuperBRS 