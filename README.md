# GTA VI Themed Videos

Assembles a horizontal episode out of four to six related GTA VI moments. Gemini chooses the premise and scene order, then reviews the completed video for continuity and context.

Add `GEMINI_API_KEY` under **Settings → Secrets and variables → Actions**. The scheduled job reads the timestamp catalog maintained by the [Shorts repo](https://github.com/justsomeoneretarded/GTA-6-Clipper-shorts) and uses its shared editing engine. The Shorts repo must run discovery successfully once to populate that catalog.

Open this repo's **Actions** tab and use **Run workflow** if you want a batch before the next daily run. Download the MP4, thumbnail, captions, title, description, and source notes from the run's **Artifacts** section. Review and post the video manually.
