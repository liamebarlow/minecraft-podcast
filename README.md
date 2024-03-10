# minecraft-podcast
## Upload MP3s
- Add mp3 files to directory for new shows in directory
- 'cd' change directory to correct directory, and 'ls' list files to make sure you are in right place
- Check files to add with `git status`
- Execute `git add *`
- Execute `git commit -a -m "add new mp3 for episode"` to commit locally.
- Execute `git commit origin main` to push mp3 to servers

## Update Podcast
- Edit podcast_config.yaml
- Execute `./rss_generator.py`
- Execute `git diff` to see changes. Should be sensible.
- Execute `git commit -a -m "add new episode"` to commit locally.
- Execute `git push origin main` to push to servers
- Check RSS is good at https://podba.se/?url=https://liamebarlow.github.io/minecraft-podcast/podcast_feed.xml

## Edit podcasts

### Spotify

https://podcasters.spotify.com/dash/home

### Google

https://podcastsmanager.google.com

### Apple Podcasts

https://podcastsconnect.apple.com/my-podcasts

### Amazon

https://podcasters.amazon.com/podcasts

### IHeart

https://podcasters.iheart.com/dashboard
