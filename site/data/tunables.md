# Tunables

Generated from `@tune` headers by the menu `CGDD/Export Trace Docs`. Hand edits are overwritten on the next export.

| Script | Field | Type | Range | Default | Note |
| --- | --- | --- | --- | --- | --- |
| AmbientAudio | droneVolume | float | 0-0.4 | 0.16 | Background drone level. |
| AmbientAudio | ventVolume | float | 0-0.3 | 0.09 | Ventilation hum level. |
| BlinkingLight | period | float | 0.2-5 | 1.2 | Seconds per blink cycle. |
| BlinkingLight | onFraction | float | 0-1 | 0.5 | Fraction of each cycle the LED is on. |
| BlockoutSeat | eyeHeight | float | 0.8-1.8 | 1.25 | Eye height above the floor while seated. |
| BlockoutSeat | maxHeadTurn | float | 0-180 | 110 | Degrees the head can turn left or right from the chair's facing. |
| BlockoutWalker | walkSpeed | float | 1-8 | 4 | Walking speed. |
| BlockoutWalker | runSpeed | float | 1-12 | 6.5 | Running speed with Shift. |
| BlockoutWalker | jumpHeight | float | 0-3 | 1 | Jump height in metres. |
| BlockoutWalker | gravity | float | -40--5 | -20 | Gravity while walking. |
| BlockoutWalker | eyeStanding | float | 0.8-2 | 1.5 | Standing eye height. |
| BlockoutWalker | lookSensitivity | float | 1-15 | 5 | Mouse look sensitivity. |
| BlockoutWalker | interactDistance | float | 0.5-5 | 2.5 | Metres for the look-at chair interaction. |
| BlockoutWaypoint | waitSeconds | float | 0-60 | 0 | Seconds the watcher stands here. |
| DeskPuzzle | tolerance | float | 1-20 | 4 | Degrees from perfect that still counts as aligned. |
| DeskPuzzle | keyRotateSpeed | float | 10-180 | 60 | Phone rotation speed with A or D. |
| DeskPuzzle | mouseRotate | float | 0.5-10 | 3 | Phone rotation per unit of mouse movement. |
| Fluorescent | buzzVolume | float | 0-0.2 | 0.07 | Tube buzz level. |
| Fluorescent | master | float | 0-1 | 1 | Level dimmer for this fixture, 0 = off. |
| Footsteps | stepLength | float | 0.2-1.5 | 0.7 | Metres travelled per footstep. |
| Footsteps | volume | float | 0-1 | 0.55 | Footstep volume. |
| Footsteps | pitch | float | 0.5-1.5 | 1 | Pitch of the footsteps. |
| Footsteps | minDistance | float | 0-5 | 1.5 | Distance where footsteps are at full volume. |
| Footsteps | maxDistance | float | 2-30 | 18 | Distance where footsteps fade out. |
| Footsteps | keysEverySteps | int | 0-10 | 0 | Steps between key jingles, 0 = never. |
| HumSource | volume | float | 0-1 | 0.8 | Humming volume. |
| HumSource | maxDistance | float | 1-15 | 6.5 | Distance where the humming fades out. |
| Level01Director | answerSeconds | float | 5-30 | 10 | Seconds to answer a question. |
| Level01Director | callInterval | Vector2 | 20-90 | — | Seconds between questions (x to y). |
| Level01Director | firstCallAtBootSecond | float | 1-10 | 3 | Seconds into the phone boot for the first question. |
| Level02Director | reachDistance | float | 1-10 | 4 | Distance at which the phone can signal her phone. |
| Level03Director | lightNoticeSeconds | float | 0.5-4 | 1.6 | Seconds of phone light before the warden notices. |
| Level03Director | awakeNoticeSeconds | float | 1-6 | 3.2 | Seconds sitting up during a bed check before he notices. |
| Level04Director | answerSeconds | float | 5-30 | 10 | Seconds to answer a question. |
| Level04Director | callInterval | Vector2 | 10-60 | — | Seconds between questions (x to y). |
| Level04Director | inspectionFallbackSeconds | float | 30-240 | 100 | Seconds after taking the phone before inspection starts if the photo is missed. |
| Level04Director | choiceSeconds | float | 5-30 | 14 | Seconds to choose an ending. |
| LevelDirectorBase | chances | int | 1-5 | 3 | Warnings before the phone is taken. |
| LevelDirectorBase | noticeSeconds | float | 0.5-6 | 2.5 | Seconds seen with the phone before danger is full. |
| LevelDirectorBase | dangerDecayPerSecond | float | 0.05-2 | 0.35 | How fast danger drains when nobody is looking. |
| LevelDirectorBase | graceAfterWarning | float | 0-10 | 3 | Seconds of safety after a warning. |
| LevelDirectorBase | interactDistance | float | 0.5-4 | 1.8 | Metres for the look-at interaction ray. |
| LevelDirectorBase | teacherLineSeconds | float | 2-15 | 7.5 | Default seconds for an authority line. |
| LevelDirectorBase | thoughtSeconds | float | 2-15 | 7.5 | Default seconds for a thought line. |
| LevelDirectorBase | gapBetweenLines | float | 0-5 | 1.4 | Silence between subtitle lines. |
| LevelDirectorBase | typeCharsPerSecond | float | 10-150 | 55 | Typewriter speed for subtitles. |
| PatrolAI | waitTime | Vector2 | 0-10 | — | Seconds waiting at a roam point (x to y). |
| PatrolAI | scanAngle | float | 0-120 | 55 | Degrees the head sweeps while waiting. |
| PatrolAI | scanSpeed | float | 0.1-2 | 0.6 | Head sweep speed. |
| PhoneController | bootSeconds | float | 1-15 | 5 | Seconds the old phone takes to start up. |
| PhoneController | raiseSeconds | float | 0.05-1 | 0.25 | Seconds to raise the phone. |
| PhoneController | lowerSeconds | float | 0.05-1 | 0.3 | Seconds to lower the phone. |
| PhoneController | readCharsPerSecond | float | 5-80 | 22 | Message typewriter speed. |
| PhoneController | glowIntensity | float | 0-5 | 1.6 | Screen glow light intensity in the dark. |
| PlayerRig | walkSpeed | float | 1-5 | 2.8 | Walking speed. |
| PlayerRig | runSpeed | float | 1-8 | 4.2 | Running speed with Shift. |
| PlayerRig | gravity | float | -40--5 | -20 | Gravity while walking. |
| PlayerRig | standingEye | float | 0.8-2 | 1.5 | Eye height when standing. |
| PlayerRig | pullSpeed | float | 0.5-4 | 1.3 | Speed when pulled to the seat. |
| PlayerRig | sensitivity | float | 1-15 | 5 | Mouse look sensitivity. |
| PlayerRig | inspectPitch | float | -30-45 | 8 | Pitch when looking into the desk. |
| PlayerRig | placingPitch | float | 0-90 | 55 | Pitch when looking at the desk top. |
| PlayerRig | lyingPitch | float | -60-10 | -28 | Pitch when lying in bed. |
| SeatedLook | sensitivity | float | 1-15 | 5 | Mouse look sensitivity. |
| SeatedLook | maxYaw | float | 0-180 | 100 | Maximum head turn from centre. |
| SeatedLook | minPitch | float | -90-0 | -55 | Maximum look down. |
| SeatedLook | maxPitch | float | 0-90 | 60 | Maximum look up. |
| SweepRotate | amplitude | float | 0-180 | 35 | Degrees swept to each side of the starting direction. |
| SweepRotate | period | float | 1-60 | 10 | Seconds for one full left-right-left sweep. |
| TeacherAI | lectureTime | Vector2 | 3-20 | — | Lecture duration range (x to y). |
| TeacherAI | boardTime | Vector2 | 2-15 | — | Board-writing duration range (x to y). |
| TeacherAI | lookAroundTime | Vector2 | 1-8 | — | Look-around duration range (x to y). |
| TeacherAI | lectureWeight | float | 0-1 | 0.35 | Chance the next activity is lecturing. |
| TeacherAI | boardWeight | float | 0-1 | 0.3 | Chance the next activity is writing on the board. |
| TeacherPatrol | walkSpeed | float | 0.2-4 | 1.2 | Metres per second along the route. |
| TeacherPatrol | turnSpeed | float | 30-720 | 240 | Degrees per second when turning. |
| TeacherVision | viewAngle | float | 20-180 | 90 | Full width of the view cone in degrees. |
| TeacherVision | viewRange | float | 2-30 | 12 | How far the watcher can see. |
| TeacherVision | eyeHeight | float | 0-3 | 1.6 | Eye height above the watcher's feet. |
| WallClock | startHour | float | 0-24 | 8.9167 | Hour shown when the level starts. |
| WallClock | minutesPerSecond | float | 0-2 | 1 | Game minutes per real second, 1/60 = real time. |

