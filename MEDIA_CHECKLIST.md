# Media checklist

## Status (October 2026)

52 of 65 files are already in `media/`, collected from papers, official company pages, government sources and Wikimedia Commons. Credit lines are filled in on each card.

**Still missing (13 files):**
- `2021-06_github-copilot-demo.mp4`: no direct video file exists. Record your own.
- `2024-05_gpt4o-voice-demo.mp4`: OpenAI hosts the demo only on YouTube.
- `2025-02_vibe-coding-demo.mp4`: your own screen recording.
- `2025-03_ghibli-original-photo.jpg` and `2025-03_ghibli-style-version.jpg`: your own photo, and ChatGPT's version of it.
- `mj-compare_v1.png` … `mj-compare_v8.png`: Midjourney's old official comparison pages are gone. You need to make these yourself.

**Files that differ from the table below:**
- **Rubik's Cube** (`2019-10_…`): a photo, not a video.
- **Computer use** (`2024-10_…`): the demo video's title frame, not a video.
- **Beijing marathon** (`2026-04_…`): a photo, not a video.
- **Waymo** (`2023-08_…`): filmed in Los Angeles in 2026.
- **Veo 3** (`2025-05_veo3-…`): Google's official sailor sample with speech, not spaghetti.
- **Nobel** (`2024-10_…`): a group photo of the 2024 laureates.
- **DARPA** (`2015-06_…`): shows the robot hanging in its tether after a fall, not the fall itself.
- **Duplex** (`2018-05_…`): the real call audio over a black frame.

To replace any file, drop a new one in with the same name.

Put every file in `media/`, using exactly the filename shown. Until a file is there, its card shows a placeholder saying what belongs in it. Press **M** in the presentation to see which files are still missing.

**Formats**
- Video: MP4 with H.264. That plays everywhere, including offline. Keep clips short (5–20 s) and trimmed to the interesting part.
- Audio: MP3.
- Images: JPG/PNG, about 1600 px on the long side.

**Real outputs only.** Every "before" image or clip must be the actual output of the historical model. Never recreate or fake an "old-looking" result.

**Credit line.** To show a credit on screen, add `credit: "…"` to that milestone's `media` block in `index.html`, e.g. `credit: "Video: Google DeepMind"`.

### Licence notes

This is general guidance, not legal advice. Every row below is tagged with one of these:

| Tag | Meaning | What to do |
|---|---|---|
| **OWN** | You make it: your own screenshot, recording, chart or AI generation | No third-party rights. For AI generations, check the tool's terms (paid Midjourney / ChatGPT / Gemini plans let you use your outputs). |
| **PD** | US government work (DARPA, NASA, FCC) | Public domain in the US. A credit is still good practice. |
| **PRESS** | Images or video from a company's blog, paper or press page | Copyrighted. Showing short excerpts in a talk usually falls under fair use (US) or the quotation right (EU, e.g. §51 UrhG in Germany). **Credit the source on screen.** If the talk is recorded, published or paid, ask the company's press office or use only OWN/PD material. |
| **NEWS** | Screenshot of a news headline or article | Same as PRESS: a brief quotation with the outlet named. |
| **UGC** | A clip or image posted by an individual (Reddit, X) | Same as PRESS, and credit the creator by username. |

## ★ Key moments: collect these first

