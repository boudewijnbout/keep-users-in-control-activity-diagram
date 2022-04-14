# 👨🏼‍💻 Keep Users In Control Activity Diagram

Activity diagram voor CRUD van de Chippr.dev website.

## 🙋🏼‍♂️ User Story
Als gebruiker wil ik een overzicht van alle projecten die in de Chippr.dev API staan, zodat ik in één oogopslag kan zien hoeveel en welke projecten er aan de API zijn toegevoegd.

## ⛷ Activity Diagram
<img width="500" src="https://github.com/boudewijnbout/keep-users-in-control-activity-diagram/blob/main/assets/IMG_0026.jpg" />

## 🖥 Uitleg pseudo-code 
In mijn activity diagram is te zien hoe de API data in het overzicht van het CRUD word ingeladen. Dit proces gaat als volgt:

1. Index.js word aangesproken.
2. De functie getApiData() word aangesproken. Hierbij word ook de loading state aangezet.
3. Vervolgens word de renderData() functie aangesproken. Hierbij word de data in de HTML gerenderd en word de loading state uitgezet.
4. Er is nog een uitzondering, die e.v.t kan verwijzen naar de error state.

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
