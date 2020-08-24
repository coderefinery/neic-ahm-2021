class: center, middle, inverse

# How to scale up your online workshop to reach 100 learners?

### Naoe Tatara, Radovan Bast, Richard Darst, Anne Fouilloux, Petri Jehkonen, Matúš Kalaš, Samantha Wittke

<!-- briefly introduce authors and say who is presenting -->

---

## Introduction to the session
<!-- Naoe -->

- Carpentries Code of Conduct
- House keeping
 - Questions about the contents -> HackMD
 - Questions about technical stuff -> Zoom Chat
- Contents
 - What is CodeRefinery? (5 minutes)
 - A vision of reaching many people at once (with BR session; 15 minutes)
 - How we did it (20 minutes)
 - Role presentation (20 minutes)
 - Future outlook and discussion (10 minutes)

---

## CodeRefinery: project and funding

<!-- RB, 5 minutes, 3 slides -->

(Radovan will add logo and/or map)

- Funded 2016-2021 by [Nordic e-Infrastructure Collaboration (NeIC)](https://neic.no/)
- Co-funding by Sigma2 (Norway), SNIC (Sweden), DeiC (Denmark), CSC (Finland), ETAIS (Estonia)
- Important hubs: NTNU Trondheim, University of Oslo, KTH Stockholm, Aalto University
- Trained over 700 learners [in over 30 workshops](https://coderefinery.org/workshops/past/)

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

## CodeRefinery: relation to Carpentries

- Using Carpentries teaching style and format
- Co-funding Carpentries coordinator Nordics/Baltics
- Lessons are not yet in the Carpentries incubator


### Questions to the audience

- Is there a need for more intermediate/advanced Carpentries-style material for
  learners who have completed a basic Carpentries training?
- What topics/courses are needed?

*Please answer via HackMD*

---

## A vision of reaching many people at once

<!-- RD -->

![The first idea... accept everyone, stream for everyone else](img/inspiration-1.png)

--

![A bit later... crazy but genius](img/inspiration-2.png)

---

## A vision of reaching many people at once

<!-- RD drafts this, 2+10+3 minutes -->

- Our previous workshops weren't very large
- The promise of technology is to be able to reach huge numbers of
  people at once.  But is that too impersonal?
- Surely we must be able to get the best of best worlds...
- With a consistent vision, yes, you can reach many people.  But it
  requires that vision from the start, and everything supporting that
  value.


### Questions to the audience

- How can large be more inclusive?  How is it less?
- What technical obstacles does it have?

10 minutes to discuss in breakout rooms, summarize here after.

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

## Lectures & code-along exercises in the main room
<!-- Anne -->
- Short lectures to explain a concept and "asynchronous Q&A" in main room
- Demonstrate it on a very short example (and often repeat explanation)
- Exercises more in the breakout rooms among groups
- Check understanding:
	- surveys with simple (yes/no) questions
	- check speed with faster/slower buttons
	- ask a question and learners write down answers in hackMD
	- ask learners to contribute to discussion via hackMD
- Sometimes make a code-along exercise and always repeat similar exercise in breakout rooms


*Move on when about 70% have answered so delegate potential misunderstanding to helpers during group exercises.
*
---

## Get help and group exercises in a breakout room

- Apply concepts previously taught to check understanding
- Helpers often "taught" again to clarify concept
- pre-defined and fixed breakout rooms with 3 to 10 people in each:
	- larger groups were allowed when learners registered together
	- helpers played a key role to animate the group
	- encouraged one learner to share his/her screen during the exercise

*First day was a bit quiet, especially in groups where learners did not know each others.
*
---

## Bring your own breakout room

- Learners could register as a team (3-10 persons) with a designated helper:
	- Registration form included a “team name”
	- Personalized emails with room numbers
	- Zoom name = “(5) Richard Darst” or “(5,H) Richard Darst”

- The designated helper was very often someone who already attended a CodeRefinery in-person workshop or someone in charge of technical support for the team

*This is how we effectively scaled...*

---

## Helper training

<!-- RB, 2 minutes -->

One week before the workshop:
- Discuss [Tips for helpers](https://coderefinery.github.io/manuals/helping-and-teaching/)
  and [How helpers manage breakout rooms](https://coderefinery.github.io/manuals/breakout-rooms-helping/)
- Course schedule walk-through with instructors and organizers
- Exercise/breakout-room walk-through (**we need to do this better next time**)


### Hierarchical helpers

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
---

## Required preparation, install times

<!-- RD drafts this, 2 minutes -->

- With 100 people, there is very little tolerance for technical
  problems.
- Huge emphasis: install and *test* software before, said in every email.
- Two pre-workshop "verification times", request that everyone attends
  (if half do, it's good enough)
- In the verification time, we would pair learners with helpers and
  have them test git and Python (not just install, but settings).
- Verification times also let us practice with the tech with helpers in advance.
<!-- refer notes https://hackmd.io/xuIr733fROuIpwQ1g2mkOw?view "install verification time" -->

---

## Collaborative notes
<!-- Naoe -->
- Use of HackMD for collection of Q&A regarding lesson contents
<ul style="list-style-type:' \002B \0020 \0020'">
  <li> Instructor -> Learners AND Learners -> Instructors
  <li> A dedicated person answered to questions raised in HackMD (HackMD specialist).
  <li> Time schedule can be kept as an instructor can focus on the lecture and live coding.</li>
  <li> Cleaned and published copy was useful to helpers and learnes afterwards.</li>
  <li> Stable most of the time with 50-100 users (depending on the edit history length).</li>
</ul>
<ul style="list-style-type:' \0021 \0020 \0020'">
  <li> Need to be careful to not overload the side channel with answers
</ul>
- For short communications for more practical questions, we used Zoom chat function.

---

## Distribution of roles

<img src="img/CC_role_distribution_illustration_HackMDspecialist.png" alt="a schematic illustration to show flexible assignment of roles of instructor and expert helper" width="100%" />

---

## Zoom room use for pre- and post-session

<!-- Naoe? -->
- We opened the Zoom room 30 minutes before the scheduled session start.
- After the scheduled session is over, we kept the Zoom room open for;
	- Debriefing among helpers and instructors,
	- Individual help by helper or expert helper,
	- Continuation of exercise by a team

---

## Streaming and recording

<!-- RD drafts this, 2 minutes -->

- If we have 100 people, interaction shifts to breakout rooms.  Why
  can't more watch the lecture?
- Zoom meetings are *not* the right format for untrusted people to watch.
- Streaming is the right format: listeners isolated from presenters,
  no risk of damage.
- Zoom can stream directly to Twitch (or other services) without any
  other software needed.
- We interacted with Twitch viewers via Twitch chat + hackmd.  It
  worked fairly well.


---

class: center, middle, inverse

# Role presentations

<!--NT will moderate this session, 20 minutes　-->

<!-- - They should: say what the role is, why the role is important, say what -->
<!--   you thought, what went well, what should be improved.  Please also check -->
<!--   what the other roles are, so that you can focus on what makes your role -->
<!--   special -->
<!--     - one slide per role -->
<!--     - Naoe starts this session by giving word to the speakers -->

---

## Learner

- Backround
- Expectation
- Arrangements:  Pre-workshop, Materials, learning tools, support organization
- Challenges
- Overall feedback
- Outcome

...

---

## Helper

<!--Matúš, 2 minutes-->

![swi](img/mk_transparent_crop_small.png)

<!-- If you're asking whether you can be a helper, you most likely can! -->
- assigned a **breakout room**  <!-- Semi-stable breakout room assignment, with minimum changes of the "assigned" learners -->
- leads exercise work in their room, or just **helps the learners** therein and answers their questions  <!-- incl. indexing where we are / what we are doing, asking how it goes, etc. -->  <!-- "My" learners mostly preferred to work alone first & then ask questions if needed. Occasionally someone sharing their screen -->
- **forwards** interesting questions and difficult problems to HackMD or expert helpers
- depending on confidence with the exercises, needs only **minimum preparation** (so awesome that CR folks prepared everything so well!)  <!-- Preparation as a helper recommended, but most of the time (would have) worked also without. I skipped preparation in one exercise (about what I do every day), and I managed to mess it up quite a bit :DD  All other exercises were smooth though. -->
- if 2 screens or fast in switching, a helper may help **answering** in HackMD and Zoom chat (there are also optional advanced exercises in CR, and advanced topics to discuss in HackMD)  <!-- If without an extra screen (recommended but not mandatory), I personally wouldn't have been able to follow hackMD, and chat also not so much. But the helper work would still function just fine. -->
- **learns** a lot, feels useful, and has a lot of **fun** ;D  <!-- Much more fun to go through the teaching material as a helper than just following it alone (and to experience the whole workshop in its interactivity and excitement!) -->
<!-- Some improvement possibilities:
	- more explicit about suggested layouts of screen(s) for learners, possibly specific to a given lecture or exercise (also presenters taking that into account for their screen)
	- more explicit when & what helpers should prepare
-->

---

## Learner/helper on a team

![swi](img/samantha.jpg)

&nbsp;

- **helper in team** from Finnish Geospatial Research Institute
- myself: in-person workshop **learner one year ago**
- **lower barrier** to interact/ask questions
- explaining topics **work-related**
- **easy to get lost** in course-unrelated topics


---

## Expert helper

![swi](img/radovan-bast.jpg "Radovan Bast")

- Expert helper knows the material well
- Cycles through breakout rooms to see how it is going
  - Ensure helpers are doing OK
  - Encourage discussion
  - Encourage learners to share screen in breakout rooms
  - Provide advice when needed
- Helper can call other helpers via HackMD/chat

---

## Instructor

### Who am I?

<img src="img/mega-cr-instructor.png" width="40%" />

### How was it to teach Mega-CR online?

- Taught from home with one screen (laptop)
- Less pressure and easier to focus on the teaching thanks to CR team work (host, helpers, hackMD, etc.)
- Need to have short assessments (surveys, questionnaires, etc.) frequently
- Code-along sessions were sometimes too fast for many learners and often became demos
- Useful to be instructor and expert helper during the workshop

---

## Host
<!-- Naoe -->
![swi](img/naoe_tatara.jpg "Naoe Tatara")
- Dedicated for Zoom room management.
	- Zoom-participant control <!-- entry approval and co-host assignment -->
	- Communication with participants <!-- mainly via Zoom chat for practical things -->
	- Breakout room management <!-- assignment, timing, disabling/enabling waiting room -->
	- Recording and making sure streaming goes fine 
- Keep consistency with team combination throughout the workshop
- If a helper of a team is absent, 2 (or 3 ) teams are merged into 1 room
- Important to pay attention to multiple communication channel

---

## HackMD specialist

<!-- RD, 2 minutes -->

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
  - Add links and "meta-information" about where we are.
  - Ensures consistent formatting, prepares it for publication

---

class: center, middle, inverse

## Future outlook and Q&A session

---

## Future outlook and Q&A session

<!-- RB, 10 minutes, q&a and "discussion" via hackmd -->

- Continue with online workshops - this is not replacement to
  in-person workshops but better in some ways
- Do larger online-workshops and streaming work for all audience types?
  (diversity, tech background, network bandwidth)
- Encourage and accept lurkers more (better experience when streaming).
- How to encourage participation and protect privacy while streaming/recording?
- How can we make a federated model via the stream? We don't know yet.
