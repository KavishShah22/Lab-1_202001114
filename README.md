# Lab-1_202001114
<!-- Submission of IT314 Lab1 -->

### Name - Kavish Shah
### Student ID - 202001114
### Course - Software Engineering (IT314)

## <center>Lab 1
 
### Q1. Library Information System
<br> 

A) Functional Requirements:

a) Requirements for librarian:
- To be able to access the entire collection of book and articles.
- To be able to check which books have been issued currently and by which member.
- To be able to add and delete a book in the records of the library system if a new book is added or if an existing book is taken off the shelf respectively.
- To be able to issue books to members requesting them and making the changes in the database that the book has been issued and also the due date of the return.
- To be able to inform the member when the book will be available if he/she has requested for a book that is currently unavailable and to also book it in advance for the member so that the member could issue it once it becomes available.
- To be able to add, update, edit and delete articles available for the users to read online.
- To be able to create an account for a new user who may be having some difficulty doing it himself. 
- To be able to group/categorise books according the subject/topic so that it becomes simpler for users to find books they are searching for.

b) Requirements for members:
- To be able to login to their account.
- To be able to check details of their previously made transactions.
- To be able to view the due date of the books they have issued but haven't returned yet.
- To be able to view fines that are applicable on him if he has not returned books on time.
- To be able to borrow books online from his account.
- To be able to check the time when a particular book is getting available if it isn't available currently and also to book it in advance so that when the book becomes available he could issue it.
- To be able to extend the borrowing of a book he has borrowed if there are no bookings made for the book.

c) Requirements for guest users:
- To be able to able to search books online.
- To be able to register as a member if he is a student/staff of the institute.
<br>
<br>

B) Non Functional Requirements:

a) Safety Requirements:
- The system must be durable. In case of a crash due to power failure or virus attack, the data should be backed up to minimise data losses.

b) Security Requirements
- There will be 3 categories of users - librarian, members and non-members/guest users. So it is important to differentiate rights given to them as is decided. Any user should not be able to access data that he does not have the rights to.

c) Software Quality and Interface Requirements:
- The interface should be made in a user friendly way where he must not be made thinking where to find a particular option or what to do after performing a specific action. New users should also not get irritated after using the system.

<br>
<br>
<br>

### Q2. Mobile Application for the aid of people with hearing disability

<br> 

A) Scope:

Approximately 5% of the total world population i.e. a stagerring 466 million people are suffering from hearing disability. Their health and safety is a huge point of concern. To ensure their safety and also to track their treatment progress, a mobile application can prove to be very beneficial. The mobile application can use cloud technology to store the results hearing tests performed by the user previously and provide tracking data to monitor their hearing condition. The tracking data would be beneficial to show that if the user is undergoing some traetment then the treatment is working well or not. The application would also have safety features for the user. These features would include the signalling the user by vibration if cars are honking nearby. This would alert the user if he is crossing a road. The application would also detect the sound a babies in case a baby is lost and is somewhere around. There are many more advantages of this application so its scope is very wide.
<br>
<br>


B) Functional Requirements:

Requiremnts for users with hearing disability:

- To be able to login to their account.
- To be able to check their past tests data.
- To be able to track the progress of the ongoing treatment if any.
- To be able to share his test data with his doctor.
- To be able to turn on road crossing mode where he would get alert signals if a car is honking nearby. 
- To be able to get alert signal if a baby is crying nearby.

Requirements for doctors:
- To be able to track the data of their patient.
- To be able to notify his patient about further treatment process and tests to be perfomrmed.

<br>
<br>

C) Non Functional Requirements:

a) Safety:
- The system should be durable. In case of any system crash/failure, user data must not be lost. Backup should be available.

b) Security:
- There are 2 types of users - patient and doctor. So abstractness must be maintained between the users.

c) Software Quality and Interface Requirements:
- The interface should be made in a user friendly way where he must not be made thinking where to find a particular option or what to do after performing a specific action. New users should also not get irritated after using the system.
