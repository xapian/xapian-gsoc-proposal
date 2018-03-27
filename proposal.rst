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
.. then pointing us at the fork by giving us a link or IRC or the mailing list.
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
Implement Bindings for Go
======================================

About You
=========

 * Name: Marco Younan

 * E-mail address: xmarcoied@gmail.com

 * IRC nickname(s): xmarcoied

 * Any personal websites, blogs, social media, etc: https://xmarcoied.github.io

 * github URL: https://github.com/xmarcoied

 * Biography: 

    I'm Marko Mohsen from Egypt, a 23 years old guy who study computer engineering at University of Ainshams.
    a pinaist who can write codes. I am so passionate about the internet as my first passion. from building web applications to making the web and internet a better place, secured and interactive.
    Through college, I found myself in love with programming and contents/competitions. (I joint many, and got qualified to ACM-ACPC the arab regional contest twice)

    I also joint some local activities in my college, start new intiaitives and so. and have been an active member at `sefrwahed <https://facebook.com/zeroone.asu/>`_ for years, and developed sessions for JS/Go before.

    Golang has became my main passion. I write in Go almost everyday, to solve problems on competitive websites (CF,Hackerrank) and for backend/server development and for desktop (CLI) programs. and I am always curious for new in Go.


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

Yes, I did `GSoC last year with Videolan <https://summerofcode.withgoogle.com/archive/2017/projects/5266266902233088/>`_. My project was about build a new update server to manage releases, update requests and so.
Most of the code I did in summer relies `here <https://code.videolan.org/GSoC2017/Marco/UpdateServer>`_ . but I continued working on it till it get merged to VLC.
also customized it for my college.

the project was written in Golang, and I felt in love with the language. also was encryption, servers and infrastructure interfacing.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I am new to Xapian (to be honest), but I used Elastic Search and Beats (in Go) before. also worked on a project using `Bleve <https://github.com/blevesearch/bleve/>`_

**Do you have previous experience with Free Software and Open Source other than
Xapian?**

I've been time with Videolan.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

Previous Internships:

    (Software Engineering Intern , Microsoft Research Cairo)

    With bing.com-team . Implementing data-mining pipeline and dashboard to provide statistics and user engagement numbers for Bing

Projects I worked on:
    
    Through college, I was lucky to work on many web-based projects. (I'd like to list :simpldon (simpldon.com) and racingteam (asuracingteam.org))
    
    Also, I've been time developing in Golang, and some of what I develop is opensourced (would like to list: goexams, cloneAll, GoTasker, ,GoMovies)

What development platforms, tools and methods do you prefer to use?
 * Platforms: Linux(Ubuntu) , Windows 
 
 * Tools : git , visualstudio code , vim , make
 
 * Methods: TDD

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

I haven't worked with a typical binding project before, but I worked on mirroring/translating packages to GO.

**What timezone will you be in during the coding period?**

Cairo,Egypt (GMT+2) . but I will be felixable to work in other timing.

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes, I'll be fully committed to the program till the last minute of it.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

* Friday , Sunday : 3~5 Hours
 
* Week days: 8~10 Hours

 I am not yet sure about timing, but I'll try my best to catch with my mentor timing and so.

**Are you applying for other projects in GSoC 2018?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

No. only you, xapian.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

The project is using Golang, It's my passion.
building upon really useful tech (xapian), and the project itself is challenging to me. also beneficial to me going through a whole project with mentorship and the golang/xapian communities.

Finally, it's going to be fun:)

**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

I think, the binding project meant to serve the xapian, also the target-language (Go in my case).

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

The project aims to implement/support Golang on xpaian
support ambiguous cases, renaming, pattern renames and so. and mostly using `Go typemaps <http://www.swig.org/Doc3.0/Go.html#Go_typemaps>`_. stuff like try-catch to golang panic.

The project will use SWIG for writing most of the Golang codes, so the very first work is about modifying needed swig interfaces.

Example of swig golang generated codes for C++ classes(`here <http://www.swig.org/Doc3.0/Go.html#Go_classes>`_)

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

My approach to binding c/c++ xapian codebase to go can be similar to other already-in-use xapian bindings, also suggested at `Golang FAQs <https://golang.org/doc/faq#Do%5FGo%5Fprograms%5Flink%5Fwith%5FCpp%5Fprograms>`_

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

    * At first, we can translate the whole xapian code to go. but it's anyway applicable. one reason that it would be hard to keep updating the projects (mirroring), also it's huge to build xapian from scratch.
    * Second approach (option) is developing the calling C/C++ from Go programs, so finally we can have written Golang statements. other than SWIG was cgo. which is so hard (or impossible to implement for c++ programs)

**Please note any uncertainties or aspects which depend on further research or
investigation.**

Well, I haven't used SWIG for larger (scale) project. but I explored other ready-in-use bindings for xapian. 
there might be ambiguous cases/corners , also challenges for making the APIs so natural for Go.
also, maybe specializing things to use Go concurrency or others (channels, routies etc..)

**How useful will your results be when not everything works out exactly as
planned?**

Well, There're already a trail (proof of concept) for the project. so I am expecting in the worsecases (or my risk plan).
I'll providing a better vision for what stopped there, leaving the code simple as I can to be easy to update anytime later when the C++ chances.

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

**Now - May 14**
        * read more about Xapian, and its APIs, classify related classes and so.
        
        * working more with swig and go

**May 14 - June 11**
    * week #1 working-on/change the "configure.ac" , "Makefile.am" in the xapian-binding , cutomized swig-golang interfaces
    * week #2 Query support at xapian-go 
    * week #3 MatchDecider , Database/* support at xapian-go 
    * week #4 Mset , Eset support at xapian-go 
**June 13 - July 9**
    * week #1 ExpandDecider/* , ValueRangeProcessor support at xapian-go  
    * week #2 implement other existing classes 
    * week #3 Support Non-class functions (after this, we should use the non-class functions at xapian in xapian-go)
    * week #4 improve exceptions/error-handling and writing tests for xapian-go
**July 13 - August 13**
    * week #1 writing examples for xapian-go (simpleexpand.go , simpleindex.go , simplematchdecide.go , simplesearch.go)
    * week #2 writing docs (index.rst) for xapian-go APIs , (docs/bindings/go) , (godoc.org/xapian/xapian-go) & writing more tests for xapian-go-testing
    documentation will be more specific for golang community at godoc.org for golang-users (gophers), also at docs/bindings/go for xapian users.
    
    * week #3 (pencil down): develop example with a real set of data and work with go-tooling
    
    * week #4 (offical  pencil down date): Fixing minor bugs, work on merging codes, and publish documentations and xapian-go package

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

I had a little discussion about the know-how binding in the `mailing-list <https://lists.xapian.org/pipermail/xapian-devel/2018-March/003247.html>`_, also IRC before.

but just a little.

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1376

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

None.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
