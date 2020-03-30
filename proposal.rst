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
Text-Extraction Libraries
======================================

About You
=========

 * Name: Kalpit Kothari

 * E-mail address: kkothari1999@gmail.com

 * IRC nickname(s): kalpitk

 * Any personal websites, blogs, social media, etc: https://www.linkedin.com/in/kalpitk/

 * github URL: https://github.com/kalpitk

 * Biography:

I am a third-year undergraduate at IIT Indore, Indore. I started programming
three years back when I joined university.

I actively participate in Competitive Programming contests involving algorithmic
, and geometry problems. I am also selected to represent the country at the
ICPC World Finals 2020, the most renowned collegiate algorithmic competition
across the globe.

I have been involved in open-source software development for quite some time now.
I have a few course projects ranging from Database Management, Algorithms,
Optimization, Parallel Computing, and Computer Graphics. Other than that, I have
a few hobby projects on GitHub. Most of the programming I did was in languages: 
C++ and Python.

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

Yeah. I participated in GSoC 2019 with 'Software Heritage'. The project involved
security, web development, and testing. It was a great experience working with a
community spread across different countries. I was able to achieve the targets
set in the beginning.

Though the mentors were very responsive, I did not get much feedback from the
other community members during the coding period.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I have a fair bit of knowledge about text search in SQL systems. However, I do
not have any practical experience with indexed text search.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have worked with various Open-Source libraries in my course projects. This
includes linux socket, multithreading libraries, and computer graphics libraries.


**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I have completed courses in Operating Systems, Database Management Systems, Data
Structure & Algorithm, Parallel Computing, and Optimization in my university. I
have a few hobby projects on GitHub like high performance HTTP/1.1 server in pure
C++.

**What development platforms, tools and methods do you prefer to use?**

    * Operating System: Ubuntu 18.04 LTS
    * CPU: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz
    * IDE: Visual Studio Code


**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

As mentioned above, I worked on GSoC 2019 project with Software Heritage.

**What timezone will you be in during the coding period?**

.. Please give at least the offset from GMT, but ideally also the timezone
.. name so we aren't surprised by any differences around daylight savings
.. time, which don't all line up in different parts of the world.

GMT+5:30

**Will your Summer of Code project be the main focus of your time during the
program?**

.. It need not be a problem to have other commitments during Summer of Code,
.. but if we don't know about them in advance we can't make sure you have
.. the support you need.

Yes, Summer of Code project will be my main focus during the period.

**Expected work hours (e.g. Monday–Friday 9 am–5 pm UTC)**

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

Monday-Friday 6:30am-2:00pm UTC

**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

Yes. I am applying to CERN-HSF project also.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

The project involves coding in C++ which I use the most while programming and
would help me increase my knowledge about Linux.


**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

This project would add support for indexing a more extensive range of files.
OpenDocument and Office Open XML formats are prevalent files in most users'
systems. Typically educational institutes and workspaces use these formats in
abundance.

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

The project is based on the GSoC 2019 project for adding Text Extraction
Libraries by Bruno Baruffaldi. Support for archive formats like Office Open XML
by Microsoft and OpenDocument is yet to be added.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

The documentation about adding support for new MIME types from the last GSoC
project demonstrates that the process of adding support for new languages is
entirely plausible.

I went through the basic documentation of libarchive on GitHub
(https://github.com/libarchive/libarchive). According to the page, it has
support for various archive formats and can work with streaming archives.
I have tried running sample libarchive codes after its installation. 
Everything seems to be working as intended.

**What other approaches have you considered, and why did you reject those in
favour of your chosen approach?**

None

**Please note any uncertainties or aspects which depend on further research or
investigation.**

It is possible to work on Office Open XML formats side-by-side with OpenDocument
formats. It will depend on the similarity between the two. For example, it is
possible OpenDocument Text (ODT) and Office Open XML Document (DOCX) can be worked
on together.

Work on Pull Request: "Add omindextest to Omega" will depend on the research done in
the bonding period.

**How useful will your results be when not everything works out exactly as
planned?**

It is possible, for some file types, we have issues fetching the content.
In that case, we'll lack support for few formats which may be fulfilled in the
future.

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

Community Bonding Period (May 4 - May 31)
    * Interact with mentors, introduce myself to the community.
    * Get familiar with Xapian’s development style. Understand expected coding, documentation, and testing standards set by Xapian.
    * Start working on some issues to familiarise with the codebase. (Not necessarily related to the project)
    * Discuss ont the various MIME types that need to be worked on.
    * Read documentation pertaining to the required libraries.
    * Understand the current situation of Pull Request: "Add omindextest to Omega" (https://github.com/xapian/xapian/pull/280).

First Coding Period (June 1 - June 28)
    * Set up code to extract files data using libarchive. (5 days)
    * Implement handler for ODT (OpenDocument Text), update build system, and add a new worker to omindex. (7 days).
    * Look for issues, start taking feedback, improve performance. (2 days)
    * Document the code. (2 days)
    * Document the procedure support for new formats based around ZIP-compressed XML-based contents extracted through libarchive. (2 days)
    * Finalize the PR and merge. (2 days)

Second Coding Period (July 6 - July 27)
    * For two types: { ODS(Spreadsheets), ODP(Presentations) } -
        * Add support for a new type. (4 days)
        * Document changes. (2 days)
        * Take feedback, improve code, and merge. (2 days)

Third Coding Period (August 3 - August 31)
    * For one type: { ODF(Formulae / Mathematical Equations) } -
        * Add support for a new type. (4 days)
        * Document changes. (2 days)
        * Take feedback, improve code, and merge. (2 days)
    * Work on "Adding omindextest to Omega" (https://github.com/xapian/xapian/pull/280) according to the research conducted in the bonding period. (7 days)

Final Evaluation Week (August 31 - September 7)
    * Document all the work done for future work.
    * Prepare the final report.

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

No, I have not discussed the project on the irc or mailing list. However, I have
carefully read the project outline on the wiki page and agree with the ideas.

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

As mentioned on GSoC Ideas page, for reading the archives 'libarchive' would be used
which has a compatible licence with GPL version 2 and all later versions, and the
MIT/X licence.
