# Big Bang Games

Games for the Wazoku Friday Big Bang. They're hosted free on GitHub Pages, with no servers or accounts.

**Home page:** https://destillero-wz.github.io/big-bang-games/

| Game | Host screen | Notes |
|---|---|---|
| Boggle | https://destillero-wz.github.io/big-bang-games/boggle/?host | [boggle/README.md](boggle/README.md) |
| Jeopardy | https://destillero-wz.github.io/big-bang-games/jeopardy/ | See below |
| Wazoku Says (Family Feud) | https://destillero-wz.github.io/big-bang-games/feud/ | See below |

## Wazoku Says (Family Feud)

- **Setup:** add questions in **✏️ Edit questions**. Each has up to 8 answers, with points usually meaning how many people out of 100 said it. You can also load the ready-made Halloween, autumn & work life set. Add players in **🏆 Scores**.
- **Playing:** read the question. When someone names an answer that's on the board, click it (or press **1–8**) to flip it, then click their name to give them its points. For a wrong guess, click **❌ Wrong answer** (or press **X**) to show the big X with a buzzer sound. Use **← →** to move between questions.
- **↺ Reset game** hides all the answers again and keeps the scores.

## Jeopardy

- **Playing:** click a tile to show the question. Press **Space** to reveal the answer and **Esc** to go back to the board. Used tiles go dark.
- **Daily Double:** a splash screen appears first, and the question is worth double.
- **Scores (optional):** in **🏆 Scores**, add players. After revealing an answer, click the name of whoever got it to give them the points. You can also adjust scores with the +100 and −100 buttons.
- **Editing:** use **✏️ Edit questions** to change the title, categories, questions and answers, and to pick the Daily Double (or use **🎲 Random**). Edits are saved in that browser only, so use **Download questions file** to keep a copy and **Load questions file** to use it on another computer.
- **↺ Reset board** makes every tile available again and keeps the scores.
- **Pictures:** any question can show a picture. In the editor, paste a picture link into "Picture link (optional)". Country silhouettes are in `jeopardy/img/`, for example `img/italy.svg`. They're drawn from Natural Earth map data, which is public domain.
- **Ready-made sets:** in the editor, choose a set and click **Load ready-made set**. The sets are "2026 in Review + Name That Country" (the default) and "General knowledge".

Each game lives in its own folder. Add a card for each new game to `index.html`.
