-----------------------------------------------------------------------SRS DOCUMENT-----------------------------------------------------------------------------------------
SRS-(Software Requirements Specification)
It is like a blueprint for building a software.

1.Introduction

This SRS Document describes the software requirements for Fable.co, This web platform aiming to connect writers and readers,story sharing,purchase of story books.

This web platform will allow users to:
·Browse,read,purchase books,Authors can submit stories,Readers can comment,Payment gateway integration,manage user profiles.

References
·Payment gateway documentation (e.g. Stripe / Razorpay)
·Web hosting / deployment guidelines
·GDPR / privacy policy compliance documentation
·Any style guides for UI/UX

2.Overall Description
·Fable is a standalone web-based system,with mobile-responsive design.It interacts with external services:payment gateway,email services.

·Product Functions
a)User Registration/login/sign up/logout/password reset.
b)Author dashboard.
c)Reader can book mark a book,can rate the book.
d)can read online.
e)Notifications.

Operating Environment
·Web browsers:chrome,brave,safari,chrome.
·Platforms:Windows,Mac,Linux,IOS,Android.
·Email,notification service

3.Specific Requirements
User Interfaces
·Web GUI for readers,authors,admin.Modern UI.
·Theme:clean,minimal,readable typography.

API Interfaces
·Public API's for content retrival.
·Payment gateway API.
·Email/notification service API's.

Software Interfaces 
·Integration with database.
·Integration with party services:payment,email,analytics.

Data Requirements
·Data model for users whether it is reader,author,Stories,Comments,Rating,Book marks.
·Sensitive data(passwords,payment)should be encrypted.
·Data retention policy:Keep user data for n years,deletion takes place when user sent's a request.

System Features
·Dark/Light mode for reading interface.
·Offline reading or download.
·Search suggestions.





