# NAV Track Day Video Editor: release notes

Versions are the date of the build (year.month.day). Newest first.

## 2026.11.17

### Coaching
- **Ghost line.** Chase your own best lap on the track map: a ghost ring to follow, the gap to it
  under the lap clock, and your trail green where you are gaining and red where you are losing. The
  review page sets every lap against it, turn by turn. One tick box: **Ghost line on the map**.
- **Ride against a coach.** Give it a coach's RaceBox file (`.csv` or `.vbo`) from the same track and
  their fastest lap becomes the ghost. Every clear run through every turn is judged against theirs:
  brake marker and force, entry, apex and exit speed, gas, coasting, line and lean, with targets in the
  coach's own numbers. On the ride, on an **Against the coach** debrief card and on the page.
- **Top 3 fixes.** The review page opens with the three turns that cost the most. Type `fixes` in
  **Try it** for a short video of each: the run that shows it, then your best run through that turn.
- **Brake feel.** How quickly the brake is built, how it is eased off into the turn, and a second
  squeeze, as pointers and on the page.
- **Lap to lap.** A table on the review page of how much each turn moves from lap to lap: brake
  marker, line, apex and exit speed, gas point and lean.
- **Track use.** How much of the track each turn leaves unused on the way in, at the apex and on the
  way out, against the widest line ridden there all session.
- **Mistake reel.** Type `mistakes` in **Try it** for a short video of the session's dearest single
  mistakes: up to eight runs, each tagged with its turn, its lap and the time it lost, and captioned
  with what went wrong.
- **Only turns.** Pick the track from the list and tick one turn or a few, and the coach speaks of
  those turns alone: the pointers on the ride, the debrief's lists and plan, the top fixes and the
  mistake reel. Nothing is typed, and the box for typing turn numbers is gone: the list has 34 US
  tracks and their 93 layouts (track list from gettrackmaps.com, CC BY-SA 4.0), and a track that is
  not in it shows its turns once a run has found them. The review page still covers every turn. With nothing
  ticked, every turn is coached as before.
- **Room in a pass.** The coach has a word on each overtake: a clean pass with room alongside is
  praised (twice a session at the most), a close or tight one is corrected with the six feet all the
  way round a track day asks for, and the debrief counts them. Judged from how big the other bike
  looked alongside: a guide, not a measurement, and it does not see how soon you pull back in front.
- **Body position (experimental, off by default).** With the camera on the tank looking back at the
  rider, the review measures how far the head moves to the inside in each turn, lefts against rights.
  It needs a helmet or visor with some orange or red on it, and says so when it cannot see the rider.
  The coach speaks of it on the ride only where there is something to correct, and the debrief has
  a **Body position** card; on the review page it sits right under the three lists.

### The app
- The window no longer turns slow or stops answering: the **from** box under **Try it** keeps only a
  time or a short word (`fixes`, `mistakes`, `review`). A long paste left there used to be measured
  again at every blink of the cursor.
- The divider's up-and-down arrow no longer stays on the whole window.

### Voices
- **Indian Uncle and Chinese Coach** are back in the list of the coach's voices, on a computer that
  has an Indian English or a Chinese voice installed (Windows: Settings, Time & language, Speech,
  Add voices).

### Please note
- **A notice at the bottom of the window**, on the review page, in the manual and in READ ME FIRST: the
  coaching is for information only, an indication that can be wrong, and no substitute for a real
  coach at a track day.

### Fixes
- **Whole session runs straight through.** The riding now starts where the opening ends and runs
  up to the sign-off, joined by a plain dissolve. Before, about ten seconds were skipped after the
  title and a few before the sign-off.
- Frame timing is measured correctly when the small preview file (`.lrv`) is picked as the recording.

## 2026.11.15

### Coaching
- **Session review rewritten.** The debrief at the end now gives the best lap time, whether you got
  quicker or dropped off through the session, how consistent the laps were, what each turn costs on a
  typical lap, which part of the corner loses most (way in, mid-corner, way out, line), the weakest
  sector, and a **Next session** plan: one turn, one skill, one lap time.
- The three lists (doing right, can improve, needs a change) are in the order of what each turn costs,
  each fault is spoken with that cost, and every "needs a change" item has a target.
- A run on your best still gets a **next step**: what the data shows is left in it.
- End-of-lap line: how far off your best, the turn that cost most, and why.
- Coaching covers race line, vision, trail braking, the 1-1000 count method, throttle and grip, with
  alternate wordings so the same line is not repeated every lap.
- The coach speaks faster, and cuts a pointer to the fix alone when the next turn is close.
- **Coach on:** every turn of every lap, fastest and slowest lap, fastest lap only, slowest lap only.
- **Five distinct voices:** calm coach (woman or man), hype commentator, British deadpan, Aussie
  trash-talker.

### On the video
- Current-lap timer at the top centre; the left box shows the best lap.
- The track map is larger and carries every turn number.
- Circuit turn numbers for Barber, Carolina Motorsports Park, Atlanta Motorsports Park and Road
  Atlanta; any track can be numbered by typing its numbers once in **Turn numbers**.

### The app
- Opens with all options showing.
- Pressing Start folds the options away so progress fills the window.
- Music: one file, or a folder a track is picked from at random for each video.
- The review page opens with "The session in short" and the plan.

## 2026.11.13

- Three packages: Windows (locked: machine code, no source), Windows (open) and Mac (Apple Silicon).
- Whole-session edits, 11 colour themes, a jokes count, one joke a pointer with coaching first.
