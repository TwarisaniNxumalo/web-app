<a name="br1"></a> 

DELIVERABLE 2

Team Name: **Innovation Quad**

![WhatsApp Image 2024-04-18 at 22 23 51_4780e5dd](https://github.com/IFMTYP2024/team13-main/assets/143531070/6c6c2474-9f1a-4218-ac29-3273273ae76d)

Project Name: **Carpooling**

Team Number: **13**

Mentor Name: **Mr Maluleka**

**Team Members:**

**->Twarisani Nxumalo**

**->Yingisani Honest Shivambu**

**->Tylon Takaidza**

**->Rishongile Tshabalala**



<a name="br2"></a> 

**Updated Problem Statement, Proposed Solution & Use Case**

**Problem Statement:**

Lift Search app faces the challenge of users bypassing the platform to pay each

other directly, leading to potential conflicts between drivers and passengers.

Additionally, the accuracy of matching pickups and drop-offs needs improvement

to enhance user satisfaction.

**Proposed Solutions:**

**Subscription-Based Model:**

To discourage direct payments and foster trust within the carpooling

community, we will introduce subscription plans for passengers. These plans

will offer incentives and value-added services, such as priority matching and

discounts, encouraging users to transact through the app. The platform will

ensure transparent and conflict-free transactions while generating revenue to

sustain operations and enhance user experience.

**Enhanced Matching Algorithm:**

To improve the accuracy of matching pickups and drop-offs, we will implement

a radius check feature in our app. Utilizing the Haversine Formula for

calculating the distance between two points on a sphere (like the Earth) given

their longitude and latitude, we will calculate the straight-line distance

between the driver's current location and the passenger's destination.

Additionally, Google Maps offers a Distance Matrix API that calculates travel

distance and time between multiple origins and destinations, including various

travel modes (driving, walking, cycling, etc.). We will use this API to calculate

the driving distance between the driver's route and the passenger's

destination, factoring in real-time traffic. By calculating distances between

passenger destinations and driver routes, incorporating user-defined radius

parameters, and considering factors like traffic conditions, our algorithm will

optimize matching efficiency, ensuring that passengers' destinations fall within

a specified distance from the driver's route, thereby enhancing user

satisfaction and the overall effectiveness of the app**.**



<a name="br3"></a> 

**Use Case Descriptions**

**User Authentication Subsystem**
![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/3e0aa86a-7a08-4381-b589-9a29f66d5c39)
**Register**

**Input:** Driver and Car, or Passenger details.

**Output:**

1\. The customer or driver will click the sign-up button on the welcome

page.

2\. The system will display the registration page.

3\. The driver or passenger will enter all the required details and submit.

4\. The system will respond by capturing the passenger or driver

information and sending a notification to the customer or driver for

successful registration.



<a name="br4"></a> 

**Extensions:**

**1. User enter incorrect registration details.**

\- an error message indicating the login credentials are incorrect.

\- System ask the user to re-enter the details

**Login**

**Input:** Driver or Passenger login credentials

**Output:**

1\. The passenger or driver will click the sign-in button.

2\. The system will respond by displaying the login page.

3\. The passenger or driver will enter their username and password and

click the login button.

4\. The system will display the driver or passenger to the home page

according to the user type

**Extensions:**

**1. Users enter incorrect login credentials**.

\- an error message indicating the login credentials are incorrect.

\- User clicks on the "Forgotten Details?" option.

\- System displays the error message.

\- System presents the "Forgotten Details?" option alongside the error

message.

\- User selects to reset password via OTP.

\- System redirects the user to a password recovery page.

\- User inputs their registered email address or username.

\- System waits for user input and validates the provided information.

\- User submits the information.

\- System validates the provided email address or username.

\- System generates and sends an OTP to the user's registered email address

or phone number.



<a name="br5"></a> 

\- User checks their email inbox or phone for the OTP.

\- System waits for the user to check their email or phone.

\- User inputs the received OTP.

\- System verifies the provided OTP.

\- User sets a new password as per the system's requirements.

\- System prompts the user to set a new password.

\- User confirms the new password.

\- System verifies that the new password matches the confirmation.

\- System updates the user's password with the newly provided one.

\- User's password is updated in the system.

\- System displays a confirmation message confirming the successful

password reset.

\- User receives a confirmation message indicating the successful password

reset.

\- Optionally, the system redirects the user to the login page for immediate

login with the new credentials.

\- User is redirected to the login page.



<a name="br6"></a> 

**Passenger Management System**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/2aec6196-7d4c-4d3b-bddb-0371da1dba0c)

