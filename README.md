# Zotero
======

[![Build Status](https://travis-ci.org/zotero/zotero.svg?branch=master)](https://travis-ci.org/zotero/zotero)

[Zotero](https://www.zotero.org/) is a free, easy-to-use tool to help you collect, organize, cite, and share your research sources.

Please post feature requests or bug reports to the [Zotero Forums](https://forums.zotero.org/). If you're having trouble with Zotero, see [Getting Help](https://www.zotero.org/support/getting_help).

For more information on how to use this source code, see the [Zotero wiki](https://www.zotero.org/support/dev/source_code).

======

# Aim of this fork: add rating system to Zotero, allow sorting of entries by rating when generating reports.

## Idea
Add a tab in the Attributes bar called "Ratings"
+ A rating can be customized with a title (ex. usefullness, relevance, reading time, reading difficulty, etc)
+ Each rating is out of 10 (or five stars with half stars). 
+ Ratings can be displayed for each item as little barcharts of "paper stats" (think car choices in mario kart)
+ Like Notes or Tags, there may be multiple ratings for a single entry 
+ Want to be able to sort entries by Rating (especially for report generation) 

## Milestones

1. Sketch idea 
2. Review how Info/Notes/Tags/Related are stored within Zotero
3. Replicate Notes implementation, figure out how to add Ratings to database
5. Understand display of Attributes tab
7. Add ratings to report output 
6. Add Ratings to column sorting 
8. Add ratings to report sorting
9. Investigate how ratings will effect Zotero cloud sync (database perturbation problematic?)
10. Intergration tests

*Pull request Zotero with this hot new feature!* 

