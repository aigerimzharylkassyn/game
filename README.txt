THE HALLWAY — in-place horror upgrade

Open THE HALLWAY.html in a WebGL-capable browser with internet access for the
existing Three.js r128 CDN dependency. No backend, build step or new package
is required. Alternatively serve this directory with python3 -m http.server.

The original photographs, report, WASD/touch movement, inspection, keypad,
wrong-code lockout, invitation, acceptance and replay remain in the HTML.
Event fields in CFG.event still contain the original placeholders; replace
those with your event details. The password remains 7314, configured in CFG.

The new director H runs six fixed distance stages. Finding the first clue
starts it. Further stages require further clues, or successful door unlock.
The creature advances only during a 150 ms environmental lighting outage.
Recognition and looking away control encounter duration. The last encounter
waits for the correct password, then stops physiological audio, holds silence,
plays an inhale, and performs a short 3D lunge before the original ending.
Pause freezes game progression and suspends audio; inspection freezes the
director. Replay reloads the page, discarding all audio and state.

All new mesh geometry and procedural material textures are original code.
reference.png is used as a visual design reference, not redistributed as a
texture. No downloaded models, recordings or additional asset licenses.
Heartbeat, breath and impacts are synthesized Web Audio, not recordings.
Only one 512px shadow map was added; contact shading supplements the chair.

Validation: node tests/sequence.test.cjs
This tests the actual director source in isolation: clue gates, look-away
advancement, six distances, inspection pause, password gate, single attack,
and hallway bounds. It does not validate WebGL rendering or audible quality.

Manual browser QA still required: walk through all four photos and report;
check chair floor contact and wall decals; observe each blink while looking
back and while looking away; listen for acceleration and the final silence;
enter the code, see the lunge and invitation; accept and replay; repeat with
reduced flashing and touch controls. Inspect close facial lighting, frame
rate, console errors and any clipping. Browser testing was unavailable in
the implementation environment; these visual/audio checks are not claimed
as completed.

Follow-up: compared index.html's quick-turn and short face-reveal choreography.
index.html is retained as supplied; THE HALLWAY.html is the upgraded game.
Walk/run speeds are now 2.65 / 4.6 units per second. Q or the turn button
performs a smooth 180-degree turn. After unlocking, the director turns toward
the actual creature once if it is outside view. Mouse aiming uses a visible
ring that highlights interactable objects; clicking also interacts.
Encounter holds and gaps are shorter. The final lunge covers 1.04 units in
0.2 seconds before the brief face reveal and black cut.
Added woven cloth shirt, collar, buttons, sleeves, trousers, articulated
limb geometry and shoes; eight extra wall blood decals; eight ceiling-corner
cobwebs batched into one line mesh. Visual and audio QA remains pending.

Latest controls/atmosphere update:
- Circular vision with soft edges and an opaque outer mask.
- Entire creature uses a pure black unlit material, including eyes and teeth.
- Appearances alternate x=-0.91 and x=+0.91 while distance keeps decreasing.
- Unlocked mouse pointer: moving it looks around; holding it near an edge
  continues rotating to inspect all surroundings. Q/touch quick-turn remains.
- Escape pauses/resumes; walking audio uses travelled strides, with layered
  heel impact, sole slap and grit. No footsteps while inspecting or ended.

Siren Head atmosphere update:
- Corridor-scale procedural Siren Head with opposing toothed loudspeakers,
  exposed ribs, long arms and hooked fingers.
- Lower ambient and fixture lighting; approach-driven irregular flickering.
  Reduce flashing uses slow dimming instead of rapid approach flickers.
- Stronger, faster heartbeat with proximity and immediate beats on appearances.
- One-time player thoughts accompany clues, encounters and unlocking.
- In-app Browser was unavailable; visual/audio QA remains pending.
