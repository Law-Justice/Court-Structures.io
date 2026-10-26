# Court Systems: Climb the Courts

A live, Pear Deck-style classroom game about the structure of the U.S. court system.
Students are "cases" on a docket. Correct answers move them from the district court up the
staircase to the Supreme Court.

## Publish on GitHub Pages
1. Create a public repository (for example `court-climb`) and upload `index.html` to the top folder.
   (Or upload this whole `court-climb` folder into an existing repository.)
2. Settings > Pages > Source: **Deploy from a branch** > Branch: `main`, folder `/ (root)` > Save.
3. After a minute or two your site appears at `https://YOUR-USERNAME.github.io/REPO-NAME/`
   (or `.../court-climb/` if you uploaded the folder into an existing repository).

## Run a class
1. Open the page and choose **I'm the teacher**. You get a 4-letter class code.
2. Students open the same address (or use **Copy student link**), enter the code, and pick a nickname.
3. Use the arrow keys or Next/Prev to move through slides. On question slides, press **Reveal answer**.
4. **The Docket** button shows each student's case on the staircase. Keep the teacher tab open during class.

## If students on another network (Wi-Fi vs. wired) can't connect
Connections are peer to peer, so some school networks need a relay. Create a free account at
https://www.metered.ca/tools/openrelay/ , make an app, then open `index.html` and replace
`var TURN_RELAY={app:'',apiKey:''};` with your app name and API key. The teacher's title slide shows
**Relay: ON** when it is working.

## Notes
- Answer keys are in the page source, so a student who views source could find them.
- Nicknames and written dissents are student-typed and are not moderated.
- "Try it solo" runs the whole deck on one device with no network.
