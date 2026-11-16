# PLAN.md: "The Pig on Trial" (Savigny, 1457)

Format: 9:16 vertical, 1080p, 30fps
Duration: 37.8 s narration, 1135 frames (0-1134 inclusive)

PROVISIONAL: frame ranges are estimated from narration word counts (111 words, about 10.2 frames per word). Re-align every boundary to work/phrases.json once timing.py has run. The engine repo is not available yet, so these are not verified against the audio.

Rule check: no shot holds longer than 90 frames. No camera angle repeats consecutively.

| # | Frames | Narration (approx.) | Setting | Light | Camera | Characters | Props / FX | SFX |
|---|---|---|---|---|---|---|---|---|
| 1 | 0-66 | "In fourteen fifty-seven, a French court put a pig on trial for murder." | Dark stone courtroom | Dramatic | MCU judge, slow push-in | Judge (stickman, gavel) | Candle flicker | Low drone starts |
| 2 | 67-133 | "...for murder." | Courtroom, wide | Dramatic | Wide, creep in | Judge, sow at the defendant's bench | Benches, banners | Gavel thunk |
| 3 | 134-200 | "The village of Savigny, in Burgundy, had a serious problem." | Savigny village, daytime | Day | Bird's eye, slow pull | Villagers scattered in lanes | Half-timbered houses, dust | Crowd murmur |
| 4 | 201-234 | (village end) | Dirt road, wooden signpost | Day | Insert, signpost push | None | Wind-stirred leaves | Wind |
| 5 | 235-300 | "A sow had attacked a little boy, and everyone demanded justice." | Village square | Golden | Low angle, villagers looming | Villagers, little boy (small stickman, reaction) | Dust puff | Murmur swells |
| 6 | 301-348 | (line end) | Square, close | Golden | Over-the-shoulder on villager pointing | Pointing villager | Pointing arm anticipation | Sharp murmur |
| 7 | 349-410 | "The court assigned the accused a lawyer, as the rules demanded." | Courtroom | Day | Two-shot, judge and lawyer | Judge, lawyer (stickman, papers) | Papers flutter | Quill scratch |
| 8 | 411-460 | (line end) | Courtroom desk | Day | Insert close-up on the scroll | None | Ink drip | Scroll rustle |
| 9 | 461-520 | "Yes, the pig got a lawyer, and the court took it seriously." | Courtroom | Day | Environment move, cross the room | Crowd of stickmen | Floating dust | Shuffling feet |
| 10 | 521-583 | (line end) | Courtroom | Day | Bird's eye on the floor plan | Stickmen, pig at bench | Bench shadows | Quiet |
| 11 | 584-644 | "Villagers laughed at the idea." | Courtroom | Day | Wide reveal, crowd laughing | Laughing stickmen | Hat tip flick | Laughter, bubble pop |
| 12 | 645-700 | "But the judges followed every procedure, down to the last letter." | Courtroom | Night-blue | MCU judge, cold light | Judge | Gavel rests | Low hit |
| 13 | 701-756 | (line end) | Judge's bench | Night-blue | Reaction close-up, judge frowns | Judge | Rolled document | Scroll unroll |
| 14 | 757-820 | "Witnesses testified, and the evidence pointed one way." | Witness stand | Day | Over-the-shoulder, witness talking | Witness, judge | Stand creak | Gentle murmur |
| 15 | 821-838 | (line end) | Witness stand | Day | Insert close-up, evidence cloth | None | Dust motes | Ting on reveal |
| 16 | 839-900 | "The sow was sentenced to hang for her crime." | Courtroom | Golden | Low angle, judge's verdict | Judge | Sun shafts | Gavel slam (1 hit, not gory) |
| 17 | 901-930 | (line end) | Courtroom | Golden | Two-shot, judge and lawyer | Judge, lawyer | Lawyer bows head | Soft drone |
| 18 | 931-1000 | "Her piglets were spared, too young to share the blame." | Courtroom doorway | Golden | Environment move, pig family walks past | Six piglets (small props), stickman guard | Door creak | Hooves on wood |
| 19 | 1001-1032 | (line end) | Doorway | Golden | Insert, small hooves on threshold | None | Dust | Light steps |
| 20 | 1033-1100 | "Six piglets walked free. Bad parenting was the real crime." | Doorway, piglets exit | Dramatic | MCU push-in with 4° roll, twist | Piglets, judge (background) | Music stops | Low hit + sting |
| 21 | 1101-1134 | (twist hold) | Doorway, fade | Dramatic | Wide pull-back, slow creep | Piglets, stickmen | Final dust | Drone holds |

Notes for the render:
- Shot 20 is the twist: music stops, low hit, push-in with roll.
- The sow's sentence is off-screen. The shot shows only the gavel and the judge, so the scene stays non-graphic.
- Every character gets idle breathing and blinks, per the motion rules.
- Shot 4 is a 34-frame hold, so it stays under the 4-second limit.
