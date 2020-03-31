.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introduction to reStructuredText see:
.. 
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See our GSoC Project Ideas List for some suggested project ideas:
.. https://trac.xapian.org/wiki/GSoCProjectIdeas
..
.. You are also most welcome to propose a project based on your own ideas.
.. 
.. From experience the best proposals are ones that are discussed with us and
.. improved in response to feedback.  You can share draft applications with
.. us by forking the git repository containing this file, filling in where
.. it says "FILLME", committing your changes and pushing them to your fork,
.. then opening a pull request to request us to review your draft proposal.
.. Please pick a useful title for the pull request - "My application" may
.. be meaningful to you, but isn't helpful to those reviewing.  Using the
.. title of the project is a good choice.  You can open a pull request even
.. before applications officially open.
.. 
.. IMPORTANT: Your application is only valid is you upload a PDF of your
.. proposal to the GSoC website at https://summerofcode.withgoogle.com/ - you
.. can generate a PDF of this proposal using "make pdf".  You can update the
.. "final" PDF proposal as many times as you want right up to the deadline by
.. just uploading a new file, so don't leave it until the last minute to upload
.. a version.  The deadline is strictly enforced by Google, with no exceptions
.. no matter how creative your excuse.
.. 
.. If there is additional information which we haven't explicitly asked for
.. which you think is relevant, feel free to include it. For instance, since
.. work on Xapian often draws on academic research, it's important to cite
.. suitable references both to support any position you take (such as
.. 'algorithm X is considered to perform better than algorithm Y') and to show
.. which ideas underpin your project, and how you've had to develop them
.. further to make them practical for Xapian.
..
.. For academic research, it's helpful to include a URL if the paper is
.. freely available online (via an author's website or preprint server,
.. for instance). Not all Xapian contributors have free access to academic
.. publishers. You should still provide all the normal information used
.. when citing academic papers.
.. 
.. You're welcome to include diagrams or other images if you think they're
.. helpful - for how to do this see:
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html#images
.. 
.. Please take care to address all relevant questions - attention to detail
.. is important when working with computers!
.. 
.. If you have any questions, feel free to come and chat with us on IRC, or
.. send a mail to the mailing lists.  To answer a very common question, it's
.. the mentors who between them decide which proposals to accept - Google just
.. tell us HOW MANY we can accept (and they tell us that AFTER student
.. applications close).
.. 
.. Here are some useful resources if you want some tips on putting together a
.. good application:
.. 
.. "Writing a Proposal" from the GSoC Student Guide:
.. https://google.github.io/gsocguides/student/writing-a-proposal
.. 
.. "How to write a kick-ass proposal for Google Summer of Code":
.. https://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

======================================
Matcher Optimisations
======================================

About You
=========

 * Name: Zhang Yuchen

 * E-mail address: whostheme@foxmail.com

 * IRC nickname(s): 2727c

 * Any personal websites, blogs, social media, etc: http://www.z2727c.com/

 * github URL: https://github.com/whostheme

 * Biography:

I am a final-year undergraduate of Software Engineering at Southwest Jiaotong University, China.
I will continue my Msc study in Computer Science at University of Copenhagen.

I discoverd my interest of and start to learn programming when I was a junior architecture student.
and manage to transformed my major officially at the begining of the third-year,and had a pretty
condensed year after that:

 - Course projects from network programming to machine learning.
 - Participated in several developing events and got up to 2nd Prize at a national competition.
 - Participated in NUS SoC summer workshop, designed and developed a VR Game in 21 days. 
 - Worked as software development intern at Ericsson for 4 months. 


Background Information
----------------------

.. The answers to these questions help us understand you better, so that we can
.. help ensure you have an appropriately scoped project and match you up with a
.. suitable mentor or mentors.  So please be honest - it's OK if you don't have
.. much experience, but it's a problem if we aren't aware of that and propose
.. an overly ambitious project.

**Have you taken part in GSoC and/or GCI (https://codein.withgoogle.com/) and/or
similar programmes before?  If so, tell us about how it went, and any areas you
would have liked more help with.**

No, I have not. 

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

From mid March, I've deployed Xapian on my machine, carefully read the design documents
about Xapian's Matcher, studied the codes related to specific PostList classes (OrPostList,
BoolOrPostList, MultiAndPostList) and understood their mechanism.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