**Search for Trips:**

**Input:** The pickup point location and destination location.

**Output:**

1\. The passenger accesses the trip search feature on the mobile or

web application.



<a name="br7"></a> 

2\. The system presents options for the passenger to input their desired

pick-up location, destination, and preferred trip time.

3\. Upon entering the trip details, the system retrieves and displays a list

of available

trips matching the criteria.

4\. The passenger can browse through the list of trips, filtering by

factors such as drivers’ location, departure time, and driver ratings.

5\. After finding a suitable trip, the passenger selects it to view more

details and proceed with booking.

**Extensions:**

**1. User enter incorrect invalid location details.**

\- an error message indicating the invalid destination or pick up location.

\- System ask the user to re-enter the details

**Select Preferred Driver**

**Output:**

1\. After viewing trip details, the passenger selects a preferred driver

from the list of available drivers for the trip.

2\. The system displays additional information about the selected driver,

including their profile, ratings, and vehicle details.

3\. The passenger reviews the driver's information and confirms their

selection.

4\. Upon confirmation, the system present subscription options

5\. The passenger selects the preferred subscription option and make

payments.

6\. the system assigns the selected driver to the passenger's trip

booking and notify driver and the passenger.

**Manage Profile:**

**Output:**



<a name="br8"></a> 

1\. The passenger navigates to the "Profile" or "Account Settings"

section within the app or website.

2\. The system displays the passenger's profile information, including

name, contact

details, and account preferences.

3\. The passenger can edit their profile information, such as updating

their contact information or changing their password.

4\. After making changes, the passenger confirms the updates by

clicking a "Save Changes" button.

5\. The system verifies the changes and updates the passenger's

profile, accordingly, reflecting the modifications made by the

passenger.

**Rating and Reviews:**

**Input:** Paragraph explaining user experience during the trip & quantity of stars

to rate the driver

**Output:**

1\. After completing a trip, the passenger navigates to the trip details

page.

2\. The system displays an option for the passenger to rate and review

the trip

experience.

3\. The passenger selects a star rating and provides optional feedback

in the review

section.

4\. The system records the rating and review, associating it with the

respective trip and driver.

**View Trips History:**

**Input:**

**Output:**



<a name="br9"></a> 

1\. The passenger accesses the "Trips History" section in their account

settings or dashboard.

2\. The system displays a chronological list of all past trips taken by the

passenger.

3\. Each trip entry includes details such as trip date, driver name, pick-

up, and drop-off locations.

4\. The passenger can scroll through the list to view past trips and trip

details.

**Manage Subscriptions:**

**Output:**

1\. The passenger navigates to the "Subscription Management" section

in their account settings or dashboard.

2\. The system displays the current subscription status and available

subscription options.

3\. The passenger can choose to upgrade, downgrade, or cancel their

subscription.

4\. Upon selecting an action, the system prompts the passenger to

confirm their choice.

5\. After confirmation, the system updates the subscription status

accordingly and notifies the passenger of the changes.

**Extensions.**

**1. User enter incorrect banking details.**

\- an error message indicating the banking details are incorrect.

\- System ask the user to re-enter the details

**2. User has insufficient balance.**

\- User makes payment.

\- System detects payment not approved

\- User notices a message indicating the funds are insufficient.



<a name="br10"></a> 

\- System ask the user to re-try making payment

**Driver’s Management System**

**Offer Ride:**

**Input:** Drivers’ location and destination location, Depart time & Number of

seats available

**Output:**

1\. The driver accesses the "Offer Ride" section in their account settings

or dashboard.

2\. The system prompts the driver to input details such as current

location, destination, departure time, and available seats.

3\. The driver submits the ride posting.



<a name="br11"></a> 

4\. The system confirms the ride posting and makes it visible to

potential passengers.

**Extensions:**

**1.Driver enter incorrect trip details.**

\- an error message indicating the trip details are incorrect.

\- System ask the user to re-enter the details

**2. Driver posting the same trip.**

\- Driver enters already existing trip details.

\- System detects the trip already exists.

\- Driver notices an error message indicating the trip already exist.

