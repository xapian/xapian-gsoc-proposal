.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
.. 
.. http://www.sphinx-doc.org/en/master/rest.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See the [wiki:GSoCProjectIdeas ideas list] for some suggested project ideas.
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
.. helpful - see http://www.sphinx-doc.org/en/master/rest.html#images for how
.. to do so.
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
.. http://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

======================================
Text-Extraction Libraries
======================================

About You
=========

 * Name: Rushikesh Najan

 * E-mail address: hrishi.najan75@gmail.com or
		   rushin@iitk.ac.in

 * IRC nickname(s): bazinga_65

 * github URL: https://github.com/bazinga65

 * Biography: I am a sophomore studying Computer Science and Engineering at the Indian Institute of Technology Kanpur, India. I have a keen interest in Linux. If I were to describe myself, I would say that I always try out tech, languages, programs, etc. I like to spend my time on giving a thorough thought about how things work, be it some lines of code or a physical mechanism. 

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

No.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

No experience.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have used Free and Open Source softwares like Vim, gcc, etc. I also have used Linux based operating systems like Ubuntu, Debian, etc. Although I have tried to understand how their codes work, I don't have much experience with contributing to Open Source softwares.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

I have worked on a web development project in the previous summer which consisted of making a web application to automate the messing facility on the campus by eliminating the use of tokens
and registers using HTML, CSS, JavaScript, PHP, MySQL to build the web-app and hosted it on Microsoft Azure. We used SendGrid API for e-mail verification and OTP, hashing to securely store passwords. I have C and C++ programming experience from the introductory programming course and BASH and Haskell programming experience from the Computing Laboratory course. I have worked on some small projects and assignments and I also have written many programs in C, C++ as a part of my coursework and as my hobby. I have participated in competitive programming and 

**What development platforms, tools and methods do you prefer to use?**

I work mainly on Vim but I do use VS Code sometimes. Also, I prefer to use Git as the version control system and Ubuntu 18.04 machine.

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

I have worked on small individual project but have worked only once in a project with other collaborators. I haven't worked in an open source project.

**What timezone will you be in during the coding period?**

IST (UTC + 0530)

**Will your Summer of Code project be the main focus of your time during the
program?**

Summer of Code project will be the main focus of my time. I have no other engagements during the summer.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

My summer vacation starts from April 29, and will end around last week of July. During the vacation, I would be available for work and be online on IRC any time I am awake (usually IST 0800 to 2330). But to organize the schedule, I plan to work during Monday-Friday IST 0830 to 1830 (45-50 hours per week) and catch up on weekends if needed. However, when the classes resume, the working hours would be determined by the schedule of the semester.

**Are you applying for other projects in GSoC 2019?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

This project has many interesting subtasks which I think I will enjoy doing. Also, an open source project is a great way to improve programming skills. There is a lot of scope to think something different and implement it such that to make work. 

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

After the implementation of this project, the omindex indexer will use external extractor programs which are available as shared libraries. These libraries will be loaded dynamically during the runtime which will avoid the expense of running other external filters and hence, will speed up indexing as dynamic linking is noticeably faster than static linking. Hence, users of omega will benefit as the search time will be reduced.  

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

The project is divided into 4 subprojects -

1) Many modern file formats are based around the zip file format with XML contents. So using a zip file reading library instead of the unzip program would is the first target. Currently, Omega uses zlib to read gzip compressed Abiword files. To cover these formats - using libarchive is probably a sensible option. Implementing this library is the first subproject.
2) Currently the extraction of text from a PDF file is done by running external commands pdfinfo and pdftotext on it and reading their output whereas those two commands use libpoppler to do their work. Hence, using libpoppler and saving running two commands per PDF file would be desirable instead of creating two child processes, and two times any set up and tear down libpoppler doe. Implementing this library is the second subproject.
3) DjVu is a web-centric format which can display documents and images. DjVuLibre can be used as an extractor for these type of files. Implementing this library is the third subproject.
4) There are number of other file formats which require external filter programs and can be replaced by available libraries. Although if we could not cover all the libraries available, we could give priority to the file formats which are used more than others such that the overall indexing speed can be reduced by a noticeable amount. This is the fourth subproject.

