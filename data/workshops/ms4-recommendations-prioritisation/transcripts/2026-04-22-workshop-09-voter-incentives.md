---
workshop_number: 9
date: 2026-04-22
title: Assessing Governance Recommendation -- Voter Incentives and Requirements
video_url: https://youtu.be/7pyAc4P8TBo
attendees:
  - Tevo Kask
  - Roman D
  - Seomon
  - Ian
  - Ken Erik
  - Seon Gbiri
---

# Workshop #9 -- Voter Incentives and Requirements

## Summary

The session reviewed two recommendations from the Beyond MVG prioritization
backlog. With a small audience the host walked through the assessment flow as
a guided monologue, with brief input from other attendees. The first
recommendation discussed was "Remove the requirement to select a DRep to
withdraw staking rewards", concluded as low-impact and low-risk but unlikely
to address DRep concentration directly. The second was the Applied R&D work
stream "Voter Incentives" by Rosito, covering bonus pools, saturation caps
and DRep compensation -- assessed as a Must with significant scope but a
multi-year delivery horizon requiring a hard fork. The host also demoed the
new "Discussed in workshop" admin flag and the AI assistant feedback panel,
and gathered feedback from new attendees on platform onboarding.

## Topics Discussed

- Remove the requirement to select a DRep to withdraw staking rewards
- Voter Incentives -- Applied R&D work streams (bonus pool, saturation caps, DRep compensation)
- Onboarding new participants to Beyond MVG
- AI assistant accuracy and the "Rate response" feedback loop
- Suggestion: show current state and projected outcome alongside each recommendation

## Attendees

- Tevo Kask (facilitator)
- Roman D (first-time attendee, Germany, GMT+1)
- Seomon (observer, new to Cardano governance)
- Ian (intermittent, connection issues)
- Ken Erik (joined mid-session)
- Seon Gbiri (joined mid-session)

## Transcript

> Tevo Kask: Hey Roman D, can you hear me?
> Roman D: Yes, I can hear you.
> Tevo Kask: So how is your day today, is it early or late at night for you?
> Roman D: I am GMT plus minus one from Germany, so I am midday right now.
> Tevo Kask: Then we are similar, plus three.

Let's see how many people join. It's so random -- one week we have 10 plus
people, another day last Friday we had three people, and now we have you and
me which is the lowest point yet. There will be at least some team members
showing up, as I am technically not a facilitator even today. But let's see,
maybe there are workshops happening right now or like other meetings.

> Tevo Kask: Roman D, have you checked up on Beyond MVG past workshops or what we do in general -- how aligned in a sense are you with the activities we are doing here?
> Roman D: This is my first time joining, and I'm basically here just to listen in. The topic was interesting so I thought I am going to listen in.
> Tevo Kask: Okay, well I will give you a quick tour for the application and a bit of background, because I don't know how many people will join later and if they need a full tour we may not need to repeat this information.

So first of all, where is my chat now -- we used to collect insights just in
like a Miro board or meeting documents and surveys. We did some surveys
through Google Form and through that we captured a bunch of insights and
observations about the governance metrics, and we are focusing on on-chain
metrics. So on the challenge page you will see multiple charts on the left
side. It shows you how the voting status breakdown -- basically Ada holder
metrics, DRep metrics, SPO metrics and CC metrics, so the constitutional
committee metrics. Each of these sectors has a few charts you can look into.
These were the most interesting things that people wanted to show. We update
the charts over the past few months based on the previous insights, and now
we have gotten into a stage where we have summarised all of that into
challenges.

So in the right side you will see under this metric there is a challenge,
"DRep voting power is concentrating", and under "percent of DRep votes that
include a published rationale" there are three challenges that were brought
out. That is the starting work, the on-chain metric part that was done. These
challenges -- we already have around 30 recommendations, and if you have any
recommendations that are not fitting here, you can click "Add recommendation"
and people can write down the recommendation and add any related challenges.
You can have multiple challenges related to a recommendation -- what the
recommendation addresses. That is how we collect these recommendations.

