# Meme Bible App

The Meme App allows users to caption memes based on the most popular stock images that are currently in use. What this means is that a user no longer has to search for an existing meme to suit the situation; they can caption one themselves and share it!


*Note: The API can be fairly slow at times so please be patient during loading. Also, there may be a delay when navigating back directly from the captioning fragment to the list of images - the RecyclerView is redrawing the images.

Demo link: https://www.youtube.com/watch?v=iF2xwmcLI9s&feature=youtu.be

Features implemented:
- Login and register with simple alphanumeric character constraints - data stored on AWS backend
- Retrieves stock images for creating memes via web API
- Search for memes relating to certain keywords via web API
- Endless scrolling of Meme images by making successive calls to web API
- Can caption an image via the web API
- Save captioned meme to device as external file so it’s not necessary to view within app
- Share captioned meme via other apps (Messenger, etc.)
- View memes that were saved to app
- Can select a saved meme to share again
