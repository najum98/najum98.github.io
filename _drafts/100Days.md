---
layout: post
title: "My #100DaysOfHacking Challenge"
tags:
  - Challenge
  - Hacking
  - Bug Hunting
author: "Najam Ul Saqib"
---

## How it all started?

I have known bug hunting since 2-3 years now but I had never been able to start hunting with consistency, I used to pick up a target after spending hours deciding which one will be good for me, spending time on recon i.e collecting all the subdomains, hunting on it for an hour or two for a couple of days, realizing that I need to learn hacking concepts first using tutorials and the cycle goes on. I was stuck in a loop of learning, though learning is not too bad but if you get stuck in learning only and dont apply what you've learn't practically you have done nothing but wasted your time.

Spending time on tutorials, labs (that too were solved with walkthroughs), writeups only was the only thing I was doing, maybe I was a bit reluctant to start fearing that if I start I won't be successful. The fear of failure!

Then one day, I came across a video of [Katie](https://www.twitter.com/insiderphd) discussing this loop of learning titled, [How to Stop Learning and Start Hacking!](https://www.youtube.com/watch?v=etP1hgJXijw) that proved to be an eye opener for me. I came to know from this video that all these years of learning hacking via tutorials only might have made me a better hacker THEORETICALLY meaning that I would know all the concepts, you name the vulnerability and I can tell you its description, impact, and what not. I only got better at learning but if you talk about PRACTICAL hacking I was not so good.

Anyways, I eventually decided to start giving time to PRACTICAL hacking and after switching so many targets I finally decided to hack on [Department Of Defense](https://hackerone.com/deptofdefense) since it was known as a good starting point for beginners for being a wide scope target. I started hacking on [Department Of Defense](https://hackerone.com/deptofdefense) in June, 2021 and spent a good amount of time on recon. I managed to get one bug triaged and I was in air but soon it was closed as informative as the triager made a mistake and according to him that bug was not valid. He was apologetic but it was very disappointing for me, imagine you get first valid bug after so much effort but it turns out to be informative later. Pretty discouraging. Well I won't go into the details but I got 13 _Informative_ Reports, 5 _Not Applicable_, 7 _Duplicates_ (thanks to Nuclei) and 2 _triaged_ reports that are still in triage state. Long Live DOD!

### Stats After Hacking A Month or Two on DOD

| Informative | Not Applicable | Duplicates | Triaged | Total |
| ----------- | -------------- | ---------- | ------- | ----- |
| 13          | 5              | 7          | 2       | 27    |
|             |                |            |         |       |
|             |                |            |         |       |

I got 2 valid security bugs and I don't know it was procrastination or what, but again I left hacking consistently, putting in so much hours only got me 2 triaged bugs out of 27 total submissions. I started doubting myself and started making excuses like bug bounties are a scam, only absolutely genius guys can find bugs and I am not one of them, bla bla!

> “Failure is the key to success; each mistake teaches us something.” – Morihei Ueshiba

### Trying To Get A Mentor

I always heard of how important it is to have a mentor, I knew I was doing something wrong and I wanted that someone could guide me, what am I doing wrong and what should be the right direction. I approached many people asking loads of questions and obviously not silly ones e.g "Can you mentor me?", "Can you teach me how to hack?", etc rather I wrote all the scenario and asked for their feedback but unfortunately almost no one responded positively. Most of them were unresponsive as well. I do not blame them, everyone has their own routine and not everyone is ready to help you. I just am saying that I had no mentor back then, I even asked people if we can hack together, on CTFs, or programs, etc but no one was interesting as I had nothing under my belt quite obviously. Why would one waste time with a noob? Therefore, I stopped wasting time asking people for help as it only protrayed me as a stupid begging for help.

## Taking the Initiative

Being a developer, I have already seen people taking on challenge of #100DaysOfCode which is very popular among developers, in this challenge people coded in some language for 100 days straight. I decided to go with #100DaysOfHacking, upon searching online only a couple of articles was available on #100DaysOfHacking challenge, one was successful and the other one failed at day 31-32. As I was definitely struggling with consistency and being stuck in learning loop I thought it was not a bad idea to give it a try and so I made the announcement of commencement of this challenge.

--- Embed the announcement tweet here ---

Therefore, I started this challenge from 1st of January 2022. In the beginning of the days I was skimming through the website trying to understand its functionality. I submitted my first bug of the year to this program on the 3rd day of this challenge which was _Improper rate limitation on OTP when OTP was not expiring_ and it turned out to be a duplicate. My first duplicate bug that didn't involve Nuclei so yeah you need something to stay optimist 😅

### Criticism

In the beginning of this challenge, though there were some people encouraging my step, unfortunately there were more people on the other side that were criticizing me that I am doing this challenge just to get fame and followers, or I am just showing off, etc but their criticism instead of bringing me down, pushed me to work even harder & prove them wrong. No matter what you do, there are always gonna be some people criticizing you, which as a human being definitely feels bad but one should not take the negative criticism too seriously.

> "To avoid criticism, say nothing, do nothing, be nothing - Elbert Hubbard"

### Is it just about 1 hour daily?

Theoretically, if I hacked 1 hour a day and tweeted the progress I was good with the challenge but I want to make clear that most of the days I hacked for 2-3 hours because 1 hour never seemed to be sufficient for me, 1 hour just used to pass by and I wouldnt have done anything concrete.

### What was my routine?

Being a full time security engineer, I had very little spare time so I used to hack early in the morning (before office) or at night (after office), usually morning time was more productive as I weren't tired out.
Being away from home, I also needed to travel some days and had to schedule my challenge accordingly. Routine used to get really tough, I used to be tired as hell but never skipped a single day of this challenge and made sure that every day I learn something new. There were days, when I was sick and some days was in hospital too and my close ones suggested me to just put some fake tweets including false claims, obviously no one can verify whether you actually did what you state or not, look at yourself, you're sick, and what not but no matter how you justify this act it remains cheating and I would tweet lie once but as a result I wont be hurting anyone but myself. I would kill the core purpose of this challenge and whenever I wont be feeling well I would be tweeting lies so I never went to that path. Whatever I tweeted each day was 100% truth and protrayed exactly what I did that day.

### Burn Out?

Yes I for the first time experienced burn out, my health was deteriorating. This challenge with a full time job was no joke and one should think 10 times before getting into it. There were days when I just didnt want to see the laptop screen still I managed to do something meaninful. You may term it as being crual with yourself but I knew that I had a bad habit of staying in comfort zone and I needed to get rid of this habit and the only way I found was #100DaysOfHackingChallenge and my decision proved to be absolutely spot on!

> “Before anything great is really achieved, your comfort zone must be disturbed.” – Ray Lewis

### My First Bounty

I was testing for IDORs for some days on this program's API, trying different stuff, making my own methodology and on _Day 31_ i.e within the first month of this challenge I found another bug and this time it was IDOR. I submitted it to the program after writing a detailed report and started waiting for the response. If you have ever submitted a report you would know this feeling of binge checking of email to see if the traiger has responded or not and to test my patience triagers did not gave the verdict on my report for next 2 weeks 😬

One beautiful morning of Day 46, at 3AM I was checking email when I saw some activity on the report. When I opened the report I saw this

<p align="center">
<img src="/assets/100DaysOfHackingChallenge/redacted-triaged.png" >
</p>
The feelings, the happiness, the dopamine rush I experienced cannot be explained in words. It was just out of this world. I was just so so happy. My first bounty was huge which I never expected, there was a time when I craved for a low 50$ bug but now I had a 4-digit bounty and high severity bug. Hardwork, persistence, consistency really paid off!

I asked the program for permission to disclose this bug so that I can release a detailed writeup on it but ofcourse being a private program they had reservations on disclosure as the severity was high so they were required to publish a press release to their customers regarding this finding and stating that the bug is fixed which they were not in a position to do so. Anyways, in a single line I can explain the bug: **Ability to download the account exports (that can contain full account information) of any user on the platform.**

This bounty gave me a confidence booster, all the self-doubts faded away. I started this challenge to develop a habit of staying consistent and as a by product I got my first bounty.

### Role of Recon in My Success

You might be expecting me to say that recon has helped me a lot during this challenge but you would be shocked to know that I did almost no recon this time, I hunted to root domains and the amount of stuff there was available I never felt the need to get more subdomains. At the same time, I am not saying that recon is useless. Recon is very important and can get you some awesome findings but I already wasted so much time on subdomain enumeration and stuff that this time I just wanted to hack and not get stuck into the recon loop.

### People who helped me along this journey

There were times when I was hopeless, feeling that I took the wrong decision of getting into bug bounties, while on other days I needed guidance. These were the special ones who responded to my tweets and never made me feel that I am talking to wall. Always up there for moral support and guidance. I owe these guys a lot for their help:

1. [Zseano](https://twitter.com/zseano)
2. [Rohan - \_Base_64](https://twitter.com/_Base_64)
3. [Demon - R29k\_](https://twitter.com/R29k_)

### The Trend of #100DaysOfHacking Challenge

### Unexpected Followers

### Conclusion

<!-- Potential headlines:
9 Lessons I learned from #100DaysOfHacking Challenge
#100DaysOfHacking Challenge: A game changer for me
The Power of #100DaysOfHacking: How it proved to be a game changer for me?
The Power of #100DaysOfHacking: How it helped me?
#100DaysOfHacking Challenge: Is it worth the effort?
Why #100DaysOfHacking is Worth Your Attention?
The #100DaysOfHacking Challenge Which Made Me a Better Hacker

Talk about: why you started, who supported you, burn out, triager congrats, crticism, appreaciation, include your repo of tweets, discuss about how your experience is fragmented and you cant give a figure of how long have you been hacking(if suitable), discuss how you have made a trend and people started following you, add your blog in multiple languages, add only main posts under posts page, rest goes to archive, talk about its not only about 1 hour, but many hours, absolutely no recon,discuss about getting complacent after finding one bug
you can talk about this https://www.youtube.com/watch?v=Ekcseve-mOg -->