In the last workshop, for example, we are now prioritising in the prioritise
page, using a Reddit-style up/down voting basically, to define whether this
should be discussed or not. Yesterday we took the most-voted item and had
almost a 40 to 50 minute discussion just on that one topic, going down with
different guiding questions to surface how valuable that recommendation is to
be implemented. That is the workshop in a nutshell, and a bit of insight into
what the team itself is doing -- previously we created the charts, we are
working on governance reports, and after this stage the next step is to help
draft CIPs or Cardano Problem Statements, or push existing ones further.

> Roman D: All right, I am clicking through the website right now, I wasn't aware of this. It is very interesting. I am going to click through it and then if I have something I will try to come on these workshops and check this out.
> Tevo Kask: Yeah. Well, even though we may have a smaller audience than last time, the good thing that has happened is that asynchronously there have been more votes and even some of the stuff has gotten comments, so that's a great thing.

Let me check -- yep, the session is recording also. So those watching from
YouTube, you also know that in the description below you will find access to
this app and you can provide your comments.

> Tevo Kask: Ian, Newa -- I don't quite remember your name -- I wonder, were you here before? Do you know what this workshop is about? If you do, I will actually just go ahead and start the discussion without giving too much demonstration. But if you need context, this could be a perfect place to ask.

How do we want to start today? Do we want to take a few minutes to browse the
prioritisation dashboard? Because we are technically at least four of us
here, we are essentially able to -- if you already did not vote, as you can
see I have voted on some stuff -- to change the order. Alternatively, we can
just go ahead and take a next item. I did a small update just five minutes
before the call started. Good thing is that the website didn't crash. But
here are a few design elements: if we have the discussion in workshops I
created this small icon and highlighted in different color, and right now I
don't see any. There will also be green background colors appearing for
items when we have multiple assessments by different people and a few
comments on an item, to indicate where the activity is happening
asynchronously, so we don't just have 30 same-looking items.

> Tevo Kask: Okay -- Seomon, you are observing. Ian was probably also observing. Roman D is new and he saw this website for the first time, so probably you will have the most time spent on reading it. But the good thing is that you can read also after the workshop, so this stuff doesn't go away.

Perhaps we can open up with some kind of discussion to get the experience of
what we do in these workshops, and for the audience watching from YouTube.
Based on the most-voted priority -- and we already discussed the DRep
incentive -- I will go to the next item, which is "Remove the requirement to
select the DRep to withdraw staking rewards". This will mitigate some users
simply picking the wallet default, which makes the wallet's DRep
significantly more powerful than they otherwise would be. It is addressing
one of the challenges called "DRep voting power is concentrating", and we
have a link to more details. Usually GitHub has also a bunch of comments.
This one is fairly new actually -- March 1, so one month old.

There's a bit of guidance where there should be a person in favour. One
person is in favour of that, some kind of ledger-related suggestion. Yeah,
because I assume that script withdrawal patterns are outdated. Okay, so
there was a comment about how the requirement works on the ledger side and
it has been overturned. "I recommend removing the section as it is not
relevant to a CIP and will only confuse readers, wrongly thinking that this
was ever a concern." Okay, so I'm going to skip that. "I said it multiple
times elsewhere, I don't believe this restriction leads to any increase in
participation and just leads to friction at the wallet level."

So removing -- I'm kind of confused. I think he is arguing that removing
this requirement for users to delegate to a DRep to get the SPO rewards will
create friction. But the argument is hard to implement. A huge reason why
some wallets give a large -- yeah, the URI is one of the wallets that
auto-delegates users or gives the option to auto-delegate. And yeah,
Volarus is referencing that the process is the problem, not really the
requirement. Agreed on a CIP meetings today.

