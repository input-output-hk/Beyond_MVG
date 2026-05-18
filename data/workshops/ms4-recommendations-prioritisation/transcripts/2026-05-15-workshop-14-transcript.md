---
workshop_number: 14
date: 2026-05-15
title: "Governance Takeover Incident Readiness and Incentives"
video_url: https://youtu.be/U3YXk6CtyGI
youtube_description: |
  Final prioritisation workshop of the Beyond MVG series. The room zoomed
  into the Governance Takeover Incident Readiness recommendation: Ken
  proposed a CIP-135-style disaster-recovery framework for governance
  (war-room thresholds, snap CC elections, alarms when Nakamoto
  coefficient or DRep voting power crosses defined limits), modelled on
  what Mike Hornan already runs operationally at Intersect since the
  November 2025 malformed-transaction incident. Hicks argued the
  structural fix is a 1.5% per-account DRep cap plus an annual delegation
  reset to break the "voting power as asset" psychology and make a
  Binance/Coinbase-style takeover infeasible (top 10 DReps now sit at
  about 48%). The group scored the recommendation as Must with
  significant impact, high regulatory weight and continuous-but-light
  maintainability. Ken confirmed default-DRep-delegation will be removed
  in the next hard fork as one tiny structural fix already heading to
  master. Closing remarks from Pedro Lucas and Ken Erik on the lack of
  governance-tooling funding and the need to continue open governance
  and funding calls beyond the project.
attendees:
  - Tevo Kask
  - Donbosco Otunga
  - Frederick
  - Hicks
  - Pedro Lucas
  - Seomon
  - Ken Erik
  - Kavinda
  - William
---

# Workshop #14 Transcript -- Governance Takeover Incident Readiness and Incentives

Raw verbatim YouTube auto-caption transcript. Timestamps and line wraps preserved.

## Transcript

