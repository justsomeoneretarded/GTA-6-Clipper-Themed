# GTA VI Themed Videos

Assembles a horizontal episode out of four to six related GTA VI moments. Gemini chooses the premise and scene order, then reviews the completed video for continuity and context.

Add `GEMINI_API_KEY` under **Settings → Secrets and variables → Actions**. This editor checks every 20 minutes for a finished Shorts run with an eligible catalog. It automatically starts one production run using that catalog and this repository's Gemini key. [Shorts repository](https://github.com/justsomeoneretarded/GTA-6-Clipper-shorts)

You can also open **Actions → Produce GTA VI Themed Videos → Run workflow** to edit the latest catalog manually. Each video folder in the run's **Artifacts** section includes the MP4, thumbnail, captions, `title.txt`, `description.txt`, and source notes. Review the clip and copy its title and description when you post it.

The optional `YOUTUBE_COOKIES` repository secret authenticates YouTube footage downloads from this editor.
