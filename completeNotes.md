# Freelance Client Lifecycle - Complete Notes

> Go from gathering the requirements to deploying the website and fixing bugs!

## 1. Gathering Requirements

Often you want to just get started designing or building the thing, because that's what you do, but failing to get the requirements right leads to more change requests, scope creep, and botched jobs!

:fire: You get burned if you don't ask the client enough questions! :fire:

:checkbox: Ask the client about general requirements first, and where do they make their money, as a business?

:checkbox: Get specific about requirements, like do they need a _simple_ contact form, or do they need something with a file upload that can go to multiple recipients, for example.

\* Ask the client if they had a dream website, at the end of the rainbow, what would that look like? You will then take their dreams, plus their hard requirements, and produce something to offer them that won't break the bank. (_And_ set you up for further business, hopefully, as well as save some headache from the architectural POV.)

(I'd probably ask about this next one, then gen reqs, then dream site, then get more specific requirements, _then_ budget.)

<!-- ... Waitt, no ... but keep going. -->

:checkbox: Ask the client about website/apps they like/dislike.

$ This is the point to ask the client about their budget!

Freelancing is business and businesses talk about money.

Deal with the money aspect up front so the client doesn't get sticker shock.

Remember, the conversation about money is a **conversation.**

:checkbox: Ask the client about contraints and offer something less expensive, something closer to what they wanted to spend, and some options with more if they want to go above and beyond.

Have a list of questions to give the client after the initial meeting. (Don't make every field required, and tell them to fill out what they can.)

! If you hear something ridiculous, link it back to contractors!

## 2. Producing the Quote

Quote will be produced ...

1k, 2k, 5k ... common prices.

"Fixed Quote"

:glasses: Gather requirements in functional areas, look at those and ask what the pitfalls might be and how long each might take you.

! Add 20-30% on top of how long you _think_ it will take!

? You're not billing hourly, but you should have an approximate idea. Shoot for $40/hr to start, up to $100-$125+/hr.

:checkbox: Consider also 'value-based billing,' where what the client gets can be something you've already built, but charge the same. Be able to ask client if they want something broken out if the price is too high! (Can have the groundwork for including ti later on in the requirements (architecture, data types ...))

:checkbox: Tell the client in the quote about the tech being used, why it will be good for their website, why it will be good for their business, that it'll be easy to update, that'll be open source (so that if you get hit by a bus, another developer could pick it up.)

## 3. Presenting the Quote

:checkbox: Have a presentation with what's included (and not included, if you broke anything out/talked a feature down.)

:checkbox: Include how long the quote is good for. (2 weeks.)

:checkbox: And the price (include tax (when legit))

## X. Timelines (Part of Quote)

Times based on client accepting by a certain time, assuming deadlines are met, and any questions or feedback get 24hr turnaround. If they blow their timelines, they have to know that you have to take another job.

:checkbox: Hard dates for launch and beta.

:checkbox: Hard dates for design time/development time.

:checkbox: Include time for three rounds of revisions, once the build is at a point it's ready to be shared.

:checkbox: Include deadlines for when the client needs to give my any assets etc.

:checkbox: Set up a shared Google Calendar

As important as their time, is your time.

## 4. Contract

$ If you need one, take a template, draft something up, and then have a lawyer check it, rather than paying a lawyer to write it!

If the quote is well drafted, you and the client signing it should be good enough, so that it's set in stone what's to be expected and what's to be delivered.

:signal: The most important thing is good communication. Remember you're working _with_ the client, do a downtown job, and maintain good communication, so that if anything _does_ go awry, you can get out from under.

## \* Setting Expectations/Establishing a Professional Environment

Set the rhythm for communication. Pick a time for email, don't send emails out at night or on weekends (unless that's when you do business) or the client is going to pick up on that and think you're available 24/7, and will text you every idea they have at 2am.

:checkbox: Tell the client when they'll get updates, like Friday afternoon.

! If they say anything about a previous developer, dig into that. It _could_ be that the previous developer was an idiot, in which case it's on you to set the standard for your trade, but it could alse be a client who's a nightmare to work with. If it just turns out they need extra hand-holding, maybe just charge them more.

## 5. Design Phase

:checkbox: Gather assets from the client. Logo, type, colors, brand guidelines ...

:checkbox: Get the client's likes and dislikes.

The website design's major goal is to generate more leads or sell more product or whatever, there's a whole other part too where it needs to make sure it gels with the rest of the company's brand, _and_ make sure the person who's getting the website is happy with it.

Make an approximate mock-up of like the home page, once you've got colors, spacing, type, anything that would be in global CSS.

! Looking good is only a small slice of good design. Back up the "why's" of what you do in the design phase!

Don't be offended by criticism and feedback, it's part of the process.

Try not to show anything _too_ early in the process, or all of that work is out the window if they get hung up on one thing.

When receiving feedback, either respond with, "Let's try that!" or "This isn't a good idea because of (accessibility, whatever.)

"This is not the layout, this is not the website, this is for colors and for look and feel." Tell them to not worry about all the fussy details, ask them how it makes them feel, what emotions are evoked.

Be prepared for "no Mustangs"* and "can we make it pop more" or "this looks cloudy, can we make it more sunny." Even Wes Bos' first response is RAGE, "What do you *mean\* cAn We MaKe It MoRe SuNnY?!" But then, just like with his two-year-old, it really just means they're trying to say something, but just can't verbalize it.

> Did you poop your pants? Are you hungry? Do you want to watch Papa Troll?

"What I hear you saying is ... and here's how I think we can make it better.

- "But it doesn't have the Mustang, and that's all I like."

## 6. Development Phase

If you've clearly specced out what each functionality should do, how it should work, then, actually, developing _to_ that spec should be easy, or not easy, but at least clear.

Here's where regular updates will be very important.

:checkbox: Include in the quote three rounds of revisions once the development is to the point where it can be shared.

"I'm not accepting feedback right now."

Maybe they see a version of the site that doesn't look any different! Is the project being worked on?

"You should be able to click through the pages."

Series of emails and a follow-up phone call.

If there are a lot of revisions, consider a kanban.

! For technical revisions, a screen share can solve a lot of headache. "What do you _mean_ it's glitchy?!" Maybe they're on IE6. Cache bust.

## 7. Deployment

$ 50% up front (25% depending on the size,) 50% on launch.

If there's a series of payments, Freshbooks can help with late pay reminders!

Remember deployment starts long before development is done, especially if you're using something like Vercel.

clients.garethfield.com/saeeds123 with url auth

! Robots no-follow the staging site!

$ The client pays for domain and hosting. It's their IP.

:checkbox: Talk to the client about backing up their data, and restoration. Maybe GH is enough.

Be available when deploying! (Don't deploy on Friday afternoon!!)

! Part of the handoff is training the client!

If the site is more complicated, include materials for anyone who would update the site, features, tests, etc.

:checkbox: Turn off what they don't need in the CMS, though obs leave them an admin account.

! Hold on to everything until you're paid, and if they don't, change their page to just a header tag saying, "Please see billing."

## 8. Bug Fixes & Support

If it breaks because of something _I_ did, in the next year, I fix it for free, and it counts as an emergency.

If it breaks from something out of my control, I can quote them to fix it. It does not count as an emergency.

The other strategy is to have a retainer in place, which can be like 10 hours a month, and maybe it doesn't get used, but if there's a problem, it gets fixed in 24hrs.

## FAQ

? How do you know how much it will cost and how long it'll take?

That's just a skill that needs to be learned. A good contractor is good at this, a bad contractor goes overbudget and misses deadlines.