So yeah, it is interesting and quite a straightforward recommendation. It
is not as large in scope in terms of "will it really affect governance"
-- this is a technical thing that we added removing. I personally don't
think it has any large impact, because essentially what happens is then
most of the people who want SPO rewards and kind of do this motion will
simply not delegate to a DRep. And is that a good thing? I don't know. I
would actually argue that if you don't care about governance then maybe I
don't participate. But would that be an auto-abstain, or is there like a
fourth category, or does that mean -- yeah. So it does put a sense of
where the default value is then going to reside.

> Tevo Kask: Any thoughts in the room on this particular recommendation in general?
> Seomon (chat): If they write rationale and vote like deals I don't see why they shouldn't get the rewards.
> Tevo Kask: I think the people we are talking rewards about is the SPOs that are getting rewarded -- or like, they won't get rewarded if they don't delegate.

Well if no one else does, then I am going to share what we have as
assessment. So each of these recommendations has this assessment submission.
If you are first there is a button "How does scoring work" which explains
the score on the right side -- by default it is somewhere around 40, I
think. Let's see -- there are below-average assessments. Okay, here is one
without any assessment, so basically a default score is 54. The 100 score
is basically if all the benefits are at maximum and all the costs are at
minimum.

Then we have movers, basically Must / Should / Won't -- we have the
ability to choose which category at a high level this recommendation
should fall into. Then we have the scoring dimensions that go in detail:
how significant it is, how time-sensitive, how many people want to
address it. Then the cost dimensions: legal risk, maintainability. So if
we address all of these areas, answer all of these questions, we should
be able to get quite a nice holistic view of where this recommendation
is sitting and what the priority for it could be. When I press the
Assess button it will open up the options to move stuff around. I
already have my own scoring. Every person who does that creates their
own scoring and the average score will be used as the final score.

The first question: how many people or processes are affected by this
mechanism?

> Tevo Kask: Roman D, let's start with you and I am going to go round table. What is your thought -- on a scale of 1 to 10, how many people will this recommendation affect, is it few people or the entire ecosystem?
> Roman D: I have no thoughts on that, sorry, I can't help with this. I am still following.
> Tevo Kask: Okay. Seomon, how about you -- do you have any thoughts on how many people or processes are affected by this recommendation to remove the requirement to select a DRep to withdraw staking rewards?

Okay, so it feels like today I am the one who is going to talk and three of
us in the call will all observe. The best you can do is argue against me or
object if I go off with my thoughts and we are seeing some kind of dead end.

So basically, "How many people or processes are affected?" -- I would say
the entire ecosystem just like the first thing, because that is baked into
the protocol so everybody will feel that already, or not feel it if we
remove it. I think this has a huge impact. But there may be a hard
consideration here -- in terms of just how many people and processes it
affects, I would put 10. Then "Is there a deadline or time pressure?" I
think yeah, it can wait indefinitely because it is something that at least
personally doesn't bother me but it may bother somebody. So here is an
opportunity for others to increase the value.

> Tevo Kask: Hello Ken Erik and Seon Gbiri. We are in a unique composition of people in this call today. Seomon and Roman D will be mainly observing tonight, and Ian too -- going in and out, maybe connection issues. Roman D is a bit new to this Beyond MVG process, so is browsing around the metrics and charts. So what we have decided for now is that I am going to go through the top-rated prioritisation and basically have a monologue, and people can comment and stop me where my thinking goes too far.

Okay, going forward: "Can this be built with existing tools?" Our top topic
today is "Remove the requirements to select a DRep to withdraw staking
rewards". Can this be built with existing tools? I would say yes -- I mean,
I think it is more about removal. So it feels like even low effort,
considering you just need to make sure you don't break any dependencies. I
don't know -- feels like an easy thing to do.

"What resources would be needed?" Again, very limited cost. Maybe talk to
Brian or somebody who has access to this ledger -- well, technically
everybody has access to that. So maybe even just asking Claude, "Hey, can
you remove it, create a pull request" might be a solution here.

