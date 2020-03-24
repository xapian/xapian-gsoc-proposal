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
Project: Text-Extraction Libraries
======================================

About You
=========

 * Name: Parth Kapadia

 * E-mail address: prkandmap07@gmail.com

 * IRC nickname(s): exter-dg

 * Any personal websites, blogs, social media, etc:

 * github URL: https://github.com/Exter-dg

 * Biography:



.. Tell us a bit about yourself.

I'm a second year undergraduate student at Institute of Technology, Nirma University, India. I am fascinated by the world of programming and have been doing competitive programming since quite some time. I've been programming in C++ for nearly 3 years now, so I'm quite comfortable in working with it.

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

No, this is my first time to apply to Google Summer of Code and/or Google Code-in.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I do not have any previous experience with Xapian or any other system for indexed text search.

I was introduced to Xapian through GSOC-2020. In order to get myself familiarized with the codebase and development workflow, I spoke with
James and Olly and have submitted a PR under their guidance.
About the Issue:
  With the introduction of semantic structure in HTML5, tags like <time> were also introduced.
  This tag allows you to represent a machine-readable date and/or time on your web pages.
  Although time and date can be simply displayed using other tags (<span> as in our case) ,
  by using various attributes of time tag it can be made clear to the browser what the date/time is.

`You can find my PR here https://github.com/xapian/xapian/pull/290`


**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

While I have used a lot of open source programs and softwares for various purposes, I do not have much experience in FOSS development.


**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

Some courses taken at college:

  * Data Structures and Algorithms
  * Database Management system
  * Operating System

I have done various small projects during my schooling and college period. Some of these can be found on my GitHub repos.
`You can find my Github profile here https://github.com/Exter-dg`

I also do competitive programming in C++ on platforms such as Codeforces.


**What development platforms, tools and methods do you prefer to use?**

* Development Platform: Ubuntu 19.04
* Languages: C++, C, Java, Python
* Softwares: Atom, Git

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

No, I have never worked on a project of such large scope.

**What timezone will you be in during the coding period?**

.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.

UTC+05:30

**Will your Summer of Code project be the main focus of your time during the
program?**

.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.

Yes this project will be my main focus during the program.
However, due to Covid19 situation, there is a nation wide lockdown in India. Because of which, my exams will be postponed.
The dates are uncertain but it will probably be held during 15-31st May. Whenever this happens, I might have to give little more time to exams some days but I will compensate in weeks prior to and after that.

Otherwise, This project will be my main focus in rest of the time period.

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

Monday-Saturday 8am-2pm UTC+05:30

As mentioned above, if my examinations are postponed to may, during that week or two, work hours might be affected as I would have to give time to exams.

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No, I am not applying for any other projects in GSoC this year.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

I want to learn how to define, manage and complete a project of such a large scope. I want to learn how to write code that is going to be used in the real world and I think this is a good way to learn and write a production level code.

I have never worked with system with indexed text search, and am eager to learn more about it. It will teach me how to coordinate and work with a team in remote and will also help me in honing my development skills.

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

Given the wide variety of file formats that users use for their personal tasks, the ability to be able to extract text and have an easy interface to do that for whatever file format a user has is extremely useful.
Support for multiple file formats was added a last year project. If a user has a new file format which he/she wants to index, he/she might not be able to do it with omega if there is no support or if it is not fast enough.
So this project focuses on making omega a one stop solution for users to use regardless of file formats.

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

The project is based on adding support for extracting data from various file formats using some external filters or shared libraries.
There was already a GSoC project which added support for multiple file formats to omega last year. I will be building my project on the top of this project by adding supprt for a wide variety of additional formats other than the ones that have already been done.


`Here is the link to the 2019 GSoC Project https://trac.xapian.org/wiki/GSoC2019/TextExtraction`

I plan to divide my project into several modules. Here is a description of what these modules will be about. Each of these modules will largely be decoupled.

**Module 1**

  * Get Familiar with Xapian's code base
  * Understanding the testing framework
  * Understand which libraries were added last year and why
  * How to documentation and testing works in Xapian
  * How text extraction libraries are added into Xapian code base


