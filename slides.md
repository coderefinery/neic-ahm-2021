class: center, middle, inverse

<img src="img/logo.png" alt="CodeRefinery logo" style="width:30%">

# An online workshop about organizing online workshops

### Radovan Bast, Richard Darst, Anne Fouilloux

<!-- briefly introduce authors and say who is presenting -->

---

## We will talk about lessons learned from teaching a number of online workshops

- [Blog post](https://coderefinery.org/blog/2020/07/31/mega-coderefinery/)
- [Presentation at CarpentryCon 2020](https://2020.carpentrycon.org/schedule/#session-32)
- [Slides of the CarpentryCon 2020 talk](https://cicero.xyz/v3/remark/0.14.0/github.com/coderefinery/carpentrycon-2020/master/slides.md/)


## Presenters at CarpentryCon 2020

<img src="img/naoe_tatara.jpg" class="round-smaller">
<img src="https://eu.ui-avatars.com/api/?name=R+D" class="round-smaller">
<img src="img/af.png" class="round-smaller">
<img src="img/petri.jpg" class="round-smaller">
<img src="img/mk_transparent_crop_small.png" class="round-smaller">
<img src="img/samantha.jpg" class="round-smaller">
<img src="img/radovan-bast.jpg" class="round-smaller">

---

## Introduction to the session

### House keeping
 - Questions about the contents -> HackMD
 - Questions about technical stuff -> Zoom Chat

### Contents (20 min)
 - What is CodeRefinery?
 - A vision of reaching many people at once
 - How we did it
 - Role presentations
 - Future outlook and discussion

---

## CodeRefinery: project and funding

- Funded 2016-2021 by [Nordic e-Infrastructure Collaboration (NeIC)](https://neic.no/)
- Co-funding by Sigma2 (Norway), SNIC (Sweden), DeiC (Denmark), CSC (Finland), ETAIS (Estonia)
- Important hubs: NTNU Trondheim, University of Oslo, KTH Stockholm, Aalto University
- Trained over 700 learners [in over 30 workshops](https://coderefinery.org/workshops/past/)

<img src="img/map.png" alt="Map of workshops" style="width:30%">

---

## CodeRefinery: audience and lessons

Our **learners are not pure beginners**, they already develop code but want to
become better at **collaboration and reproducibility**


### Typical workshop

- Introduction to version control
- Collaborative distributed version control
- Reproducible research and FAIR data
- Social coding and open software
- Documentation
- Jupyter
- Automated testing
- Modular code development


### More lessons

https://coderefinery.org/lessons/

---

## A vision of reaching many people at once

<!-- RD -->

![The first idea... accept everyone, stream for everyone else](img/inspiration-1.png)

--

![A bit later... crazy but genius](img/inspiration-2.png)

---

## A vision of reaching many people at once

<!-- RD drafts this, 2+10+3 minutes -->

- Our previous workshops were in-person and not very large (~25 learners)
- The promise of technology is to be able to reach huge numbers of
  people at once.  But is that too impersonal?
- Surely we must be able to get the best of best worlds...
- With a consistent vision, yes, you can reach many people.  But it
  requires that vision from the start, and everything supporting that
  value.


### Questions to the audience

- How can large be more inclusive?  How is it less?
- What technical obstacles does it have?

*10 minutes to discuss in breakout rooms, summarize here after. Please
write answers in HackMD.*

<!--
- Why you need a vision (Mega-Coderefinery vs HPC kickstart)
- You can get even *more* out of it
- Question to audience via breakout room, answers in HackMD:
  - How can large be more inclusive?  How is it less?
  - What technical obstacles does it have?
- Do we discuss results in main room?
-->

---

class: center, middle, inverse

# How we did it

### Lectures & code-along exercises in the main room

### Get help and group exercises in a breakout room

### Bring your own breakout room

## An effective team work!

---

## Main room: Lectures & code-along exercises
<!-- Anne -->
- Short lectures to explain a concept, and "asynchronous Q&A" in the main room
- Demonstrate it on a very short example (and often repeat explanation)
- Exercises more in the breakout rooms among groups
- Check understanding:
	- surveys with simple (yes/no) questions
	- check speed with faster/slower buttons
	- ask a question and learners write down answers in HackMD
	- ask learners to contribute to discussion via HackMD
- Sometimes make a code-along exercise and always repeat similar exercise in breakout rooms

*Move on when about 70% have answered, so delegate potential misunderstanding to helpers during group exercises.*

---

## Breakout rooms: Get help and group exercises

- Apply concepts previously taught to check understanding
- Helpers often "taught" again to clarify concept
- Pre-defined and fixed breakout rooms with 3 to 10 people in each:
	- larger groups were allowed when learners registered together
	- helpers played a key role to animate the group
	- encouraged one learner to share his/her screen during the exercise

*First day was a bit quiet, especially in groups where learners did not know each others.*

---

## Bring your own breakout room

- Learners could register as a team (3-10 persons) with a designated helper:
	- Registration form included a “team name”
	- Personalized emails with room numbers
	- Zoom name = “(5) Richard Darst” or “(5,H) Richard Darst”

- The designated helper was very often someone who already attended a CodeRefinery in-person workshop, or someone in charge of technical support for the team

*This is how we effectively scaled...*

---

## Helper training

<!-- RB, 2 minutes -->

One week before the workshop:
- Discuss [Tips for helpers](https://coderefinery.github.io/manuals/helping-and-teaching/)
  and [How helpers manage breakout rooms](https://coderefinery.github.io/manuals/breakout-rooms-helping/)
- Course schedule walk-through with instructors and organizers
- Exercise/breakout-room walk-through (**we need to do this better next time**)

*This is how we get new people involved in the project: next
generation of instructors?*

---

## Hierarchical helpers

.left-column[
- Helpers
  - They don't have to know "everything"
  - They can call in other helpers
- Expert helpers (more about this role later)
  - They support helpers
  - They cycle between breakout rooms]

.right-column[
<img src="img/CC_hierarchical_helpers_illustration.png" alt="Expert helpers cycle between breakout rooms while helpers are assigned to one specific breakout room" style="width:100%">

]

*This is how we could take advantage of new helpers without worrying
too much.*

---

## Required preparation, install times

<!-- RD drafts this, 2 minutes -->

- With 100 people, there is very little tolerance for technical
  problems.
- Huge emphasis: install and *test* software before, written in every
  email.
  - Very thorough setup instructions + university-specific instructions.
  - Made three videos about git configuration, plus "shell crash
    course" ([link](https://coderefinery.github.io/2020-05-25-online/#prerequisites))
- Two pre-workshop "verification times", request that everyone attends.
  - In the verification time, we would pair learners with helpers and
	have them test git and Python (not just install, but settings).
  - Verification times also serve as a "soft start" to practice tech
    early.
  - Credit to [Jason Bell](https://youtu.be/MzsJyOkxqv8) for the idea.
- In the end, we did not have major problems.
<!-- refer notes https://hackmd.io/xuIr733fROuIpwQ1g2mkOw?view "install verification time" -->

<img src="img/config-videos.png" alt="configuration videos" style="width: 40%;">

---

## Collaborative notes
<!-- Naoe -->
- Use of HackMD for collection of Q&A regarding lesson contents
<ul style="list-style-type:' \002B \0020 \0020'">
  <li> Interactive questions and answer (among learners and instructors).
  <li> Index where we are right now, links to lessons.
  <li> Safer way to ask questions anonymously.
  <li> Easier to ask questions in an open landscape office.
  <li> A dedicated person answered to questions raised in HackMD (HackMD host).
  <li> Time schedule can be kept as an instructor can focus on the lecture and live coding.</li>
  <li> Cleaned and published copy was useful to helpers and learners afterwards.</li>
  <li> Stable most of the time with 50-100 users (depending on the edit history length).</li>
</ul>
<ul style="list-style-type:' \0021 \0020 \0020'">
  <li> Need to be careful to not overload the side channel with answers
</ul>
- For short communications for more practical questions, we used Zoom chat function.

---

## Distribution of roles
<!-- Naoe -->
<img src="img/CC_role_distribution_illustration_HackMDhost.png" alt="a schematic illustration to show flexible assignment of roles of instructor and expert helper" width="100%" />

---

## Zoom room use for pre- and post-session
<!-- Naoe -->
- We opened the Zoom room 30 minutes before the scheduled session
  start.
  - Icebreaker starts 10 minutes early, ask people to come early
  - Also extra install help and discussion
- After the scheduled session is over, we kept the Zoom room open for;
	- Debriefing among helpers and instructors,
	- Individual help by helper or expert helper,
	- Continuation of exercise by a team

*This promoted community and let us more actively recruit for the next
generation of workshops.*

---

## Streaming and recording (1/2)

<!-- RD drafts this, 2 minutes -->

- If we have 100 people, interaction shifts to breakout rooms.  Why
  can't more watch the lecture?
  - Zoom meetings are *not* the right format for untrusted people to watch.
  - Streaming is the right format: listeners isolated from presenters,
	no risk of damage.
- Zoom can stream directly to [Twitch](https://twitch.tv) (or other services) without any
  other software needed.
- It's a short step to recording
  - Recordings were very requested by learners, so they could re-watch
    what they learned.

---

## Streaming and recording (2/2)

- [Twitch](https://twitch.tv) is a streaming platform originally focused on games, we
  knew it and it worked well.
- We interacted with Twitch viewers via Twitch chat + HackMD.  It
  worked fairly well.
- We should have had less separation between zoomers and streamers,
  and generally engaged the streamers more

<img src="img/twitch.png" alt="Twitch screenshot" style="width:60%">

---

class: center, middle, inverse

# Role presentations

### 1. Learner
### 2. Helper
### 3. Helper on a team
### 4. Expert helper
### 5. Instructor
### 6. Zoom host
### 7. HackMD host

<!--NT will moderate this session, 20 minutes　-->

<!-- - They should: say what the role is, why the role is important, say what -->
<!--   you thought, what went well, what should be improved.  Please also check -->
<!--   what the other roles are, so that you can focus on what makes your role -->
<!--   special -->
<!--     - one slide per role -->
<!--     - Naoe starts this session by giving word to the speakers -->

---

## Learner

<!--Petri, 2 minutes-->

.left-column-70[
- Petri Jehkonen, **learner**, Master student at Aalto University
- Background - SW (C, Assembly) for embedded solutions
- Expectation - Git (only)
- Workshop arrangements from beginning to end were well managed
- Challenges for learner
- Outcome - Much more than Git
]

.right-column-30[
<img src="img/petri.jpg" class="round">
]

---

## Helper

<!--Matúš, 2 minutes-->

.left-column-70[
- Matúš Kalaš, University of Bergen (Norway)
<!-- If you're asking whether you can be a helper, you most likely can! -->
- Assigned a **breakout room**
<!-- Semi-stable breakout room assignment, with minimum changes of the "assigned" learners -->
- Leads exercise work in their room, or just **helps the learners** therein and answers their questions
<!-- incl. indexing where we are / what we are doing, asking how it goes, etc. -->
<!-- "My" learners mostly preferred to work alone first & then ask questions if needed. Occasionally someone sharing their screen -->
- **Forwards** interesting questions and difficult problems to HackMD or expert helpers
- Depending on confidence with the exercises, needs only **minimum preparation** <br/><small>(So awesome that instructors prepared everything so well!)</small>
<!-- Preparation as a helper recommended, but most of the time (would have) worked also without. I skipped preparation in one exercise (about what I do every day), and I managed to mess it up quite a bit :DD  All other exercises were smooth though. -->
- If 2 screens or fast in switching, a helper may help **answering** in HackMD and Zoom chat <br/><small>(There are also optional advanced exercises, and <br/>advanced topics to discuss in HackMD)</small>
<!-- If without an extra screen (recommended but not mandatory), I personally wouldn't have been able to follow hackMD, and chat also not so much. But the helper work would still function just fine. -->
- **Learns** a lot, feels useful, and has a lot of **fun** ;D
<!-- Much more fun to go through the teaching material as a helper than just following it alone (and to experience the whole workshop in its interactivity and excitement!) -->
<!-- Some improvement possibilities:
	- more explicit about suggested layouts of screen(s) for learners, possibly specific to a given lecture or exercise (also presenters taking that into account for their screen)
	- more explicit when & what helpers should prepare
-->
]

.right-column-30[
<img src="img/mk_transparent_crop_small.png" class="round">
]

---

## Learner / Helper on a team

.left-column-70[
- Samantha Wittke, PhD student at Aalto University and Researcher at Finnish Geospatial Research Institute (FGI)
- **Helper on a team** from FGI
- Myself: in-person workshop **learner one year ago**
- **Lower barrier** to interact/ask questions
- Explaining topics **work-related**
- **Easy to get lost** in course-unrelated topics
]

.right-column-30[
<img src="img/samantha.jpg" class="round">
]

---

## Expert helper

.left-column-70[
- Radovan Bast, University of Tromsø (Norway)
- Expert helper knows the material well
- Cycles through breakout rooms to see how it is going
  - Ensure helpers are doing OK
  - Encourage discussion
  - Encourage learners to share screen in breakout rooms
  - Provide advice when needed
- Helper can call other helpers via HackMD/chat
]

.right-column-30[
<img src="img/radovan-bast.jpg" class="round">
]

---

## Instructor

.left-column-70[
- Anne Fouilloux, Research Software Engineer at the department of Geosciences, Oslo University (Norway)
- Taught from home with one screen (laptop)
- Less pressure and easier to focus on the teaching thanks to CR team work (host, helpers, hackMD, etc.)
- Need to have short assessments (surveys, questionnaires, etc.) frequently
- Code-along sessions were sometimes too fast for many learners and often became demos
- Useful to be instructor and expert helper during the workshop
]

.right-column-30[
<img src="img/af.png" class="round">
]

---

## Zoom host
<!-- Naoe -->

.left-column-70[
- Naoe Tatara, University of Oslo Science Library, Digital Scholarship Center
- Dedicated for Zoom room management, including recording and streaming
	- Zoom-participant control <!-- entry approval and co-host assignment -->
	- Communication with participants <!-- mainly via Zoom chat for practical things -->
	- Breakout room management <!-- assignment, timing, disabling/enabling waiting room, flexibility and consistency -->
- Important to pay attention to multiple communication channels
- Details on [our blog post](https://coderefinery.org/blog/2020/07/31/mega-coderefinery/)
]

.right-column-30[
<img src="img/naoe_tatara.jpg" class="round">
]

---

## HackMD host

<!-- RD, 2 minutes -->

- Richard Darst, Aalto Scientific Computing, Aalto University (Finland)
- This role focuses on watching the HackMD and answering questions
  there.
  - This requires a different type of attention than paying attention to
    lessons, so we have a dedicated role for this.
  - Everyone can help with answering questions, but at least one person
    always dedicated to it.
- Typical tasks
  - Answer questions
  - Bring up important questions to the instructor
  - Organize/comment on complicated answers
  - Add links and "meta-information" about where we are
  - Ensures consistent formatting, prepares it for publication

---

class: center, middle, inverse

## Future outlook and Q&A session

---

## Future outlook and Q&A session

<!-- RB, 10 minutes, q&a and "discussion" via hackmd -->

- Continue with online workshops - not replacement to
  in-person workshops but complementary.
- Advantages: more reach, cheaper to participate, possible to
  involve remote helpers.
- Do larger online-workshops and streaming work for all audience types?
  (diversity, tech background, network bandwidth)
- Encourage and accept observers/[lurkers](https://en.wikipedia.org/wiki/Lurker)
  more (better experience when streaming).
- How to encourage participation and protect privacy while streaming/recording?
- How can we make a federated model via the stream? We don't know yet.

### Join us: [coderefinery.org](https://coderefinery.org/), [@coderefine](https://twitter.com/coderefine), [coderefinery.zulipchat.com](https://coderefinery.zulipchat.com/)