"Aligns with Cardano roadmap and priorities?" Okay, this is a hard one,
because either way it doesn't really affect the roadmap. So I'm going to
skip that. It is a very technical recommendation. Even -- yeah, it is
addressing the challenge of "DRep voting power is concentrating", but I
don't know if this is a solution here. It probably only affects very
specific wallet providers or platform providers, to have less people who
don't care about governance vote for them or delegate to them. But it
doesn't stop concentrating, it just reduces the amount of people who
participate.

"How quickly can benefits be realised?" Yeah, the question is what are the
benefits. Maybe there is some benefit we can get realised. I am just going
to keep it in, because that's a measurable thing, especially now as we
have this feature -- if we turn it off we will definitely see the on-chain
effect, probably already in a few months. But is it beneficial? We don't
really know. I am trying to value in a sense -- the outcome should be
quite measurable.

"How much uncertainty is in this approach?" I will say highly uncertain.
Well, it depends -- for me it is highly uncertain because I don't know if
it solves the problem of concentration. It does a pretty particular thing
here. But as a technical risk part of it, yeah, I think it is low risk to
remove. This is probably very low risk because before it wasn't
necessarily so -- for the hard fork basically doing a reverse. I am going
to lower it to four.

"Regulatory compliance considerations" -- I think none. "Ongoing effort
needed to maintain" -- maintainability is also set-and-forget, but maybe
I want to come back and reintroduce that, but it is still a forget part.
After hearing my monologue going through all of these assessments, does
anybody have final comments on the way I was thinking and assessing that
requirement?

> Seon Gbiri: Yeah -- in regards to DRep concentration, we have seen a lot of the concentration might happen due to actually the default wallet setting which we have identified happens over quite some time. I am not sure if it will have an immediate effect, but perhaps in the long term it will, because you cannot un-delegate what has been delegated to you as long as it is active.
> Tevo Kask: Mhm. Okay.

And now I am going to also show the new feature: admins can now say that
this is "Discussed in workshop". Okay, it doesn't automatically update --
but if I refresh, what happens here -- it gets this icon that we have
discussed it. We have 30 minutes to go. I have no plans other than being
in this call, so let's just pick another one and go to that.

Voter incentives -- "Applied R&D work streams". Did I really now lose the
expand button? Weird. This is not good that I cannot show you the full
info here. Is this the one from Mark? Yeah. Okay, so there is a thing I
introduced -- so we cannot fully expand the recommendation, and that is
prior to the speech. Anyway:

"Applied R&D work stream focused on incentive models to encourage delegators
to be more active, redelegating their voting power more frequently
according to a DRep's performance, in order to break delegation
stickiness. I conducted research and developed a model that will solve
the problem."

"How can we increase meaningful participation? There are different ways to
design governance incentives and it's important to distinguish them
clearly from the start. At a high level incentive mechanisms can be
divided into two broad categories: positive incentives, which are about
rewarding behaviour, and negative incentives, designed to reduce benefits
or add friction. Both approaches aim to influence participation but they
do it in very different ways."

In governance this could mean offering some additional benefits, and
negative incentives in governance can take the form of forcing users to
take periodic actions to preserve access to rewards. Then it provides a
link to additional information -- an article, "How can we increase
meaningful participation: addressing DRep delegation stickiness and
barriers to entry" -- which goes quite at length.

In simple terms, the answer is this: meaningful participation in
governance can be increased by recognising that incentives can be
designed either as rewards or as disincentives, either inside or outside
the protocol. The article suggests that the current governance problem is
driven by concentration, inertia and weak re-engagement. From that
starting point it points toward the need for mechanisms that make
delegation more dynamic, lower the practical barriers facing small DReps,
and improve accountability. There is also another piece of additional
information.

