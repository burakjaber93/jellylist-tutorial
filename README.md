# How to Stream Full Jellyfin TV Series/Albums to VLC or Dispatcharr

Hey everyone! I've put together a self-contained HTML tutorial on how to use a fantastic tool called Jellylist. This small program bridges the gap between your Jellyfin server and external media clients that natively support M3U playlists, like VLC or stream managers like Dispatcharr.

What Jellylist Does
Normally, Jellyfin only gives you a direct link to a single episode. Jellylist runs locally and creates a dynamic M3U playlist link that contains all episodes of a TV show or all tracks of an album. When you open this single link in VLC or Dispatcharr, it immediately starts playing the entire series or album in order.

How to Use the Tutorial
Download and Save: Download the attached file and save it as Jellylist_Tutorial.html.

Open: Open the file in any web browser. It contains all the steps, prerequisites, and example links you need.

Read and Follow: Pay special attention to Part 1 (API Key) and Part 2 (Running the Server). The Jellylist server must be running on your local machine for the links to work.

⚠️ IMPORTANT: Security and Placeholders
The tutorial is written using generic placeholders like [YOUR_JELLYFIN_URL], [YOUR_SERIES_ID], and [YOUR_API_KEY].

DO NOT SHARE YOUR FINAL LINKS The final stream URL you create in the tutorial contains your private Jellyfin API Key, which acts like a permanent password. This information is highly sensitive and should never be shared. The tutorial clearly explains where to put your unique details to make the links work privately on your network.

Credit to Jellylist for making the tool!