Never participated in the development of any formal open source project,
but I have used many open source APIs in my student projects, such as ArcSoft's 
face recognition module used in the meeting management system project, VRTK tool, etc.
I am also used to share the outcomes on github.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

My most related courses at college:

 - Internet Search Engine (on going this semester)
 - C++,Java Programing with object-oriented.
 - Data Structure
 - Algorithm Analysis and Design
 - Database Principle

**What development platforms, tools and methods do you prefer to use?**

Operating System: Ubuntu 18.04 LTS

CPU: Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz

IDE: Visual Studio Code

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

During my internship at Ericsson, I contribute to developing a remote automated testing tool
and modified test cases adapting to new design of their upgrading RF software.
In this process, I strengthened my programming skills (C++,python) and became 
familiar with the collaborative mode similar to open source software development,
including addressing&claiming of user story&tickets, submission&reviewing of codes.

**What timezone will you be in during the coding period?**

.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.

GMT+8:00

**Will your Summer of Code project be the main focus of your time during the
program?**

.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.

Currently, I am also working on my graduation project, which should be finished at late May.

After that I can devote all my work time on GSOC project.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

.. A common mistake is to think you can work a huge number of hours per week
.. for the entire duration of Summer of Code. If you try, you run the risk of
.. making yourself exhausted or ill, which may mean you are unable to keep
.. working right the way through. It's important to take good care of
.. yourself. Make sure you leave adequate time for other commitments, as well
.. as for eating, exercising, sleeping and socialising. Summer of Code
.. doesn't have to take over your life; it's better to think of it as you
.. would a job, leaving time to do other things.
..
.. If you have commitments for particular periods of Summer of Code, such as
.. exams or personal or family events, then please note in your timeline
.. (further down) when you'll be unable to work on your project. Providing
.. these are few, it is usually possible to get enough done across Summer of
.. Code to make for a worthwhile project.

Monday-Friday 4:30am-12:00pm UTC

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No, Xapian is the only project I prepared for and applied.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

Because I am interested in studying searching/NLP, I aim it as the future theme 
for my master degree. This particular idea enables me to access and learn most
about the core algorithm and principles of searching.


**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

Regular users of Xapian based software and developers that use Xapian API would
glad to enjoy a bit faster search service.

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

The theme of this project is the optimization of Matcher, and thus based primarily
on Matcher's existing implementation. The way Matcher works is to build a tree structure
with PostList nodes, based on the text to be searched.
In a most common situation:
 - Each leaf PostList encapsulates a mapping from a term to a list of the ids of all documents containing that term, while virtual PostList as non-leaf nodes represents the layers of logical relationship among these terms or phrases.
 - Through a top-to-bottom passing and allocating of matching-weight threshold, and a bottom-to-top filtering and passing of document ids, matching documents are found one by one.

The basic task of this projest is to implement three of the suggested optimization ideas.
 - Idea #215 is based on the current implementation of  BoolOrPostingList class(matcher/boolorpostlist.cc).It is a multi-way virual PostList node. The current docid is used as the key value to maintain the minimum heap of pointer array to the sub-PLs.
Without using the optimazation idea, skip_to(target_id) is recursively called on each sub-PL that falls behind the target_id.
 - Idea #378 is based on the current implementation of  MultiAndPostList class(matcher/multiandpostlist.cc), also as a multi-way PostList node.In the current version, the weights are not calculated until all sub-PLs have settled on a same position. If we calculate the weights along with going through sub-PLs, We could judge and abort the query process of a unqualified docid in advance.
 - Idea #394 is based on phrase-settling-pond.patch(https://trac.xapian.org/attachment/ticket/394/phrase-settling-pond.patch).


**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

FILLME

**What other approaches have you considered, and why did you reject those in
favour of your chosen approach?**

None

**Please note any uncertainties or aspects which depend on further research or
investigation.**

Without much experience with xapian, I'm not sure if implementing these three ideas will 
appropriately fill the 3-month coding period. I would like to propose a new optimization 
strategy, but that require further research on matcher.

**How useful will your results be when not everything works out exactly as
planned?**

Even if some of the optimisation ideas do not bring much positive results, still my
efforts would help to prove its invalidation, which could prevent others from useless work.
It may also lay basis and open new ideas for futher optimisation.

Project Timeline
----------------