"Distributing direct influence with delegator incentives -- approaches to
improve delegation intention and the representation quality." As a result,
proposals typically fall into three parts: delegator-side mechanisms
(reward expansion, generalised delegation rewards, increased donations,
reallocating value, creating new recurring obligations, access friction,
conditioning staking rewards), DRep-side incentives and compensation, and
saturation caps and DRep-effective opt-in.

So there is a lot of context here about incentivisation ideas, or at least
requirements, or having that overall idea for how to do incentives.
"Pressure-based delegation" -- and I guess there are also multiple
recommendations here.

Coming back to the item itself, essentially what it is proposing is
applying voting power more frequently. So based on the title it feels like
there needs to be teams who work on incentives, and these articles help
to understand what goes into drafting incentives and disincentives. Then
there was a lot of text to read there, but on a high level it is looking
at like a K parameter, if I understand it correctly, for DReps -- they are
talking about compensation and saturation caps. Yeah, on their voting
power.

> Tevo Kask: So this would be a little harder to assess because it is a bundle of recommendations.
> (assent)

But regardless, incentivising governance or activity where people are
experts -- the community comes together, understands an issue and starts
to come up with models to experiment with -- I think that is the only way
we can get healthy governance. So instead of having one or two entities
to dictate what is the experiment and what we are going to experiment
with.

I just read that article. Now I also see -- here it is called a "bonus
pool". I also know that others in the community have been debating, you
know, doing a treasury draw and fully saturating a stake pool and have
that for distributing rewards. So yeah, I think I saw somewhere a
recommendation about that exact thing -- making a stake pool fully
saturated and using that to reward. Oh, maybe that was the last
workshop's comments where we touched on it. The first place I spotted it
was Yuda who suggested this, in an X post.

> Tevo Kask: So yeah, but he didn't talk about K parameter or capping the voting power.
> Seon Gbiri: From what I can read at least from this Voter Incentives item, they are going for saturating a pool -- bonus pool as I call it -- and also tapping the DRep holding power.
> Tevo Kask: But here in that thing, what you are describing is these rewards then go to the voter, or to the DRep doing the voting?
> Seon Gbiri: It's for a DRep.
> Tevo Kask: Okay.

I just realised that both of these "Applied R&D" work streams are done by
Rosito -- the first one we discussed last time, "Applied R&D DRep
Incentives", was also his. So I think he opted into two different buckets,
one focusing on DRep incentives and the one we are looking at now which is
voter incentives. In both cases you can reward users with the stake for
rewards, or have some mechanism for that.

At a high level I would say yes, this is a Must. We do need both
incentives and disincentives, like better gamification methods that are
more interactive and feel more like healthy conversation for both voters
and DReps. I am going to put it as a Must. As impact, I put 9 instead of
10 because it still won't affect everybody. Those companies who just want
to use the protocol for specific things -- store data or get verifications
-- or those who are using ADA as a hedge against risk asset and just
distribute their portfolio, for those it doesn't matter what we do here.
But yeah, I will put it in.

There is even calculation here -- a circuit breaker for the jackpot epoch
box and boost crashers. This is something you have to take notes when you
read. See, the bonus pool here. This is a lot to read. But we do have
Seon Gbiri and Ken Erik, so I don't actually have to do a monologue now anymore.

Next question: "Is there a deadline or time pressure for this?" Any
thoughts from Seon Gbiri? How urgent or non-urgent do you feel this
recommendation is?

> Seon Gbiri: Yeah, I think it is quite urgent and currently aligns with the absolute Must, basically -- I am reading because I have not taken a look at it before, I am just trying to understand a lot of things right now. But looking at it, the incentives and the disincentives are actually very important. Yeah, the saturation cap looks like the better approach because it is directly from the treasury. So yeah, it is a Must for me.
> Tevo Kask: A Must then. "Can this be built with existing tools?"
> Seon Gbiri: The pool part can be used, as far as I know, but it is the distribution mechanism here that is a little bit tricky. It needs a hard fork. The reason for that is the ledger -- there are these two parts. The ledger doesn't see a DRep certificate. So currently you cannot for example make logic with smart contract and stuff like that utilising the DRep certificate. But I know at least from what I have been catching up on that that is something actually that has been looked into, and it has nothing to do with the DRep compensation or incentivising to do.

