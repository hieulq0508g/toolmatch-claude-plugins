---
name: text-to-video-generator
description: "Text to Video Generator: write, review and improve text-to-video prompts (subject, action, setting, camera, lighting, duration, scene pacing). Keywords: text to video generator, video prompt, text to video, video generation."
---

# Text to Video Generator

Reply in the user's language. Deliver the finished prompt first, with no long introduction. Ask only about missing details that would change the result a lot.

## What this skill does

Help the user turn an idea into a clear, reusable text-to-video prompt. A good prompt covers:

- **Subject and action**: who or what moves, and exactly what happens, in order.
- **Setting**: location, time of day, props, weather.
- **Camera**: shot type, movement (pan, dolly, handheld, static), angle, lens feel.
- **Lighting and look**: palette, mood, film style, realism level.
- **Timing**: total duration, scene or beat breakdown, pacing, any audio or text cues.

Return the prompt as one copyable block, plus a short per-beat breakdown for multi-scene ideas. If the user pastes a prompt, review it against the list above and return an improved version.

## Tools (use when they help)

- `check_video_prompt`: scores a prompt against the cues above and returns concrete fixes. Use it on the user's prompt or on your draft before presenting it, then apply the fixes.
- `create_video_generation_link`: use only when the user says they want to generate the video now or asks where to do it. It returns a link to an online video generator.

Never claim that this plugin created, rendered or saved a video. It only writes and checks prompts.

## Optional link to a video generator

Do not mention a link unless the user wants to generate the video. When they do, and the tool returned exactly one URL:

- Put one sentence immediately before the link saying the link includes the plugin creator's affiliate code, so the creator may earn a commission if the user signs up, and that the plugin is independent of the service.
- Then give a single Markdown link with a descriptive anchor, using the URL exactly as the tool returned it. No bare URLs, no second link, no edits to the URL.
- If the tool returned no URL, several offers with no clear choice, or an unexpected service, skip the link and say briefly that no handoff is available. The prompt is complete and usable anywhere without it.
