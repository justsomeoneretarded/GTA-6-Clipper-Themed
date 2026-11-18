# GTA VI Themed Videos

Produces up to two horizontal GTA VI episodes per run. Each develops one theme through four or six moments, evenly split between YouTube and Twitch.

Add `GEMINI_API_KEY` under **Settings → Secrets and variables → Actions**. This editor checks every 20 minutes for a finished Shorts run that published a catalog. It then searches both YouTube and Twitch using this repository's Gemini key and adds the shared Shorts candidates to its own search results. [Shorts repository](https://github.com/justsomeoneretarded/GTA-6-Clipper-shorts)

You can also open **Actions → Produce GTA VI Themed Videos → Run workflow** to start a search and edit manually. Each video folder in the run's **Artifacts** section includes the MP4, thumbnail, captions, `title.txt`, `description.txt`, and source notes. Review the clip and copy its title and description when you post it.

The optional `YOUTUBE_COOKIES` repository secret authenticates YouTube searches and footage downloads from this editor.
