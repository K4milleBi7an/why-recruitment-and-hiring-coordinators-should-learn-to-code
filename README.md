# why-recruitment-and-hiring-coordinators-should-learn-to-code
why-recruitment-and-hiring-coordinators-should-learn-to-code

#this is a work-in-progress blog

# Why recruitment coordinators should learn to code

*The Recruiter's Commit History · Part one*

Nov 3, 2026 · @Kamille

It kicks off with a green boot screen in my parents' shop, runs through six years of rather untidy commits and ends up somewhere I didn't anticipate at all: wanting to spend the rest of my career working on the security of the hiring and onboarding process. Here's the whole line including the bits that don't really flatter me.

*Kamille — Talent Acquisition & People Ops, 8 years in fintech and tech recruitment. Registered ISPr with APSO. BCom Honours in HRM. Founder of Notion Nakama (HR systems and POPIA compliant process consultancy).*

Written for the recruitment interns and junior coordinators: the people who deal with the most candidate data in a hiring team and who are taught absolutely the least about it.

## A green screen in a retail shop

My parents ran a retail shop and there was a work PC in there. I can't tell you what version of Windows it was. All I remember is that when it booted up the screen was green and you just had to type words to get anything to happen.

That's the very first text I ever sent to a computer. Not code. Just words, into a machine that was sitting there waiting to be told what I wanted.

I played Invaders on it. Ping Pong. Some game which involved a cow which I have never been able to work out what it was since and may well be misremembering.

I grew up around computers and have always got on with them much better than with most people. I'm not suggesting that's a boast or a complaint, it's just the way it was.

What they mostly did for me was travel. A PC was the way I got around and once I had the internet it was the way I got to virtually anywhere. The internet was capped and very expensive so I worked out a way of having an effectively uncapped account every other month. I'm not going to explain how (it wouldn't work now anyway and I'm not sure it was even permitted at the time).

But look at what that was. A system with a rule in it and a teenager who wanted to find out how the rule actually worked rather than just take on board what it said on the box. I didn't consider that to be technical at the time. I thought of it as just getting online.

Hold on to that sentence. It comes back at the end of the post with a job title on it.

## The resident troubleshooter

Here's the bit I've had to wrestle with the most.

We grew up in a house where being the one who was good with technology didn't in any way make you a person who might go on to build things. It made you the in-house troubleshooter. The printer, the router, the thing your aunt did to her laptop. You were the one who fixed it. Being good at fixing it was the end of the line.

Nobody (not even I) ever asked whether the individual who could fix it might in fact be the one who'd want to build one.

Then at school there was a lad who was actually paying his full school fees via coding work for US businesses. I need to be absolutely clear about the impact of that: it completely changed my perception of what was possible. A kid my age, in my country, in my school, getting paid real money by people on the other side of the world for doing work on a computer.

It changed what I wanted and it didn't change what I did. I had decided at some point that I wasn't good at maths, or logic or problem solving. So I didn't go and study that at all and I didn't go in for a career in it.

I'd just like to highlight the two things that are side by side in that sentence. I thought I was a terrible problem solver. I was also the person that everyone in the house would bring their problems to.

Nobody corrected it. I wasn't looking.

What actually happened was that I went into HR and within about 10 minutes of every job I'd had I'd become the systems person. The one who knew the applicant tracking system inside out. The one who could work out why the integration had stopped. The tech person for the team again by default, exactly as at home. I've worked on Mac, Linux and Windows and I do have a preference, which is entirely dependent on what I'm doing that day.

The troubleshooting was never in doubt. The only thing missing was the notion that I was entitled to go the other way with it.

I did keep taking the opportunities that came my way. Any training a job would have paid for, any certification you could go for, anything to do with systems. That habit was never the issue because it simply didn't point to this. I'd never put this on the list of things I was allowed to want.

I did my very first `Hello, World` in 2019/2020 via The Odin Project, at about thirty years of age having been technical all my life.

## What that produced: three files

