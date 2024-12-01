# Club-Membership-Management-System
Implemented a system to manage club member records, allowing filtering and displaying based on criteria like join date, membership type, and team affiliation.
_______________________________________________________________________________________________________________________________________________________________

Club Membership Management System
_______________________________
Overview:
The provided code constitutes a basic Club Membership Management System implemented in Java. It is designed to manage information about club members, including their personal details, membership types, and join dates. The system allows for the creation of member records and performs various operations such as filtering and displaying member information based on specific criteria.
 
Classes:
Date Class: Represents a date with day, month, and year. It includes methods to compare dates and retrieve individual date components.
                                      -------------------------------------------------

 > Attributes: day, month, and year.
 > Constructor: Initializes the date attributes.
 > Method isBefore(Date d1): Compares two dates to determine if the instance date is earlier than the provided date.
-------------------------------------------------------------------------------------------------------------
 
Member Class: Represents a club member with attributes such as member ID, name, gender, handicap score, team, membership type, phone number, and join date. The class provides constructors to create member objects with different attribute combinations and a method to display member details.
                                      -------------------------------------------------
> Attributes: memberId, lastName, firstName, handicap, gender, team, memberType, coach, phone, and joinDate.
> Constructors: Allow for various combinations of member attributes.
> Methods: Include getters for different attributes, display() to print member details, and getHandicapScore() to retrieve handicap information.
 -------------------------------------------------------------------------------------------------------------

Main Class: Contains the main method and serves as the entry point for the program. It creates an array of member objects and demonstrates various functionalities of the Member class.
                                      -------------------------------------------------
> The main method initializes an array of Member objects with different attributes.
> It performs various operations:
> Displays records of members who joined before a specified date.
> Displays records of senior members with a handicap score less than 12.
 > Displays records of female senior members in a specific team.

 -------------------------------------------------------------------------------------------------------------


Functionality:
Display Members by Join Date: The program displays member records whose join date is earlier than a specified date (07-Apr-09 in the example). It utilizes the isBefore method of the Date class to compare dates.
 
Display Senior Members with Handicap Score: It lists records of senior members (members with a senior membership type) whose handicap score is less than 12. This operation involves filtering members based on their membership type and handicap score.
 
Display Female Senior Members in Team B: The program showcases female senior members who belong to Team B. It filters members based on their gender, membership type, and team affiliation.
 
Output:
The program produces formatted output displaying member details for each operation performed. The output includes member ID, name, handicap score, gender, team, membership type, coach (if applicable), phone number, and join date.
The Output Is : - 
                             
Members with join date earlier than 07-Apr-09: 
 
Member ID: 118
Name: Melissa McKenzie
Handicap: 30
Gender: F
Team: N/A
Member Type: Junior
Coach: 153
Phone: 963270
Joined on: 28-May-2005
 
Member ID: 153
Name: Brenda Nolan
Handicap: 11
Gender: F
Team: TeamB
Member Type: Senior
Coach: 0
Phone: 442649
Joined on: 12-Aug-2006
 
Member ID: 235
Name: William Cooper
Handicap: 14
Gender: M
Team: TeamB
Member Type: Senior
Coach: 153
Phone: 722954
Joined on: 5-Mar-2008
 
Member ID: 239
Name: Thomas Spence
Handicap: 10
Gender: M
Team: N/A
Member Type: Senior
Coach: 0
Phone: 697720
Joined on: 22-Jun-2006
 
Member ID: 290
Name: Thomas Sexton
Handicap: 26
Gender: M
Team: N/A
Member Type: Senior
Coach: 235
Phone: 268936
Joined on: 28-Jul-2008
 
Member ID: 332
Name: Deborah Bridges
Handicap: 12
Gender: F
Team: N/A
Member Type: Senior
Coach: 235
Phone: 279087
Joined on: 23-Mar-2007
 
Member ID: 414
Name: Jane Gilmore
Handicap: 5
Gender: F
Team: TeamA
Member Type: Junior
Coach: 153
Phone: 459558
Joined on: 30-May-2007
 
Member ID: 415
Name: William Taylor
Handicap: 7
Gender: M
Team: TeamA
Member Type: Senior
Coach: 235
Phone: 137353
Joined on: 27-Nov-2007
 
Member ID: 461
Name: Robert Reed
Handicap: 3
Gender: M
Team: TeamA
Member Type: Senior
Coach: 235
Phone: 994664
Joined on: 5-Aug-2005
 
Senior members with handicap score less than 12:
 
Member ID: 153
Name: Brenda Nolan
Handicap: 11
Gender: F
Team: TeamB
Member Type: Senior
Coach: 0
Phone: 442649
Joined on: 12-Aug-2006
 
Member ID: 239
Name: Thomas Spence
Handicap: 10
Gender: M
Team: N/A
Member Type: Senior
Coach: 0
Phone: 697720
Joined on: 22-Jun-2006
 
Member ID: 323
Name: Daniel Wilcox
Handicap: 3
Gender: M
Team: TeamA
Member Type: Senior
Coach: 0
Phone: 665393
Joined on: 18-May-2009
 
Member ID: 415
Name: William Taylor
Handicap: 7
Gender: M
Team: TeamA
Member Type: Senior
Coach: 235
Phone: 137353
Joined on: 27-Nov-2007
 
Member ID: 461
Name: Robert Reed
Handicap: 3
Gender: M
Team: TeamA
Member Type: Senior
Coach: 235
Phone: 994664
Joined on: 5-Aug-2005
 
Female senior members in Team B:
 
Member ID: 153
Name: Brenda Nolan
Handicap: 11
Gender: F
Team: TeamB
Member Type: Senior
Coach: 0
Phone: 442649
Joined on: 12-Aug-2006
 
Member ID: 339
Name: Betty Young
Handicap: 21
Gender: F
Team: TeamB
Member Type: Senior
Coach: 0
Phone: 507813
Joined on: 17-Apr-2009
 
Usage:
This Club Membership Management System can be utilized by clubs or organizations to maintain records of their members, track membership details, and generate reports based on various criteria such as join date, membership type, gender, etc.
 

