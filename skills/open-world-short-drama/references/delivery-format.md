# Mission packet format

## Series header

- Title, logline, selected format and timing, and a short synopsis including the ending.
- Canonical cast and asset bible. Give each recurring asset an ID and a portable text descriptor. Establish visual geography, recurring wardrobe, object ownership, voice, and optional overlay layout.
- One-line cause-and-effect spine from M01 through M10. Assets may change only at an explicit event. Record that event and carry the changed state forward.

## Each mission

Label each mission with its ID and a distinct title.

1. **Objective and handoff.** State what happened immediately before, what the characters want here, and what visible outcome sets up the next mission. Resolve the central question on the last mission.
2. **Opening image prompt.** Specify the frame at second zero. Include aspect ratio, shot size, camera orientation, composition, scene lighting, visible character descriptions and poses, and the current location and state of key objects. Describe visual texture using concrete details such as reflected wet neon, humid air, and third-person camera height. Leave out overlays if they compete with the frame. If enabled, reserve a consistent area for a custom overlay and composite precise labels in editing.
3. **Video prompt.** Restate the opening composition and visible asset descriptions, then describe the moves in order with approximate timings, focused character reactions, scene audio, camera behavior, and the final frame. Keep still and video inputs usable without referring to previous text. A cut between missions can bridge a location change; the reason for the move belongs in the handoff.
4. **Narration and character dialogue.** Put narration and on-screen dialogue in separate fields, with speaker IDs and approximate time slots. Keep speech short enough to fit. Narration may be added in post. If dialogue has no useful role, state “No on-screen dialogue” and leave that time for visual action or ambient audio. Exact speech and on-screen text can be added during editing if the chosen generator does not reproduce them reliably.
5. **Continuity out.** Give the viewer a visible answer or question and record any object, time, wardrobe, or location changes that the next scene must honor.

## Paste-ready first-scene brief

Give a short block containing the premise, relevant cast descriptions, format, three visual beats, opening composition, final frame, and dialogue where present. Use the opening, action, and final frame already established for M01. The user can paste the brief into LuxReal and check its storyboard before spending time rendering. If a change is needed, correct the bible or the one affected shot and recheck the downstream handoff.
