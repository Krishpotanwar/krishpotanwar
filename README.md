<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Krishpotanwar/krishpotanwar/main/assets/ground-track-dark.svg">
  <img src="https://raw.githubusercontent.com/Krishpotanwar/krishpotanwar/main/assets/ground-track-light.svg" alt="A line drawing of a small satellite gliding along its orbit above a grid of square ground tiles. It stops, frames one patch of tiles between corner brackets, and the patch lights up in orange, like a dated photo of one place.">
</picture>

# Hi, I'm Krish

I'm a B.Tech student in Computer Science (AI & ML) at Ramdeobaba University, Nagpur. Right now I'm building [GrahSaboot](https://grahsaboot.grahsaboot.workers.dev), a free website for dated satellite photos of any place on land, and [HisaabKitaab](https://hisab-rust.vercel.app), an app for splitting group expenses. I like taking a problem from "this is annoying" to a working product that real people can open on their phone: the idea, the design, the code, the tests and the words on the screen. I'm open to internships and collaborations.

I keep coming back to everyday and public problems in India: splitting a bill without arguments, getting around a flooded road, looking at dated satellite photos of a place to see what changed, and helping an officer decide which public works to inspect first.

Three habits I try to bring to everything I make:

- **Plain language.** If a person who is not technical cannot follow it, it is not finished.
- **Honest limits.** A good tool says what it cannot do. My satellite project never says whether a claim is true. Its report says only what a fixed rule measured, and that the rule cannot tell a building from a crop or a season.
- **Made for everyone.** I design for the keyboard, screen readers, slow phones, and dark and light themes. In GrahSaboot, automated accessibility tests check every screen; trying it with a real screen reader is still on my list.

I move fast, I ship, and I write things down. I build with AI coding tools, often by speaking my prompts instead of typing them.

## Main projects

### GrahSaboot: dated satellite photos of any place on land

<a href="https://github.com/Krishpotanwar/grahsaboot/blob/main/docs/media/grahsaboot-explainer.mp4"><img src="https://raw.githubusercontent.com/Krishpotanwar/grahsaboot/main/docs/media/grahsaboot-preview.gif" alt="A 24-second silent preview of the GrahSaboot video, on a loop: the six-step diagram, a before and after swipe at the Navi Mumbai airport, the report's What we measured block, and a real case replayed, the Kakhovka dam in June 2023, with the fingerprint of each photo. The link opens the full 3-minute video's file page." width="640"></a>

A free website where you pick a place and get real, dated satellite photos (Sentinel-2) with the clouds checked. Put a "before" photo next to an "after" photo, pin the dates that matter, and save a report. Every photo in a report gets a digital fingerprint, so someone else can check it later, and the site is upfront about what 10-metre photos cannot show. Since 24 October 2026 it also has "Watch it change", six pictures of the same place, one a year, played as a time-lapse (for looking only: those pictures are never fingerprinted), and a switch that hides the live satellites. It is a live prototype, built with TypeScript, React, MapLibre and a Cloudflare Worker, and tested in three browser engines and for accessibility.

[Live site](https://grahsaboot.grahsaboot.workers.dev) · [Code](https://github.com/Krishpotanwar/grahsaboot) · [The 3-minute video](https://github.com/Krishpotanwar/grahsaboot/blob/main/docs/media/grahsaboot-explainer.mp4) (the picture above is a 24-second silent preview; the full video is a file, so GitHub opens its page, where Download saves it)

### HisaabKitaab: splitting group expenses, built for India

A full-stack Progressive Web App for friends, roommates and trips. It shows real-time balances and who owes whom, scans receipts with OCR, opens a UPI app to settle up with the payee's details filled in, and has a Razorpay "Buy me a chai" button. No install needed: it works in any phone browser, with dark mode.

[Live site](https://hisab-rust.vercel.app) · [Code](https://github.com/Krishpotanwar/Hisab)

## More things I've built

| Project                                                                                                                                                                    | What it is                                                                                                                                                                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **NidhiNetra** ([live](https://nidhinetra.vercel.app) · [code](https://github.com/Krishpotanwar/NidhiNetra))                                                               | A Smart India Hackathon 2026 prototype for MoSPI's problem statement SIH26102. It ranks public works under the MPLADS scheme, with the reasons shown, to help district officers choose which to inspect first. Its score orders the list; it is not a verdict. |
| **FloodRoute** ([live](https://flood-route-rosy.vercel.app) · [code](https://github.com/Krishpotanwar/flood-route))                                                        | A hackathon prototype of flood-aware route planning for Indian cities: road conditions, community reports and a rerouting demo. The live site runs in demo mode with illustrative data. React, TypeScript, MapLibre, FastAPI, PostGIS.                         |
| **BreatheWay** ([live](https://daakrish.vercel.app) · [code](https://github.com/Krishpotanwar/daa_krish))                                                                  | Air-quality-aware route navigation, a team project for the design and analysis of algorithms lab at RBU Nagpur. The live app is now called PureWay.                                                                                                            |
| **SmartRoadHazard** ([live](https://smart-road-hazard.vercel.app) · [code](https://github.com/Krishpotanwar/SmartRoadHazard))                                              | Road hazard detection and alerts, a team project: an IoT simulation with an ESP32 (simulated in Wokwi), Flask, SQLite and a Leaflet map.                                                                                                                       |
| **WorldPolicy-Env** ([code](https://github.com/Krishpotanwar/WorldPolicy-Env))                                                                                             | A reinforcement-learning environment in which seven country agents debate and vote, made for the Scaler × PyTorch × Hugging Face × Meta Hackathon 2026.                                                                                                        |
| **Macin** ([code](https://github.com/Krishpotanwar/Macin))                                                                                                                 | An IDM-style download manager for macOS with a Chrome extension: parallel chunk downloads and smart file routing. A Swift app with a Rust download engine.                                                                                                     |
| **MoodTune** ([v4 live](https://moodtune-v4.vercel.app) · [v4 code](https://github.com/Krishpotanwar/MoodTune-v4) · [original](https://github.com/Krishpotanwar/MoodTune)) | A mood-based music recommender. The original is a Python demo project (Streamlit and scikit-learn); v4 is a web version built with Next.js and Supabase.                                                                                                       |
| **QuizForge** ([code](https://github.com/Krishpotanwar/quizforge))                                                                                                         | An adaptive AI tutor and quiz generator at an early stage: the skeleton (a health check and a streaming echo) works, and quiz generation has not started yet.                                                                                                  |
| **ML roadmap tracker** ([live](https://ml-roadmap-tracker-five.vercel.app) · [code](https://github.com/Krishpotanwar/ml-roadmap-tracker))                                  | An interactive learning-path tracker for ML engineering.                                                                                                                                                                                                       |
| **My personal vibe coding setup** ([code](https://github.com/Krishpotanwar/my-personal-vibe-coding-setup))                                                                 | A public template of how I set up my AI coding tools so they feel like one continuous assistant.                                                                                                                                                               |

## Tools I use

- **Languages:** TypeScript, JavaScript, Python, Swift, C, C++
- **Web and maps:** React, Next.js, Vite, Tailwind CSS, MapLibre, Leaflet
- **Backend and data:** FastAPI, Flask, PostgreSQL and PostGIS, SQLite, Supabase
- **Quality and shipping:** Vitest, Playwright, GitHub Actions, Cloudflare Workers, Vercel, Git

## Competitive programming

I practise on LeetCode, Codeforces and CodeChef, mostly dynamic programming, monotonic stacks and graph patterns.

[LeetCode](https://leetcode.com/u/GODXKRISHNA16/) (GODXKRISHNA16) · [Codeforces](https://codeforces.com/profile/KRISH_POTANWAR) (KRISH_POTANWAR) · [CodeChef](https://www.codechef.com/users/krishpotanwar) · [HackerRank](https://www.hackerrank.com/profile/24potanwark) · [Codolio](https://codolio.com/profile/krishpotanwar)

## Away from the screen

You will find me on a football pitch, at the gym, or editing bike trip videos with friends. I also like finding someone new to talk to. Collecting perspectives is my favourite hobby.

## Ground track: my last year on GitHub

A ground track is the path a satellite traces over the ground. Mine is my contribution graph: one square for each day of the last year, a stronger orange on busier days, with a snake that winds across it and eats the coloured squares. A small GitHub Action redraws it every day.

<details open>
<summary>The snake animation (close this to hide it)</summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Krishpotanwar/krishpotanwar/output/github-contribution-grid-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/Krishpotanwar/krishpotanwar/output/github-contribution-grid-snake.svg" alt="My GitHub contribution graph for the last year: one square per day, a stronger orange on busier days. A snake winds across the grid and eats the coloured squares, then the animation starts again.">
</picture>

</details>

## Play: Clear Pass

I made a small game about a problem GrahSaboot runs into all the time: a cloud can hide the ground when a satellite passes over. Tap when an orange target is inside the four orange corners and no cloud covers it. You get ten targets. It runs in your browser, makes no outside requests and stores nothing.

<a href="https://krishpotanwar.github.io/clear-pass/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Krishpotanwar/krishpotanwar/main/assets/clear-pass-dark.png">
  <img src="https://raw.githubusercontent.com/Krishpotanwar/krishpotanwar/main/assets/clear-pass-light.png" alt="A screenshot of the game Clear Pass: a line-drawn satellite above a strip of ground tiles, with four orange corners around an orange target and pale clouds drifting nearby. The picture opens the game." width="640">
</picture>
</a>

[Play it in your browser](https://krishpotanwar.github.io/clear-pass/) · [Code](https://github.com/Krishpotanwar/clear-pass)

## Let's connect

If you have an internship, a collaboration or a problem worth solving, I would like to hear about it.

[![Krish Potanwar on LinkedIn](https://img.shields.io/badge/LinkedIn-Krish_Potanwar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/krish-potanwar-192146321)

_Still figuring it out, but shipping anyway._