0:00
Hello, Don Bosco. Hi. How are you doing?
0:05
I looked at the email inboxes and realized I have to do the twominut uh
0:10
video for the intersect proposal. Totally forgot
0:17
now been generating slides with AI trying to
0:23
make something useful out of it. True. True. Um yeah, it's been a minute. I think the
0:30
last time I joined this one was um um it's it was a while back. I recall
0:39
that time you at least four or five people who are joined for that meeting
0:45
and I was like oh I've been seeing this around but I've not been getting the exact timing and scheduled in my
0:53
calendar. always been a conflict or maybe it's too late for me to join. And then so I decided to just see how
1:01
things are going. But then I saw this one was uh at 1 p.m. and I was like, "Oh, nice. Uh I can join this one and
1:08
see what people have been up to and how how the updates are going." Um
1:14
looking forward I wonder in in team we had like a back and forth like do we want people to
1:20
choose the time they want to have a workshop because the coordination
1:25
manager where I put the times there people could actually put their perspect
1:31
prefer time when they want to meet but we never met did the communication because he thought if we ask people to
1:38
prepare a time maybe it's too much asking and just maybe Yeah, there's that. But then maybe you
1:46
can find you can't there's no one rule fits all. Um considering people may be
1:53
coming from different time zones and all of them want uh to get out to their own uh timelines and availability too. So
2:01
that's one thing but at least it gives you um an idea of when is the most
2:07
suitable that you can find the most people and then for those who uh can't join maybe they can catch up on the next
2:14
session um such as myself here
2:19
money Jun. Thank you Teo it's good to be here
2:24
again. Okay. Well,
2:30
um I wonder we have a few minutes more to wait because you spot on time. Um
2:36
uh just kind of opening up would anybody everybody speak on like what state you
2:42
are in like the Cardano governance in general like try to come up with like a twominut
2:48
intro of what are you involved in and yeah how how do you think this CIP 1694
2:57
is working or yeah whatever the chip name was basically the DEP and SPO
3:03
system and do you find like a good governance or or what you feel like lacking. So going around the
3:10
room starting with Don Boskov would you what would you say
3:17
about that? How do you feel like engaged you are with Cardana governance and how you
3:23
understand it in like two minutes?
3:28
uh speaking from an end holder or
3:33
which perspective or just free? Yeah, all the perspectives if you have Yeah, that's a good idea. Maybe describe
3:40
the roles you think you have like one other one maybe direct SBO maybe like a
3:46
proposal assessor from old days like any kind of role you see yourself as part of
3:52
Cardano governance if at all maybe you don't feel like it at all and then that's also so that we kind of get the
3:58
feeling of what people you have in the room. Oh, okay. I will just say for u
4:06
personally like uh having the chance to effect uh decisions in the Cardano um
4:12
ecosystem is one up upward uh thing that we cannot underestimate in consideration
4:19
that other platforms don't offer um an interaction with their user base. So you feel part of the ecosystem and you can
4:26
actually talk about how the experience is for you. uh personally like uh what
4:31
you're doing right now and then uh you feel like um you also get different perspective from how people feel like um
4:39
the ecosystem should respond to um different situations and the best uh
4:45
case for decision making and stuff and this just pertains to things such as uh
4:50
protocol changes uh maybe treasury withdrawals and maybe project uh which
4:56
projects get to to be funded and stuff. So I would say from a governance perspective and someone who all that the
5:03
inclusion and the community is one thing um I really cherish and you actually
5:08
feel part you're part of something hugger than yourself.
5:14
Oh okay thank you so much. Um this is actually my first time of taking part in
5:19
this um a webinar for me meeting. Um really what captivates me um is um
5:29
the openness of governance at to incorporate all people who feel they can
5:36
do something for the ecosystem. Yeah. So that accommodation really intrigues me
5:42
and it makes me uh do more. Thank you.
5:47
Thank you. Let's try one or Frederick. Do you want also introduce yourself and
5:53
how engaged you are with Cardano governance and what roles you feel like your embody?
5:59
Yeah. So um apparently I'm I'm the hub lead for
6:05
for the MIBT Kadano hub and we we are trying to um
6:12
develop the the the community especially in southern Africa.
6:19
Okay. So we we've not been uh very much involved. Um so I remember my last interaction
6:27
with Nick Cook when we met in Nairobi during the Kadano um Africa Tech Summit.
6:34
The encouragement was you guys you need to because we are we are focused on
6:39
building innovations. Okay. Yeah. So we we've been working on a number of Cardano innovations and one
6:46
of them actually uh came out as one of the top five innovations in Nairobi, Kenya. So now
6:54
Nick Cook was like you guys need to come into governance so that uh you know we can develop the the community and the
7:00
ecosystem especially in southern Africa. So I love the concept of uh you know um having
7:07
this inclusive kind of um you know governance arrangement and um I'll be delighted to see if we
7:16
can get more into regional uh representation as we you know we develop
7:21
um you know the ecosystem and stuff like that but um otherwise I love the
7:27
inclusivity the the community centered kind of arrangement. It's very different with
7:32
the the other ecosystems I've worked with before like ICP, Ada, you know, and
7:39
all these. Yeah. So, I love um what is happening within the Kadano ecosystem.
7:45
Yeah. Trying to uh take, you know, governance as much as possible to, you
7:51
know, to the to the lowest communities, you know, uh regardless of even language barriers and stuff like that. So, uh
7:59
it's a delight to be part of this process. Thank you. Thank you. Um for all the new people
8:07
joining, Pedro Hicks, Coffee, Simon, Kenic, we had a bit of introduction of
8:12
ourselves while we were uh waiting for more audience. Um but now I would like to jump into like the uh real stuff. I'm
Workshop/prioritisation page walkthrough
8:21
going to share also the screen, the applications and and the stuff we're going to focus on today.
8:29
But many of you already had also been in the previous workshops and people know about them. Um at the first Yeah, here
8:37
is the workshop page. Here we have all the list of the previous stuff. You can download transcripts, you can ask AI
8:43
assistant what happened in what meeting um anything you fancy. And I know we had
8:49
a final workshop but this is now the final final workshop in any sense of the prioritization. Um um and when you click the
8:58
prioritization page and this URL, it should automatically filter you bound MVG um recommendations. So last three
9:07
weeks uh we were like doing uh each individual kind of was submitting
9:13
recommendations like what they see and looked at the charts and how can we uh like improve the governance and now the
9:21
team put together a top nine of all of the like aggregated versions and tried
9:26
to and give them general like not general but uh yeah what was most spoken
9:34
was like aggregated together or what seem to be similar. And now we're trying
9:39
to again go around of like prioritization of which uh which of these we should focus most um and and
9:46
have like the most cover like discussions about um in that prioritization page when you
9:52
join there uh you will have this like Reddit like um updown voting and so this
9:58
will basically prioritize what is our today's workshop agenda
10:03
and you will see that there are two topics that we already discussed then with this like who human uh uh so even
10:12
if they are like top ranking ones we may skip them for now so that we cover as
10:18
much as ground as we can. Um if you click on the recommendation you will be
10:24
able to read um on the what what's on the recommendation here scroll through
10:30
the evidence attached and yeah right now we haven't done
10:36
assessments for this and if you feel like okay we should talk about voting tools for SPOS um and it's something
10:44
that's interest you to dive deeper you can upload it or there is an alternative
10:49
way if you feel like you don't want this discussion happening like you can also download it.
10:55
Um I feel like voting to for has been discussed quite a lot of time and in the
11:01
previous discussions. Uh however this doesn't mean it's like less impactful. So if you feel like we do need these
11:09
tools but you don't want to discuss it then later we're going to do assessments and all of that can be also done as
11:15
synchronously. So we don't have to come for workshops but workshop is a great way to collectively do that and get the
11:21
grasp of what what are we working with. Um so I give a bit like five minutes for
11:28
everybody to open the app on their own pace and skim through the like the
11:34
titles you feel like most compelling for you. Check click on the details
11:42
uh what is this more about and then yeah either upote download
11:49
based on do we want to have a bigger discussion today and then as usually
11:55
have we have in the previous workshops people will share opinions give give
12:01
clarity help to make decisions and I will take as much comments as possible but you can also individually write down
12:08
your statements and go around already download these just
12:15
because we haven't had a discussion on them. I have if any questions or unclarity now
12:21
is the opportunity to ask what do we do and that we're going to talk about
12:27
governance takeover incident readiness as for the first topic
12:33
let me click back then or sometimes it doesn't show me the show more the emergency response team security
12:40
committee within intersect documents uh the scenario of malicious governance
12:46
attack and prepares any monitoring and communication channels required to swiftly respond if incident occurs
12:53
monitoring should be driven by defined scenarios but uh but may include
12:59
technical and no PS I don't know what is that and large CS6
13:05
other custodial apps in case they change their stance on using voting rights of
13:11
custodian assets a rate of change of the DO 35 reps coordinated power increases
13:19
among many small D reps within seconds of each other. Maccomicient
13:25
and large vote volume lating in in a voting window addresses ecosystem
13:30
responsiveness to mitigate impact of coverance incident.
Governance Takeover Incident Readiness recommendation
13:36
Uh so this is more looking at who is voting and making sure that
13:44
and uh doesn't yeah somebody's not trying to co-opt the governance
13:50
and not the slow but the real lift in voting power concentration famed as a low cost high impact safeguard and swift
13:58
action to governance takeover or stall notifying CC members for example that could reverse or prevent an attack
14:05
want to kind share their opinion on this kind of recommendation. Do you feel like
14:10
there should be a body that has like a veto power or um
14:16
yeah some kind of onchain ability to stop the show in some sense we right now
14:22
have the no motion that kind of turns off the all the social governance. Um
14:28
but it's it's slightly different. This is more killing power to those who we elect.
14:33
Um yeah then you can open it. Yes I hope my internet works fine for
14:40
you guys. Uh so the uh idea behind here
14:45
uh is that we have let's say some sort of disaster recovery uh similar to what
14:51
we have for stake pool operators. Uh we do have CIP 135 um which uh
15:02
handles uh like three different scenarios for SPOS's and in regards to
15:10
network uh security and as you guys know uh that our SPOS's
15:17
uh that was activated in November uh 2025 when we had uh the pig chain um pork uh
15:26
on Cardono due to uh bad eboard serialized sing
15:32
um even though it's like two different uh type of domain um I think it is
15:40
important that we have uh a similar uh response or if we are
15:47
able to piggyback on that framework as put forward in uh CIP1 135 and then
15:56
comes to questions uh we have like uh um
16:02
for SPOS's and network security we have certain metrics like if this happens we
16:09
are going to gather a war room um if this happen we need to do this this um
16:16
and currently this is run by Mike Horn um
16:21
he sit as uh oper operations security network operate security at intersect
16:27
and currently it is intersect that is uh managing and let's say blowing the
16:34
whistle if something happened and I think it is important uh to have a similar mechanism
16:40
um in regards to governance so what kind of scenarios have we been looking into
16:47
well uh what if I'm just saying what if um I going to use the infamous Binance
16:54
scenario which has currently I think they're running something similar to 13
17:01
uh stake pool um and Coinbase they collude and they decide to create their
17:09
own DREP um uh and they will like
17:16
basically reach an enormous amount of voting power uh which will in regards to
17:24
our measurement um uh kick out on both the Nakamoto
17:30
coefficient and um
17:35
and uh the decentralization of uh voting power.
17:41
So that is the idea behind that and uh I want you guys to put in the comments
17:46
there what you guys think and um make a up vote if you guys think that is
17:52
important or down vote it if it's uh you feel that is irrelevant. Uh yeah Lucas
17:59
welcome. Hey everyone uh great to be here. Thanks for putting this together. Um I'm just
18:07
focusing on this topic. The two ma the two first things that come to mind to react of this kind of governance
18:14
takeover would be the CC so making things not constitutional unconstitutional and the vote of no
18:22
confidence. So but I think that the problem there is that both these mechanisms are also
18:29
dependent on steady staking voting. Is that the the issue or
18:35
so did that mean that those mechanisms were not really ever safeguard or
18:43
yeah we we had like let's say governance uh security issue um in December where
18:50
november as well before the pigpark uh we had Atlantic Council uh withdrawing from the CC basically meaning that uh
18:58
the ledger hob uh below uh CC min size
19:04
um forcing for election. Um and what Intersect did there, they didn't have
19:11
to, but they did it. They uh on behalf of the community, that's it, kick off a
19:17
tiny emergency. It wasn't a big emergency, but like a tiny emergency uh to have like a snap election. that is
19:24
kind of an incent that that is a kind of a scenario that perhaps should be included in such a CIP uh framework. Um
Voting concentration & exchange (Binance/Coinbase) risk
19:34
uh the most scary part uh in my mind is voting concentration. Uh we know that
19:41
approximately 60% about 67% of circulating supply is parked in
19:48
centralized exchanges in their consent. Um and um
19:55
and uh yeah uh what happens like it's a Binance
20:02
I'm not saying that they going to do but what if they did uh to preserve their own interest what kind of mechanism do
20:09
we have to protect ourselves and this is where this let's say state of emergency and let's say if Nakamoto coefficient
20:17
falls below XY Z then this kicks in If um
20:24
if um the voting threshold for update the constitution falls below let's say
20:32
15 d reps you know just just for example this have to kick in
20:38
those type of mechanism lucas yeah thanks for uh let me here and um
20:46
I'm deeply concerning about the uh the concentration right now and uh every day
20:53
I uh posted like how much uh top 10 concentration rate is about currently
21:00
and now we have 48% for top 10 DFS and um it is still
21:10
I'll say steadily include in improving and we can also yeah easy uh I'll say
21:19
easily imagine like we going to have maybe one day six most the the
21:24
centralization up to 65%. So it's quite
21:30
concerning right now. And uh I noted uh
21:35
I put the note here about the solution as a I always say um caps and reset as
21:43
one of the sol could be imagined solution because um firstly um maybe we
21:49
can have dip for like a 1.5% per account
21:57
but we can imagine like Binance might have like tens of thousand and de
22:02
account and then consequently
22:07
just a cap mechanism doesn't actually uh how say prevents the concentration so I
22:16
also suggest annual delegation reset that means like uh uh the direct
22:24
delegation some uh will be reset in once maybe once a year or twice a or
22:31
something then you have to rede it to one dip. So this means like uh
22:39
it's you know firstly my 1.5% cap is you have to divide the account but also if
22:48
you have annual reset then you have to correct the delegation from the a
22:56
holders. So it means uh uh managing uh multiple D account is considerably
23:03
difficult. So like uh for Binance or some some sort
23:09
of entities they they need to have hundred of managing hundreds of accounts
23:17
that also cost a lot but also they have to rededlegate in certain time then you
23:24
know it's makes more difficult to managing multiple accounts.
23:31
So the just the printing caps and the reset is seemingly like a easy solution
23:39
but uh it also uh makes the account management and so
23:45
difficult. So maybe possibly um how say affect some some sort certain
23:53
part certain how um maybe affect I say have going to have
24:01
positive outcome maybe. Yeah, I actually wrote
24:07
the write down my article why this and
24:13
uh C could be one solution. Uh so if you are
24:19
interesting please look at it. So yeah this is it. Thanks for that. The
24:25
problem is DF concentration is right now is uh I think we I mean also I'm DF so
24:33
we have a voting power as an asset that means uh we have you know some sort of
24:41
psychological incentives in DV like uh if we increase my voting power that you
24:49
know persuade me to be happier rather than getting lower.
1.5% DRep cap + annual delegation reset
24:54
um let's say voting power and also if you have strong voting power that means
25:01
you you will be treated by you know proposals as in you have you're going to
25:06
have goods access to like a new project or new proposals and sometimes they
25:14
might pay to you for yes vote maybe and
25:19
uh we have no you know legitimate restrictions about you know their
25:26
collusions like uh if you if teams might pay but you know if you use like dollars
25:33
or something without a then we cannot know about it. So if you have uh as much as B uh strong
25:42
voting power that means you can correct you know kinds of incentives still we
25:48
don't have incentive mechanism in ADA but we already have psychological incentives also
25:55
um incentives from community participation I mean or I mean
26:02
or like the community uh I say uh reputation I
26:08
So we still have some sort of incentives as a voting power. So people actually
26:14
try to maximize uh their voting power. That means you
26:19
don't need uh cooperate to other DS because uh if you cooperate to with
26:27
other DEPs that means you know you may
26:32
saying that the other D is also better option that means you you might reduce
26:38
your chance to get more delegation. uh psychologically this delegation game
26:45
actually prevent to be able to cooperate. This is how the feature of the uh our
26:53
gaming uh I say gaming theory based uh the
27:00
direct game I mean delegation game. So we need to stop that kind of you know
27:06
maximizing voting power because yes we have uh voting as asset. I also, you
27:13
know, got a lots of DMs from the projects and uh if I
27:19
actually rarely do that, but I, you know, uh vote yes, then you know the
27:26
team DM me and expos something like you know it happens and uh we going to have
27:32
uh billions of treasury funding. So that means you know you can if you are
27:38
proposer then you can pay for big deals for voting. Yes. No, it's easy to
27:44
imagine that could be happen in near future. I'm not saying I'm seeing that sort of things right now, but uh it
27:52
could be. So I mean having the D voting power
27:58
actually reduce the risk of the and also destroy the mechanism of the DP and I
28:07
mean voting power as asset. If you know your boarding power going just last one
28:14
year then you don't really care about boarding power. If you have kept 1% five
28:21
uh 1.5% you know it's going be going to be zero
28:27
for next year then and also the maximum cap would be 1.5%.
28:34
then we you know don't really care about how much voting power I have or the
28:40
projects also don't care about individual DF
28:45
and uh we going to you know going we are the D going to cooperate to
28:53
say one certain proposal should be success because one DP cannot you know
29:00
influence to more than 1.5% % and also
29:05
the voting power will be liquidated for one year. So you have to uh cooperate
29:11
with other dips otherwise because otherwise you have only 1.5%.
29:18
Something like that. So I mean firstly we have to destroy the mechanism and
29:24
also psychological uh trick you know as a you know if you
29:30
have more voting power then uh you're going to be more influential in governance it means you you're going to
29:36
be the you know it's going to be you know kinds of like dark side of the
29:42
governance you know so actually yeah that's all those things uh all are
29:48
written in my article. So if you are really interested so please sorry uh
29:55
interrupting the meeting. Hello. I love it. It's a very very wise words
30:01
there uh from you guys in Kadano. Thank you also this is from my
30:06
experience. So yeah but uh you know uh Kano started out
30:12
of Japan. you guys have listed the most experience from this. Uh you know um
30:17
uh and just also on a side note out of beyond minimum volume governance um um
30:24
we also are going to recommend and put forward a way uh a standard of actually
30:30
how to measure. Uh I don't know if you have noticed but if you see on uh coin
30:37
market cap in you see on binance and coin and even on our t tools you will
30:44
see different numbers on circulating supply. I don't know if you noticed it but um
30:51
and for how to calculate let's say voting power and how to put up let's say
30:58
if we reach this threshold we have to activate an emergency uh threshold and we also have like uh provided it's going
31:05
to be published on currently it's in my private uh repo now uh but it's going to
31:11
be published on um IOG's uh GitHub repo uh along with this one um
31:19
So this is important to it is important to have a
31:24
standard of how to measure before we say 10% 5% because otherwise
31:31
yeah I know um I I'm not actually engineering person and I'm content
31:37
creator so it I just put on my ideas and also critical analysis of the but uh I
31:44
need to more you know uh program I and engineering side of overview and also
31:51
research but uh it's kind of kickstart of you know inspire people for the to
31:58
rethink about uh governance problem and also what could be the solution of
32:04
something and because this is not still not CIP so yeah I need to yeah sort of
32:11
research about it thank you that's cool and everybody for listening in here uh If you can put into the
32:18
comment field if you have like the great solution uh for this or suggestions or
32:25
something that we need to look into uh please uh add it here in the comment field. I see while we have been talking
32:31
to have been hammering on the keyboard and adding on as great work. U should we do like um have have we done an an
32:38
assessment on the um score? Yeah, I wanted to kind of bring it back like it
Assessment: MoSCoW tier
32:44
it's a another interesting way to solve this takeover incident be like uh yeah
32:50
incentives because the incentive discussion has been like a recurring theme I guess over almost all the
32:56
recommendations we have discussed um and and indeed also like inspired to
33:03
thinking in terms of like yeah having a bit of like plutoaucracy to to elevate
33:08
people to DEFS and then but having them not representing the amount of ADA they
33:14
have but just as an individual voice but then we have this yeah so that we have a
33:20
protocratic and kind of what is that the social thing where people need humans to collaborate um but yes let's go to the
33:29
assessment page and I wonder hick if uh you can kick it off with also since you have a lot of knowledge here you can
33:36
also do on your own like assessments I clicked on the assessment button on the recommendation and it will open up this
33:44
uh list of like scaling options each our collective effort is averaged here um
33:50
but right now I'm doing it from my kind of response is based on all your opinion
33:58
the first like is the Moscow here where we just ask is this governance take incident a
34:04
must should or won't like and do you need it right now like it's blocking
34:11
something important or is it more like a shoot that is a high value expected to happen and or nice to have so I don't
34:18
really need it and that's in a terms of like if the incentive is the solution
34:24
then this may be like a cool because then we don't have to like deliberately
34:29
think of a team or some kind of rule book to like
34:36
like yeah manage the incidents Um, so yeah, where do you stand in the
34:42
Moscow Kier? Um, by the way, just a minor uh tutorial,
34:49
remember to click on the save button if you
34:55
um before you close the Yeah. So you have here you can see you can you have
35:00
the MOS code here. If you choose must uh a lot of defaults will come up and then
35:06
if you click on uh like the skip uh
35:13
uh um skip part here you will be able to drag from like unproven to high effort
35:20
or low effort to high and you can make your assessments of of how this will
35:27
impact or and how important it is. I get back to you Hicks
35:34
should be must because we don't have like a prevent mechanism at this moment
35:39
so and would you say then the impact is also there like does it affect the
35:45
entire system ecosystem or it should be yes I mean uh yeah I mean
35:54
this impact is significant so so I'm not really familiar with this
36:01
platform. So I'm just um looking really taking time for looking at it. So
36:08
yeah, but yeah um the you know takeover incident is actually yeah we have to do
36:15
it right now. um because top 10 concentration is really 48%. So
36:24
it's not really I mean as a as a corporation I mean listed corporation is
36:31
you know that concentration like 48% is significant risk.
36:39
Um okay and another question for um for you uh is can this be bullet with
36:46
existing tools like is that unproven high effort to kind of create these kind
36:52
of incident readiness teams or is it like a proven and we all kind of know
36:58
how it's done. It's just selecting the people or maybe that's a bit yeah visibility on that selecting that team
37:04
of people to take care of that is a hard one. So where do you feel in like a one
37:09
to 10 uh measurement like how high effort or low effort this uh
37:16
recommendation is to implement? Yeah,
37:22
CPS and coordinated solution. What does CPS stands for? Actually I couldn't
37:29
really understand what is it. Um CPS is Cardano problem statements. I'm
37:35
not sure very good or or
37:40
and by the way you guys don't have to be expert you are allowed to guess as well and I was also like
37:46
if someone is like like have an opinion oh this is not feasible to implement I
37:53
would like you to raise the hand and and tell me also why no but okay sorry
38:01
okay yeah but yes the population distributed their population to be here.
38:09
It's really also important and uh
38:14
yeah but for DF compensation actually I had a
38:20
negative view and probably we can keep it later because before concentration I
38:27
mean I mean before solving concentration problem the direct concentration might
38:32
accelerate the the concentration because if you if you get reverse or
38:39
compensation as a direct then you can more actively
38:44
uh participate in governance that means if you don't have compensation
38:50
that sort of people I mean Dre can't uh actively participate in the governance
38:57
so I mean you know there's a some problems in compensation we have um we
39:05
need to tackle two kinds of compens compensation problem like um firstly
39:11
financial and uh problem I mean how if you pay every DFS then you're going to
39:19
run out the treasury and uh if you select DFS to get compensation I mean
39:26
then uh you're going to have uh accelerate the comp concentration because you know
39:34
if you have two types of DF I'm But you are going in detail of the
39:41
compensation proposal. But yeah, we're looking at the governance takeover like that specific
39:46
recommendation right now. The compensation proposal is this. Okay. So you were
39:51
reading this one. Yeah. Yeah. Today's topics is the governance state coincident one.
39:57
Um but yeah. Okay. Let's and also
40:03
now banking robot but I think it's more important. I mean voting tools for SPOS's as well also DPS we have uh g
40:11
tools and uh I mean temples and uh CF voting tools but um I think we need to
40:20
more like options and but in in just in regards to the
40:26
Europe compensation so I I it it touches a little bit I feel uh in regards to uh
40:32
governance takeover as well so just imagine this scenario Uh, I put forward a proposal to withdraw
DRep compensation tradeoffs
40:39
$60 million from the Treasury and um because um uh it only needs 20 DRPs uh
40:50
to actually get that pass um I decide to
40:55
just pay uh 20 DRPs uh $200,000
41:00
uh to vote in my favor. And this leaks out by accident. And a scenario like
41:07
this um is also important to be managed by uh
41:13
governance. Uh it's a scenario in governor's takeover.
41:19
I feel uh Steon first and then we will put it forward to Hicks later if you
41:25
raise your hand. No, I'm sorry. I I'm just mistaken. Right. I I think um it's a fair point,
41:33
but also on the other hand, there's a problem where if we don't incentivize them, we're asking them to do work that
41:41
is um like they're just like where the incentives don't align with what Cardano
41:49
wants them to do, right? Maybe they want to use their voting
41:54
power then to g to gain something right to for for another incentive that we
42:02
didn't design for them. For example, voting for something that
42:07
makes themselves money, right? So I think and also so when when I talk
42:15
to people a lot of the time I feel like um that they have already ideas on how
42:21
this incentive could look like but as um um as H pointed out incentives can look
42:29
very different like they can take all kinds of forms and we can incentivize all kinds of behaviors. It doesn't have
42:36
to be the top 20 dres to you know with who have the maximum stake and we can we
42:44
can use all kinds of parameters as well. Okay. And is it a very high priority? Is
42:51
the saying it is a must and it has a
42:57
large impact on the ecosystem and critical to implement
43:04
and it's feasible. Is there anything like is there anybody I would just try
43:11
to step on the other side is like well intersect shouldn't manage this uh it
43:18
should be someone else.
43:23
Is there anyone thinking along those lines like who should be responsible? Is
43:30
it okay to leave this responsibility to Intersect? And is there if if Interext said, "Okay,
43:37
we're going to have this. It's going to cost a million dollars." Do you think the dre will vote in favor for it?
43:44
I think it's good for Intersect to to like oversee it. That's the word.
43:53
Good for Intersect over to oversee it. I don't think they should do the work itself. Um I I mean
44:00
that's maybe I'm a bit biased because I'm going to bring forward a a proposal to do exactly that work
44:07
but seems like Intersect has enough on its hand and I'd be very happy for them
44:14
to oversee the work but I don't think they need to do it like there's re there should be research involved in my
44:19
opinion. Let's move to three more questions uh on
44:25
the negative side. How much uncertainty is in the governance take our incident
44:30
readiness recommendation? How much is that uncertainty happening there in a technical risk site when
44:38
you're trying to implement such bodies or we assuming we we have a perfect
44:45
incentive mechanism. So the thing here in terms of you know
44:52
this governor is is not let's say technical at all. I think it's not uh
44:58
something wrong with the ledger or some some this is like human factors that
45:03
would lower the technical treasure but we do have to decide how to measure it
45:09
agree and that is just some Python script and
45:14
SQL's queries and card like
45:21
okay yeah I was thinking in terms of like technical Calhorn
45:27
if if the incentives is a solution for
45:32
the readiness and what we discussed today on like all of these different
45:38
incentive models then it's becomes quite unclear if there
45:43
is a need of a ledger or some kind of different rules like how do we create that coalition of governance that we
45:51
trust and there is probably some kind of technical
45:57
like clarity on or standardization required in order to make that work.
46:04
Um but if you are going more to the like a lower part I'm going to then keep it
46:09
in the middle of three. Uh two more questions regulatory or a compliance.
46:14
I'm good with this. Uh no legal concerns or significant
Technical risk, regulatory & maintainability scoring
46:20
hurdles. I feel like this is a maximum on the legal stuff
46:27
because it requires like a heavy accountability and and making very clear where the
46:33
borders are. I think it's like important here. And finally maintaining I think it's
46:41
also I wonder you never really hear about
46:47
like security teams maintaining stuff and In my experience of eat administrator,
46:54
it's usually the first three months setting it all up and then it's kind of like forget until
47:01
internet is gone or electricity is gone and then I get a call and hey why nothing works well entire country is out
47:07
of energy what I'm supposed to do but I'm not sure how governance
47:13
just just to clarif as I give people some insights. So both Cardano
47:19
Foundation, Intersect and IO, they have dedicated people looking at each block uh and they
47:27
have put some threshold for themselves for when to blow the whistle and the
47:33
alarm. Uh so um uh in regards to
47:38
maintainability, this is like a continuous process, but you don't we don't need 10 devs looking
47:45
at it, but uh you have to have someone that uh gets an email or SMS or a red
47:53
screen when some certain threshold um pop ups and then okay, now it's war
47:59
room. Um what can we do? Okay, I then moved the mental two from
48:07
my perspective. Yep, let's save. I skipped the cost estimate because yeah, that's a very
48:14
highly uh I could be in the middle. It's just that it depends on the specific
48:20
solution, I think. And um yeah, well, we created one
48:26
recommendation here with full assessments. If you feel you want to give a different view on the um please
48:34
do so or do any other recommendations because now we're no longer doing
48:40
workshops but there is still at least until the weekend the platform will
48:47
remain open and if there are things happening on on the site and people are
48:52
going around every day I think we will keep it open until there is like a slowdown of no engagement. event.
49:00
Um but yeah, thanks for everybody joining for earlier to sharing um what you do in
49:06
the Gardana giving thought on what is important in the recommendations and
49:14
yeah doing some assessments and providing opinion. Does anybody want to leave off our workshop with a closing
49:20
comments from I don't know Kavinda, William, Pedro Lucas, you didn't share
49:26
that much information. Yeah. Yeah. Um I think since I'm new in
49:32
the ecosystem, um I'm learning and um yeah, I'm ready to to give my best for
49:39
the ecosystem. Thank you so much, guys. Um I can't really add much about
49:45
the specific theme. So I would just ask about MVG in general if you this you
49:52
said is the last the final final workshop but I'm not sure if you want to
49:57
still close up any topics on this specific matter topics are closed so yeah sure ask
50:03
anything regarding team platform it's a good so so I know you've maybe mentioned
50:10
something or maybe you were talking about hypothesis of of putting things on on chain or more governance uh request
50:16
requests for for your initiative. Is there anything or are you going to continue doing anything proono or how
50:24
has the team worked in closing like since you're closing sort of your your
50:30
public side of your project? Um how do you see the future of this initiative?
50:38
Can I just like kick in? Um what is unfortunate but I was hoping for was actually that we would see some
50:46
governance treasure withdrawals with the sole purpose of uh governance and
50:52
measurement. Uh unfortunately that haven't happened. The only thing is the IO research part. Um I know governance
50:59
it ain't sexy. It doesn't pump any bags but it's actually very very important. Um there is a few uh uh and what is
51:08
unfortunate is that there are no let's say actionable that produce a product uh
51:15
for beyond minimum vibals. Uh so I'm all over the SIP editors meeting right now.
51:21
uh we have uh currently I um in regards
51:27
to reduce the DREP uh concentration like
51:32
um emergency fix it called not emergency fix but it's a CIP that um default
51:39
delegations uh we will we will suggest to on the next hard fork uh we will
51:46
suggest uh is for Jinxa um to remove that it's mandatory to delegate a DREP
51:54
um to get uh staking rewards. Uh that is like uh one tiny step out of many to
52:02
reduce the pressure of um the rep uh concentration. Uh that's one thing um
52:08
and that's already um um branched into master uh and on the
State of governance funding, in-flight CIPs
52:17
let's say road for hard forking to uh two I think insta is uh aiming for uh we
52:26
also have uh service committee um uh I'm
52:31
going to make sure uh the c committee get informed about all our recommendation and we also have a
52:37
working group um that look at for example the rep uh compensation uh or CC
52:45
compensation and um yeah so there going to be out of this
52:50
report they are going to be actionable that something that you will in
52:56
foreseeable future actually see that oh this is not just yapping and talk.
53:04
Yeah, from me I would say pretty cool like team um and like a project
53:09
experience. Um I did spend a lot of more time not just facilitating but building
53:15
this app as you can see and I think that actually elevated me to be a a slightly
53:20
like a unique facilitator in a sense that capturing data in different formats
53:25
again like from going from Google to mirror and now mirror to websites. Um
53:31
and in short term what we can expect is like packaging more of that data into
53:36
consolidated report and data structures. I think Ken is also working on a GitHub that has like all the stuff for the
53:44
agents to feed into um and then like another short-term thing that um many of
53:51
the participants here um got to write an intersect proposal for this process uh
53:57
or this inter proposal process about governance coalition governance prototypes and RFP program which is the
54:06
goal is to create like funding cycles to deliver imple or and implement any of
54:12
the recommendations done in these workshops that was done in here or just
54:17
been coming up from I don't know other spaces hey we need this or that like a technical solution a social solution
54:24
then we have like a a quick way to run like a catalyst style stuff to implement
54:31
these specific governance uh solutions um yeah and in the longer term um The
54:38
proposal the bond energy proposal was set up as like a one shot without
54:44
continuous. So that is a bit of a downside that we are not able to go into solutioning right away and we have to
54:50
again negotiate who is doing that and why they are doing and what exactly is doing. Um
54:58
but well in a sense it's still working like at least there is an opportunity
55:04
but now to need again community kind of gathering around these ideas and and
55:10
pushing proposals through which is going to be a hard discussion because I think around 100 million has to be not funded
55:18
in order for this to get a chance.
55:25
Yeah. It's crazy how how everyone's just getting funded for research and technology and um the governance system
55:32
itself is I would say being sort of neglected like can Eric was saying there's is there zero governance
55:42
specific proposals can Eric so at the moment there are
55:48
zero proposals as far as I'm aware of that actually produce a product
55:55
something change not even gov tool builders not even gov tool builders
56:03
um and they're not funded by the way so they're probably going to disappear uh in a force
56:08
yeah I meant I meant overall governance so the gov tool is going to probably disappear that's what you're saying
56:14
yeah uh I don't see so I don't know if you guys there was an incident here it
56:19
took them like a freaking week to uh fix it because there's no devs it. But uh
56:25
when when it comes to uh let's say uh what I so I am what I'm most proud of of
56:32
the Beyond team is like it was so hard to get funding for this. It was like I
56:37
don't know if you remember the budget ground last year but was like governance was not sexy at all and hopefully uh we
56:45
are able uh with this project uh to prove everybody wrong because I know we
56:51
have 10 uh so so since I I have 10
56:57
actionable item where we actually so we we are not able to like you have to do
57:02
this Lucas you know we are not but we going to provide the CIP like if you
57:08
don't implement this in your wallet, you're going to be an idiot husky holder. You understand?
57:14
That's the motivation. And because and what and this is what
57:19
most people don't understand. Um me and Max wondres we spend uh from we started
57:27
in June last year all the way to November and unfortunately we lost uh
57:33
Mox on this road but we were re reading research paper research paper research
57:40
paper but it's like some of those are like in the 250 and it's like the the capitals are like this big you know um
57:47
and we have rooted all our recommendations and our actionable
57:54
recommendation in actionable research. So like why are we measuring
58:00
why why are we so much into direct compensation? I know you guys like oh yeah they you guys could do some job you
58:06
know but uh couldn't but actually it's rooted in uh uh OSC observer report uh
58:14
which is like a handbook for election observers like when they look into governances around the world how they
58:21
are performing elections if the organization is not funded
58:27
is not fair it's not equal um to participants and it doesn't represent
58:32
the will of the people I ordered like so that's how we have rooted like the silos
58:38
in a report but you can follow that from all beginning to the end you know this kind of of a discussion
58:45
that you're touching on now contrasts with some discussions that you've had here that are more technical and
58:52
parameters and etc and although you've put out a number like when I ask you now
58:57
what's the followup of this you've pointed at very concrete things you we want to do this, we want to do that. But
59:05
what I feel is appalling in the ecosystem is that we
59:11
don't have governance tooling builders being funded. Not even the official incumbents, let's say, which in my
59:17
opinion never did that amazing job. They created the infrastructure that that
59:23
yeah, that is granted. But uh other gov tools like when I wanted to register to
59:29
vote I went and used uh tempo you know and I did it like that. So how much did
59:35
tempo get awarded like we've now gotten to two years 700 million ADA how much
59:41
did the gov tool builders like tempo get you know it's like I don't know that
59:47
doesn't make sense. So that's one thing that I feel should be nurtured nurtured
59:52
and the the other thing is what I'm doing with my initiative like governance uh and funding calls in in by or
59:59
facilitated by myself um you guys have been doing this I would hope that you
1:00:04
guys still do that even aside from intersect working groups and and committees uh and I feel like the
Closing
1:00:11
because what you were touching on now that's governance education like we have agora we all these like governance
1:00:19
literacy basic things and we should have people in the ecosystem funded to
1:00:25
nurture that and to continue making Cardano into a network state like I mentioned into your uh in your on your
1:00:32
call like three days ago. uh people need to be motivated to participate because
1:00:38
of their they see this as a a journey into creating Cardano as a
1:00:44
network state type of thing and they need to be civic in and caring not just
1:00:50
delegating uh but also keeping their DREAP in check you know we can I could
1:00:56
go on and on but so I'm going to continue as much as I can to host these
1:01:02
open government and funding calls Uh it's very very tricky because I'm I was tweeting the other day I'm delivering
1:01:08
catalyst proposals that are overdue and that were funded for ADA at 50 cents. So
1:01:15
I'm having trouble even delivering that those. So my time is very very scarce and like I can drop it on the chat. I
1:01:22
spent 20 minutes on Monday interviewing Sirurin who's doing a number of work for
1:01:28
SPO incentives mainly. Um, and what I feel like it's you mentioned like people
1:01:33
just yapping on calls and that's not offensive. I find it funny but it's when
1:01:39
you guys meet with Sir Curran when Sir Curran meets with me when we continue doing this work that also although it's
1:01:45
just people networking and in fact for example I'm not doing anything in concrete I'm just reviewing gov tools
1:01:52
he's doing all that work you guys are doing all the work that you're doing but us having spaces where we know about
1:01:58
each other's work I and and help promote each other which is what I'm doing for him now with tweets and and all that I
1:02:05
think that should be funded somehow and even drawing a parallel with what 45b is
1:02:13
doing it's also not fundable because 45b is onboarding people to web 3 spaces in
1:02:19
and you know workshops and that's not a product so I can't really put in a proposal and ask for a million to spin
1:02:26
up this this um intersect alternative or CF alternative that's not going to on
1:02:31
board NASA but it's going to on board small and medium businesses It's tricky, you know, and and you know, sorry, I'm
1:02:38
I'm rambling a bit, but I feel like we should find ways, although it's not
1:02:44
direct funding proposals, that someone else that already got these 700
1:02:50
million ADA can subsidize, donate to these this cause, let's say, uh,
1:02:56
somehow. So, yeah, that's another thing that I've been exploring, ideating
1:03:01
around a lot. Why should we all need to go to the treasury and get millions? Why, if this
1:03:09
is something that's as transversal to the ecosystem, why shouldn't the founding entities and everyone else just
1:03:15
donate a,000, 10,000, 100,000 ADA to someone running this instead of having
1:03:23
to go to the treasury? So, I don't know. Thanks for listening and and I hope that
1:03:28
that helps you, motivates you guys to also continue networking and finding ways to work on this because otherwise
1:03:36
I feel like we continue to have a fair amount like provable amount of grifters
1:03:42
out there getting literally millions and yeah, we need to to find ways that that
1:03:48
doesn't make us become the next polka dot or or whatever. Cheers guys.
1:03:54
Okay, guys. Uh thank you so much uh Simon, Lucas,
1:04:00
Linda and Hicks and all the other guys who have participated in this um
1:04:07
in this uh workshop session. Um it's is good to see that we actually
1:04:14
align uh very much uh on where we want to go. That is actually very
1:04:21
very impressing uh to be honest. Everybody wants to go in that direction. So you might not have the exact path uh
1:04:27
but contribution in workshops like this you certainly are doing an impact and as
1:04:33
I said for um beyond uh minimum governance and state of report uh there
1:04:40
will be actionable items that you will feel and see uh on on shame on ledger
1:04:47
and um uh we have some really really solid uh arguments uh on how to for
1:04:54
example I know Simon is working on uh compensation schemes uh in the ecosystem
1:05:00
for dref and CC members. Um we have some tweaks that needs to be done to the
1:05:05
ledger in to prevent the d concentration fix here like uh also align a lot with
1:05:13
what we have like if you have like a k parameter or like a cap for
1:05:18
that's also very much within that makes uh governance on cardano representative
1:05:25
and actually represent uh the owners um uh on what they want. So we just need to
1:05:32
remove frictions block by block. Thank you.
1:05:38
Thanks guys. Ready? Bye.
