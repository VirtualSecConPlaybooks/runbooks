# Streaming the DEF CON Red Team Village May’hem 2020 Virtual Summit from Home

This article is also posted at in [Medium](https://medium.com/@santosomar/streaming-the-def-con-red-team-village-mayhem-2020-virtual-summit-from-home-fe3493e77066)

The DEF CON Red Team Village had a very successful virtual event in May 2020 during the COVID-19 quarantine. The event took place on May 16, 2020. We had great speakers, 3 live training sessions, and a very cool CTF! The event was streamed to [our Twitch channel](https://www.twitch.tv/redteamvillage), [our YouTube channel](https://youtube.com/redteamvillage), Periscope, and Facebook. All videos are posted in [our YouTube channel](https://youtube.com/redteamvillage) and embedded in the event website: https://redteamvillage.io/mahem.
We had hundreds of participants in our Discord Server talking to the presenters and collaborating with each other. The community is very active in our Discord Server. You can join the Red Team Village Discord Server by just going to https://redteamvillage.io/discord.

In this post, I share the basic, yet effective setup that I used to stream the whole conference. I am already enhancing the systems to be able to support more tracks and additional collaboration.

The setup was very simple:

![](https://miro.medium.com/max/1400/1*eCS7QykHji2PYvyibHeZGQ.png)

Speakers joined a Webex bridge, a laptop was setup as a Webex client and the audio and video was captured by a capture card in a Linux (Ubuntu) system running Open Broadcaster Software (OBS). Yes, you can use the same Linux box with Webex and capture desktop audio and video in different scenes in OBS; however, I ran into some issues of audio being cut every few minutes during streams.

**Note:** I strongly suggest that if you are going to run a live event to this magnitude, you have a dedicated streaming system (Windows, Mac, Linux, whatever), but have one that is dedicated to stream.

We used the Restream.io service to simultaneously stream to to Twitch, YouTube, Periscope, and Facebook. As previously mentioned, all attendees continue to be engaged in our Discord Server. Many many others have joined the Discord server after the event. The May’hem event was a sneak preview of the main event during DEF CON Safe Mode in August 6–9. During that event, I will be using a similar setup with additional systems, including a BlackMagic ATEM Mini Pro. Stay tuned and visit our website (https://redteamvillage.io) for additional details!


