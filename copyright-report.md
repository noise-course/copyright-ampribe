# Platform Analysis
For my analysis, I chose to research SoundCloud.
- SoundCloud detects copyrighted works through two systems. First, an automated content ID system compares the uploaded file to a database of protected tracks and automatically blocks matching content. Second, SoundCloud allows manual reports of copyright infringement, which can result in an account "strike" that can lead to termination of an account. 
- When content is automatically flagged or manually reported, SoundCloud blocks or takes down the content.
- Users can file a "dispute" if they feel that their content was wrongly blocked or taken down. The dispute will be manually reviewed by SoundCloud's copyright team.
- Users may only monetize content that they own completely or have rights to. They may not monetize derivative works like unofficial remixes.
- Yes, SoundCloud allows rightsholders to submit content they would like to protect or manually flag content that violates the copyright policies.

Sources

https://help.soundcloud.com/hc/en-us/articles/4402636813979-What-are-SoundCloud-s-copyright-policies

https://help.soundcloud.com/hc/en-us/articles/360051037454-SoundCloud-for-Artists-Copyright

# Fair Use Experiments
Experiment 1: ~20 second clip of "Shake It Off" by Taylor Swift
[Screenshot](folder/original.png)
- Because this was a raw copyrighted clip, I expected it to be automatically detected. However, as of right now, it has not been taken down and can be accessed [here](https://soundcloud.com/play-plosive_8q/original).

Experiment 2: Remix of  the same "Shake It Off" clip (altered pitch, tempo, added drums)
[Screenshot](folder/remix.png)
- This version also was not taken down and I received no warnings. It can be accessed [here](https://soundcloud.com/play-plosive_8q/remix).

# AI-Generated Content Investigation
Experiment 1 (Direct Reference): I used Suno to generate a song with the lyrics of "Shake It Off" and in the same style (I used Claude to generate keywords to put in Suno). Interestingly, Suno said the generation was not allowed because the lyrics contained copyrighted content, but it still allowed me to generate and download the song. SoundCloud did not take the song down and it is available [here](https://soundcloud.com/play-plosive_8q/suno1).

[Screenshot](folder/suno1.png)


Experiment 2 (Style Mimicry): I asked Claude to write lyrics and describe the style of a song in the style of Taylor Swift. Then, I generated a song in Suno using the lyrics and style description. Below are the prompts I used, the output, and a screenshot.
```
Write lyrics in the style of Taylor swift
```



```
Output just the lyrics as they would be sung (repeat chorus, no labels like "Chorus")
Describe in a short paragraph with keywords how it would be sung and the style
```


```
**Polaroid Memories**

Coffee shop on a Tuesday morning light
You wore that jacket, faded blue and white
Said forever like we had all the time
Drew our initials in the window shine

And I believed every word you said
Now I'm dancing with ghosts instead

We were polaroid memories
Fading in the sun too fast
Thought we wrote our story
In permanent, not photograph
Now I'm holding onto moments
That are slipping through my hands
We were polaroid memories
Never meant to last

Midnight calls and your old pickup truck
Small town dreams and a little bit of luck
You said you'd stay, cross your heart and hope
Now I'm here learning how to let you go

All the promises we made back then
Are just echoes on the wind

We were polaroid memories
Fading in the sun too fast
Thought we wrote our story
In permanent, not photograph
Now I'm holding onto moments
That are slipping through my hands
We were polaroid memories
Never meant to last

Maybe someday I'll look back and smile
At the girl I was, if only for a while
But tonight I'm still learning how to breathe
Without you here next to me

We were polaroid memories
Fading in the sun too fast
Thought we wrote our story
In permanent, not photograph
Now I'm holding onto moments
That are slipping through my hands
We were polaroid memories
Never meant to last

Never meant to last

---

**Style Description:**
This would be sung as a mid-tempo pop-country ballad with acoustic guitar foundation and building instrumentation. The verses start intimate and conversational, delivered with a gentle, slightly wistful tone. The pre-chorus builds anticipation with rising melody, then the chorus explodes into a soaring, anthemic hook with layered vocals and full production—drums, synths, and strings. The bridge strips back to vulnerable and raw, almost whispered, before the final chorus returns with maximum emotional impact. Think *Red* or *Folklore* era production with confessional storytelling and that signature Swift melodic catchiness.
```

[screenshot](folder/suno2.png)

The content was not taken down and can be accessed [here](https://soundcloud.com/play-plosive_8q/suno2).

Research Findings
- The Suno [Terms of Service](https://suno.com/terms) says that users must have rights to all the content they upload (lyrics, tracks, etc.). 
- The TOS says that, for users on the Pro or Premier plans, Suno assigns the rights to the generated content to them. However, for users on the free plan, Suno retains the right to the generated content and the user must give credit to Suno. So, Suno owns the copyright to my generated content.
- SoundCloud allows AI-generated content but requires that you own the copyright to monetize the content. It notes that SoundCloud must verify that the AI service granted you rights to the content before monetization. [Source](https://help.soundcloud.com/hc/en-us/articles/32096725354779-Distributing-and-Monetizing-Content-Made-with-the-Help-of-AI)

# Legal Analysis
Raw Copyrighted Clip
1. The purpose and character of the use was not transformative (I didn't change anything) but also was not commercial (I didn't monetize the clip).
2. The copyrighted work is creative in nature, so it is less likely to count as fair use.
3. I used a small amount of the content (20 second audio clip of a 4 minute song). However, my clip likely constituted a substantial portion of the original work since it retained the style and character of the original. It could clearly be identified as the original work.
4. Nobody looked at my clip, so there was no effect on the market value. Also, it would not substitute for the original because people would likely want to listen to the entire song instead of a 20 second clip.

Remix
1. The purpose and character of the use was more transformative than the raw clip because I altered the pitch, tempo, and added drums. It was still clearly derivative of the original work. Like before, the use was not commercial since I didn't monetize it.
2. The copyrighted work is creative in nature.
3. I used the same 20 second clip, but the modifications made it less of a direct copy. However, the core melody and structure were still recognizable as the original work. 
4. A remix could harm the market for the original work. However, since my remix was only ~30 seconds, it likely doesn't substitute for the original.

Gap Analysis
- Suno had a clear gap between the platform policy and enforcement. Even though the policy stated that copyrighted lyrics were not allowed and my lyrics were flagged as copyrighted, it still allowed me to generate and download the content. 
- SoundCloud also had a gap between platform policy and enforcement. SoundCloud does not allow uploading copyrighted works and the automated system is supposed to identify such content, but my 20 second raw clip of a copyrighted work was not removed. 
- Suno's platform policy is not clear about generating content in the style of a particular artist. It allowed me to generate content in the style of Taylor Swift. However, this usage may be questionable under copyright law because the generated content is not substantially different from the original and may hurt the market value of the original work since users who enjoy Taylor Swift's style could listen to comparable AI-generated songs instead.
