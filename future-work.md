Enhancements for Github-bookeditor and the OERPUB fork of Aloha-Editor 
======================================================================

This is a rough list of things that developers could get involved in extending in the bookeditor and page editor (fork of AlohaEditor). 

This first version may be a bit lean on context, in an effort to make sure that things are recorded. We will work to update the list with more context.

The OERPUB team works from a redmine instance and from pivotal. Those detail current issues found and work planned. This list has projects that haven't yet been started. They are in order of memory, not of priority.

github-bookeditor
==================

1. Replace the current web view of the books with EPUBjs with Hypothes.is annotation integrated. (Come to the BIB13 hackday!)
1. Firefox support for github-bookeditor. This used to work, but currently is broken. 
2. IE support for github-bookeditor. The Aloha-Editor team works hard to keep IE supported, so we should also be able to.
3. Edit and save metadata for the ebooks.
4. Save the html in a pretty printed format so that edit differences are always meaningful.
5. Include link to download an EPUB of the book. Can almost just link to the github repo zip. But need to unwrap one level and make sure that only one book is included.
 1. May want to use branches to create clean EPUB version of each book in a repository.
6. Include link to download PDF of book (from the continuous PDF service)
7. Validation on save. 
8. Converting back and forth between sections and headings. The editor uses headings to represent sections which are representable by headings. Complex sections are left as is.
9. Finer grain collaboration support -- ability to simultaneously change a single page in abook.
10. Import a book. (Needs a service to copy into an existing git repo)

page editor (OERPUB Aloha Editor fork)
======================================

1. Switch from using class to using data-type to record semantics.
2. Implement inline editing features from the mockups
3. Implement sweep away formatting for semantic blocks
4. Implement "convert to" for semantic elements.
5. Multimedia -- add video, audio, slides, etc.
5. Put the cheatsheet functionality back in. Create cheatsheet for LaTeX. Use mathjax to render the cheat previews rather than images.
6. Paste cleanup -- paste from word, open office, or html brings in unwanted styles. 
7. Undo support
8. Performance of large documents
 1. Deeply nested semantic structures.
 2.  Lots of math
 3. Lots of images

both
====

1. Font for new icons
2. Accessibility 
 1. For learners
   1. Add metadata so can discover appropriate content
   2. Enrich plugins to create more accessible content. 