.. We want you to think about the order you will work on your project, and
.. how long you think each part will take.  The parts should be AT MOST a
.. week long, or else you won't be able to realistically judge how long
.. they might take.  Even a week is too long really.  Try to break larger
.. tasks down into sub-tasks.
.. 
.. The timeline helps both you and us to know what you should do next, and how
.. on track you are.  Your plan certainly isn't set in stone - as you work on
.. your project, it may become clear that it is better to work on aspects in a
.. different order, or you may some things take longer than expected, and the
.. scope of the project may need to be adjusted.  If you think that's the
.. case during the project, it's better to talk to us about it sooner rather
.. than later.
.. 
.. You should strive to break your project down into a series of stages each of
.. which is in turn divided into the implementation, testing, and documenting of
.. a part of your project. What we're ideally looking for is for each stage to
.. be completed and merged in turn, so that it can be included in a future
.. release of Xapian. Even if you don't manage to achieve everything you
.. planned to, the stages you do complete are more likely to be useful if
.. you've structured your project that way. It also allows us to reliably
.. determine your progress, and should be more satisfying for you - you'll be
.. able to see that you've achieved something useful much sooner!
.. 
.. Look at the dates in the timeline:
.. https://summerofcode.withgoogle.com/how-it-works/
.. 
.. There are about 3 weeks of "community bonding" after accepted students are
.. announced.  During this time you should aim to complete any further research
.. or other issues which need to be done before you can start coding, and to
.. continue to get familiar with the code you'll be working on.  Your mentors
.. are there to help you with this.  We realise that many students have classes
.. and/or exams in this time, so we certainly aren't expecting full time work
.. on your project, but you should aim to complete preliminary work such that
.. you can actually start coding at the start of the coding period.
.. 
.. The coding period is broken into three blocks of about 4 weeks each, with
.. an evaluation after each block.  The evaluations are to help keep you on
.. track, and consist of brief evaluation forms sent to GSoC by both the
.. student and the mentor, and a chance to explicitly review how your project
.. is going with Xapian mentors.
.. 
.. If you will have other commitments during the project time (for example,
.. any university classes or exams, vacations, etc), make sure you include them
.. in your project timeline.


**Community bonding** (4 MAY-31 MAY)

Week 1 · Learning & Experiencing
 - Consolidate concepts & knowledge about searching.
 - Experience using Xapian API, 
 - Understand the design and the process of building a PostListTree.
 - Find out when and for what those main functions of PostLists are called.
 - Keep in touch and get familier with the community.

Week 2 · Catching up
 - Learn and practice the way to test and evaluate the performance of matcher
 - Track and go through the histroy and progress of targeted 3 tickets, understanding related codes.
 - Carefully review each line of key PostList.
 - Address questions and get them cleared.

Week 3-4 · Dash Weeks for graduation preparation
 - --

**Coding**(1 JUNE-2 AUG)

Week 5-6 · Sketching
 - Draft the initial implementation plan of each optimazation idea, discuss with the community and mentor, finalize the first version of the plan.
 - Follow up with irc and participate in discussions related to matcher positively.
 - Clarify new confusions.

Week 7-8 · Implementing idea #215

Week 9-10 · Implementing idea #378

Week 11-12 · Implementing idea #394

Implementing Steps:

 - 1.Code as planned.
 - 2.Run and pass the test. Fix bugs and optimize the algorithm.
 - 3.Evaluate the improvment on performance.
 - 4.Adjust design if necessary, back to 1.
 - 5.Make PR for the changes, reply comments, adjusting codes and retest.
 - 6.Update documents if needed.


**Reflection and Extension** (3 AUG-24 AUG)

Week 13-14

 - Organizing the codes and the performance evaluation outcomes
 - Follow comments and keep refining.
 - Try promote new optimazation ideas.

Week 15-16 · Buffer Weeks 

 - For unexpected stalemate with graduation project.
 - For any trouble encountered during implementing suggested 3 ideas.
 - For implementing new optimazation ideas if everything goes well.


Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).
..
.. One of the things we've discovered sets apart many of the best applications
.. is that the students in question have discussed the project with us before
.. submitting their proposal.

I have post my envision of the implementation of the #215 idea on the irc and got 
feedback from the community.

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

.. For more details, including the rationale for this with respect to code,
.. please see the "License grant" section of our developer guide:
.. https://xapian-developer-guide.readthedocs.io/en/latest/contributing/contributing-changes.html#license-grant

I agree to dual-license all my contributions to Xapian under the GNU GPL version 2
ans all later versions, and the MIT/X licence.

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.

None