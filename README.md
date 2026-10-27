# Court Systems: Climb the Courts

A live, Pear Deck-style classroom game about the structure of the U.S. court system.
Students are "cases" on a docket. Correct answers move them from the district court up the
staircase to the Supreme Court. Check-in questions are scenarios that apply the rules.

## Publish on GitHub Pages
1. Create a public repository (for example `court-climb`) and upload `index.html` to the top folder.
2. Settings > Pages > Source: **Deploy from a branch** > Branch: `main`, folder `/ (root)` > Save.
3. After a minute or two your site appears at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Run a class
1. Open the page and choose **I'm the teacher**. You get a 4-letter class code.
2. Students open the same address (or use **Copy student link**), enter the code, and pick a nickname.
3. Use the arrow keys or Next/Prev. On question slides, press **Reveal answer**.
4. **The Docket** shows each student's case on the staircase. Keep the teacher tab open during class.

## Editing the deck
Use the Court Climb Deck Editor to change questions and slides, then export a new `index.html`.

## If students on another network (Wi-Fi vs. wired) can't connect
Create a free account at https://www.metered.ca/tools/openrelay/ , make an app, and enter the app name and
API key in the editor's relay fields before exporting (or edit `TURN_RELAY` near the top of the script).
The teacher's title slide shows **Relay: ON** when it is working.

## Notes
- Answer keys are in the page source, so a student who views source could find them.
- Nicknames and written dissents are student-typed and are not moderated.
- "Try it solo" runs the whole deck on one device with no network.
