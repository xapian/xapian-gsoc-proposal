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

============================
Python Bindings Improvements
============================

About You
=========

 * Name: Niwesh Gupta

 * E-mail address: niweshgupta@gmail.com

 * IRC nickname(s): niweshgupta

 * Any personal websites, blogs, social media, etc: http://linkedin.com/in/niweshgupta , http://facebook.com/niweshgupta

 * github URL: http://github.com/niweshgupta

 * Biography: 

.. Tell us a bit about yourself.

I'm Niwesh, a third year Undergraduate student at Heritage Institute Of Technology, Kolkata, 
India, majoring in Computer Science and Engineering. I'm interested in working on the 
project Improving Python Bindings for GSoC '19. I have good experience with Python and have also done various projects using it.

During my spare time, I participitate in various competitive programming challenges which has helped me improve my overall programming skills.
I find learning new skills and technologies very intriguing.


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

No, I don't have any prior experience with GSoC, GCI or other similar programmes.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

I have been checking and modifying xapian's code and its bindings for the past couple of weeks to understand it better. 
I only have experience with Google and Bing search engines.

**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have previously contributed to FreeCodeCamp by adding various examples and algorithms to its guide.

 link : https://github.com/freeCodeCamp/guide/commits?author=niweshgupta

Being a core memeber of Google's DSC Heritage, I've conducted a number of sessions related to open source and git.

On a daily basis, my tech life relies on many open source softwares namely Linux, LibreOffice, Firefox, Hex Chat etc.


**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

During my college curriculum, I have taken courses which include using git, valgrind, gdb and other testing/ development tools.

I have been writing Python codes since past 3 years and have done specialization in Python from Coursera which covered everything from basics to advanced topics like scraping and accessing web data using Python. Also, I'm the organizer and tutor at Python Hobby Group which is a part of ACM students chapter of Heritage Institute of Technology. 

I have won various inter college competitive programming competitions, have been to ACM ICPC Kharagpur (2017) and Amritapuri regionals (2018). 

Also as far as development is concerned, I've secured 3rd position in pre-qualifier round of NASA space apps challenge (Hackathon). 


**What development platforms, tools and methods do you prefer to use?**

- Operating System - Linux Mint
- Text Editor - Sublime Text
- Version Control - git

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

Uptill now, I do not have any involvement with any full fledged open-source project of similar scope. But, as we are talking about topics related to development, I am an active crew member of the Google DSC Developer's society of my college and have been constantly working on various projects one of which is an app that can be used by students to keep a track of their attendance.

**What timezone will you be in during the coding period?**

IST (Indian Standard Time) (UTC +5:30)

**Will your Summer of Code project be the main focus of your time during the
program?**

Yes, GSoC will be my main focus as I don't have any other commitments.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

Monday-Friday 10am - 6pm IST (UTC +5:30)

**Are you applying for other projects in GSoC this year?  If so, with which
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

Having a lot of experience in Python and PyPy, I would be able to execute this project with good perfection and majorly contribute to Xapian with my ideas. I'm so much excited to complete this project and finally execute "pip install xapian" in my terminal to watch Xapian's Python bindings running on virtual env.


**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

The developers and users of Xapian will majorly get benefitted from my project. It will become much easier for the python users to install and run Xapian using pip. PyPy bindings will become availabe for Xapian and PyPy users. 

Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

My project is entirely based on the existing Xapian Bindings for Python and Swig's -builtin function.

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

Xapian supports almost all of the languages other than PyPy. As Xapian has Python bindings, I'll also be able to write the same for PyPy.
I tried using -builtin function and written few testcases to test the difference in speed and memory usage with and without -builtin. By modifying the typemaps for exception handling, we'll be able to use -builtin for Xapian.

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

The only part in my project which can have different approaches is for the trac issue #263. There are two approaches which Olly has suggested Either: doxy2swig.py should combine the comments for all the possible overloaded forms, or we should provide manually written overrides for all cases where these forms exist. 

There's another potential option for this now - SWIG has fairly recently gained the ability to pick up doxygen-format documentation comments from the headers it is parsing and output them in the generated Python wrappers.

So I think I can try the last one suggested by Olly, it will be much easier of implement that and check how it compares to doxy2swig.py


Again, for the PyPy part, extending swig for PyPy will take so much time as suggested by James. So, wrapping a C++ library for PyPy is the option which is preferred by me.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