\- System ask the user to re-enter the details

**Manage Trips**

**Output:**

1\. The user accesses the "Manage Trips" section in their account

settings or dashboard.

2\. The system displays a list of upcoming trips.

3\. The driver selects a trip to view its details or make changes.

4\. Depending on the action chosen, the system allows the driver to edit

trip details or cancel the trip.

**Manage Car Details**

**Input:** Car details

**Output:**

1\. The driver accesses the "Manage Car Details" section in their

account settings.

2\. The system displays the current car details.

3\. The driver selects an option to add, edit, or remove car details.

4\. The driver submits the changes, and the system updates the car

details accordingly.



<a name="br12"></a> 

**Manage Profile**

**Output**:

1\. The driver accesses the "Manage Profile" section in their account

settings or

dashboard.

2\. The system displays the current profile information.

3\. The driver selects an option to edit the profile details.

4\. The driver submits the changes, and the system updates the profile

accordingly.

**Rate and Review**

**Output**:

1\. After completing a trip, the driver receives a prompt to rate and

review the passenger.

2\. The driver selects a rating and writes a review based on their

experience.

3\. The driver submits the rating and review.

4\. The system records the feedback and may display it publicly on the

passenger’s profile.



<a name="br13"></a> 

**Admin Management System**



<a name="br14"></a> 

**Register as Admin**

**Inputs:** Admin details

**Output:**

1\. Navigate to the registration page or admin registration section within the

system.

2\. Fill out the required information such as name, email address, contact details,

and desired administrative credentials.

3\. Submit the registration form.

4\. Await verification and approval from the system administrator.

5\. Upon approval, receive confirmation and access to administrative

functionalities.

**Review Complaints**

**Output:**

1\. Log in to the administrative dashboard.

2\. Navigate to the "Complaints" or "Feedback" section.

3\. Review each complaint or feedback item thoroughly.

4\. Take necessary actions such as responding to the user, escalating the issue,

or resolving it directly.

5\. Ensure proper documentation of actions taken for reference and auditing

purposes.

**Suspend/Unsuspend Accounts**

**Output:**

1\. Access the user management section within the administrative dashboard.

2\. Locate the user account requiring suspension or unsuspension.

3\. Choose the appropriate action based on the situation - suspend or unsuspend.

4\. If suspended, specify the reason and duration if applicable.



<a name="br15"></a> 

5\. Confirm the action and ensure proper communication with the user regarding

the status change.

**Review Documents**

**Output:**

1\. Access the document management section within the administrative

dashboard.

2\. View the list of submitted documents awaiting review.

3\. Examine each document for completeness, accuracy, and compliance with

regulations or guidelines.

4\. Take appropriate actions such as approving, rejecting, or requesting revisions.

5\. Maintain proper documentation of document review process and outcomes.

**Manage Payments**

**Output:**

1\. Navigate to the payment management section within the administrative

dashboard.

2\. View a summary of recent transactions, pending payments, and invoices.

3\. Process pending payments or invoices as necessary, ensuring accuracy and

timeliness.

4\. Monitor any discrepancies or irregularities in payment records.

5\. Generate reports or analytics regarding payment activities for analysis and

decision-making.

**Review Emergencies**

**Output:**

1\. Access the emergency management section within the administrative

dashboard.

2\. Monitor any alerts, notifications, or indicators of emergency situations.

3\. Assess the severity and scope of the emergency based on available

information.



<a name="br16"></a> 

4\. Initiate appropriate response actions such as notifying relevant parties,

implementing emergency protocols, or escalating the issue.

5\. Coordinate with other stakeholders and authorities as necessary to resolve the

emergency efficiently and minimize impact.



<a name="br17"></a> 

**Activity Diagrams**

**Register Activity Diagram**

**Log in Activity Diagram**

**Book Trip Activity Diagram**

**11.**

**12.**

**13.**

**14.**

**15.**

**16.**

**17.**

**Suspend Account Activity Diagram**

**Start Trip to Destination Activity Diagram**

**Pickup Passenger Activity Diagram**

**Posting Trip Session Activity Diagram**



<a name="br18"></a> 



<a name="br19"></a> 



<a name="br20"></a> 



<a name="br21"></a> 



<a name="br22"></a> 



<a name="br23"></a> 



<a name="br24"></a> 



<a name="br25"></a> 

**Database Design**

