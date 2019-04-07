.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
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
.. You can do this even before applications officially open.
.. 
.. IMPORTANT: Your application is only valid is you upload a PDF of your
.. proposal to the GSoC website at https://summerofcode.withgoogle.com/ - you
.. can generate a PDF of this proposal using "make pdf".  You can update the
.. PDF proposal right up to the deadline by just uploading a new file, so don't
.. leave it until the last minute to upload a version.  The deadline is
.. strictly enforced by Google, with no exceptions no matter how creative your
.. excuse.
.. 
.. If there is additional information which we haven't explicitly asked for
.. which you think is relevant, feel free to include it. For instance, since
.. work on Xapian often draws on academic research, it's important to cite
.. suitable references both to support any position you take (such as
.. 'algorithm X is considered to perform better than algorithm Y') and to show
.. which ideas underpin your project, and how you've had to develop them
.. further to make them practical for Xapian.
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
FILLME WITH THE TITLE OF YOUR PROPOSAL
======================================

About You
=========

 * Name: Alexander Slesarev

 * E-mail address: alexander.g.slesarev@gmail.com

 * IRC nickname(s): alexander

 * Any personal websites, blogs, social media, etc: no

 * github URL: https://github.com/Random90000

 * Biography:

 I am a student of Saint-Petresburg State University, Databases and algorithms department. My most well studied language is C++, but I have some experience in Pyhon with some additional libraries like NumPy. As for my background, I got award in Baltic engeneer fair with `code formattig project <https://github.com/Random90000/Code-Formatting-Tool/>`_ . Also I wrote a papaer with my mentor in Uni, it get good reviews on SEIM2019 conference, it will be published in journal of this conference wich is indexed in Scopus. 

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

I try to do it first time

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I have no experience with systems like this

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have some experience with using Open Source libraries, but not with developing 

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I have cources of maths, algorithms, and programming languages(Ocaml, C++, Python). Also my first cource work from my mentor is to write SQL parser in C++ for his development team, but I am at the very beginnig of study what GNU bison and some other software are.

**What development platforms, tools and methods do you prefer to use?**

There are some experience with Qt platform and cmake in my life, but now I decided to use Visual Studio Code for Linux and write makefiles in make.  

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

I am involved in ine small teem project in my Uni. There some ways to seed up queries to database, so we are writing framework with implementation of several algorithms. I have a draft of my part of job in git, but it bad structured and now documented yet.    

**What timezone will you be in during the coding period?**

Moscow time

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes, I will try to get understanding of project structure before the start of GSoC.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

3pm - 10pm with 2 days off each week

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

This project is first, maybe I will try another one.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

I have read several articles about how Google search works and it is get interesting to me to have some experience in this area.  

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

Firstly, I want to get skills of interacting with people inside project. Secondly, it is very important to try to understand code wich written by other people.  

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

I have read info about previous step of project and noticed following:
	1) There are not automated way to transfer data from Omega to Letor
	2) Letor has one click model with one algorithm inside, tested on one dataset
So it is possible to improve ranking quality by developing these two points.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

I have some experience in developing framework with many algorithms based on common dataset. Given the mistakes of that project, it is importatnt to collect and transfer data automaticlly, so that is why point 1) from previous paragraf is most critical. After the implementation of 1) it could be much easier to develop and test other click models or other algorithms for DBN.

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

Actually, implementation of algorithms seems more interesting to me than realising Omega-Letor communication, but as I said, I should understand the interaction Omega and Letor interaction firstly.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

As for me, it is not enough documentation and examples of code which is already done. So it could be some changes in my timeline during development, because I do not have full understanding of how complex some inner parts of Xapian are. Also I will spend enough time documenting my part of job to save possible followers from problems like this.

**How useful will your results be when not everything works out exactly as
planned?**

I will try to note my reflections and measure difficulty one each step of project, so you will have ability to post it and help to other developers how do not have any experience in this area. Also I will try to reach the expected minimum: enable an end-to-end use of Letor with Omega. If it necessary, I will done it after the end of school. 

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

06.05 - 26.05
	Understand how Xapian works; fully understand the code predecessor; read articles about algorithms.

27.05 - 02.06
03.06 - 09.06
	Choose writing language for Letor-Omega interaction. Develop structure of interaction interface (should it be a part of Letter or separate application). Realise interfase.

10.06 - 16.06
	Test interfase and write documentation.

17.06 - 23.06 
	Additional week to rewrite code\documentation if some preblems will appear. Also this week is peak of exams in Uni.

24.06 - 30.06
	Discuss results of interface developing. If it is success, start developing Expectaction-Maximization algorithm for DBN model.

01.07 - 07.07
	Finish first evaluation of developing and write tests\documentation.

08.07 - 14.07 
	Collect one or more datasets for compare effectiveness of algorithms. Write about results.

15.07 - 21.07
	Depends on result of comparing, start developing another one click model (DCM or UBM) or improve existing.

22.07 - 28.07
	Discuss results of algorithms developing. Fix some bugs and decide what to develop next.

29.07 - 04.08
	Developing another click model or fixing bugs. Maybe some changes in Letor ranking will need.

05.08 - 11.08 
	Finish developing another click model.

12.08 - 18.08
	Test click model and write documentation.

19.08 - 25.08
	Compare quality of click models.

26.08 - 01.09
	Week for finish developing.

I hope I can realise at least part with interface interacting and develop at least one algorithm in Letor. 

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

I have only asked some general questions by the email.

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

I agree.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1399

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

I do not exactly know the existing way of transferring data between Letor and Omega, I think it could be fit to do it by Python Pandas library. As I have seen, click models released in C++, so I will do it in C++ too because of speed benefits.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
