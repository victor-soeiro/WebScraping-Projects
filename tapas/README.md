![tapas](cover.jpg "Tapas Cover")


Tapas - WebScraping Project
===========================

Introduction
------------

Comics are popular among people of all ages. It's a form of art, a narrative expressed as draws. Since the late 20th century, the publishers have translated mangas (comics originating from Japan) to the world. The fast growth of the popularity gained a significant worldwide audience. In 2021 in the US, mangas made up [76% of overall comics and graphic novels sales](https://www.animenewsnetwork.com/news/2022-03-01/npd-bookscan-via-the-beat-manga-made-up-76.71-percent-of-adult-fiction-graphic-novel-sales-in-2021/.182296) according to NPD Group.

This projects aims to scrape the mangas available on [Anime-Planet](https://www.anime-planet.com/), a great source to search for mangas and animes. This data will be stored on a CSV file, and available on GitHub and Kaggle for study purposes.

The acquired data it's a great database for EDA and Recommender Systems with Content-based filtering.

> **Disclaimer:** This is a personal project to practice webscraping skills and exploratory data analysis. I do not recommend to use for other purposes. Use it at your own risk.

Data Description
----------------

#### `data.csv`

| variable    | class   | description                                             |
| :--------   | :------ | :------------------------------------------------------ |
| title       | string  | Name of the webtoon                                     |
| item_id     | integer | Webtoon id on Tapas                                     |
| link        | string  | Link to webtoon page on [Toomics](https://toomics.com/) |
| cover       | string  | Link to webtoon cover                                   |
| creators    | list    | Creators of the webtoon                                 |
| genres      | list    | Genres of the webtoon                                   |
| views       | string  | Number of views                                         |
| subscribers | string  | Number of subscribers                                   |
| likes       | string  | Number of likes                                         |
| banner      | string  | Link to webtoon banner                                  |
| details     | string  | Description                                             |
| tags        | list    | Tags of the webtoon                                     |
| episodes    | integer | Number of episodes                                      |
| released    | date    | Released date of the first episode                      |

Licence
---------
Copyright (c) 2022 Victor Soeiro

This project is licensed under the MIT License

Contact
---------
If you have any questions or suggestions, send me an email to victor.soeiro.araujo@gmail.com


