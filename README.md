# Radio Web Logger
A webpage to improve the logging system for radio stations.

## An Overview
Radio stations have often been the spaces where we were introduced to some of our favourite musicians and songs for the first time. Today too, radio, and in particular campus (/college/student), community and public radio strive to give emerging artists their first breaks in the music industry and exposure to wider audiences. But if you've ever been at the frustrating receiving end of the experience of hearing a brilliant song and not being able to find out the artist and song's name (I have!), this project might be able to address that, when it's complete. 

Additionally, campus and community radio stations are often run by volunteers and funded by listener donations, which means both time and funds are always in low supply, and the obstacles to creating a sophisticated website that can give you all the information you need about a brand-new artist you're listening to, who you cannot just Shazam because they aren't of a very high stature yet, are twofold: 1) not enough funds to make said sophisticated website with expensive features, and 2) volunteers just not having the time to create elaborate writeups and webpages for every artist played on a weekly show. 

Radio DJs are required however, to log everything that is said or played on their shows anyway, as per CRTC guidelines, and these logs are informative but can take a lot of time, depending on how efficient the logging systems used by the station are. 

## Goals
The Radio Web Logger hopes to make the process for updating self-reported hourly logs for radio stations in accordance with CRTC guidelines, more efficient,  interactive and visual, as well as making them more informative by harnessing information broadcasters are already required to log.

## Features
Ideation in progress. Currently, some planned features include:
- [ ] Uploading logs as CSV files with the same format as the [CFRC Radio](https://cfrc.ca) logs: START_TIME,	END_TIME,	ARTIST,	SONG_TITLE,	CATEGORY,	CATALOGUE_#,	NEW,	INST,	CAN,	HIT,	INDG,	EMRG
- [ ] Ability to log audio segments from timestamps on waveforms, audio pulled from a provided mp3 weblink.
- [ ] \(Optionally) Ability to log audio segments from waveform timestamps, audio temporarily uploaded to a server from user's computer.
- [ ] Ability to link to songs on a streaming service like YouTube or Spotify using these platforms' web APIs, similar to how the [BBC Sounds](https://www.bbc.co.uk/sounds) does.
- [ ] For logs completed via mp3 weblink, option to play audio back with a pop up informing you what song is being played	(again, a feature similar to Sounds). Users are able to click on the song title pop up to open the song on an external streaming platform.
- [ ] \(Optional additional feature) Ability to include Bandcamp links that pop up under an artist name, which can similarly be clicked on.
      
More to come as the project grows and I get more ideas. If all goes well, I may even open it up to ideas, requests or contributions.

## Expansions in the future
At the moment, this application is meant to serve staff and volunteers at Canadian radio stations, particularly campus and community stations, whose logging requirements I am most familiar with. Extensions in the future could include interfaces for the other kinds of broadcasters.
What I would be more interested in adding further down the line, is the ability for radio station websites to offer their _listeners_ the ability to see this synced up artist and song information while they listen back to a show in program archives.