Not found so far.

**How useful will your results be when not everything works out exactly as
planned?**

Most of the tasks are divided into small independent subtasks. Therefore after the completion of each subtask, there will be useful result available. Also I plan to maintain the documentation along with each subtask so that the progress can be well tracked. Thereby making it easier to extend the work in future.

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

Overview:
	| First 2 weeks : Modify to use swig's -builtin function
	| 3rd week : working on issue #263 (https://trac.xapian.org/ticket/263)
	| 4th - 9th week : Adding support for PyPy
	| 10th - 12th week : Adding PyPI package for Python bindings

May 6 - May 27 (Community Bonding Period)

	- Getting to know Xapian's codebase better
	- Getting familiar with Swig's codebase (mainly Swig and Python part) to implement builtin
	- Discuss my approach to solve doccomments overloading issue


Week 1: May 27 - June 2


	- Figure out and pass -builtin with Python inside the required Makefiles
	- Adapt custom typemaps for excpetion handling
	- Rectify and debug other errors (if any)


Week 2: June 3 - June 9


	- Test the speed and memory usage with and without passing -builtin
	- Test whether it gives error for prewritten bindings code
	- Documentation of changes and getting things ready to merge


Week 3: June 10 - June 16


	- Modify doxy2swig.py to combine the errors for all possible overloaded forms
	- Discuss and test whether the error gets resolved by combining comments only
	- Testing overall bindings after modification
	- Merge the changed file


Week 4: June 17 - June 23, Week 5: June 24 - June 30 and Week 6: July 1 - July 7

	
	- Create module 'Xapian' to import from PyPy 
		- Get familiar with Xapian’s C++ API
		- Wrapping a C++ library for PyPy (The main task)
	- The wrappers which needs to be written :
		- Database
		- Document
		- Enquire
		- Query
		- RSet
		- Stem
		- TermGenerator
	- Take help from references of other language bindings :
		- Erlang		
		| Available from: https://github.com/arcusfelis/xapian-erlang-bindings/#readme

		- Node.js		
		| Available from: https://github.com/mtibeica/node-xapian#readme



Week 7: July 8 - July 14 and Week 8: July 15 - July 21


	- Buffer for previous work (if any)
	- Create Makefiles for PyPy to get easily installed with other language bindings
	- Write testsuite
	- Figure out and write testcases for smoketest
		- The objects are not freed instantly in PyPy when they are no longer reachable. This might reach OS's limit on number of concurrent files opened.
		- In many corner cases, CPython can silently swallow exceptions.
		- CPython has an optimization that can make repeated string concatenation not quadratic but we'll have to modify that for PyPy
	- Create smoketest file



Week 8: July 15 - July 21


	- Documentation for Pypy bindings
		- Without documenting the bindings, they aren't likely to be useful to anyone else
		- Add few example cases where there is much difference in PyPy compared to CPython
	- Add example codes with proper comments in Documentation
	- Merge the newly created PyPy bindings 


Week 9: July 22 - July 28


	- Create the necessary package files for PyPI package
	- Gather metadata and description to pass inside setup() in setup.py


Week 10: July 29 - August 4

	- Buffer for previous work (if any)
		- This week has less task as PyPy bindings can take more time than assumed
	- Create readme file
	- Discuss and create licence.md file
	- Generate distribution archive
	- Upload the generation archive


Week 11: August 5 - August 11


	- Install and test the newly uploaded package into virtualenv with different version of Python
	- Discuss the credentials and register at pypi.org for twine upload as the uploaded generation archive remains temporary
	- Test and fix bugs (if any)
		- Testing requires significant amount of time here


Week 12: August 12 - August 18


	- Finally, execution of "pip install xapian" into the virtualenv
	- Documentation of the PyPI package 
		- Good documentation with proper usage examples needs significant time.


Final Evaluations: August 19 - August 26

	- Final reading of documentation and discussion with mentor for any further changes
	- Final code submission for evaluations

Stretch Goals:

	- Include Xapian-core in the PyPI package
	- Add more PyPy examples


Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

I've discussed the project on IRC under the nickname 'niweshgupta'. 

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
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1399

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

As of now, I don't think I'll need to use any existing code which can have conflicting licenses. If found later, I'll discuss with my mentor before using the same. 

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
