---
slug: 'podcast-summer-reflection'
category: 'Podcast'
title: 'Podcast summer reflection'
date: '2020-07-20'
---

# Podcast summer reflection

This summer marked the end of the third season of my [podcast](https://trevligmjukvara.se). Me and my co-host decided to take a short break and focus on enjoying the summer, which feels like a really good decision. The break is almost over (season 4 begins in 10 days) and it's time to reflect on the previous season and on the podcast as a whole.

This reflection will be recorded and released as an off-season episode on the podcast in case anyone is interested in hearing our take-aways and discussions about what it's like to run a weekly podcast.

Link to the episode here: [INSERT LINK](http://trevligmjukvara.se)

## The structure of the podcast

The topics are collected passively as we go about our regular days. If we find an interesting article or some podcast-worthy news we save it and write down our notes and thoughts separately. We store all the links and topics in a shared document which lives in a git repository. This document also becomes our show notes for the realeased episode. Here's an example: [s03e03](https://github.com/trevligmjukvara/trevligmjukvara.se/blob/master/site/src/episodes/s03e03.mdx).

During the recording we each present our finds of the week to each other and discuss it. This is basically the structure of the whole podcast. Sometimes we need to "play dumb" and ask each other to define or explain something if we feel the topic needs more context. This is all for the benefit of our listeners and to make sure that we present a coherent piece of material. Other times, speaking for myself at least, I'm super confused about a topic of concept that my co-host is trying to explain. Those times I don't have to *play* stupid, and will genuinely pester him to explain it again util I feel I understand it better.

## The questions

We decided on a few topics to cover and discuss. They are:

- What has worked well?
- What hasn't worked well and how could we improve on it?
- What has been fun?
- What hasn't been fun?
- Software and hardware we use. Could we improve anything?
- How do we see the future of the podcast?

I will go through the questions from my point of view. If you'd like to hear the opinions of my co-host and/or listen to the discussions around this, I suggest you listen to the episode (only available in Swedish).

### What has worked well?

#### Schedule

Our schedule look like this:
---
Monday - Sunday: Collect topics for next episode.
Sunday 20:00 - 00:00: Record, edit, release episode.
---

The passive collection of topics I feel works well. It's very important to have a good and **quick** workflow to save a topic or article. If there's too much resistance here I will be too lazy or too focused on something else to do it. At the moment I use [Mozillas Pocket](https://app.getpocket.com/) service/app to save links and a loose markdown document to scribble down my notes. Pocket is built into my browser (Firefox) and works well since most topics are based on a web link. The markdown document for notes is not optimal but works well enough. I think I will keep doing it this way until a better option presents itself.

The, usually around 4h, recording/editing session is most of the work, naturally. Since the podcast format is basically a discussion, most of the actual words we're saying are not scripted, but rather an organic process where we react together. Live. Uncut. Well.. almost.

[Fuck it. We'll do it live.](live.gif)

#### Content

The content of the podcast kind of creates itself. Every week there are loads of things happening in software. You can always count on some new exciting version of an app we like, or some VPN company to screw up leaking millions of users data when they **promised** they didn't even save it in the first place. This means a never-ending stream of content for us to pick up on and discuss.

Some of my sources for finding topics are:
- [r/opensource](https://www.reddit.com/r/opensource)
- [r/linux](https://www.reddit.com/r/linux)
- [TUXURLS](https://tuxurls.com/)
- [The Linux Experiment](https://www.youtube.com/channel/UC5UAwBUum7CPN5buc-_N1Fw)

#### Our community

Our listeners seem very keen on interacting with us and their fellow listeners. Our audience isn't the biggest (yet!), but a decent percentage of them are active in at least one of our channels. I would love to see the community grow even more and I think that we should put some effort into tending to that "garden" to make sure the conditions are as good as possible for that to happen.

Our main channels are our [Telegram channel](https://t.me/trevligmjukvara), [Twitter](https://twitter.com/trevligmjukvara) and our fediverse home, [Linuxkompis](https://mastodon.linuxkompis.se/@trevligmjukvara).

### What hasn't worked well and how could we improve on it?

#### Schedule

Even though the schedule has mostly worked well, I feel there's a lot riding on that 4h recording/editing/uploading session on sundays. Technically we wouldn't have to schedule the editing since we edit 50% of the episode each. During the editing we normally just mute our microphones and do one half each. When both of us are done we unmute and upload the episode together. If we instead split the 4h session into two separate sessions, one for recording and one for uploading, we could do the editing when we have some free time during the week. Technically both of us don't actually have to be present during the upload and we could do every other week or something along those lines. That would result in a schedule that looks something like this:
---
Sunday (1,5h): Recording
Any day (1,5h): Editing
Every other saturday (0,5h): Release episode
---

This would mean that we could relax more during the recording session and not feel like there's a ton of work to be done before we can go to bed.

#### Editing

Our workflow looks like this:
- Upload recording to shared [Nextcloud](https://nextcloud.com/) server
- Pull everything into [Audacity](https://www.audacityteam.org/)
- Edit your half of the episode
- Upload edited file to shared Nextcloud server again
- Run [production script](https://github.com/trevligmjukvara/production-scripts)
- Upload finished episode to our podcast host [Fireside](https://fireside.fm/)

This feels very optimised, and we have iterated quite a bit on this process. 95% of the time this takes goes into the actual editing in Audacity, therefore this is where we should make improvements if possible. 

Another type of editing that looks interesting is transcription based editing. The idea is that if you can create an automatic transcription (think: subtitles) of an audio file, you can get a much better overview and edit portions of the episode without even having to listen to it. There are applications that lets you do this by simply deleting or moving text in the transcript. One example of this is [Descript](https://www.descript.com).

#### Reaching our audience

We would of course like to have more listeners than we already have. The podcast has **almost exclusively** grown organically up to this point. It's spread by word of mouth, or by searching for one of our tags in podcast players. This seems like the most sustainable way to grow an audience, but it's also probably the slowest. Things like promotion through ads, collaborations with other podcasts and other ideas could be worth exploring.

#### Marketing

We have tried Google ads with a **very** small amount of money. This didn't give us much at all as far as I can tell from the data. Perhaps increasing the budget is an option? Risky investment though.

### What has been fun?

#### Recording

The actual recording of the podcast is always fun. I get to converse with a friend, about a topic I'm interested in, with the knowledge that I'm creating content enjoyable for others at the same time.

#### Bloopers

A more recent addition to the format of Trevlig Mjukvara is bloopers. At the end of (almost) every episode we have a "secret" section which contains bloopers from the recordings.

#### Learning about FOSS

#### Creating content and sharing it

#### Feedback

### What hasn't been fun

#### Pressure to stay consistent

#### Paying for third party services

### Software and hardware we use. Could we improve it?

#### Software

#### Hardware

#### Improvements

### How do we see the future of the podcast?

#### Scaling up

#### Consistency

#### Branching out

#### Plans for next season