**Module 2**

  * Researching and identifying what other file formats can be added and what libraries are necessary and have not been included in Xapian in discussion with the community.
  * How to provide indexing capabilities to extract text from various file formats.
  * Understand where these shared libraries are in the code base.

  For eg, `https://www.documentliberation.org/projects/#import-libs` has number of libraries for various file formats. Many such libraries are available, so the goal is to identify which libraries are important to the users and how we can include them in the code base.


**Module 3**

  Omega already uses zlib to read gzip compressed Abiword files. Addition of a zip file reading library would further cover several popular formats.
  The goal of this module will be to identify such libraries in discussion with the community, Implement code to add library to the project , Test codes and fix issues and write proper documentation for it.

  (To be further improved)


**Module 4**

  * Adding support for other file formats that have been discussed in module 2 (atleast 4).
  * Testing and documentation


**Module 5 (Stretch goal)**

  * If time permits, add next set of libraries which are necessary.
  * Testing and Documentation


**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

In previous year's project, Bruno added support for multiple file formats using libraries and filters such as Poppler,Libe-book,Tesseract to omindex.
A documentation on how to add support for external filters and shared libraries to omindex has also been written.

`Here is a link to the documentation https://github.com/xapian/xapian/blob/master/xapian-applications/omega/docs/newformat.rst`

Support for various file formats has been added during this project successfully, so I believe this approach will work on adding new formats as well.


**What other approaches have you considered, and why did you reject those in
favour of your chosen approach?**

FILLME

**Please note any uncertainties or aspects which depend on further research or
investigation.**

During the coding period, it may happen that some external library is incompatible or cannot be successfully integrated with omega. This may cause unexpected hurdles to integrate that library so the goal would be to find other such libary that is compatible and provides similar results.


**How useful will your results be when not everything works out exactly as
planned?**

As planned, my project will have modules, each of these modules will be decoupled. Each one of these will focus on adding support for a new library to omindex and will function independent of each other.
If it turn out that a particular library is incompatible for whatever reason,  it will be difficult to integrate it with omega.
Hopefully, we will be able to solve it but even if not, we will find an alternate library.


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


**Community Bonding Period: (May 4 - June 1) Module 1,2 **

  * Get to know the community and interact with its members
  * Understand Xapian Code Base, coding conventions and all relevant classes
  * Understand how the code I am going to add will be structured and what kind of tests i will have to write
  * Understand which file formats were chosen for previous year's project and why and understand how they were integrated
  * Discuss with community, other than zip, which file formats are important and are needed to be added to omega.


**Coding Weeks 1-3(June 1 - June 20) Module 3**

  * Research about different zip file reading libraries- eg libarchive,libzip ( Compare them and discuss with the community which is the most appropriate)
  * Implement code to add support for the library
  * Test code. Fix Issues if any.
  * Write proper documentation and publish changes to the project


**Coding Weeks 4-11(June 22 - Aug 14) Module 4**

During this period I will pick modules one by one and add support for the chosen file format. Each format is estimated to require between 1 and 2 weeks within which the following activities will be carried out:

  * Research about different available libraries (Discuss with the community regarding which is the most effective one)
  * Implement code to add support for the library
  * Test code. Fix Issues if any.
  * Write proper documentation and publish changes to the project.

Support for atleast 5 formats will be added during this period. However, I believe I will be able to add more in the given time frame.

A week has been kept free as a buffer in case of any delay in any of the modules.

By the first evaluation (July 29 - July 3), I will hopefully complete module 3

By the second evaulation (July 27 - July 31), I plan to complete adding support for 2 more file formats.

And by Aug 24, I will add support for 2 more, Hopefully I will be able to add support for more file formats as discussed(Module 5)

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

I have had discussions about the project on the irc with the community.

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

I totally agree to dual-license all my contributions to Xapian under the GNU GPL version 2 and all later versions, and the MIT/X licence.

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

I would have to use external libraries. These libraries will belong to free software and be under licenses compatible with MIT/X license and GNU GPL version 2 and later.
