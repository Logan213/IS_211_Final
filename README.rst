###########################
Final Project: Book Catalog
###########################

Given my interest in working with data, including databases, apis, and queries,
I chose to complete the Project Option 1, which involved creating a book
catalogue.

********
Overview
********

Interface
=========

I borrowed heavily from the Flask tutorial, using the same initial setup, and
modifying the html and css files.  I was able to learn a bit about how to
manipulate both the templates and the css file to work with my web app, so I
have more than just a white screen with plain black lettering.

Upon starting the app, the user will be taken to the login screen, which has
links to the index (homepage), isbn lookup, and login pages. I was able to only
allow the user to use the lookup function by being logged in. The login page is
not located on the main page, but the user is directed to the login page by
either using the link in the menu, or within the text.

Login Display
=============

Upon successful login, the user will be presented with their book catalog
(library) if any books have been entered.  If the library is empty, the table
will display a message recommending the user to lookup ISBNs to add with a link
to the ISBN lookup function.

After adding books, they will be displayed with the requirements given in the
project outline (ISBN, Title, Author(s), Page Count, Average Rating), along with
an option to delete that particular book from the library.

ISBN Search
===========

I enjoyed working with JSON returns in IS 210, and have used them quite a bit in
my data acquisition course this semester. I found that using the same framework
from the Flask tutorial and making a few changes to the adding and display of
the information returned by the ISBN lookup to be fairly straightforward. Making
everything work still took a bit of work. The ISBN search will still flash an
error if the number entered contains any dashes; I will revisit this by trying
to utilize regular expressions or strip functions.

**********
Conclusion
**********

I found that working with Flask to be fairly intuitive, and the part I have the
most trouble with is utilizing thehtml end of it, given my lack of experience
with web developing. I plan to complete some W3, Codecademy, or similar
tutorials to get a better grasp on this end of it. I actually have a need to
create my own databases and webforms at work, so I will be continuing my
education with Python and Flask after this course is over.
