# Stream_media
### This is the repository for streaming media.


:bird: Clarification
  - No copyright infringement intended. All rights (media) belong to the respective owners. Project is only intended for providing help for difficult access to twitter to certain fans group.(:star2:Breaking information barrier)


:octocat: Statement
  - Finished: Streaming a limited amount of tweets through twitter API under specific searching, extracting media_url accordingly and downloading files have been realized. 
  - Still to be worked: 
     - Object: Can't run .py file using -q with advanced settings eg. searching for hashtag topics especially with Korean, let alone filtering retweets and irrelevant tweets(selling/purchasing etc.) -> leading to problems of repeated pics.
     - Amount: API limits tweet streaming amounts per user per time window. Need solutions for this part.
     - Type of media: Only images that are saved in twitter repository link (pbs.twimg.com/media/..) have been extracted. gifs(typically accessible through cfile...) and video haven't been extracted in this version.


:pushpin: File explanation
   - config.py and get_tweet.py : streaming search key word to .json file.
   - stream_parkwoojin.json : sample result.
   - Stream_media1.0: extracting media_url (if exists) from. json file and downloading (since even source urls are not accessible to those areas with firewall).
   - pic_folder: sample pics result from all scripts. As not filtering retweets initially, repetition of images does exist.


:coffee: Fun fact

1. Initially inspired by this pd48 ranking amazing visualization:(visualization) https://ajyu124.github.io/p48ranking/ ; (project)  https://github.com/ajyu124/p48ranking
,thinking as a kpop fan also to contribute sth through coding;
2. Finding an interesting page when searching for markdown cheatsheet for writing README.md [Emoji cheat sheet!](https://www.webpagefx.com/tools/emoji-cheat-sheet/)
