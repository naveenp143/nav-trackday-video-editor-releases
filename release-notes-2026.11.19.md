## 2026.11.19

### Cameras and data sources
- **GoPro HERO** (HERO9 to HERO13) joins the Camera box, with **AiM Solo 2, RaceBox or RaceChrono**
  as the data source. It is edited like the DJI: the wide picture as shot, every number from the
  logger, lined up by how the picture swings through the turns. The GoPro's clock is often whole
  hours out, and that is allowed for. Set for the Wide lens; a recording the GoPro split into parts
  is edited part by part.
- **RaceChrono.** Sessions exported from the RaceChrono app (CSV, either layout, or VBO) are read.
  Not yet tried on a real RaceChrono file.

### Fixes
- The download no longer carries the developer's working notes.

## 2026.11.18

### Cameras and data sources
- **Pick the camera, then the data.** Two new boxes at the top of the window: **Camera** (make and
  model) and **Data source**. Each pairing has its own way of making the edit:
  - **Insta360 X series (X3, X4, X5, X6)** with Insta360 GPS, RaceBox or AiM Solo 2: the full 360
    edit as before.
  - **Insta360 GO 3S** with RaceBox, AiM Solo 2 or Insta360 GPS, and **DJI Osmo Action 5 Pro** with
    RaceBox or AiM Solo 2: the wide picture as shot, with pushes in for the replays. Every number
    comes from the logger, lined up with the picture by how the view swings through the turns.
    Overtakes, the rev light, body position and the views round the bike need a 360 camera and are
    left out.
- **AiM Solo 2.** The logger's own `.xrk` files are read directly (no export needed), and a Race
  Studio CSV export works too. Laps are AiM's own times; the out-lap and in-lap are left out.
- **When the picture and the data do not match**, a wide-camera run stops and says so instead of
  guessing. A camera clock set to the wrong time zone is allowed for; `--logger-offset` lines the
  two up by hand.
- Only tested so far on an X4, a GO 3S and an Osmo Action 5 Pro, and AiM only on its own.
