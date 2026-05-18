---
workshop_number: 12
date: 2026-05-02
title: Beyond MVG Workshop -- Governance Recommendations & Prioritisation Final Session
video_url: https://youtu.be/kn1iWt3BRbs
youtube_description: |
  Final Beyond MVG workshop session. The group focused on Constitutional
  Committee (CC) recommendations: only four existed on the overview map and
  none were tagged Must. Ken Erik (Tingvoll CC member) walked through the
  real complexity of operating CC credentials -- consortium key management,
  air-gapped signing, Cardano CLI / cbor / NFT-based orchestrator scripts,
  and a deep learning curve with no formal education path. The group added
  a new recommendation "Operating, creating and maintaining CC credentials"
  and elevated CC tooling and CC incentives to Must-tier through full RICE
  assessments. Sebastian Pabon argued for trading some absolute security
  for low-friction process; Rodrigo Pacini stressed financial AND
  reputation incentives; Ken cited the prior CC budget figures
  ($350k compensation/legal, $265k hardware, $221k training). With a CC
  election landing inside three months and CC keys expiring 1 September,
  the urgency was rated 10. Session closed with a workshop retrospective
  (Oliver, Sebastian, Rodrigo, Ken) and the announcement that new
  recommendations and assessments freeze on Monday so the data can move
  into analysis for the milestone 4 state-of report.
attendees:
  - Tevo Kask
  - Ken Erik
  - Sebastian Pabon
  - Rodrigo Pacini
  - Oliver Sterzik
  - William Nyirenda
---

# Workshop #12 Transcript -- Governance Recommendations & Prioritisation Final Session

Raw YouTube auto-caption transcript with original timestamps preserved.
Stored verbatim for machine reading and future reference. The cleaned,
paragraph-formatted version of this conversation is summarised on the
workshops page card; this file is the source of truth for the spoken content.

## Chapters

Chapter markers for the recording. Two kinds:

- **Assess** -- a RICE / MoSCoW assessment question Tevo walked the group through (impact, urgency, cost, etc.)
- **Guide** -- an open-ended guiding question or framing the group debated.

| Time    | Kind   | Topic |
|---------|--------|-------|
| 0:03    | Guide  | Arrivals and small talk on proposal complexity |
| 2:37    | Guide  | Goal: tackle the missing Must-tier CC recommendations |
| 4:30    | Guide  | Walkthrough of the overview map and CC recommendations |
| 8:18    | Guide  | Ken proposes new recommendation: operating CC credentials |
| 10:02   | Guide  | How CC consortium credentials, signing and orchestrator scripts actually work |
| 14:26   | Guide  | Pivot to CC tooling: pressure from DReps, uncompensated, complex proposals |
| 19:08   | Guide  | Constitutional debt and member interpretation |
| 22:28   | Guide  | Tenant 8 example: voting unconstitutional on the CF summit proposal |
| 25:31   | Guide  | AI / scripts to instil CC institutional knowledge |
| 27:30   | Assess | CC tooling: impact (Sebastian: 10, blocker) |
| 31:30   | Guide  | Balancing security vs low-friction usability |
| 35:12   | Assess | CC tooling: feasibility (Ken: 4, deep learning curve) |
| 38:10   | Assess | CC tooling: urgency (10, CC keys expire and election in 3 months) |
| 39:32   | Assess | CC tooling: cost (10 -> 6, composable solutions exist via Match / OS committee) |
| 43:06   | Guide  | Past CC budget: $350k comp/legal, $265k hardware, $221k training |
| 44:44   | Assess | CC tooling: roadmap alignment, time to value, uncertainty |
| 45:48   | Assess | CC tooling: regulatory / legal risk (above half) |
| 49:19   | Assess | CC tooling: maintainability and CC as critical infrastructure |
| 51:24   | Guide  | Move to CC incentives & productivity optimization |
| 54:18   | Guide  | Preliminary CC votes; AI limits (intention, gut feeling, math) |
| 1:00:00 | Guide  | Rodrigo: financial AND reputation incentives |
| 1:01:05 | Assess | CC incentives: impact (governance halt risk if CCs step down) |
| 1:04:52 | Assess | CC incentives: urgency 10 (election in 3 months, halt 1 September) |
| 1:06:55 | Assess | CC incentives: feasibility 10, cost low vs damage |
| 1:08:58 | Assess | CC incentives: roadmap, time to value, technical risk |
| 1:11:28 | Assess | CC incentives: regulatory (conflicts of interest) and maintainability |
| 1:13:41 | Guide  | Wrap up CC assessments: now have a Must-tier CC recommendation |
| 1:14:32 | Guide  | Retrospective: Oliver on simplicity vs oversimplification |
| 1:18:09 | Guide  | Sebastian: Miro for ideation, this tool for decision-making data |
| 1:19:32 | Guide  | Rodrigo: lack of participation, fragmented silos in Cardano governance |
| 1:20:23 | Guide  | Health page metrics: 63 signups, 40 ideas, 120 votes, 69 comments |
| 1:22:14 | Guide  | Ken: monitor governance metrics continuously, use for emergency war rooms |
| 1:25:22 | Guide  | Data freezes Monday; site stays available for the year |
| 1:27:02 | Guide  | Closing: congratulations on the workshop series |

## Transcript