Six years on from that I actually opened up my own GitHub account and had a proper look at it (I'd never really done that before). 47 repositories. Most of them were just stopped rather than finished. In one of them there were three files sitting side by side:

| File | What it is |
| --- | --- |
| `metrics2.rb` | 26 lines. Calculates time to fill, time to hire, time to alignment and cost of hire. The dates are entered at the foot of the file. |
| `metrics3.rb` | 70 lines. Same sums, but now it's asking you for the dates and it checks what you've typed. |
| `metrics4.rb` | 56 lines. Adds a budget check. Also contains the line `# ... existing code for getting date input ...` where the checking used to be. |

Three copies of one script, saved as three separate files, in a repository concerned with measurement. That's precisely the sort of thing version control is designed to stop. I was using version control at that stage. Four commits over the course of four months, one of them being the initial commit, and that one also included the readme file.

Now look at the third one. Date checking was present in `metrics3.rb`. In the next version I simply replaced it with a comment saying what it had been. The latest one is the broken one.

I can only see that because I've kept all three. If I'd been any more tidy there would be one file, it would be incorrect and no-one would know.

Consider what that means. The neater version of me knows less.

This is why I'm doing it in the open. Not to appear competent. A history I can't just quietly clean up is the only history that can set me right.

## The first useful thing

The GitHub account opens in July 2020 with two repos called `git_test` and `git_te`. That's it really. Then some coursework via Zaio and The Odin Project: a tutorial video platform, then a second one, then a third go at the same one. Recipe pages. Ruby exercises. I was good at getting things started and terrible at finishing them, and none of that was actually the work I was paid to do.

January 2024 is when that changed. I opened a file and started writing a cost of hire calculator as I'd worked that figure out by hand so many times I was sick of it.

It became a little Sinatra app called `recruitment_calculator`. You put in a requisition date, a hire date, a start date, recruitment fees, advertising costs, a salary and an equity %, and it checks that all the fields are there, parses the dates (rejects any that aren't dates), gives you the time to hire and a cost of hire calculated on a 250 day year.

It wasn't clever at all. It was the very first thing I'd actually made that was of any use and it did a calculation that nothing I had access to would have been able to do for me.

In May I built a second one: an HR metrics dashboard, again in Ruby and Sinatra with numbers flowing into a chart. All the standard KPIs: time to hire, cost per hire, time to close, time to alignment, each against a target. The data came from `faker` and a mock CSV of made up job titles. Human Farming Analyst is in there. Nothing in that repo is a real person.

I didn't give that the slightest thought at the time and that's the bit I'd most like to pass on. Nobody told us to use fake data. There was no policy in place to cover it. I just reached for it, it was the obvious thing to do, roughly two years before I could have possibly told you why.

Both repos are private. They've been private since the day I created them which is why they've taught absolutely nobody anything, not even me.

## Six years, as it went

| When | What | Notes |
| --- | --- | --- |
| 2019–20 | Hello, World (The Odin Project) | First line of code deliberately written, roughly 30 years into a life spent around computers. |
| Jul 2020 | `git_test`, `git_te` (private) | Two repos that exist in order to find out what git is. That's where the record begins. |
| 2023 | Other people's exercises (Zaio, The Odin Project) | Tutorial clones, recipe pages, Ruby drills. Three goes at the same project, which is pretty much a summation of the year. |
| Jan 2024 | `recruitment_calculator` — Ruby, Sinatra (private) | The very first thing I built for the job rather than for a course. |
| May 2024 | HR metrics dashboard — Ruby, Sinatra, Chart.js (private) | Four hiring metrics against targets on faked data. Two commits, the second one an additional commit for Git practise. |
| Oct 2024 | `portfolio_on_rails` — Rails, Hotwire | A complete Rails app: CI, Docker, RuboCop, Stimulus. 142 files, one commit and almost nothing in it that I actually wrote. I generated a skeleton that I still haven't managed to fill out. |
| 2025 | Thirteen months without a commit | Nothing at all between December 2024 and February 2026. Work took the time. That's the period invariably omitted from the typical account of learning to code, and the bit I'd expect the majority of readers to have experienced. |
| Aug 2026 | `easterncape-job-board` — HTML, CSS | A regional job board. First time I'd made a branch and opened a PR rather than just pushing directly to main. A minor bit of discipline, arrived at very late. |
| Oct 2026 | `googleKeepProject` — JavaScript | A notes app, four commits in one morning, each one doing one thing. The first repo whose history is a series of decisions rather than a series of saves. |

The pattern is very clear and it's not a technical issue at all. The two most useful things are private. The most impressive one is actually empty. Nothing I ever produced had a reader, so nothing I produced had any need to be finished.

## Why in public

This is not my method. It's swyx's method — he's a software engineer — and his 2018 essay [Learn in Public](https://swyx.io/learn-in-public) makes the case far better than I can. The problem he identifies is that most of us learn in private, take it all in and produce nothing. The solution is to leave a trail: notes, posts, repositories, whatever. That's what he calls learning exhaust.

> "Make the thing you wish you'd found when you were learning."
>
> "Simply try your best to be right, don't worry if you're wrong."

Two of his points are spot on here. Write for yourself as you were three months ago (for the purposes of this series that means writing for a coordinator who's just been handed an export and told to clean it up). And pick up what the more experienced people put down: take the work they're willing to hand off, because a beginner's attention is worth something to them.

That second one changed the plan for the series, which the section on where it goes makes clear.

## The five skills, in order

Hillel Wayne spent a lot of time talking to people who had moved from civil, mechanical and chemical engineering into software. He was expecting them to tell him that software wasn't real engineering. Most of them said it was. He therefore published the finding against his own initial assumption. The difference between the two, he concluded, was circumstance rather than essence.

That's the point I'm making about you and code, and I have 20 years of evidence for it in the sections above. Nothing about my ability changed from the green screen to Hello World. What changed was that at some point someone told me the door was open, and that someone was a free website.

Here's the situation. Your week is spent being given an export and then having to clean it. You're chasing missing fields, you're merging the duplicate records, you're building the Boolean strings, you're pulling the figures for someone else's report. You have more raw personal data than anyone else in the organisation, you had absolutely no input into which systems the business actually bought, and your induction was on the applicant tracking system rather than the data in it.

The proposal is not that you become a developer. It's actually quite small and more immediately useful: learn enough Ruby to be able to look at the data you already have, understand it, change it safely, get something out of it and protect it properly. That's the order in which it needs to be done.

### 01 See it

Open the export with nothing in between. What a CSV is, what a row and a column actually are, how to read one in a few lines of Ruby. The code is not the point. The point is that the file stops being something you double-click and hope about.

### 02 Understand it

What's in each field, where it came from, what's missing and how much. How many candidates are in there twice. How many dates are in a format which is absolutely nothing that you can read. Which columns contain personal information you hadn't even realised you were holding. A lot of it is just counting, and the counting is where the surprises are.

### 03 Change it safely

Work on a copy. In a kit you dry fit the part before you put any cement on it, as cement is not reversible and dry fitting costs you a minute.

An export is the same. Copy the file, work on the copy and leave the original alone until you're absolutely sure. A small habit. Most of the discipline.

Then: clean it, de-duplicate it, standardise the dates, split the name column which absolutely shouldn't have been a single column. Twenty lines of code you can just re-run next month is infinitely better than an afternoon of careful clicking which you can never re-do.

### 04 Get something out of it

This is the one that actually changes how a team will treat you. Time to fill, time to hire, source effectiveness, where the pipeline actually gets stuck. That's where `metrics2.rb` comes back and is properly re-written. A coordinator who can say "offers are taking eleven days and the delay is sitting with the panel, here is the working" is doing a completely different job to one who simply forwards a spreadsheet.

### 05 Protect it

Nobody teaches this bit really, which is why the series is in existence. Work on copies. Never commit the data itself. Strip the identifiers off before anything ever leaves your machine. Generate fake people when you need to demonstrate the work. Deliberately delete what you no longer need.

POPIA expects an organisation to know what personal information it holds, on what basis and how it is protected. A huge amount of that information exists in the form of exports on the laptops of the very junior people in the team. Nobody ever tells them. Five habits, a few lines of code each, will get you further than any policy document.

That fifth skill is also the one I've absolutely no intention of stopping at, which is precisely what the final section of this post is about.

## Why Ruby

Three reasons actually, in the order they happened rather than the order that sounds rational.

First of all I like Japanese things. Food, films, the language (which I'm slowly learning). Ruby was written by a Japanese programmer called Yukihiro Matsumoto and the whole philosophy behind it was that the language should be pleasant to the programmer rather than convenient to the machine. That was quite enough for me to go with it over Python and I won't pretend that was a more analytical decision than that.

Secondly, the companies I worked for were all built on Rails. There's something very particular about knowing that the applicant tracking system you're using every day and moaning about every day is actually in the language you're learning. It goes from being weather to being a decision that's been made by someone.

Thirdly, and this is the one that actually stands up to scrutiny: Ruby's primary web framework has a design principle which is precisely this scenario. In 2021 the creator of Rails laid out what he called the [one person framework](https://world.hey.com/dhh/the-one-person-framework-711e6318).

> "A toolkit so powerful that it allows a single individual to create modern applications upon which they might build a competitive business."
>
> "Giving the individual rebel a fighting chance against The Empire."

I'm not a rebel and recruitment isn't an empire. The model is the same really: one person in an HR team, no budget line, no engineering support, who just needs a working tool rather than a line in someone's backlog. Rails is the only mainstream framework I'm aware of that actually designs for that person as the intended user rather than treating them as an edge case.

I should be very precise about the tense there. Rails is what I want to be good at. It's not what I am good at, and the 142 file repo with one commit in it is the proof of that.

Rails' creator is also a very controversial figure in that he'll say exactly what he thinks in very large volumes. I find that far easier to learn from than a committee. You always know what the thing believes and what it is arguing against, and you're free to decide that he's wrong on any particular point. That's far more useful to a novice than consensus with the reasoning all filed off.

Python is an equally reasonable option really, has the larger community and the better data tooling, and if it's already in front of you then use it. The thinking is the same either way.

## What already exists

Before I go on to describe what I want to build, what is already built. I had thought this space was emptier than it actually is.

**[OpenCATS](https://github.com/opencats/OpenCATS) — PHP.** The established open source ATS (well over 700 stars on GitHub) used by staffing agencies. Its own documentation is very frank in that it "does not compete with most modern paid applicant tracking systems feature for feature", that resume parsing and keyword search have both been lost over time and that access controls are very limited.

**[FreeATS](https://www.freeats.com/) — Ruby on Rails.** A self hosted ATS under an MIT licence, maintained by Toughbyte. Built on Rails with PostgreSQL, ViewComponents and Slim templates. Fully multi-tenant, around 30 models, Docker deployment, Conventional Commits enforced in CI. Has pipelines, scorecards, duplicate merging and an embeddable careers page. Small (in the low tens of stars at the time of writing) and very active.

That second one stopped me. A working ATS in Rails, MIT licensed, every line of code readable.

I was about to write that nobody had built one. Sit with that for a moment. I was ready to state there was a gap in a field I work in on a daily basis, without having done any looking at all. My existing view of open source HR software did the looking for me, which is the normal way perception works and the very reason it's worth checking.

A kit isn't an insult to the builder either. You learn how a thing is engineered by building one to somebody else's design.

What's actually missing is the finer, more interesting detail. Both of those systems track. Neither one explains anything at all about the system to the person who is using it. There's nothing in the category that tells a coordinator where a number came from, why a field is being collected or what the law requires of that field whilst it's sitting in the database. The gap isn't another ATS. The gap is the teaching layer that they all lack.

## Where this goes next

The plan has changed whilst I was writing this, which is perfectly reasonable to acknowledge in the very first post of a series about working in the open.

### 01 Read somebody else's

I've now had a proper look at the FreeATS schema and three things in there were worth the afternoon.

The first is that what I've always referred to as "a candidate in the pipeline" is not in fact a candidate at all. It's a placement. It's a record which links one candidate to one post at one point in time and has its own status of qualified, reserved or disqualified. A candidate is a person and they only exist once. Their involvement in four vacancies is four placements. I've explained that distinction very badly in a huge number of intake meetings, never having had the word for it.

The second is the Event table. Every stage movement is captured with the originating stage, the destination stage and the timestamp. That's the insight I referred to earlier in this post (that offers are taking 11 days and the delay is sitting with the panel) which is not something you need to build as a feature at all. It's just a query against data the system already has. The insight I was after was already sitting in somebody else's schema the whole time.

The third is tiny and tells you that a fairly competent recruiter was in the room when it was put together. The disqualification reasons are their own table, two of which are hard coded in ("No reply" and "Position closed") and you can't delete a reason once it's been used. Someone in that room clearly understood that rejection data is reporting data.

| What recruiters say | What the schema calls it |
| --- | --- |
| The person. They exist once, however many roles they are considered for. | `Candidate` |
| The vacancy or requisition. | `Position` |
| A stage in that vacancy's pipeline, ordered, with "Hired" forced to the end. | `PositionStage` |
| One candidate in one position. What we loosely refer to as "a candidate in the pipeline". | `Placement` |
| The rejection reason, as a real record rather than free text. | `DisqualifyReason` |
| The audit trail. Where time-in-stage and bottleneck analysis actually comes from. | `Event` |

### 02 Contribute to it

Two openings fit what I actually have, which is domain knowledge rather than Ruby.

The first is the documentation. The README is very thorough on deployment and makes absolutely no mention of how to run the app locally in order to work on it, even though the scripts to do that are in `bin/setup` and `bin/dev`. There's no contributing guide at all. A contributing guide would be the guide to getting the thing running (the education) and then writing down what you did (the contribution).

The second is more of a question than a fix really, and it needs to be asked carefully as it may have an answer I haven't come up with. There's nothing in the codebase that refers to retention, erasure or anonymisation. A candidate deletion does correctly cascade to their email addresses, phone numbers, notes and history, so the mechanism for that is sound. The absence is in any notion of when that should happen. There's a very real tension there. You can blacklist a candidate, and a suppression list only works if you have sufficient identifying data to be able to identify the person you're suppressing. That's precisely the sort of question a recruiter should be asking the engineers, and precisely the sort of thing that doesn't get asked when the two groups don't share a common language.

Their CI enforces Conventional Commits on every pull request title. A project that gates the discipline which is obviously absent from my own history is as good a place as any to get it.

### 03 Build the missing layer

Then the bit that doesn't exist: a lightweight tool, or a contribution to one of the existing ones, where you could open up any figure to see the formula and the records underneath it, and every field would tell you why it was collected and when it should be deleted. It would be fast and very low demand, as the vast majority of the people I'm writing for aren't issued with the good kit.

The point of the whole thing is a system that builds up the operator's skill rather than hiding the work and leaving you no more knowledgeable after two years of use.

I can't do stage three yet. To put it plainly, that's the very premise of the series rather than a caveat. Each post is one piece and the gap between this post and that tool is the curriculum.

## Where I want it to end up

All of the above is in service of something which I've only very recently been able to name, so I may as well put that in the first post and be held to it.

I want to work in the security of the hiring and onboarding process. Not security in general. That very specific seam where a stranger becomes a candidate, the candidate becomes an employee and the employee then becomes the person with the laptop and the login.

The role I'm talking about doesn't have a name quite yet. The closest I can get is a hybrid of HR and recruitment process specialist with a blue team's skillset and, more importantly, a blue team's methodology. Defensive security. You map what you actually have, you model how it could go wrong, you put the controls in the right place and you detect the failure rather than just writing a policy that says you won't do it.

Here's why I think the seam is worth somebody's career. Think about what's actually in it.

- **Your employer's brand is an attack surface and no-one in HR has any ownership of it.** You've got fake adverts, fake offer letters and fake application portals all using a real company's name to harvest ID and banking details from people who are job hunting and therefore trusting and in a rush. Recruitment marketing own the brand. IT security own the domains. The gap between them is where the candidate gets hurt.
- **The person you assessed and the person who starts are assumed to be the same person.** In most cases they are. Remote hiring has made it worth testing that assumption rather than taking it as a given.
- **Candidate data is by far the most copied data in a business.** It's copied out by the ATS, by the agency, by the background check vendor, by the assessment platform, into an interviewer's inbox, into a coordinator's downloads folder. Every one of those is a copy in its own right with its own lifecycle and its own access list, and the process creates more copies than it ever destroys.
- **Onboarding is an access control decision taken by HR and executed by IT.** What a new joiner can actually access on day one is determined somewhere between a start date field and a provisioning script. Whether a leaver's access actually terminates is decided the same way. Both are process issues with a security outcome.
- **Retention and erasure are the whole of it, and no-one owns them either.** That's where the question I've got for the FreeATS maintainers came from. It wasn't idle curiosity. That's the very thing I'd be paid to ask.

Every one of those is a process issue. I've spent eight years on recruitment processes. The bit I'm missing is the defensive approach, and that is learnable, which is precisely the argument of this post as applied to its author.

The five skills aren't a hobby curriculum. See it, understand it, change it safely, get something out of it, protect it. The first four are how you earn the right to be trusted with the fifth.

And here's the thing I didn't see until I'd written the opening of this post. Blue teams are troubleshooting with a method and a name. I've been the resident troubleshooter since I was a kid, in a house where that was the ceiling rather than the beginning. There is in fact a profession at the other end of it.

A system with a rule in it, and someone who wants to know how the rule actually works rather than just accept what it says on the box. That was a teenager going online. That's also a job description.

## The series

1. **Opening a candidate export in Ruby.** Twelve lines, no spreadsheet. What a CSV is and how to read one.
2. **Counting what is actually in your pipeline.** Missing fields, duplicate records, dates in four different formats. Finding out before anyone else does.
3. **Cleaning an ATS export safely.** De-duplicate and standardise on a copy, so that you can run the same script again next month.
4. **Time to fill and time to hire, properly.** Rewriting `metrics2.rb` in public, with the regression in `metrics4.rb` fixed in a commit which you can read.
5. **Keeping candidate data out of trouble.** Redaction, faked data, gitignore, retention. The POPIA habits that are a few lines each.
6. **Reading a real ATS schema as a recruiter.** Why a candidate in your pipeline isn't actually a candidate, and where time-in-stage actually comes from.
7. **What happens when a candidate requests to be deleted?** Cascading deletes, suppression lists and the retention question which no-one actually writes down.
8. **Counting the copies.** Map every single place that a candidate's details exist within your own process. The very first piece of defensive work a coordinator can do without having to ask anyone for permission.

## How this series works

|  |  |
| --- | --- |
| **Data** | No actual candidate or employee data is in any repository or post. All examples use fabricated or invented records. |
| **Code** | All code is in a public repository with a README that details the problem, the requirements and what a successful outcome would look like. |
| **Corrections** | Any errors are corrected in a commit which shows what the error was, and are also noted in the post. |
| **Security** | Security is a constant theme throughout. We cover how to find and protect what your own process holds. We will not publish anything that reads as a method of attack against someone else. |
| **Independence** | There are no vendor sponsors of this series and there is no paid placement in any post. If a commercial tool is the right tool then it will be named as such. |
| **Credit** | Other people's work is credited appropriately. Where this series is built upon open source work, the licence is respected and the maintainers are acknowledged. |
| **Level** | Written by someone who is still learning, for people who are just getting started. Where in doubt, we will say so. |

## Common questions

**Do recruiters need to know how to code?**

No. There's absolutely no shortage of excellent recruiters who never write a line. Where the role is one involving exports, spreadsheets and figures that other people will act upon though, a bit of code turns a fairly routine afternoon into a script and turns a figure you're just passing on into one you can actually explain. That's the career move for an intern or a coordinator.

**Am I too old, or too non-technical, to get going?**

I wrote my very first line of code on purpose at around thirty, having spent a lifetime as the person everyone brought their broken laptops to. The thing that held me back wasn't any lack of aptitude. It was that I'd decided I was rubbish at maths and logic and no-one ever really argued with me about that. If you're the person your team bring their system problems to, you've already been doing the hard work for years without ever having the title.

**What is an HR-security role?**

It's not a role you'll see advertised very often, which is one of the reasons I'm writing about it. It's the intersection of how the hiring and onboarding processes actually operate and how they could be attacked or result in a data leak. It's about the employer brand that's used in the recruitment scam, the verification that the person who actually starts is the person who was assessed, tracking every copy of a candidate's data as it moves through an ATS and its various vendors, and the access a new joiner gets on day one. Those are process questions which have security implications, and they currently lie in the gap between an HR team that doesn't think in terms of threats and a security team that doesn't attend the intake meetings.

**What's the difference between time to fill and time to hire?**

Time to fill is the measure of the process: from the day the role opens to the day the offer is accepted. Time to hire is the measure of the candidate: from the day they enter the process to the day they accept. The first is a measure of how slow the process is; the second is a measure of how slow you were with the individual who actually got hired. A third measure, time to alignment, is from the day the role opens to the first day of the new joiner, as the role isn't considered filled until someone is actually in the seat.

**Isn't there already an open source ATS?**

Yes there are. OpenCATS has been around for years in PHP and FreeATS is an actively maintained MIT licensed system built on Ruby on Rails. If you're looking for a self hosted ATS at the moment you should be looking at those rather than waiting for anything in this series. The thing they don't do is explain themselves to the person using them, which is the very narrow issue this series is trying to address.

**Should I learn Ruby or Python for HR and recruitment work?**

Either serves and the thinking transfers. Python has the bigger community and the better data tooling, so if it's already in front of you then use it. Ruby reads very close to English and Rails is explicitly designed around one developer shipping an entire application on their own, which is pretty much the case for most people doing technical work in an HR function. I'd much rather be good at one language than conversant in two.

**Do I need a CS degree?**

Not in the least. I still do want a proper formal qualification in CS or networking at some point and I'm waiting to see how the curricula evolve before I commit three years to one. The issue I have is that a huge amount of what is taught currently produces people who can build a CRUD app and have never had to get hardware to do something that is in any way non-trivial. The interesting work, the work that employers appear to be desperate for, is much more likely to be at the metal end of thinwho'st's an opinion from outside the academy and should be treated as sucit
**ractice run on c youandidate data from work?**

No, and that's the one point in this post which I'd absolutely insist on. Practise on faked data. Ruby's `faker` library will generate you names, addresses and dates as and when you need them, and a file of made up people is utterly indistinguishable from a file of real people for all the purposes you're trying to learn. Real candidate data sitting in a forgotten folder on a personal laptop is one of the most common data protection failings in recruitment, and it's invariably the result of someone being helpful.

**How long before this is of any use in the workplace?**

The first script in this series is only a handful of lines and is simply a replacement for something you currently do by hand, so that bit is trivial. Being good at it takes a hell of a lot longer, and the commit history above is six years of that.

## Commitments

1. **No real candidate or employee data anywhere.** All faked data and invented records, which was the practice prior to me knowing to say so.
2. **One commit, one decision.** No more additional commits for Git practice.
3. **Corrections in public.** Mistakes get fixed in a commit that shows what was wrong.
4. **Read before building.** Where good open source work already exists, study it and contribute to it before starting something parallel.
5. **Defensive only.** Everything here is about protecting what your own process holds.
6. **Small and finished over large and abandoned.** A twenty line script that runs beats 142 files with nothing behind them.

## Sources and further reading

- [Learn in Public](https://swyx.io/learn-in-public) — swyx. The essay this series takes its method from.
- [Are We Really Engineers?](https://www.hillelwayne.com/post/are-we-really-engineers/) — Hillel Wayne, on people who crossed from traditional engineering into software, and where "circumstance, not essence" comes from.
- [The One Person Framework](https://world.hey.com/dhh/the-one-person-framework-711e6318) — David Heinemeier Hansson, on Rails as a toolkit for a single developer.
- [The Odin Project](https://www.theodinproject.com/) — where the first Hello, World happened, and still free.
- [FreeATS](https://www.freeats.com/) and its [source on GitHub](https://github.com/freeats/freeats) — an MIT licensed applicant tracking system built on Ruby on Rails. The schema notes above come from reading it at commit `ac650df`.
- [OpenCATS](https://github.com/opencats/OpenCATS) — the long established open source ATS, and its [unusually honest documentation](https://opencats-documentation.readthedocs.io/en/latest/introduction.html).

## Follow the series

If you are an intern or coordinator who has been handed an export and thought there must be a faster way to do this, you are who I am writing for. No experience assumed.

Code: [github.com/k4mille-bi5an](https://github.com/k4mille-bi5an)

Next: Opening a candidate export in Ruby — twelve lines, no spreadsheet.

I am not trying to turn you into a developer. I want you to be able to look at the bulky dashboard you use every day and know roughly what is underneath it, because that machine is still, under everything, waiting to be told what you want. I would also like to spend the back half of my career making that machine safer for the people whose details are inside it. Six years of commits say I am better at starting than finishing. Nothing private has corrected that. This is the other thing to try.