| # | Filename | What it should show | Where to find it | Licence |
|---|---|---|---|---|
| 1 | `2014-06_gan-faces-original-paper.png` | The real 2014 GAN face samples (grey, blurry). Left side of the slider. | Goodfellow et al., *Generative Adversarial Nets*, arxiv.org/abs/1406.2661. Open the PDF, Figure 2, and crop the face panel (Toronto Face Database samples). | PRESS (paper), credit "Goodfellow et al., 2014" |
| 2 | `2026_ai-portrait-today.jpg` | A photorealistic portrait from a current model. Right side of the slider. Square crop works best. | Generate it yourself, e.g. Midjourney V8, Gemini or ChatGPT: "studio portrait photo of a smiling woman, natural light". | OWN |
| 3 | `2016-03_alphago-lee-sedol-match.jpg` | Lee Sedol at the board vs. AlphaGo | A still from Google DeepMind's free documentary *AlphaGo* (2017, on DeepMind's YouTube channel), or DeepMind's AlphaGo page | PRESS, credit "Google DeepMind" |
| 4 | `2022-11_chatgpt-launch-interface.png` | What ChatGPT looked like at launch | Sample conversations in OpenAI's launch post (openai.com/index/chatgpt) or screenshots in Dec 2022 news coverage | PRESS / NEWS |
| 5 | `2024-05_gpt4o-voice-demo.mp4` | GPT-4o talking, laughing or singing in real time | OpenAI's YouTube channel, May 2024 GPT-4o demo videos (e.g. the live conversation or "two GPT-4os singing") | PRESS, credit "OpenAI" |
| 6 | `2024-10_nobel-chemistry-announcement.jpg` | The 2024 Chemistry laureates (Baker, Hassabis, Jumper) | nobelprize.org → Chemistry 2024 → press images / illustrations | PRESS, credit "© Nobel Prize Outreach" (check their image terms) |
| 7 | `2025-02_vibe-coding-demo.mp4` | Someone types one sentence and a working app appears (sped up, ~15 s) | Record your own screen with Claude, ChatGPT, Lovable or similar | OWN |
| 8 | `2023-03_will-smith-spaghetti-original.mp4` | The original melting spaghetti clip (also used as the "2023" half of the Veo comparison) | Originally posted by u/chaindrop on r/StableDiffusion, March 2023, made with ModelScope text-to-video. Widely re-uploaded on YouTube. Use a copy that is clearly the original. | UGC, credit "u/chaindrop / ModelScope, 2023" |
| 9 | `2025-05_veo3-spaghetti-with-sound.mp4` | The same idea made with Veo 3 / 3.1, with audio | Best: generate it yourself in Gemini/Flow with Veo ("a man eating spaghetti at a kitchen table, eating sounds"). Avoid a real person's likeness; it doesn't need to be Will Smith. | OWN |
| 10 | `2025-07_imo-gold-ai.jpg` | IMO 2025 / the gold-medal announcement | Header image of DeepMind's IMO gold post, or IMO 2025 official photos (imo-official.org) | PRESS |
| 11 | `2015-06_darpa-robots-falling.mp4` | Robots toppling at the DARPA Robotics Challenge (also the "2015" half of the marathon comparison) | DARPA's own DRC Finals footage (DARPA YouTube channel), or IEEE Spectrum's well-known "robots falling down" compilation from June 2015 | DARPA's footage: PD. IEEE Spectrum's compilation: PRESS, with credit. |
| 12 | `2026-04_beijing-robot-half-marathon.mp4` | The winning robot running in Beijing, April 19 2026 | News footage from Reuters, AP, CGTN or Xinhua (YouTube) | NEWS, credit the agency |
| 13 | `2026-09_fluid-vortex-visualization.jpg` | Swirling fluid / vortex (purely illustrative) | NASA image libraries (images.nasa.gov), e.g. NASA Langley's coloured-smoke wingtip-vortex photo | PD, credit "NASA" |

## Image and video comparisons

| Filename | What it should show | Where to find it | Licence |
|---|---|---|---|
| `mj-compare_v1.png` … `mj-compare_v8.png` (8 files) | **One identical prompt** rendered with each Midjourney version V1 → V8, square crop | Run it yourself in Midjourney with `--v 1`, `--v 2` … `--v 8`, same prompt. Midjourney's docs list V1–V3 as "legacy" versions you can still select; check this first. If an early version can no longer be selected, leave that slot empty. Do not substitute anything else. | OWN |
| `2025-03_ghibli-original-photo.jpg` | A photo you took (you, your team, your city) | Your camera | OWN |
| `2025-03_ghibli-style-version.jpg` | The same photo converted to Ghibli style | ChatGPT: upload the photo, "turn this into a Studio Ghibli-style illustration" | OWN |

## All other milestones (date order)

