OppiaMobile Server Change Log
================================

.. _serverv0.12.6:

v0.12.6 - not yet released
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_6
	
Key updates:


Issue list:

* OPPIA-281 Add v2 of the API on the server
* OPPIA-285 Store time taken for quiz attempts
* OPPIA-275 Class based views for activitylog
* OPPIA-273 Class based views for content
* OPPIA-18 Cursor error when running summary cron on SQLite db
* OPPIA-200 Graphs on summary page aren't formatted correctly
* OPPIA-264 Class based views for profile/manage
* add django admin search options for some models
* Updated Pillow package
* OPPIA-228 Add API endpoint to return the media embed variables
* OPPIA-260 Show full list of activities and digests for a course


.. _serverv0.12.5:

v0.12.5 - released 18 Mar 2020
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_5
	
Key updates:

* Update to Django 2.2.10
* Option to update profile
* Improved configuration options
* Sonarcloud and Django code improvements implemented

Issue list:

* OPPIA-193 Django-GCM package no longer required
* OPPIA-206 Move OPPIA_ALLOW_SELF_REGISTRATION to be bool instead of int
* OPPIA-28 Activity map page configuration
* OPPIA-16 Github actions: new migration
* OPPIA-17 Github actions: static files
* OPPIA-197 Fix the sonarcloud code smells for oppia server
* OPPIA-258 Fix next redirection vulnerability
* OPPIA-241 When downloading a course from the server interface, it doesn't 
  increase the "downloads by users"
* OPPIA-191 Use get_or_created in uploader.py
* OPPIA-262 Class based views for reports
* OPPIA-249 Class based views for av
* OPPIA-13 Remove management command to update short answer scores
* OPPIA-197 Fix the sonarcloud code smells for oppia server
* OPPIA-276 Migrate to using django.urls.path()
* OPPIA-277 Add email field in the LOGIN response
* OPPIA-95 Add option for user to edit their profile - online only



.. _serverv0.12.4:

v0.12.4 - released 29 Jan 2020
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_4
	
Key updates:

* update to Django 2.2.9
* additional tests and improved code coverage (85%+)

Issue list:

* 717: Create OppiaTestCase class to be used in tests
  (`#717 <https://github.com/DigitalCampus/django-oppia/issues/717>`_)
* 586: Add tests for quiz/management/commands/check_duplicate_quizzes.py
  (`#586 <https://github.com/DigitalCampus/django-oppia/issues/586>`_)
* 721: Add permissions and tests for the new QuizAttempt/detail views
  (`#721 <https://github.com/DigitalCampus/django-oppia/issues/721>`_)
* 566: Add tests for profile password reset
  (`#566 <https://github.com/DigitalCampus/django-oppia/issues/566>`_)
* 550: SonarQube - complexity of profile/views.py - several functions
  (`#550 <https://github.com/DigitalCampus/django-oppia/issues/550>`_)
* 713: Quiz language dictionaries not being saved correctly
  (`#713 <https://github.com/DigitalCampus/django-oppia/issues/713>`_)
* 710: Add tests for gamification/forms.py
  (`#710 <https://github.com/DigitalCampus/django-oppia/issues/710>`_)
* OPPIA-32 - Move some other settings from settings.py/settings_secret.py to
  SettingProperties

.. _serverv0.12.3:

v0.12.3 - Released 20 Dec 2019
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_3
	
Key updates:

* Allow custom fields for profile form
* API for profile updating
* Refactoring of API code
* SonarCloud fixes for duplicate code, code smells and test coverage
* Remove deprecated quiz API endpoints

Issue list:

* 697: Fix email sending
  (`#697 <https://github.com/DigitalCampus/django-oppia/issues/697>`_)
* 692: Add specific test for implementation
  (`#692 <https://github.com/DigitalCampus/django-oppia/issues/692>`_)
* 645: Emailing password reset not working
  (`#645 <https://github.com/DigitalCampus/django-oppia/issues/645>`_)
* 682: Update user profile to include custom fields
  (`#682 <https://github.com/DigitalCampus/django-oppia/issues/682>`_)
