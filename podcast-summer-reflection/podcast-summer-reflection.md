---
slug: 'podcast-summer-reflection'
category: 'pod'
title: 'Podcast summer reflection'
date: '2020-07-20'
---

# Podcast summer reflection

This summer marked the end of the third season of my [podcast](https://trevligmjukvara.se). Me and my co-host decided to take a short break and focus on enjoying the summer, which feels like a really good decision. The break is almost over (season 4 begins in 10 days) and it's time to reflect on the previous season and on the podcast as a whole.

This reflection will be recorded and released as an off-season episode on the podcast in case anyone is interested in hearing our take-aways and discussions about what it's like to run a weekly podcast.

Link to the episode here: [Sommar 2020](http://trevligmjukvara.se/sommar2020)

## The structure of the podcast

The topics are collected passively as we go about our regular days. If we find an interesting article or some podcast-worthy news we save it and write down our notes and thoughts separately. We store all the links and topics in a shared document which lives in a git repository. This document also becomes our show notes for the realeased episode. 

Here's an example: [s03e03](https://github.com/trevligmjukvara/trevligmjukvara.se/blob/master/site/src/episodes/s03e03.mdx).

During the recording we each present our finds of the week to each other and discuss it. This is basically the structure of the whole podcast. Sometimes we need to "play dumb" and ask each other to define or explain something if we feel the topic needs more context. This is all for the benefit of our listeners and to make sure that we present a coherent piece of material. 

Other times, speaking for myself at least, I'm super confused about a topic of concept that my co-host is trying to explain. Those times I don't have to *play* stupid, and will genuinely pester him to explain it again util I feel I understand it better.

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

Our schedule looks like this:

|Monday - Sunday|Sunday 20:00 - 00:00|
|---|---|
|Collect topics for next episode|Record, edit, release episode|

The passive collection of topics I feel works well. It's very important to have a good and **quick** workflow to save a topic or article. If there's too much resistance here I will be too lazy or too focused on something else to do it. 

At the moment I use [Mozillas Pocket](https://app.getpocket.com/) service/app to save links and a loose markdown document to scribble down my notes. Pocket is built into my browser (Firefox) and works well since most topics are based on a web link. The markdown document for notes is not optimal but works well enough. I think I will keep doing it this way until a better option presents itself.

The, usually around 4h, recording/editing session is most of the work, naturally. Since the podcast format is basically a discussion, most of the actual words we're saying are not scripted, but rather an organic process where we react together. Live. Uncut. Well.. almost.

![Fuck it. We'll do it live.](live.gif)

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

Even though the schedule has mostly worked well, I feel there's a lot riding on that 4h recording/editing/uploading session on sundays. Technically we wouldn't have to schedule the editing since we edit 50% of the episode each. During the editing we normally just mute our microphones and do one half each. When both of us are done we unmute and upload the episode together. 

If we instead split the 4h session into two separate sessions, one for recording and one for uploading, we could do the editing when we have some free time during the week. Technically both of us don't actually have to be present during the upload and we could do every other week or something along those lines. That would result in a schedule that looks something like this:

|Sunday|Any day|Every other saturday|
|---|---|---|
|Recording (1,5h)|Editing (1,5h)|Release episode (0,5h)|

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

I'm originally a Windows user. Recently I have made the fulltime switch to Linux (currently running Manjaro with i3 WM) and I'm absolutely loving all the new thing I discover and learn. 

With the creation of this podcast I've gotten to know some Linux and with that comes exposure to the FOSS community and all the wonderful tools which are available when you break free from the closed source nature of Windows.

#### Creating content and sharing it

It's a good feeling knowing that you create something that is of value to others, as well as yourself. The act of uploading it to the web is a bit scary and you're really putting yourself out there. The feedback has been wonderful though, and without that there would be much less motivation to continue putting in the time and effort.

Since the podcast started, I'm making an effort to give more feedback myself. Now I know first hand how good it feels when someone gives their thoughts on your work, good or bad, and as long as it's done the right way (always be nice to other people!) it's a huge confidence booster and really makes it worth the effort.

### What hasn't been fun

#### Pressure to stay consistent

There's a certain pressure to stay consistent. All self inflicted of course. We made a rule saying that we will release 1 episode per week, and we've managed to stick to that so far, but some days you just dont "feel it".

It's for sure an excersise in self control. Ultimately it's worth it, but in the moment it can be very hard to motivate oneself.

![No pain, no gain!](pain.jpeg)


#### Paying for third party services

Our expenses at the moment are as follows:

|Fireside|Domain|Proton mail|
|---|---|---|
|1200 SEK / year|150 SEK / year|500 SEK / year|

One way to get rid of these charges would be to develop the functionality ourselves. With Fireside, it's definitely possible to replace it with something we build ourselves. "All" it would take is an investment in time.

Another way to fix the problem would be to ask for and recieve donations, or to sell some merch. There are ideas in this space, stay tuned.

We could also look for sponsors to the podcast. I love that Trevlig Mjukvara has no breaks at all and is just content all the way through, but a sponsor segment is more or less the norm for podcasts these days, so perhaps it would be okay. **If you'd like to sponsor the podcast, contact us at kontakt@trevligmjukvara.se and we will be more than happy to work something out**.

It would be really nice to break even or even make some small amount of money of the podcast.

### Software and hardware we use

#### Software

- Audacity (editing, recording)
- Mumble (communication during recording)
- Nextcloud (storing files)

All open source, free and wonderful.

#### Hardware

- Cheap XLR microphones
- Cheap mixer
- Pop filter
- Cheap mic stand

All in all this cost us about 1200 SEK each. The keyword here is "cheap", but I'm very impressed with the audio quality and feel like there's little need to spend more money on hardware at the moment. The diminishing returns on microphones are steep, so there's little gain per SEK you spend. We have hit the sweet spot here I feel like.

### How do we see the future of the podcast?

#### Scaling up

We would definitely like to have more listeners. As mentioned, the growth has been organic up until now and that feels very nice. Some ideas for growing our audience could be collaborations with other podcasts and guest appearances, which we are very open to moving forward.

#### Consistency

Keep being consistent. This is one of the most important things I feel like, for the listeners to become inversted, interested and happy when they know that they can listen to the new episode of Trevlig Mjukvara on their way to work on Mondays. Just like they always do.

I myself have these kinds of routines as well. There are mornings when I know there's a new episode of some podcast I'm subscribing to and I'm excited to listen to it.

#### Branching out

We would like to explore other types of formats and content. A special episode every now and then, or a new segment in the podcast.

We have experimented with this all along and if your'e a regular listener you will surely remember some of our abandoned ideas for segments. We've had battles, scoring software on the "Torvalds/Gaben" scale, contributor league and other things.

We will continue experimenting and trying out new things. The last thing I want is for the podcast to feel stale and repeating.

#### Plans for next season

No major changes will be implemented in season 4. I have iterated a bit on our website during the vacation and some things are a little bit smoother now than they were before.

Generally we both feel like the progress is good at the moment, and our slow iterations and changes/experiments will continue.

I very much look forward to season 4 of Trevlig Mjukvara! So much has happened in software during the summer that I'm just dying to talk about. **I hope you will join us on the 3rd of August for S04E01**.
