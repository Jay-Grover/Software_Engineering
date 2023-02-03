<h3 align="center">IT314-Software Engineering Lab-1</h3>
<h3 align="center">Identifying Functional and Non-Functional Requirements</h3>

**Name:** Jay Grover<br/>
**ID:** 202001467<br/>
**Date:** 03-02-2023<br/>

<h3>A.1.</h3>
<h3 align="center">Indentification of functional requirements:</h3>

**New user registration:**<br/> To use the library's resources, a new student or member of the organisation must be a subscriber to the Library Information System. New users must register themselves for this. Every user receives a fresh user ID and password after successfully registering. A user must first log in with these credentials before issuing books.<br/><br/>
**User login:**<br/> A member can log into the Library Information System using their user id and password after properly registering. The user is directed to the home page after successful login, where they can issue returns or extend the return deadline. The user is displayed a message indicating a login failure and then redirected back after an unsuccessful login attempt. If a user tries to log in three times in a row without success, the account is temporarily locked and the user is given the option to change their password by having a link sent to their registered email address. The password must be reset in order to unlock the account. The locked account may be unlocked by the administrator.<br/><br/>
**Search book:**<br/> To determine whether a specific book is available in the institute's library, any member or non-member may use this option. You could search for a book using its title, authors' names, or publisher's name.<br/><br/>
**Isuue book:**<br/> Only a Library Information System member can issue a book to his account as long as:<br/>
a) The library has the required book.<br/>
b) No other member has issued the book at this time.<br/>
c) The current user has not issued the maximum number of books that can be issued.<br/>
The member receives the book if these conditions are satisfied. Professors can only issue a maximum of 10 books, while students and research scholars can only issue a maximum of 4 volumes. The successful issue of a book is reflected in the user account update.<br/><br/>
**Return book:**<br/> A book can only be published once (assumed 20 days). This borrowing duration may differ for various users, such as professors and students, and the administrator may adjust the maximum number of days permitted. The user account is updated to reflect the successful return of a book.<br/><br/>
**Reissue book:**<br/> Depending on whether his conditions are satisfied, any member who has issued a book may desire to keep it for longer than 20 days. In that situation, he can decide to republish the book and retain it for an additional 20 days. A member is only permitted to republish any book a maximum of twice before having to return it. The user account is updated to reflect the new information once a book has been successfully reprinted. A member may reissue a book solely in the event that no other member is interested in reading it.<br/><br/>
**Add/Drop books:**<br/> When a new book is bought, the librarian, who has administrative rights and total control over the system, can add a new record; similarly, if a book is taken off the shelf, a record can be removed.<br/><br/>
<h3 align="center">Indentification of non-functional requirements:</h3>

**Performance Requirements:**<br/>
a) This system should be online 24x7<br/>
b) At least 75 users should be able to access the system at the same time.<br/><br/>
**Security Requirements:**<br/>
a) This system should be accessible only within the institute LAN<br/>
b) The database of LIS should not store any password in plain text [a hashed value has to be stored]<br/><br/>
**Design Constraints:**<br/>
a) The LIS has to be developed as a web application using HTML 5 and it should work with Firefox 5, Internet Explorer 8, Google Chrome 12.<br/>
b) The web application should have the capability of modifications and updates so that the technology used does not get outdated too quickly and can be easily updated even if the developer team of the website changes.<br/>
<h3>A.2.</h3>
<h3 align="center">Identify scope, features and non-functional aspects of the problem</h3>

**Scope:** <br/>The primary objective of the project is to provide an application for those who have hearing loss. Their daily needs for communication and safe travel will mostly benefit from it. This programme would have a massive user base and receive government funding because it will be for the benefit of society. They make up about 5% of the world's population. Due of its real-time nature and potential for user and environment interaction, this will be a very effective solution.<br/><br/>
**Features:** <br/> a) To identify important sound occurrences of importance to this community, such car horns and infants, our mobile application will use artificial intelligence (Al). <br/> b) These will mostly consist of the continuous logging and immediate alerts that are essential to the user. <br/>
c) The system will employ several color schemes for urgent notifications, monitor behavior and alarms, and convey them to any members of its family or colleagues so they may take the appropriate action. <br/>
d) The network of the government will be directly connected to the system, allowing it to execute safety-related policies.<br/>
e) Continual logging of events in the app. <br/><br/>
**Non Functional Aspects:** <br/>
a) The application should be optimized in Android. The application should have low latency so that it works in real time.<br/>
b) It should have accessibility for deaf users. <br/>
c) The sound detection should be accurate and continuous. <br/>
d) It should be scaleable to accomodate large number of users. <br/>
e) It should be easy-to-use & Intuitive UI.<br/><br/>