| Filename | What it should show | Where to find it | Licence |
|---|---|---|---|
| `2015-02_deepmind-atari-breakout.mp4` | DQN playing Breakout and discovering the tunnel trick | DeepMind's 2015 Breakout footage (widely re-uploaded on YouTube, e.g. "DeepMind DQN Breakout") | PRESS, credit "Google DeepMind" |
| `2016-03_microsoft-tay-profile.png` | Tay's Twitter profile or a shutdown headline. **No offensive tweets.** | News coverage from 24–25 Mar 2016 (The Verge, BBC) | NEWS |
| `2016-09_wavenet-speech-samples.mp3` | An old-style computer voice, then WaveNet (10–15 s) | The audio samples embedded in DeepMind's WaveNet blog post | PRESS, credit "Google DeepMind" |
| `2016-10_microsoft-speech-parity.jpg` | The Microsoft research team, or the headline | Microsoft's Oct 2016 blog post (link is in the card) | PRESS |
| `2017-01_libratus-poker-match.jpg` | The "Brains vs. AI" poker match in Pittsburgh | CMU news story (link in the card) | PRESS, credit "Carnegie Mellon University" |
| `2017-12_alphazero-chess.jpg` | A chessboard from an AlphaZero game | Make your own: load a published AlphaZero vs. Stockfish game in lichess.org's analysis board and screenshot it | OWN |
| `2018-05_google-duplex-salon-call.mp4` | The hair-salon call with the on-screen transcript | Google I/O 2018 keynote on Google's YouTube channel (the Duplex segment) | PRESS, credit "Google" |
| `2018-12_waymo-one-phoenix.jpg` | A Waymo minivan in Phoenix, 2018 | Waymo press resources (waymo.com) | PRESS, credit "Waymo" |
| `2019-02_gpt2-unicorn-sample.png` | The "unicorns in the Andes" text sample | OpenAI's GPT-2 post. Screenshot the sample text. | PRESS |
| `2019-02_stylegan-faces.jpg` | A grid of StyleGAN faces | The NVlabs/stylegan GitHub repo or the paper (arxiv.org/abs/1812.04948) | PRESS. The repo's images are CC BY-NC 4.0: credit "NVIDIA, Karras et al.", non-commercial use. |
| `2019-04_openai-five-vs-og.jpg` | The OpenAI Five Finals event | OpenAI's OpenAI Five post / YouTube | PRESS |
| `2019-10_openai-robot-hand-rubiks-cube.mp4` | The robot hand turning the cube | OpenAI's "Solving Rubik's Cube with a Robot Hand" video (YouTube) | PRESS, credit "OpenAI" |
| `2020-09_guardian-gpt3-article.png` | The Guardian headline "A robot wrote this entire article…" | theguardian.com (link in the card) | NEWS |
| `2020-11_alphafold-protein-prediction.mp4` | Predicted protein structure overlaid on the lab result | Animation in DeepMind's AlphaFold CASP14 post | PRESS, credit "Google DeepMind" |
| `2021-01_dalle-avocado-armchair.jpg` | The avocado armchairs | OpenAI's original DALL·E post | PRESS, credit "OpenAI" |
| `2021-06_github-copilot-demo.mp4` | Copilot suggesting code as you type | GitHub's 2021 launch demo, or record your own | PRESS or OWN |
| `2022-02_alphacode-contest.png` | A contest problem with AlphaCode's solution | DeepMind's AlphaCode post | PRESS |
| `2022-04_dalle2-astronaut-horse.jpg` | "An astronaut riding a horse in photorealistic style" | OpenAI's DALL·E 2 launch page | PRESS, credit "OpenAI" |
| `2022-07_alphafold-database.jpg` | The "protein universe" graphic | DeepMind's July 2022 post (link in the card) | PRESS |
| `2022-08_theatre-dopera-spatial.jpg` | *Théâtre D'opéra Spatial* | Wikipedia article (link in the card) or press coverage | PRESS, credit "Jason M. Allen / Midjourney" |
| `2023-03_gpt4-exam-results-chart.png` | The exam-results bar chart | OpenAI's GPT-4 page, or the GPT-4 Technical Report (arxiv.org/abs/2303.08774) | PRESS |
| `2023-03_pope-puffer-jacket-ai.jpg` | The Pope in the white puffer coat | Widely circulated (created by Pablo Xavier with Midjourney, posted on Reddit). Show it with an "AI-generated" label. | UGC |
| `2023-04_heart-on-my-sleeve-news.jpg` | A news headline about the fake Drake song. **No audio** (copyright). | NYT, BBC or Billboard coverage, April 2023 | NEWS |
| `2023-08_waymo-empty-driver-seat.mp4` | A Waymo in San Francisco with an empty driver's seat | Waymo press B-roll (waymo.com), or film one yourself if you're in SF / LA / Phoenix | PRESS or OWN |
| `2024-01_fcc-ai-robocall-ruling.png` | The FCC's Feb 2024 announcement, or a robocall headline | fcc.gov press release (link in the card) | PD (FCC) |
| `2024-02_sora-tokyo-street.mp4` | The woman walking down a rainy Tokyo street | OpenAI's Sora page / YouTube | PRESS, credit "OpenAI" |
| `2024-07_alphaproof-imo-silver.png` | The score chart | DeepMind's AlphaProof post | PRESS |
| `2024-09_openai-o1-math-chart.png` | The AIME comparison chart | OpenAI's "Learning to reason with LLMs" post | PRESS |
| `2024-10_claude-computer-use-demo.mp4` | Claude moving the mouse and filling in a form | Anthropic's Oct 2024 computer-use demo video (Anthropic YouTube) | PRESS, credit "Anthropic" |
| `2025-01_nvidia-stock-drop-chart.png` | Nvidia's share price around 27 Jan 2025 | Make your own chart from public price data (e.g. Yahoo Finance) | OWN |
| `2025-05_alphaevolve-diagram.png` | How AlphaEvolve works | DeepMind's AlphaEvolve post | PRESS |
| `2025-07_atcoder-final-scoreboard.png` | Final standings with Psyho first and OpenAI second | AtCoder's World Tour Finals 2025 Heuristic results page, or Psyho's post on X | PRESS / UGC |
| `2025-08_gpt5-launch.png` | The GPT-5 announcement | OpenAI's GPT-5 page | PRESS |
| `2025-09_icpc-world-finals-results.png` | The results graphic | DeepMind's ICPC post | PRESS |
| `2025-09_sora2-sample.mp4` | An official Sora 2 clip with sound | OpenAI's Sora 2 page / YouTube | PRESS, credit "OpenAI" |
| `2025-11_billboard-breaking-rust.png` | The chart or a headline | Billboard coverage (link in the card) | NEWS |
| `2026-01_erdos-problems-site.png` | erdosproblems.com/728 marked as solved | Screenshot it yourself | OWN (screenshot of a public page) |
| `2026-01_moltbook-screenshot.png` | The Moltbook front page with agent posts | Screenshot it yourself, or use one from press coverage | OWN / NEWS |
| `2026-02_claude-c-compiler.png` | The compiler post / Linux build output | Anthropic's engineering post (link in the card) | PRESS, credit "Anthropic" |
| `2026-02_seedance-hollywood-headline.png` | A headline about the Cruise/Pitt clip and Hollywood's reaction. **Not the clip itself** (real actors' likenesses). | Variety, Deadline or eWeek, Feb 2026 | NEWS |
| `2026-02_first-proof-challenge.png` | The First Proof site or the Scientific American headline | 1stproof.org / scientificamerican.com | NEWS |
| `2026-05_unit-distance-diagram.png` | Dots on a plane joined by equal-length lines (illustrates the question, not the proof) | Draw your own, e.g. a few points on a triangular grid with the unit-length links highlighted | OWN |

---

## Presenting

- Open `index.html` in Chrome or Edge and press **F** for fullscreen. Everything works offline.
- **→ / PageDown** steps to the next key moment and **← / PageUp** steps back. After the last one comes the **Today** card. **Esc** closes a card, **Home** returns to the start.
- Click any dot or label to open it. Scroll (or **+ / − / 0**) to zoom. **16 extra milestones appear once you zoom in.** Drag to move along the timeline.
- **T** toggles light/dark mode. **?** lists all shortcuts.
- Videos start muted and looping. Use the **🔊 Sound on** button (Veo 3, GPT-4o, Duplex, Sora 2) or the player controls.
- To change text, edit the `INTRO`, `TODAY` and `EVENTS` blocks at the top of the `<script>` in `index.html`. The Today card's last line is `TODAY.closing`.