* 687: Add API endpoint for user to update their profile info
  (`#687 <https://github.com/DigitalCampus/django-oppia/issues/687>`_)
* 699: Split out api/resources.py into separate files
  (`#699 <https://github.com/DigitalCampus/django-oppia/issues/699>`_)
* 605: Remove signup_callback function
  (`#605 <https://github.com/DigitalCampus/django-oppia/issues/605>`_)
* 660: In tests for file opening use `with ... as ...` instead of file=
  (`#660 <https://github.com/DigitalCampus/django-oppia/issues/660>`_)
* 700: Course_download_views allows anyone to download any course
  (`#700 <https://github.com/DigitalCampus/django-oppia/issues/700>`_)
* 684: Remove OPPIA_*_EARN_POINTS settings
  (`#684 <https://github.com/DigitalCampus/django-oppia/issues/684>`_)
* 709: Upload users function does not work
  (`#709 <https://github.com/DigitalCampus/django-oppia/issues/709>`_)
* 552: SonarQube - complexity of 
  quiz/management/commands/update_short_answer_scores.py handle function
  (`#552 <https://github.com/DigitalCampus/django-oppia/issues/552>`_)
* 587: Duplicate code blocks in quiz management commands
  (`#587 <https://github.com/DigitalCampus/django-oppia/issues/587>`_)
* 548: SonarQube - complexity of oppia/uploader.py - several functions
  (`#548 <https://github.com/DigitalCampus/django-oppia/issues/548>`_)
* 551: SonarQube - complexity of quiz/api/serializers.py format_quiz function
  (`#551 <https://github.com/DigitalCampus/django-oppia/issues/551>`_)
* 547: SonarQube - complexity of oppia/signals.py tracker_callback function
  (`#547 <https://github.com/DigitalCampus/django-oppia/issues/547>`_)
* 712: Quiz API... mainly deprecated?
  (`#712 <https://github.com/DigitalCampus/django-oppia/issues/712>`_)
* 678: Display user full quiz attempts and responses
  (`#678 <https://github.com/DigitalCampus/django-oppia/issues/678>`_)
* 711: Split out oppia/view.py and profile/view.py into separate files?
  (`#711 <https://github.com/DigitalCampus/django-oppia/issues/711>`_)

.. _serverv0.12.2:

v0.12.2 - Released 27 Nov 2019
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_2
	
Key updates:

* Additional logging of course publishing
* Updates for PEP8/Flake8 formatting of code
* Add pytest integration with Github workflows
* Remove old/redundant code

Issue list:

* Updated version of Pillow -
  https://github.com/DigitalCampus/django-oppia/pull/669
* 441: Keep log of when a course is republished with the old/new activities -
  (`#441 <https://github.com/DigitalCampus/django-oppia/issues/441>`_)
* 542: Remove OPPIA_EXPORT_LOCAL_MINVERSION setting -
  (`#542 <https://github.com/DigitalCampus/django-oppia/issues/542>`_)
* 676: Add tests for quiz attempts in activity log upload -
  (`#676 <https://github.com/DigitalCampus/django-oppia/issues/676>`_)
* 680: Check that the server can be set up with SQLite as the db - 
  (`#680 <https://github.com/DigitalCampus/django-oppia/issues/680>`_)
* 512: Remove GCM push/device admin functionality
  (`#512 <https://github.com/DigitalCampus/django-oppia/issues/512>`_)
* 685: Add pycodestyle to requirements
  (`#685 <https://github.com/DigitalCampus/django-oppia/issues/685>`_)
* 672: Find out why media views showing as 0
  (`#672 <https://github.com/DigitalCampus/django-oppia/issues/672>`_)
* 683: Replace raw_input() with input()
  (`#683 <https://github.com/DigitalCampus/django-oppia/issues/683>`_)
* 688: Configure github workflow yml file
  (`#688 <https://github.com/DigitalCampus/django-oppia/issues/688>`_)
* 666: Make left hand side bar collapsible
  (`#666 <https://github.com/DigitalCampus/django-oppia/issues/666>`_)
* 692: Add specific test for implementation
  (`#692 <https://github.com/DigitalCampus/django-oppia/issues/692>`_)
