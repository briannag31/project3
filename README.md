# Therapist Finder


**Summary**

| Field | Detail |
|-------|--------|
| Project Name | Therapist finder|
| Group names| Brianna Gaines, Germano Kuerten, Jonathan Pierre, & Alejandro Rojas|
| Description | This app will allow the user to find therapists and leave/read reviews on them.
| Trello Board | https://trello.com/b/6QD9GxhK/therapist-directory|


## Technologies to be used:

- HTML
- CSS
- JavaScript
- Google Fonts
- Heroku
- Express
- Netlify
- React
- MongoDB
- Mongoose
- SASS
- Node


## Intended Routes
| Endpoint | Method | Response | Other |
| -------- | ------ | -------- | ----- |
| /therapist | GET | JSON of all items | |
| /therapist | POST | Create new item return JSON of new item | body must include data for new item |
| /therapist/:id | GET | JSON of item with matching id number | |
| /therapist/:id | PUT | update item with matching idea, return its JSON | body must include updated data |
| /therapist/:id | DELETE | delete the item with the matching id | |

## Model
![Model](https://i.imgur.com/dQXQMFo.png)

## Wireframes
![Index Page](https://i.imgur.com/mitheam.png)
![Show Page](https://i.imgur.com/OxamYvs.png)


## Bonus Features (if time)

- add authentication
- add separate profiles for user and therapist
- filter therapists
- Make it mobile friendly