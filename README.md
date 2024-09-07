# Your Podcast Site

## What to do next

1. Congiguration
    - Adjust the `podbard.yam` file to fit your podcast site
    - Locate `static/images/artwwork.jpg` if you like
2. Locate the audio files (MP3 or M4A) and commit them
    - Put the audio files in the `audio/` directory (You should remove the sample files)
3. Locate the episode files (Markdown) and commit them
    - Put the episode files in the `episode/` directory (You should remove the sample files)
    - Hint: You can use the `podbard episode <your.mp3>` subcommand to create a new episode file
4. Push, build and deploy to the GitHub Pages
    - After the push, the GitHub Actions will build the site and deploy it to the GitHub Pages
    - Check [.github/workflows/build-deploy-pages.yaml](./.github/workflows/build-deploy-pages.yaml) for specific settings

You can manage the podcast site with the `podbard` command for more customization.

See. <https://github.com/Songmu/podbard> for more details.