So we would say feasibility is 8 out of 10 but it has technical risk of 5,
because yeah, it is a technical barrier that we reach. I would assume then
the cost estimate will also go a bit -- I don't know, as same as
feasibility then. If it required hard fork and ledger stuff then IOG is
going to ask a few millions for that. Sometimes it is a good question:
should they pay millions to those who are in control of protocol, or use
these millions to incentivise the people to actually do the work already?
Because there was -- yeah, in the chat people were sharing that we have
the tools as they are already, the problem is just people don't
collaborate, we don't look at the values we want to do, and the human
layer is much harder to achieve. It is not about whether the proposal is
going up or not -- we can put any proposal up there and anybody can budget
the cost into there. But the human layer of getting people into
agreement, and knowing that this is where we are going with this
blockchain, that is the hard part, and it is not a technical issue.

"Aligns with Cardano roadmap priorities?" I think it does, because we are
trying to give -- especially with this -- we are decentralising power. In
case somebody wants to get through my door -- so Ben, you are in charge.
We have three more questions, and when I come back you tell me what the
numbers are.

> Seon Gbiri (taking over): When it comes to ongoing efforts needed for maintenance -- as everything that we put on, when we do some changes it probably needs updates and optimisation. So there is maintenance there. Regulatory compliance consideration -- no, I don't see any issues there. Technical risk -- probably yes, have put it up there. And how quickly it can be realised -- they have been debated, but the development for this is a long process, so we are talking about two, maybe even three years. Then on top of that this needs to be prioritised along with other stuff like updates.
> Tevo Kask: Right, you forgot to mute yourself. But now you have muted yourself.

So similar like yesterday: it is a long road to implement such a feature
because you need to update the ledger. Regulatory consideration is
absolutely very low, and then maintenance is medium, I will say, because
every time you do an update you have to look at previous changes. I think
it is even five, because this is voter incentives applied work streams,
so it is consistent research and development, and even if you implement
that you would probably need another round to re-evaluate how it is
working right now and what we need more of. The more we do it, the more
active people get to coming up with new experiments. So I think it has a
high cost, needs to be tweaked.

Okay cool, we now have two assessments for this, but both are Must score
-- I think that's the highest score. And let's do this -- now it appeared,
this "show more" button was not visible before. I cannot open the same
view that you have, but everybody has their own assessment scores. That is
why you cannot see the exact same scoring.

> Seon Gbiri: Well, I cannot get up the assessment score at all -- that was interesting.
> Tevo Kask: What happens if you click on the prioritisation item then?
> Seon Gbiri: Hold on, I will share my screen here. There we go.
> Tevo Kask: Okay -- and your issue is...
> Seon Gbiri: Well, now I found it -- I didn't find that button. Oh, okay.

We have an average of 20 minutes that goes for an item.

