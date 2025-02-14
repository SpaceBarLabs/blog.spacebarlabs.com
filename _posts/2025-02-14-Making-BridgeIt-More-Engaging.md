---
layout: post
title:  "Making BridgeIt More Engaging"
category: ""
date:   2025-02-14
---

## Building BridgeIt for growth

[BridgeIt](https://apps.spacebarlabs.com/?rby=2025-02-14-Making-BridgeIt-More-Engaging) is an early access product and we're actively iterating with feedback from all of you!

## What did we do?

We’re working on spreading the word about BridgeIt so that we can see how people engage.

## Spreading the word

* We previously created our [Discord](https://discord.gg/drPR7dv5vS) and [blog](https://blog.spacebarlabs.com).  Now we’re on [Facebook](https://www.facebook.com/profile.php?id=61572416627190), [LinkedIn](https://www.linkedin.com/company/spacebarlabs), [Mastodon](https://mastodon.social/@bridgeit), [Reddit](https://www.reddit.com/r/bridgeit), and [Twitter](https://x.com/bridgeit_sbl)
    * All have logos and a profile picture
    * Blog posts automatically get posted to the new social media channels
    * If you haven’t already, please follow your favorite platform
    * We appreciate whatever you can do to help spread the word!  Social media has been one of our better ways of reaching users so far, so help is very appreciated.
* We have the start of a new referral code system.  Referral codes are internal-only right now.  Primarily, we’re trying to see what works and what doesn’t.  How do people like to sign up?  How can we help them do that better?  You’ll see this on some marketing materials and the sign up form.  
* We would love to have you refer your friends to BridgeIt! During our alpha and beta testing periods, BridgeIt is completely free. Someday, it will be at least a partially paid service. We're considering a referral program. If you're interested in being a part of it someday, please let us know at <a href="mailto:referral@spacebarlabs.com">referral@spacebarlabs.com</a>. We appreciate your support!
* We made a new “BridgeIt Phrase Book” zine.  It has some useful phrases for the top 6 languages being learned in the United States, along with information on how to practice with BridgeIt.  If you would like, you can [download it](/assets/2025-02-14/BridgeIt-Phrase-Book-Zine-Rev-1.pdf), print it, and leave it in appropriate locations.  For example, little free libraries in your area and meetups.  (We suggest doing at least one test print before making multiple copies.  Be sure to set the printer to flip on the short edge.)

<center>
    <form action="/assets/2025-02-14/BridgeIt-Phrase-Book-Zine-Rev-1.pdf">
        <input type="submit" value="Read the Zine" style="font-size: 18pt; padding: 7px; margin: 1em;" />
    </form>
</center>

## Making it easier to sign up

* We’ve found that many people like engaging BridgeIt first via text.  Now that we’re leaving BridgeIt’s phone number out in the wild, we’ve added a basic response for phone calls so that users know to text instead: "Hi! I can't take your call right now. Please send me a text message. Thanks!"
* We’ve made it easier to sign up by making our phone number field more forgiving with regards to formatting.  It also prevents mistakes such as area codes that do not exist.
* We’ve also made the phone number easier to read. <a href="sms:+18568807734?body=[blog] 👋">Text (856) 880-7734</a> is a lot nicer than +18658807734, isn't it? Though it does make the whole "flipped upside down like an old calculator" thing a bit harder to do. 🙃 HELLO-BB-GSB
* We’ve also added more information explaining BridgeIt to the landing page.

## Keeping users engaged
* We’ve added a new “nudge” feature for users who have gone dormant for at least 3 days.  To help keep users aware of their previous language practice, we send a simple wave emoji as a gentle reminder of the conversation thread.

## Known issues
* BridgeIt only supports “+1” phone numbers (USA, Canada, etc).  This is now listed on our sign up form.  We hope to improve this situation, as we had a Spanish phone number attempt to sign up.

## Technical Improvements
* BridgeIt now stays awake all day, rather than taking naps between chunks of requests.  In some circumstances, BridgeIt might not have responded prior to this change.  We’re sorry if that affected you!
* We’ve added background jobs so that some requests are less likely to bog down the server.  In addition, background jobs make it so that we can work on new types of features that were not possible before, like nudges.  It also makes some errors less likely to impact users, such as when signing up.
* Like all good software companies, we update our dependencies regularly.  We also clean up unused code regularly.  We also are continuing to build out test coverage so that we can be more confident in how BridgeIt behaves.
* We have also improved our automated testing, to help us catch bugs before they reach you.

## So talk to BridgeIt!

We've been working REALLY hard on this and would love for you to try things out and let us know what your experience was like.  Let us know if you have any questions or feedback.  We're always looking to improve!  Especially if you aren't finding BridgeIt engaging, we want to know why.  We're here to help you learn a new language, and we want to make sure we're doing that in the best way possible.

<center>
    <form action="https://apps.spacebarlabs.com/users/sign_up?rby=2025-02-14-Making-BridgeIt-More-Engaging">
        <input type="submit" value="Try BridgeIt" style="font-size: 18pt; padding: 7px; margin: 1em;" />
    </form>
</center>
