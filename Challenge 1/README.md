
# Challenge 1: Plex

You've just discovered **Plex**.

![](https://zhf1943ap1t4f26r11i05c7l-wpengine.netdna-ssl.com/wp-content/uploads/2018/05/image-home-why-plex-1-7-1440x982.jpg)

> Plex brings your favorite media together in one place, making it beautiful and easy to enjoy. Plex organizes your personal video, music, and photo collections and streams them to all of your devices. With Plex Live TV & DVR and a growing catalog of great online content, including Plex News and podcasts, we’re making it easier to find and enjoy all the media you love on all of your devices, no matter wherebyou happen to be.

You don't have a large music or photo collection, but you **do** have a large collection of TV Shows.

Plex will show them as a catalog with poster images, IMDB ratings, proper episode titles and descriptions, theme music for the show and even download subtitles for a particular episode automatically. It'll note the precise episode and even the location that you were on, so you'll never get lost when returning to watch the latest show you've become addicted to. **On top of all that**, you can have multiple user profiles so your whole family can browse your collection like they're on Netflix! 

But... a *slight* snag.

Plex requires the following structure:

	Show
		/ Season XX
			/ SXXEXX - Episode Title.mp4 (or other filetype)


Good news! Your own organising method isn't far off:

	Show
		/ Season XX
			/ Episode XX - Episode Title.mp4 (or other filetype)


You'll need to rename all of the files, but you have over 1000 episodes of TV shows. It'll take ages!

You decide to create a **Python script** to do the work for you.

You've decided that it must:
1. Scan through each TV show in your "TV Shows" directory
2. Scan through each season of the show
3. Rename each episode from:

		Episode XX - Episode Title.mp4 (or other filetype)

	to

		SXXEXX - Episode Title.mp4 (or other filetype)

4. Notify you of all successful and failed attempts

You love a challenge, so you've decided to **only use libraries that come with Python 3 out-of-the-box** - and you've got a few hours before the family get home.