> Tevo Kask: So let's roll back on Roman D and Seomon. How do you think so far the platform works? How is the discussion going? Do you feel the recommendations are great here? Do you think there is something missing? What are your initial thoughts on the first workshop you joined, aside from the overwhelming amount of information?
> Roman D: Yes, this is the first point -- a big amount of information. For now I have to read in what all the recommendations are about, try to understand them and then get into the discussion. There are just many pieces of information to take in when you first visit the website.
> Tevo Kask: Can it somehow be made easier for users? Should I make a top three or something instead of throwing all the data at once? Are there any expectations for you to see different overviews or top selections, or do you think this is fine and it just takes time to consume?
> Roman D: I think there have to be something like the ribbons -- there are ribbons but they have to be more specific for the topic maybe. I read a "Strong recommendation is to support the place research dada da dada for the Applied R&D DRep incentives" and I have more to read into it until I understand what's everything about. Yeah, has to develop over time.
> Tevo Kask: Okay, anyway, welcome to governance Roman D. We all start somewhere and I am glad to have you here. It is a steep learning curve but everybody gets there eventually.
> Tevo Kask: And Seomon, how about you? How do you feel about today's workshop and the platform in general? Maybe it is a good time to give feedback so the next one on Friday will be even better.
> Seomon: I share almost the same sentiment as Roman D. But I prefer to take everything in because I am not new to governance per se in the web space -- I have done governance before but I am new to governance on Cardano. So I am trying to take in all the information to be able to interpret it. I feel this is going great. I like the Beyond MVG platform -- I am on it right now and I am trying to look through everything and everything seems fine. So I will just take my time to read through it, understand it, and be better informed ahead of the Friday workshop.
> Roman D: Something just came to me for an optimisation. Maybe in such recommendations it would be interesting to have the now-state of the governance issue and then the recommendation itself -- what could it change, like which metric could it change. I had to think about Polymarket, where you have different outcomes and you can kind of see what could change if I vote this or otherwise.

Yeah, I wonder how it would best be implemented. At the easiest I guess I
could say just a user tells me what's the current state, but on the other
hand the challenges that we have crafted for this workshop series are kind
of the current state. For example I opened "Remove the requirement to
select DRep" and the user has applied supporting evidence, which is "DRep
voting power is concentrating", so that kind of is the current state. If I
share the screen again -- there are small features hidden all over the
place. So when you open up a challenge and you see this supporting
evidence, every place you see this M21 -- this is actually the chart name
-- so you can open up and that is the affected magic.

> Roman D: Yeah, I mean, like to explain -- with magic, a recommendation would be there and some kind of related graph would appear there, and then it would say "if we vote for this, the outcome could be this" -- like a visualisation to get more into the topic and what the recommendation is.
> Tevo Kask: Okay. What I am going to do is show you also a bit of feature on the right side panel. There are three options: support, feedback, and AI assistant. Worth trying it out -- it's not perfect, but every feedback you give through the agent itself, for example "Who is in Beyond MVG team?" -- I don't know if it answers correctly and I understand that, but what I'm trying to show is it has this "Rate response" option. If you rate that, whatever you submit, then we will see the result and I can optimise the AI to give better answers, and we then know what people are actually asking and are interested in.
> Roman D: All right, I see.

Right now it doesn't really tell who it is. We know that Fanny is part of
the team, we know Kenny -- so it's like a guessing game, but it is not
really quite sure who is in the team. It does not know about me. And it
leads to a link.

> Roman D: What was the query?
> Tevo Kask: I asked "Who is in Beyond MVG team?" -- and it says it's not detailed, although it's quite detailed, it's on the front page of the site, with 1% accuracy just to look at -- what is that? Yeah, just looking at the interview notes.

Okay, so technically this was kind of bad, not really trustful. So I will
see -- next time when I look up the improvements to do for the website I
know that I can fine-tune the documentation that has information about
the team itself, and make sure it recognises that. So that is one
feature. Another one you mentioned was "add the ability to add a future
state or recommendation, aka what happens if this gets accepted". Yeah,
this is enough. Same thing -- feedback will be registered and I will be
able to pick it up when I am doing development.

> Seomon: This AI explains a lot of the DMs I have got.
> Tevo Kask: Okay, well, all righty. With that, I think today we are done. We got two workshops, or like two discussions covered, a bit of that. Everybody is welcome to ask asynchronously, add comments, add assessments, and the next time we meet we go again from the top votes.

Everybody who is able to consume all the content -- if it is too much to do
manually now, as there are so many recommendations, on top here you have
the Data button and you can export some data yourself, if you just want to
feed it to your agent and talk to it that way. Because my agent, our
agent, may not be that great for that, but you may have fine-tuned stuff.

> Tevo Kask: Okay, thanks for joining again and see you on another. Bye, and thank you for listening.
