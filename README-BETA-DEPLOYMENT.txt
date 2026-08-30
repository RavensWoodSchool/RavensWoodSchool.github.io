ZIGGY'S BLACK & GREEN QUEST — BETA RELEASE (student-ready)
================================================================
This is a clean build with the staff "Admin" testing panel removed.
Students will only be able to reach games the normal way — by
playing and earning the score to unlock them — with no shortcut
button visible anywhere.

Current feature set in this build:
  - Values memory match + the flight minigame
  - The First Day Adventure (entrance, bike shelter, Reception,
    Year 7 Playground, Form Time, Know Your Places) + free
    exploration across four school views
  - The Timetable Challenge (bedroom routine + pack-the-bag)
  - Black & Green Keepers — Scene 1 (The Form Room) and
    Scene 2 (The School Toilets) and Scene 3 (The School Site)
  - A branded loading screen
  - Two sound effects (confirm / correct-answer), with a mute
    toggle on the title screen — remembered between visits
  - The Ziggy Flight Challenge bonus mode, unlocked once every
    other game is unlocked
  - Progress (best scores, unlocked games) is remembered per
    device/browser


WHAT'S IN THIS FOLDER
----------------------
  index.html              The game itself (~124KB)
  assets/                  42 files — images and the two sound effects
  README-BETA-DEPLOYMENT.txt   This file

index.html and the assets folder must stay together, in the same
relative position to each other, wherever you upload them.


DEPLOYING TO YOUR GITHUB PAGES SITE
--------------------------------------
1. Upload this entire folder (index.html + assets/) to your GitHub
   Pages repository, keeping the same structure.
2. Once GitHub Pages rebuilds (usually under a minute), open the
   live address fresh — not from a cached tab.
3. Quick pre-flight check before sharing the link with any students:
     - Loading screen appears and the poses cycle
     - Title screen shows the school name and Start button
     - No "Admin" button is visible anywhere (bottom-right of the
       title screen, where it used to sit) — if you still see it,
       you're looking at the wrong file
     - Sound plays on a correct answer, and the 🔊 mute toggle
       (bottom-left of the title screen) works
     - Play through at least one full game on both a phone
       (portrait) and a laptop

If you ever need to make further changes, come back to Claude with
the working copy (the one WITH the Admin panel) — don't edit this
beta build directly, since it's a generated, stripped-down copy of
that source, not the master version.


STILL TO COME
----------------
Black & Green Keepers' Canteen scene is not yet built. Everything
else currently planned is in this build.