0:03
Hello William, welcome here early.
0:12
Hello everyone. Thank you so much. My name is William. I'm connecting from Zambia. I'm a colleague to thank you.
0:23
Okay.
0:27
Are you candidating for intersect position because I somehow recognize your picture but I don't know where.
0:36
Yes, I'm standing in MCC. I am coming from Zambia.
0:43
Okay. And so you have been in this workshop. Yeah, I think I remember.
0:53
Well, let's see. Um, let's give it a few minutes and see how many people will join up.
1:06
See, yeah, you mentioned proposals take longer than usual.
1:15
I kind of feel the same way. It's so hard to decide like the
1:22
proper level of information to be shared like there is so much room and things to
1:30
like say but then you recognize it gets way too overwhelming to read. So
1:37
exactly the same problem we identified here too proposals are too complex. So
1:44
we are now trying to actually do like internally.
1:52
Yeah. Yeah. Like to get some kind of clarity on the costs. But for the
2:00
proposal itself, I think it's going to be more like high level budget lines just so it's easier to later execute on
2:09
proposals and not to overwhelmed with people with all the details where the hours go when building a treasury.
2:17
And hello input endorsers.
2:22
You probably have a name too that you have shared that long forgotten.
2:30
Hello. Glad to be here.
2:37
We are basically four minutes in. It's going to be uh well not as big audience as I was
2:45
assuming due to like giving a lot of head start for people. But we have all the right people in here. Uh Ken is
2:53
dropping in and out. But in terms of uh like timing and the people who are here, I think we're going to get
3:02
somewhere with a bit of um we we recognized that basically we have not
3:08
that much uh constitutional commit recommendations and if we do none of
3:14
them are must. So one of thing is let's try to tackle this and see if we here are able to come up with a
3:23
recommendation for a constitutional committee that could be like let's implement that this year next year um
3:32
and then I guess we can kind of conclude the recommendation session in a sense that we have addressed all different
3:40
challenges and all different areas. Um yeah, we'll see how our energy is at the end of like looking into the
3:49
constitutional commit stuff and then we can find more data points. we want to touch Dutch and make sure they are listed and out there.
4:01
And finally finish with bit of a retrospective to which is also part of like I guess uh
4:10
improving and harnessing our governance experience for the future cycles. If we
4:17
if Cardano intends to finance and continue to provide funding to reshares and development side of stuff.
4:30
So I'm going to drop in the workshop uh application and also I'm
4:36
going to share screen uh screen
4:44
and um I'm going to share an overview page is the last page in this list who
4:53
works this let me see if I can drag them away.
4:58
Okay, it exploded and this basically gives entire list of all of these circles are like recommendations we have
5:05
made and all of these boxes are challenges we have um identified through this observation page
5:13
and I mentioned we have a constitutional commit area where we have about like five recommendations
5:21
and but none of them are must and one of them is yeah two of them actually haven't been
5:28
assessed uh tier none. Yeah. So they could be must. So I was thinking um
5:36
let's like give a quick brief on what we have and then go around the room to
5:43
recognize if there are any anything missing we should be adding.
5:50
And yeah let's me show how to kind of do the filtering. So in the prioritization page
5:58
I'm going to filter out only constitutional committee and now the same you see on the overview map you
6:05
will recognize the same uh four recommendations here. Uh currently the
6:13
most prioritized here is the CC incentives and pro u productivity optimization.
6:20
Um but looks like there are have been two assessors who have already said that this is more like a should thing rather
6:28
than a must thing and mandatory 7day early uh signal
6:34
standard um is not yet rated um in in the Moscow priority.
6:42
Next go by the microservices uh is um rated as cooled. So even more
6:50
downgraded compared to should and then championing cause is something that somebody has rated even that we
6:59
shouldn't be doing at all. We won't be done.
7:03
Um so yeah in the chat will inject put into the overview page. Um how do you feel
7:12
about like taking few minutes off uh reading these recommendations using the
7:18
up vote down vote to signal our current cohort of people who are here Rodrigo
7:25
William input and also Ken to see which seems to be the most um important
7:32
recommendation to be discussed and if you feel like none of it addresses There's a recommendation that
7:41
has been floated around in community or you are aware of or just by reading tools you came up with a even better recommendation.
7:51
This is a opportunity to kind of speak up.
7:55
Let's add it here and then yeah bring that up into this like cons consolidation of other recommendation
8:03
and figure out where do we spend today a bit of our time to to fine-tune the
8:11
at least one of the CC recommendations.
8:18
So, u I thought about uh adding um a recommendation.
8:27
I don't know um if we couldn't debate that.
8:32
Are you able to write that recommendation into here or you preer that we discuss?
8:37
I'm cooking on it. I'm cooking on it now. Hold on two seconds. I will just keep writing it and then we can debate it.
8:44
Okay. Yeah, we can extend a few more minutes also for Sebastian to get his uh bearings on the
8:54
Yeah. No, please go ahead. I'm going to read I'm going to I'm going to make the job under.
9:06
Okay, I think I got the recommendation in here now.
9:14
when I refresh I do not see um when you created the recommendation maybe by
9:21
default it show up gives an option in general governance uh what I can do is I can say what's the
9:29
newest and take that off
9:36
then I see operating creating and maintaining CC credentials yes That's the one.
9:44
Okay, I'm going to take a quick edit here and move it to the constitutional committee metrics. Um, you didn't attach
9:51
any um charts.
9:54
Uh, oh yeah, it goes I think for the response time and um
10:02
yeah, the response time for CC members to uh vote. Um I don't know is is there
10:10
anyone here that is also a CC member because I am a CC member at ting
10:16
and um okay so uh from a high level uh you can
10:24
be a corona constitution member both as a business you can be as a consortium
10:30
and as an individual um operating as an individual
10:38
requires some skills uh in quadi uh to generate um
10:46
uh hashkey that we use when we um put forward the update committee um for
10:56
uh consortiums. Uh this is um managed by a tool that Mike Horn and
11:05
Adam Dean made. It is um it's actually based on NFT
11:14
um where you have uh uh an orchestrator that literally just
11:21
uh receives um some witness signing files. you have what we call a member
11:29
um where which make it possible to generate new keys and rotate uh
11:35
consortium keys and when we are let's say signing credentials making a
11:44
signature on a vote uh as part of a consortium uh this requires to
11:52
run a script it requires us to keep the credential s for the signing keys uh in
12:00
a very secure environment. We don't want to have you know um signatures uh
12:08
so it's like you have to keep it in what we call a air gap environment and then the orchestrator have to take
12:16
all the signatures from the consortium and uh create a transaction and then
12:24
broadcast this. So it's a very complicated it's not as easy as uh buying a meme
12:31
memecoin on tap tools uh uh but uh it's a very very deep learning curve to
12:38
become a CC member and um
12:46
and uh one thing is to actually evaluate the rational and stuff like that but you
12:53
actually need some skills uh to actually perform the vault and like we are doing
13:01
in ting void we have like weekly meetings and then we debate the rational we write
13:09
the rale and then we vote on it internally as like yes I'm voting yes no abstain or like this
13:17
and then it starts the process where each individual member sign the keys
13:24
And then I have to pass on the witness uh file as it's called uh to the orchestrator and he will actually
13:33
uh sign the transaction compile the transaction and put it on the ledger. Um,
13:40
so it's quite complicated and I was wondering if uh people here agree with
13:47
me uh that this might affect the time it takes for um CC member to respond. And
13:56
then I'm thinking about the the chart uh that you can see here that says that um
14:04
uh we have like uh on an average like um what was again 20 24.5 days of
14:14
this dre stickiness is the one link. Oh no.
14:24
Yeah.
14:26
Well, let's start with then the CC tooling and then I guess we can after that we look at the CC incentives.
14:35
Yeah. Yeah. From my experience, I have no I don't really watch what Cardana constitutional committees are doing.
14:44
Um, I don't even know where I will watch their activities. Um,
14:52
maybe they had a channel in the Intersect Discord.
14:59
Yeah. So, it's Yeah, for me it feels like they have um
15:06
more tooling needed to like distribute information. But of course you internally know that okay if there's
15:13
like a signing stuff and that's like a thing of course and and to look at in the whole picture
15:23
you know um we as CC members we often get pushed on by DREPs like you have to
15:30
vote now is this is this proposal constitutional or not? Should we as DREP um vote on this? Is constitutional? do you
15:39
need to waste time on it? Um but um that's also another challenge. Uh you know it's uncompensated or it's
15:48
complicated tooling. Um and sometimes it's very complex uh proposals
15:55
and like you see right now we have like a bunch of proposals coming out. is you
16:01
know treasury withdrawal times and um it's quite consuming um
16:09
I think it's proposals feel like easy I mean budget proposals probably are like easier because
16:16
there you just take the general like the headlines what the what
16:24
the proposal is suggesting I don't know you AI compare it with the constitution and that's basically it I think we're at
16:30
harder part is the info actions the like parame like other stuff I feel like are more
16:38
complicated because we haven't made so much like strict rules how do we manage budget or like what do we allow pay for
16:45
or not so I feel like most of the stuff is constitutional what people put in
16:54
um I don't know does have you ever felt like the community is complaining that
17:01
your rationale is crap or your vote is in incorrect and have does this happened in general.
17:11
Yes, of course. If we vote something unconstitutional um I'm going to just for an example and this is actually in the period that we
17:20
have measured in beyond um everybody do anyone remember snack community uh they
17:27
wanted to ask for a treasure and um they managed to uh create two uh
17:36
well technically one was like unconstitutional but they made a typo they
17:43
um didn't um put forward their request for a loan in loveless they did it in ADA. So it become five ADA instead of uh
17:52
5 million. Um and this first one was also like uh unconstitutional because they didn't meet the requirement
18:00
and you know um I I did just like for fun you know like put on X like
18:09
congratulation on uh uh like community you've just managed to put forward two
18:17
uh two very first actually two very first unconstitutional proposals in the govern area. And I must say that was um
18:27
uh in regards to impressions that was uh I think the most unpopular post I have
18:34
on X and um yeah so um
18:40
it was uh at the moment a very heated debate. Um someone even said that we should you
18:49
know look through the fingers. um this was too difficult and stuff like that.
18:54
So um and we also see other CC members they um
19:01
pack a lot of heat. Um uh that brings me to another challenge.
19:08
It is to be a corona constitutional when it comes to tooling. I I will say that the corona constitution it itself is a tool that we use.
19:18
Um when we put it forward uh
19:26
in Argentina we all agreed that this constitution was not complete. It had
19:33
what we call a lot of constitutional debt. Um but the constitution that they put forward
19:42
were at least like bare minimum and there were non not any
19:50
let's say loopholes that you could let's say explo exploit constitutionality um
19:58
there haven't been any success on adding and updated the current constitution it was
20:04
Utah did one It took him tremendously amount of hours and several
20:13
attempts to update let's say minor changes uh to the consortium. The
20:21
biggest one that he changed was like the treasury withdrawal. he removed the removed the budget infection.
20:28
Um but still for a CC member um we basically
20:36
um we are very much up to ourself to
20:43
uh interpretate the constitution um when we are making a decision.
20:53
Um and and I must say on top of that since
21:02
it's let's say not compensated uh it it leaves you let's say okay you you do an effort to it but I got to be
21:10
honest um I don't have time to spend like a day or two on each proposal
21:20
going to be honest. Yeah, for me I feel like maybe this series like where the AI really helps because you all kind of
21:27
mentioned that the constitution is more like a checking if they are filling all the requirements and like the basic stuff is the proposal impact or not. I
21:36
think that's the secondary that the collective t the conscience has to vote for and uh kind of agree to
21:45
um where yeah just the constitution is more like a wipe check if we are doing good governance
21:56
but I I understand it's it's more like yeah like that I don't know how
22:03
every member are doing it but it's more Like people if there a single one or a multiple especially if they're a team
22:11
they are spending like specific meetings to to read the
22:17
proposal on entirety then they go around talk about it uh probably the scope is much larger.
22:28
Is is there an unclear what's the role of constitutional committee? does f kind of come up every now and then or was it
22:36
just early time to kind of get in mood and once like few months passed or few weeks passed then everybody kind of got
22:44
used to coming up with so so so challenge I can give you like a recent one so now there's a bunch of
22:52
pressure with rules um so as a CC member I am I'm not going to let's say get caught up
23:02
in like how much uh we pay the developers like how many
23:09
uh the scope of proposal like how much ADA what kind of work uh is going to be done. So as a CC member I I I that is up
23:18
to the DREPs to uh decide but we have for example tenant 8 the cred no
23:25
blockchain shall not unreasonably spend resources.
23:30
So what is that? You know, um if you if you put that into an AI tool,
23:40
um yeah, you will have to define that and I guess maybe that's the NCL.
23:50
Yeah. Is it like just so I know it was like just just to give you an example.
23:57
So teamwide we voted actually unconstitutional uh to the Cardano Foundation's proposal
24:06
and the reason for doing that was actually using tenant 8.
24:12
um they had a proposal last year where they're going to let's say um use treasury funding uh to host summit and
24:22
that's going to become and why they got the funding is because it's going to be an income stream to the treasury in the fur season. the football room like at
24:30
2028 it's gonna get x amount ADA into treasury again it's gonna be like a net
24:36
profit and then now they did like um let's say 180 and this like we're
24:44
going to do like two events uh it doesn't look anything similar to what they have like said for summit before
24:52
and it was like basically twice as expensive Um
24:58
so there we decided of course very unpopular to use tenant uh 8 because
25:07
um even though uh the some der voted for it and someone
25:14
voted against it um the scope of the proposal uh we as um
25:23
uh CC member uh eval that this was like wasting available.
25:31
So I guess that's a good like starting to to understand the scope of like here you
25:40
kind of mentioned in title CC credentials and were like very specific uh but in general there are like wide
25:48
range of tooling that we the CC member needs and I feel like maybe through this discussion I
25:56
feel like maybe we found the must assess like the the the recommendation that is must not in a sense that that specific
26:04
maybe the credential tooling is needed well that's also like nice to have because if yeah I think the credential
26:12
tooling is nice to have but something which Sebastian mentioned and I put a um comment here having scripts running
26:20
through proposals uh and the scripts are maintained by CC members because what you're doing here you are instilling
26:28
your global into like repeatable processes.
26:34
So when like every proposal yeah there is an endless way and a lot of dimensions you can look at the proposal
26:41
but if you take it like case by space you are going to end up in the scenario where you're going to have like a rich
26:48
uh knowledge base of information that gives you like false true statement what happened before and the more you spend
26:55
time on it the richer the knowledge base gets the AI is able to handle the organization and like the context
27:03
building and storing and when the CC kind of leaves their position the the
27:10
institutional knowledge or that the the CC knowledge is instilled in a product instead of the members who now move to other things.
27:20
Uh and this is where I think it's a yeah it could like a a must must priority item.
27:30
Uh I'm going to move it to must here and moving to the assessment page of this link.
27:37
Um I see hello Pedro joining here. Uh we are in the Pondi application and looking
27:46
at constitutional commit recommendations.
27:51
We created a new one and that new one we're just addressing right now. We're going to like tackle the constitutional committee from two angles. One is what
28:00
tooling they need. And here you will find that on the comments we went off bunch of like details
28:08
and then we're going to look at CC incentives next.
28:14
And now I'm going to go around the room and we're going to tackle all of these assessments questions like how many people or processes are affected. And
28:23
I'm going to start with uh Sebastian because you have your you have camera on and
28:32
reactive. So on your uh kind of perspective and regarding like CC tooling in general, not just the
28:41
CC credentials but all what we discussed in this call right now. How many people or processes are affected if you are
28:50
doing this tooling? Do you think just the CC members or also the other people
28:57
who are affected by the CC decisions making now beat these tools and how far you think it will go
29:07
to the is the impact of uh
29:14
nonfriendly tooling to make the job is is that is a blocker definitely.
29:22
Uh so I I'm to be honest I'm not uh deep into the the details of how the
29:28
constitution the SEC works but based on my work in the the open source committee.
29:37
um it's pretty difficult if you don't have the the the the at least the the right tooling to to to take decisions,
29:46
right? That accelerates many negative things. You take too much time to make decisions.
29:54
It's in my in my in my opinion is is is a hand a 10
30:00
because uh that uh difficults the job doing the job for example my my my
30:09
comment around the shell scripts using shell scripts to support uh the from the
30:16
beginning some kind of filter that uh is we we use that in In one of the of the
30:24
programs we we have to we run in the we run in the in the committee toing sustainability, right? People send applications and and one of the first
30:33
steps if this the projects have to must to to to deal with or have to use the the the
30:41
shell script, right? It's different from AI because you can see the the internals the editors of the script, right? And
30:50
from that you you can see okay this is th and those are considerations that we
30:56
as committee the human committee we we put in the script right that facilitates the the approval of of of the reject the
31:05
rejection of the of the of a proposal from the beginning right so those are a little bit of the the
31:14
what we leave in the open source committee in this case how we try to to deal with the the decision making the
31:22
daily decision making. So to to to conclude in my opinion is a 10 it's needed
31:30
the tooling is I have a question for you Sebastian since you are in the open source uh I I I
31:39
think so you are not let's say let's say aware of let's say the process of setting up CC credential and you know um
31:47
the voting process and stuff like that um but like on a high level uh on a general eneral basis. So when you have
31:55
to balance security versus um what's called uh usability or like
32:05
like something easy to use uh user friendly. There we go.
32:10
Yeah. Um what what challenges do you identify like open source developer?
32:18
Yeah, it's not a secret that we have to to to let go some
32:26
some security uh to provide better conditions to to to in this case
32:35
to make decisions, right? I know I know it's it's widely discussed that uh we
32:44
need security. We need to to secure some the the workflow in some way. But
32:51
um yeah, we need to to let let go some let it go some some some security on behalf
32:58
of the the more more a more sleek and and low friction process. I know why. I I know how. I'm not I'm not sure how.
33:09
But what I know is when the the technical people starts they they start thinking on on security they are pretty
33:18
uh robust and and they don't don't allow some kind of a space to to to drive a
33:25
better process and that's that's that's not good. That's not that's not okay because
33:33
this is a human process. So in in the humans we need some kind of a space to to to to move to movement. So
33:41
yeah is it's very difficult to balance security. So like if you have
33:50
it will be like devastating for corona if you had uh let's say three
33:57
three CC keys. Uh it could be like two individuals and let's say one consort that's got compromised just just by a
34:07
state actor or yeah
34:12
targeted attack uh basically yeah yeah I think we are
34:21
make huge damage to a billion dollar ecosystem. Yeah. And I think we are in a good in a good path in a good in in the
34:30
right path to to in in this governance process.
34:34
We if we puritize processes instead of instead of the designing the design of
34:41
the process the scaffolding instead of uh how we can facilitate the decision making and the participation and how to
34:48
accelerate the things and take notes uh to learn in the in the in the meantime.
34:56
this is going to be slow in in many in many corners of the governance process.
35:05
Yeah, that's all I can say. Yeah, thanks.
35:12
um a bit was discussed also um from your own experience like these tools already
35:19
exist and practices exist but it's a but looking at the much larger level maybe
35:26
Ken can uh address like how feasible it is to create these processes and
35:33
improvements to CC credential management and like handling is this something new
35:40
and requires like leisure level knowledge or this is more just
35:47
like offchain tooling that is well integrated with the main chain and then it's all there. It's just not put
35:54
together. Yeah, that's a I might put it this forward like a mouthful, but like I
36:04
just having CC members putting themsel forward at the moment now
36:11
I think it's it's a very very deep uh learning curve and that means they are
36:19
like a very narrow field of knowledge who can tap around Cordana CLI, who
36:28
knows, you know, Cordana SER, who knows what the uh S key is and
36:39
so just getting like just to become a CC member, it's a very very deep learning
36:47
curve. There is no education. Uh you have to know what a seabboard is.
36:53
few people on the planet know what it is. Um as an orchestrator uh you have to
37:00
be very familiarized with uh how a UTXO model works and yeah
37:08
and also how an NFT actually work. So yeah um there have been uh some attempts uh to
37:18
do like CC credential uh education. I know Mike Horn had done something. Uh
37:25
but at the moment there is no uh no good ed and complete uh
37:35
educational guidance. Um uh and you definitely have to have a
37:42
network around you to ask about stuff if you just out of the blue decided to go for a CC membership.
37:53
Okay, I moved the feasibility down to four. Should I take it down even further or is it now somewhere there like it?
38:05
Yeah, I think we are in the right area.
38:10
Regarding urgency, is there a deadline or time pressure to have tools for CC members? Do you need it now or you kind
38:17
of like ah yeah sure I can just kind of drag on?
38:22
I think you can wait right we can you can wait.
38:26
Uh well the thing is so so we're going to have a CC election now um if we don't have four members uh putting themselves
38:35
forward uh who successfully are able to create TC credentials. Uh we're going to
38:43
be in um governance loophole again because there are CC keys that will expire.
38:51
Uh basically bring governance to the halt and there's a lot of stuff in the pipeline. We have
38:59
uh min pool in the there are bunch of stuff bunch of importing stuff in the pipeline. We
39:06
don't have time for a pause in governance. Um so I think that's uh and on top of that the CC
39:16
is the check and balance on governance on Cardano. So I think this is highly critical both compensation and tooling.
39:26
I don't know if someone else agree thumb up in the chat.
39:32
Yeah, I put that on 10. um for the cost estimate
39:40
I I it feels like very expensive if nobody's doing it or because it's requires technical skills and knowhow
39:47
and actual experience and in order to get that experience you also need to get to be elected and that's so I will put
39:55
10 here but I don't anybody want to argue against having like the cost of GC
40:02
dueling Although the scripts feel like cheap thing to do and it's like
40:11
and and I have to say there are mechanisms to to to to get to fund to funding this because for
40:18
example from the open source committee I know match is uh match is doing something previous preview conversation
40:28
with CF something like that I know but the the the the match and the some
40:35
organizations and want to to to say something that I'm not sure but match is able to to to take the problem and
40:43
create some easy and simple solution right and if the solution is clear they can go to to get some funding from the
40:52
open source the the open source uh committee for example they can they can present a proposal
40:59
describing the the solution ution and the impact and the necessity, right? And if this proposal goes not only from the
41:08
match side but also is supported by the the constitutional committee for example or the other organizations that are are
41:17
involved in the problem and know well the have a good understanding of the of the problem.
41:27
What I want to say what I mean is the ex the the mechanisms to get the solution
41:33
exist currently. So the the the only the thing we need is to start connecting points right from the committee from the
41:41
the fund the the organ the organisms that have the the funding
41:48
different points but I think we can structure something and and and create a a concrete proposal a concrete solution to this situation.
42:01
reduce the cost estimation to eight from 10 based on yeah that there are avenues and
42:08
triage ways of like starting small so the costs are not that high and and even more like
42:18
it's I think it's is a six because if speaking of of match
42:26
right they take a composable composable uh uh components of the existing library
42:34
right and they can build something some something on top of that right I think we have the solutions internally in the in the ecosystem
42:43
uh but we need awareness of the problem
42:50
I'm sorry in other words we need to take this problem to out to the to the out of
42:56
this face and start to talk with the the savvy developers of the that can build something. Yeah.
43:06
Uh regarding costs here. So I I just had a peek at um um 2025 budget of uh in
43:16
that uh did not uh pass or was any popular at all amongst the rep. Uh they
43:25
have uh CC compensation uh that was uh for all seven members $250,000.
43:34
It was a $80 uh legal uh fund that was uh put a fight aside.
43:43
Uh, no, sorry, 350,000 and then uh it was up to 265,000
43:53
in CC uh reimbursement of um
43:59
of hardware and and it was also educational and training that was like 221,000.
44:08
So like it is like a very very solid cost
44:15
and I yeah to operate CC but this was more like incentives rather than just tooling. So it's like
44:25
uh this is like the whole let's say CC um from compensation, legal support, uh
44:31
education and training and hardware and they even have like a handover ceremony. Yeah.
44:38
To to chat. So I think that will go with the other recommendation we have here.
44:44
Um but with the technical stuff um just to finish it I think road map alignment
44:51
is easy vibe because it's like clearly to Cardano governance time to value
45:00
I would say maybe not in weeks but clear probably in months already you can because yeah you can take it like one step at a time and already see results.
45:11
So I think there is a value in depending on the tool that we taken of
45:18
how much uncertainty uh I think well understood and based on
45:26
what Sebastian kind of mentioned like pulling on composibility and and you also your experience claiming that the
45:33
fact that it's not done or or there is some kind of uncertainty because if it's well understood it will be probably
45:40
already done by somebody, right? So there could be two here
45:48
regular. Okay, just this may be complicated. Regular regulatory or compliance considerations,
45:58
any legal risks like hold any legal obligations or risks
46:05
or Yeah. So, I'm not going to mention name and point fingers, but uh there have
46:13
been CC members that have been in let's say didn't go as far as um a legal um
46:23
dispute, but uh there were lawyers involved.
46:29
Um uh if you zoom out even more uh this has
46:35
have been repeatedly debated. Uh so you know uh Kano is you know uh a public
46:44
blockchain. uh there might be critical infrastructure or critical interests,
46:51
financial interests um involved and some of the CC uh decision uh might uh how
47:01
can I say u affect those financial conflicts and you know Cardano is actually
47:10
classified as a digital reserve in the US Congress. Yes. Um
47:19
and uh yeah there might be like like on very very
47:29
unpopular let's say you know there is um collusion with let's say Binance and Coinbase they
47:38
get together and they use uh their voting power as a SPO to let's say you
47:45
run a hard fork or yeah do something harmful and we deem it unconstitutional
47:51
that might be like put members in a very severe legal disputes that is very
47:59
costly because you're going up with the big boys they will just come there with like
48:05
25 lawyers and like f you okay so there is a challenges but in
48:14
terms of like uh today's discussion like how
48:20
yeah how well is the security or credentiing process maybe very legal risks but um having AI
48:30
scripts run through proposals and provide assessments it doesn't mean that they make the decision
48:38
so but yeah I don't know do I leave it in middle or just skip here for the tooling
48:45
Yeah, in regards to legal uh you know operating creating and maintaining CC credential and votes if
48:54
you look at that process like in whole like from creating a credential to you actually vote on proposal I will put uh
49:02
legal risk uh above half above half because uh okay so you can get in trouble if you
49:11
lose your keys or give it to your friend There have already been CC members who have been in trouble.
49:19
Uh ongoing effort needed to maintain um maintainability.
49:25
Yeah, I think this is something again which is is going to be like has to be recurringly always kept up to date and that's the cost these tools will bear.
49:38
Um does anybody disagree with this kind of notion of having maintability on file takes constant updates?
49:50
Yeah, I don't have any contrament against maintenance. Um uh the
49:58
election is like we have to have staggered rotation on CC members. Uh we need them present. Um
50:07
it is part of critical infrastructure you know like at the moment since we have volarian governance by my standard
50:15
it is critical as API standards for exchanges and trading you know because
50:22
it all goes to a halt um if it's not maintained and um it will be very unfortunate to figure that out in the
50:31
hard way to put it like that we already had like a governance crisis that uh
50:38
uh almost made us lose a lot uh a lot of lot of very solid deals
50:47
because you know um we have entities uh and legal entities you know um doing
50:56
agreement with in like three comma doubledigit million
51:05
sizes and um without a well functional uh CC
51:12
those deals goes down the drains. You like prevent treasury withdrawals, you will prevent payment on time and stuff like that.
51:24
Okay, we addressed the tooling side of CC. Um and soon hello I don't know when
51:32
you slide in today is a constitutional committee day and I'm going to drop also
51:39
the link and we're going to go through one more topic for CCS and this is incentives and
51:48
productivity optimization as a and the quick read here is the
51:55
clearest issue is lack of incentives and operational support. If constitutional committee members are taking too long to
52:02
respond, one plausible reason is that it's important function being performed without sufficient dedicated support.
52:10
Faster constitutional review could benefit full system by helping proposers revise earlier helping DEPs. Um a useful
52:18
direction would be study how to compensate constitution commit work more effectively.
52:24
Instead of assuming payment model from the start since some seats are represented in by individuals and other
52:31
by groups. It does not makes much sense to simply scale the compensations by the members. The ecosystem should instead
52:39
explore fixed support model per seat while also studying whether internal redundancies uh are really adding to the proportional
52:48
value. AI tools and better can reduce the costs. The goal should not be to replace the human judgment but to
52:57
understand the work workload compare methodologies compensation models. In short, more reasonable recommendation is
53:06
to support applied researchers or pilot focused constitutional committee operations, incentives and productivity.
53:12
So if you have been in the uh workshop sessions in the last two
53:19
weeks um we often brought up some kind of incentive models because we had talked about voter
53:27
incentives, dates incentives and now this is also very similar. I think this is like methodically uh like similar
53:37
stuff to each of these roles because they're the main roles in Gardana governance.
53:43
Um let's try to also assist him get some kind of general thoughts on here. I
53:52
don't know Rodrigo if you're able to also speak up and give a bit of like to from your own
54:00
perspective like uh do you have some kind of incentive models in mind or
54:09
yeah some proposals or how this this kind of recommendations could be there towards.
54:18
I also very much like so you cannot let's say desire
54:25
like they cannot demand sorry you cannot demand CC you know to let's say do a vote within the first seven days you see
54:32
there in the comment field here but it is a very good indicator for the
54:39
community because there's many many many times DREPs are sitting on the branch to put it like
54:47
that uh before they are voting. Uh and they don't want to waste their time
54:54
um uh assessing let's say something that's unconstitutional.
55:02
Uh and I think it would be a good practice for CC members to like make a preliminary vote.
55:13
I I've se I've seen CIP suggestion that where you use uh optimistic rollups basically doing this arbitragey that
55:22
automatically CC members vote yes uh that part I do not like at all well
55:30
then let's add in a way that go through the assessment section I myself felt like this is not as much
55:39
as a must and more like a shield and the reason I put it as a shield was because I felt
55:47
like u it's also like an expectation from the CC and it's more like a
55:56
guidance but it would be great if you are being more public and you have processes and uh yeah you you're kind of
56:05
but this does give like I to me it feels like this this various development or
56:13
this product or the space is created for CC's to join in share learnings share
56:20
their own experiences get some kind of guidance uh to tackle some kind of information but we can't make it like a
56:29
requirement for them and so that's why I feel like yeah I put sure
56:36
if you disagree then join click must or any other choices Well, I as I uh I'm
56:44
not going to speak speak for other CC members, but uh what I have seen uh out there in the wild is that there you can
56:52
use AI like claw Gemini uh feed it with the corona constitution
56:59
and you can like uh feed it with the proposal and you can like on a high level just is this constitutional or not.
57:10
Um um uh what an AI will not be able to
57:17
detect is perhaps like the intention um behind uh rational or proposal.
57:27
um it will not uh provide let's say uh as
57:33
as far as I know um like if we implement layos just for example you know what
57:40
kind of limitation would this put on card in the foreseeable future and
57:48
yeah so um intention
57:54
uh limitation S um what else?
58:03
The gut feeling. AI don't have a gut feeling if it if uh an intention is good
58:10
or not. But it sure helps. It sure helps to just check you know um uh the basic requirements.
58:19
Um,
58:22
we're going to see for like uh I think the min poolool scene now is coming up.
58:27
That's going to be very interesting because you need like very good uh uh some very good math
58:36
skills there to just be able to comprehend the math behind what's coming up. uh you also have
58:44
uh min uh committee size like coming up there also
58:52
uh there's a lot of let's say intentions and um and security risk uh that you need to
59:01
evaluate that is not in scope of AI I think but it is a supporting tool for
59:12
Now coming back to the recommendation of providing incentives and like a supporting team or
59:22
a space to improve like the productivity of the CC members.
59:30
So I'm I'm going to imagine there is a team of who are just like technical or like business experts and they they are
59:37
not in the seat positions but they are around the CC member themselves and kind of observe of how can they help them optimize their work.
59:49
Did I capture it correctly what this recommendation is suggesting?
59:56
Uh, Rodrigo.
1:00:00
Well, I I think we when we speak about incentives, we should consider not only
1:00:07
financial incentives but uh reputation incentives as well and
1:00:14
currently cardinal governance is not compensate compensating in any manner.
1:00:20
So there are two types of incentives at least.
1:00:28
Okay. So there is a let's say a team in place who helps to
1:00:37
incentivize the CC members both financially and like improve the optimization but
1:00:44
also in a way that it brings out the the good aspects of the CC member themselves
1:00:54
so that the kind of reputation increases I guess. Yeah, just making a more transparent, more accessible seat itself in general.
1:01:05
Now, if that program or a team is in place, how much impact it will have to the ecosystem.
1:01:21
Last year, the Atlantic Council submitted a governance action to request funding for the
1:01:30
uh at least five members of the CC and there was a lot of lot of push back
1:01:37
against this. But in my view, some dats that voted no to pay uh CC's would
1:01:46
would like to see a more detailed financial plan, financial considerations
1:01:52
about the compensation side. And if we integrate AI to diminish the costs, the
1:02:02
human cost related to the effort and time to do these evaluations as a member of CC. In my view, the reps would be
1:02:11
more would be more lenient to to vote yes.
1:02:23
Mhm. Yeah, this takes back us to the previous recommendation where we were focusing on tooling
1:02:30
and this is why I felt like it's more a must compared to here but in this
1:02:38
what you say the impact is is it impact is then one because it's financing the
1:02:46
the small team itself or you feel like this is like a butterfly effect of impact to entire ecosystem.
1:02:56
Well, we we need to understand if uh CC's are going to continue doing their work without compensation because
1:03:04
Atlantic Council already give it give up on their their role a few months before.
1:03:10
So, I'm not sure if other CC's are going to continue doing this amount of effort
1:03:18
without any kind of compensation. So in my view this would be a a high high impact area to tackle.
1:03:31
Mhm.
1:03:33
But of course we we should have more input from other members of of CC.
1:03:41
But right now, okay, you mentioned that the area or that challenge is a high impact area, but in terms of this
1:03:49
specific recommendation to yeah to help incentivize and recognize
1:03:56
and improve the productivity of CC members,
1:04:02
how impactful will that specific like activity be for the Cardano ecosystem?
1:04:10
Well, I think the impact is tied to the the situ situation we had last year when
1:04:18
council decided to step down their position and the governance went into a hot for some weeks.
1:04:28
If we see the same situation occurring this year, we may face another halt in the governance.
1:04:35
So that's where where I'm thinking to set my impact as high because if the
1:04:41
other members of CC decide to give up their role, we may face some problems in the governance system.
1:04:52
I might just add on to that. So we're going to get the correct answer to this now within the next three months because there's a CC election going on.
1:05:02
If there is no candidates uh putting themselves forward for this governance will halt uh 1st of September and
1:05:11
unfortunately at the moment it is not time to put together a CC compensation plan that going to get upward through by DIPS.
1:05:25
So I think the urgency is quite high
1:05:31
and the impact of this uh is um is very high because
1:05:40
as you know without uh a CT members there is no treasury withdrawals there is no parametric change there's no hard
1:05:47
fork initiated there's like literally nothing going on it's only budget only in factions
1:05:54
and update committees. It's going to be valid.
1:06:00
Well, I climbed the impact from one to eight now. Is that enough?
1:06:08
Okay, I see noting and thumbs up. Urgency is 10 because yeah, if we are
1:06:16
not able Yeah, because it's a good interesting point. We don't know how we empowered Cardano members enough to become this position and when we find
1:06:25
out then it's too late. So it's in a sense it's Yeah, exactly. Because there is too much uncertainty right now. We don't know how
1:06:34
the process of the next election will unfold. So it's really hard to set the the score for these two questions.
1:06:44
But if we get to a scenario in which we don't have enough CC members to vote, we would be screwed.
1:06:55
For the feasibility, I think here is a 10 like all of these incentive empowering discussions. We have had
1:07:04
years of experience in community pooling and I think just we need to get the right people in the right group and I think this is kind of solved problem.
1:07:16
What resources would be needed?
1:07:19
This may be much harder because now it depends how much we're willing to put resources in here. Um because it's
1:07:28
targeting a specific group and specific individuals, I would assume the cost is small, maybe even one, two, but it does
1:07:38
need to come from somewhere. Does anybody feel like the costs are much higher? And
1:07:47
it's actually I would say like it's like the cost of of incentivizing CC members
1:07:55
and you know the toolings that is incredibly low if to compare to the
1:08:03
damage. So just for example, if Intersect didn't have put forward this snap election, they have no mandate to
1:08:10
do that by the way, but they they did it because you had the pentad stable coin
1:08:17
that would not be passed and there was like um like doubledigit
1:08:27
million uh that already had been committed and it was very close to being flushed
1:08:35
down the drain because they were lacking a CC member.
1:08:42
Yeah. Interesting. And the reason CC member left I think was because there was no incentives like and not incentive
1:08:50
for themselves but not for the community because there is like a I remember they get discussions a lot of debate on there
1:08:58
regarding road map alignment. I think this is easy. Five time to value. Um
1:09:06
yeah, I I wouldn't say again with weeks but probably three five in like months or so we've already get some kind of clarity.
1:09:18
Um yeah, I agree.
1:09:22
um at least people will get to kind of know there is a honeybot and there's a reason to exist and put their effort into it.
1:09:33
How much uncertainty is this pro?
1:09:36
Somebody mentioned uncertainty is like very uncertain. Um
1:09:43
and even with if we provide incentives and empower people it's not clear if um
1:09:51
if it have the required positive effect probably it is but here it's more like technical
1:10:00
risk and I think technically we have like no issues
1:10:07
so yeah yeah I agree that we wouldn't face technical risk because it's more tied to
1:10:15
compensation and schemes and I don't see how technical would be a barrier in this case.
1:10:26
add a little bit to that table and that is like uh when it comes to making it easier to uh let's say vault as a CC
1:10:34
member create credentials uh you need to lean on battle tested encrypt encryption technology.
1:10:45
Um yeah and um if you are doing that wrong
1:10:53
um that is like very bad for them. So it's it's not without technical risk but of course the funding
1:11:02
and you know putting forward the proposal that's very low but uh when it comes to productivity and incentivize
1:11:12
I was like yeah yeah I agree I think the technical part is more tied to the tooling the tooling
1:11:20
would be the key part that would increase the technical risks
1:11:28
for regulatory or compliance considerations.
1:11:33
this I don't know I I would even propose significant hurdles
1:11:41
uh because I wonder how much conflicts of interests there can raise if like this body is
1:11:49
I guess like finance specific seats and some not
1:11:57
or like providing yeah because they're all going to be different so I don't know How if if that's going to
1:12:05
create in incentives, bad and good incentives to increase the participation and we may face some people just willing
1:12:13
to participate to get a a piece of the pie. So we could face more conflicts of
1:12:20
interest and there is a a potential problems tied to this and for maintainability.
1:12:33
Yeah, it depends how well it goes. If the incentives kind of work up, I think the maintainability actually will goes
1:12:42
down because CC is a very very important. It's like a president of United State positions. There should be
1:12:49
like a a lot of like fighting for over that seat position and so the
1:12:57
maintainability cost should also go down because of of that kind of competition there. But in current their situation it's like as we mentioned uncertain.
1:13:09
Um so I don't know do I leave maintainability somewhere in middle or somebody feels it goes either way. I
1:13:19
would choose the middle option because in the beginning of this process we may face more work to develop this
1:13:25
incentives model but uh we if we continue this this effort and model
1:13:34
probably the the amount of work would be reduced. So I would vote for a three in this.
1:13:41
And with this we have finished assessing two recommendations and welcome Oliver.
1:13:49
Today we had a CC day. Uh we looked at the overview page and filtered out
1:13:57
constitutional committee and we recognized there were only four recommendations. So we open it up and
1:14:05
now we have more options here and even one must before we didn't have operating that kind of recommendation.
1:14:16
Well,
1:14:18
with that I would actually conclude the the so-called hard part of the session
1:14:27
and I see William also uh jumped off.
1:14:32
Um but before leaving off I was wondering um does anybody want to share
1:14:40
their like general experience um going through this workshop material or staying up to date with what we have
1:14:48
been doing? How do you feel about participating about the app itself? like I put lot of effort into trying to
1:14:58
connect people trying to get the data in one place and speaking of data in one place there's a data page all of the
1:15:06
comments all the assessments people have done if you have your own AI and you do
1:15:13
not want to try our own uh I think it's GPT 4.5 that's used here fed with the AI
1:15:22
context and some research papers You can click the export button and
1:15:29
download the data yourself and just feed it to your own AI to make sense of it.
1:15:35
Uh we in the beyond which definitely going to do that and prepare some kind of report out of this. There going to be
1:15:44
also recommendations with part of the state of report um itself on the milestone 4.
1:15:54
Um so yeah you can feel free to ask synchronously play around but then let's go around the room and people just kind
1:16:01
of share your experience experiencing the our m workshops and and our projects in general and I start with
1:16:11
the bottom corner here. Um I know Olive you just joined but are you able to open your mic and share your experience?
1:16:20
Sure. Um I feel I can share mostly about the process of using the site in terms of submitting you know raw recommendations.
1:16:31
I found that extremely straightforward and simple um which I really appreciated. Um and as you say I just
1:16:38
joined. So as far as how that uh the raw recommendations are now filtering down into final kind of proposal and
1:16:46
submission um yeah I mean I think it's a nice tool where you can probably do a
1:16:53
nice job of that. I I hope that um I always think of AAM's razor uh kind of
1:16:59
the idea that the simplest um way of presenting an idea uh is
1:17:09
better than more complicated ways of explaining. But at the same time, it's possible to oversimplify. And so I guess
1:17:16
my hope at this point is for um where the recommendations go from here is that they're not oversimplified as far as the
1:17:25
the information that gets back to uh CF or IO.
1:17:30
Um those are my comments.
1:17:36
Thank you. I will take these recommendations also to deem itself because yeah we're I feel like in some
1:17:43
sense when the challenges came up we kind of had to oversimplify because there was hundreds of observations and suggestions and having like we had to
1:17:53
kind of get it down to small challenges. Um but yeah thanks for that. Um, seven.
1:18:02
Jibi, do you want to chat? Oh, you just dropped off. Well, then next one.
1:18:09
Sebastian. Yeah, I like it. I like it. In fact,
1:18:15
this this is a good evolution of the usual process we we deploy we have
1:18:23
deployed over the years. In this kind of exercise,
1:18:27
usually we use the MO board, right? And and MO is good
1:18:33
for ideiation. It's pretty a really good experience in in the
1:18:40
ideation side. But when we want to gather some data spec of making decision
1:18:48
making specifically, this is better. I have to say and I know you t you are the
1:18:55
the uh advocate of of mirror I guess but and and we use mirror for ideiation and
1:19:03
and that's I would to for that but this is to be honest pretty pretty
1:19:11
straightforward in terms of okay we discuss some specific topic and we can
1:19:18
uh gather information and data to make decisions. It's pretty I like it. It's fantastic job with that that application. Congratulations.
1:19:29
Looks pretty nice.
1:19:32
Yeah, just a small comment. I really like this tool that you developed and in
1:19:38
my view it's interesting way to gather people's sentiment and opinions regarding the different aspects of
1:19:47
governance. The only downside I see is not tied to the tool itself, but the lack of participation,
1:19:55
but this is a wide problem we have on Cardano governance because the discussion is fragmented across many
1:20:03
silos and it's really hard to engage more people in this kind kind of debate.
1:20:08
So this is not on your side of course but as a community it's a a challenge we
1:20:15
may we should embrace to to tackle it's really hard.
1:20:23
Yeah, I have a health page on the site if somebody also wants to just engage in
1:20:29
data itself. And here, yeah, you can see it's almost like a beer market going down.
1:20:42
and thin.
1:20:45
Yeah. Um, so I must say I am actually I think you know the the chart that you showed there actually more impressive
1:20:53
that I actually thought uh of in the beginning like how many watts was it likeund and
1:21:01
you know this is not the most popular topic in uh in the Cardano ecosystem. Um
1:21:10
I I that I fairly understood. How many was there? 294. Yeah.
1:21:15
Um so these are all actions. I Yeah. Yeah.
1:21:18
Signups is 63. Submissions of ideas is 40. Vote is 120. Comments is 69. Very
1:21:27
good number. And observations I kind of deleted all of them.
1:21:34
Yeah. And short findings. So they have these are um some old uh tags here.
1:21:40
Yeah. just to put it at uh let's say uh it has better numbers than go to at the moment and that is like I don't know how
1:21:48
many millions we have thrown after that but uh okay I'm jokes aside um uh yes uh for me
1:21:58
uh I think what is most interesting is to see if so uh as a community perhaps
1:22:06
will understand those metrics that we are looking at Um those are like critical metrics that we need to monitor
1:22:14
like in a similar similar way that we are looking at you know uh circulating supply and voting
1:22:23
power and stuff like that. uh this needs to be um continuously monu monitored uh and I
1:22:32
really hope that uh this tool can be adopted in that monitoring uh process
1:22:40
and also so we are also looking into um like uh emergency
1:22:47
emergency uh debate uh like what kind of preparation should we have for governance emergency and see and I'm
1:22:55
going to do recommendations for that and I think this is a very nice tool uh to
1:23:01
uh offchain uh async and also use for debate in like Google means that this
1:23:08
like let's say there is a governance emergency um in the foreseeable future and we need
1:23:15
to put down a war room like we did with the pig chain and then we need to have uh people's opinion and this is a very
1:23:23
nice tool where you look at some we show some measurement it's agreed upon how to measure it uh so there's no no dispute
1:23:32
in the data and then people can look at chart uh any visualization and debate it
1:23:40
and uprank efforts like that needs to be done so yeah
1:23:48
I like it very good tool very intuitive you know Sebastian mention and a mirror master and went to a website tooling and
1:23:57
that was kind of the I felt like yes we do ideation and it's kind of nice to visualize but it's always the a
1:24:05
synchronous activity later when you want to kind of extract or make sense of it it requires so much like massaging where
1:24:14
here you kind of construct the structure and then people just fill up and the
1:24:21
system itself kind of organizes the information and labels it to the correct place and then having an ability to like
1:24:30
the AI has made it very interesting to allow us to use more like sophisticated tooling in workshops itself and I felt
1:24:39
like this is a good opportunity to test something like that lot of data is coming in and and making use of as much
1:24:47
of that yeah not sure how the future or what what the future holds us. But I
1:24:55
do hope we're getting more of these kinds of toolings where we can put our own data in, connect our AIS or use AIS
1:25:05
and just waste a not that much time on on organizing the information but rather
1:25:14
yeah just have an ability to source the information.
1:25:22
Uh what's next I guess for the this weekend
1:25:30
um those who plan can still put some kind of assessments down some recommendation down but I think from
1:25:37
Monday we will close down the ability to add new recommendations
1:25:44
and ability to add new assessments because then we are going to kind of freeze the data and
1:25:52
Yeah, move to analysis page in our like be on the machine team.
1:25:57
The site itself will be available for at least this year. Uh so if you are not in
1:26:04
hurry to scrape the data off if you find it valuable. Um but it's but as you know there is the access for you to to get
1:26:14
that information and yeah like Kane mentioned when you're doing proposals or governance improvements
1:26:22
um try to see if you can find any recommendations here the charts here and grounded your your recommendations your
1:26:29
proposals with these measurements like hey if you would deliver on something what would change in these metrics Um so
1:26:39
this way we can build on top of each other's work and if people use our work if people talk about our work the chance
1:26:47
that we be able to repeat these kinds of governance exercises
1:27:02
we have 20 minutes left. I don't know do we want to go to our weekend open some drinks or to
1:27:10
ask anybody have some open questions or like we can discuss anything we used to have swarm Saturday sessions this time
1:27:17
so used to do crazy stuff then it
1:27:25
I don't know about you guys but I have some uh fried duck that is about to get
1:27:32
cold and uh and I have a few beers in the fridge. Uh so I think I'm going to
1:27:39
jump on to that. I recommend everybody to do that actually.
1:27:48
But I want to to congratulate to and for all these series of worships.
1:27:55
Incredible effort. Incredible work. Thanks a lot. All right.
1:28:04
Well, with that then I'm going to end here. Thanks for joining again in this lovely weekend putting some brain power into governance which is not easy.
1:28:17
But if you do it right, we will change the world. Absolutely.
1:28:24
All right. Have a nice meeting everybody. Bye-bye. Bye. Bye.