The approach for making the libraries work on replacement of external filter programs with shared libraries having same functionalities and hence reducing the time required for indexing is to dynamically load at the runtime. Also, to avoid library bugs from crashing omindex, they can be implemented in a subprocess isolated from the parent process. The output of the child subprocess created using fork() syscall could be piped to the parent process. Another issue is if the library ends up in a memory or CPU eating infinite loop. This can be avoided by using sandboxing to put resource constraints on the process so that the loop will eventually terminate.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

Preliminary findings are from the implementation of Olly's patch (which adds supportfor using libwv2) that isolating it in a subprocess does avoid bugs in the library from crashing omindex. Hence, this method is likely to work. 

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**
Other approach could have been to compile all the current external filter programs into a single shared library which can be used instead of other available libraries.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

The uncertainties which can appear would mostly be about using the libraries and their functionalities aptly. The documentations can help in this case. In any case, the usage of libraries would be isolated from omindex. 

**How useful will your results be when not everything works out exactly as
planned?**

The project is broken down into various subtasks which can be implmented independently of each other. In case of any delay or change in plans, the implemented part would still work. 

Deliverables
-------------
* Implementation of libarchive library for reading formats based around the zip file format instead of running the unzip program.
* Use of the PDF rendering library libpoppler in the PDF text extractor instead of running external commands pdfinfo and pdftotext.
* Implementing the DjVuLibre library for reading DjVu format
* Adding support to other file formats such as AbiWord, Microsoft Publisher, etc. using the libraries available.
* Using the functionalities of the libraries including loading them dynamically and run in a subprocess to avoid the bugs in the library to be isolated from omindex. 

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

* Pre-acceptance Period from Present to May 5th
	This one month period can be utilized to work on issues related to omega so that I can get familiar to the codebase and also to gain some familiarity to Linux system programming.
	
* Community Bonding Period from May 6th to May 26th
	Understand the usage of the shared libraries to be used to replace external filter programs by reading the documentation and discussing it with mentors and continue working on issues related to omega.

					 ----- Coding officially begins -----

* Week 1 from May 27th to June 2nd
	Testing Omega before adding any library to the project and check how it runs with the verbose mode to get the grasp of the sequence of implementation of current source code. Continue search and understanding the usage of libraries. Discuss the outcomes with mentors.

* Week 2 and 3 from June 3rd to June 16th
	Implementing the libarchive library for reading zip file formats. Testing and documentation along. (This phase may take a longer time than expected as this is the beginning of coding)

* Week 4 from June 17th to June 23rd
	Implementing the libpoppler library for reading zip file formats. Testing and documentation along. Getting libarchive and libpoppler to work before Phase I evaluation will be my main goal.

					 ----- Phase 1 Evaluation -----

* Week 5 and 6 from June 24th to July 7th
	Implementing the DjVuLibre library for reading DjVu format. Testing and documentation along.

* Week 7 from July 8th to July 14th
	Although the libarchive would be able to read the AbiWord files, the extent of AbiWord is large. Hence, I would like to implement the library libabw in case the library crashes. This week can be devoted to it. Testing and documentation all along.

* Week 8 from July 15th-July 21st
	Implementing other libraries which are available after discussing with mentors. The overall number of libraries to be implemented can be less than the available but I think we could focus on the file formats which are used more than others.

					 ----- Phase 2 Evaluation -----

* Week 9 from July 22nd to July 28th
	Continue implementing other libraries.

* Week 10 and 11 from July 29th to August 11th
	Buffer period: Can be used if any of the previous work is lagged and shifted .Else continue implementing other libraries.

* Week 12 from August 12th - August 18th 
	Again this period can be used as a buffer period. Final testing and documentation and reviews on the documentation.

* Week 13 from August 19th - August 26th
	Finishing all the remaining tasks (probably testing and documentation) and preparing final report.

					 ----- Phase 3 Evaluation -----

NOTE - The pace of work is likely to be slow during the last two weeks as my regular classes begin. But I will try to re-organize the scheduleso that I can handle both.

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

Discussion on IRC with handle bazinga_65.

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1376

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

This project requires the use of existing code i.e. to import various open source file reading libraries such as Poppler, DjVuLibre and other available libraries from the Document Liberation Project.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
