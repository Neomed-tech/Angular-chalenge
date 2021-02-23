# Anime site

We need to create a solution for an online anime netflix. Must have a home page, a 'myList' page and a navbar.

#### List all animes on home page with some of these features.
 - Filters of search (title), genres, year, season.
 - Button for change visualization
 - Pagination, 20 animes by page.
 - The card has to a button to add to mylist.

#### List all animes from my list.
 - Filters of search (title), genres, year, season.
 - Button for change visualization
 - The card has to a button to remove from mylist and to highlight the anime.

#### Navbar
 - Expand My list (title, image)
 - Face

#### Unique page
- Banner image
- More information: Overview, characters, reviews, etc.


## BACK-END

https://github.com/AniList/ApiV2-GraphQL-Docs
https://anilist.gitbook.io/anilist-apiv2-docs/

## FRONT-END
Try to book all animes into my list without any server request.<br>
Take care of validations and build a facelit interface if you can. <br>
Please use the wireframe as a guide.

### Rules:
- The navbar and page "mylist" must be updated when adding or removing anime from home list.
- Create a button on animes to add and remove from my list.
- The "mylist" can have 20 animes only.
- Create a button to highlight the most interesting animes on "mylist".
- Sort "mylist" by highlighted and normal animes.

### Requirements
1. You must use Angular 11, no other frameworks are accepted.
2. You must manage your application state in a maintanable way (NgRx or similar).
3. You can create CSS from scratch and use the angular material.
4. You must add unit specs with jest or similar.
5. You must add acceptance specs (end-to-end) like Cypress.
6. You must version your work using Git and the repository must be private (Do not make one commit with all of your work, we need to see your work in logical commits to follow your work logic)
7. All your commits must be in english.

### Nice to have
1. Deploy your solution somewhere like Heroku or Netlify.