* 667: test_quiz_attempt_points_included test failing
  (`#667 <https://github.com/DigitalCampus/django-oppia/issues/667>`_)
  

.. _serverv0.12.1:

v0.12.1 - Released 15 Oct 2019
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_1
	
Key updates:

* Updated version of Django
* Initial version of DHIS2 export

Issue list:

* 648: Update to django 2.2.x 
  (`#648 <https://github.com/DigitalCampus/django-oppia/issues/648>`_)
* 664: Cohort leaderboard shows empty page
  (`#664 <https://github.com/DigitalCampus/django-oppia/issues/664>`_)
* 663: Initial version of DHIS2 export
  (`#663 <https://github.com/DigitalCampus/django-oppia/issues/663>`_)
* 564: In management commands replace print() with self.stdout.write()
  (`#564 <https://github.com/DigitalCampus/django-oppia/issues/564>`_)

.. _serverv0.12.0:

v0.12.0 - Released 17 Sept 2019
--------------------------------

.. toctree::
   :maxdepth: 1

   upgrading/to_0_12_0

Key updates:

* Moving to Python 3 and Django 2
* Use material design layout

Issue list:

* 539: Moving to python 3 and django 2
  (`#539 <https://github.com/DigitalCampus/django-oppia/issues/539>`_)
* 468: RemovedInDjango20Warning - update for deprecation/changes
  (`#468 <https://github.com/DigitalCampus/django-oppia/issues/468>`_)
* 571: For python 3 - replace __unicode__ with __str__ in models
  (`#571 <https://github.com/DigitalCampus/django-oppia/issues/571>`_)
* 591: Update media_url_check to remove urllib2 dependency
  (`#591 <https://github.com/DigitalCampus/django-oppia/issues/591>`_)
* 601: Python 3 - v0.12.0 branch - check usage of urllib/urllib2/urllib3
  (`#601 <https://github.com/DigitalCampus/django-oppia/issues/601>`_)
* 640: Error with Gamification db migrations on v0.12 branch
  (`#640 <https://github.com/DigitalCampus/django-oppia/issues/640>`_)
* 577: Drawer menu for admin users
  (`#577 <https://github.com/DigitalCampus/django-oppia/issues/577>`_)
* 625: Crispy-forms - move to using the BootStrap4 template pack
  (`#625 <https://github.com/DigitalCampus/django-oppia/issues/625>`_)
* 639: Merge material design branch into latest dev branch
  (`#639 <https://github.com/DigitalCampus/django-oppia/issues/639>`_)
* 635: Points/gamification not working on staging server with python 3/django 2
  (`#635 <https://github.com/DigitalCampus/django-oppia/issues/635>`_)
* 636: Deprecation warning for BaseException.message
  (`#636 <https://github.com/DigitalCampus/django-oppia/issues/636>`_)
* 638: Fix tests for v0.12.0 branch
  (`#638 <https://github.com/DigitalCampus/django-oppia/issues/638>`_)
* 649: Date range selector with styles that match the customizable theme
  (`#649 <https://github.com/DigitalCampus/django-oppia/issues/649>`_)
* 646: Upload view fails if user has no associated UserProfile
  (`#646 <https://github.com/DigitalCampus/django-oppia/issues/646>`_)
* 650: Add tests for activitylog upload
  (`#650 <https://github.com/DigitalCampus/django-oppia/issues/650>`_)
* 655: Updates from SonarQube recommendations
  (`#655 <https://github.com/DigitalCampus/django-oppia/issues/655>`_)
* 585: Add tests for recent updates to activity log
  (`#585 <https://github.com/DigitalCampus/django-oppia/issues/585>`_)
* 189: Remove CourseXML class as no longer used?
  (`#189 <https://github.com/DigitalCampus/django-oppia/issues/189>`_)

Previous Versions
------------------

.. toctree::
   :maxdepth: 2
   
   changelog_server_v0.11
   changelog_server_v0.10
   changelog_server_v0.9
   changelog_server_v0.8
   changelog_server_v0.7
   changelog_server_v0.6
   changelog_server_v0.5
   changelog_server_v0.4
   changelog_server_v0.3
   changelog_server_v0.2
   changelog_server_v0.1