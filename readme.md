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

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/e537e1d2-3142-44ec-b223-626acd4936ec)

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

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/95d1fd21-24b4-44ee-93a2-bbef1f39d660)

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

<a name="br18"></a> 
**Register Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/33ce20b4-cfc0-4e37-bd29-8c90b72e1c07)

<a name="br19"></a> 
**Log in Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/68eaf999-9555-4489-83a1-b6120d760313)

<a name="br20"></a> 
**Book Trip Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/07327ea6-d895-436b-a034-47959c0e5861)

<a name="br21"> </a> 
**Suspend Account Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/37ce6d33-7977-42f6-a54a-ef91c036ce31)


<a name="br22"></a> 
**Start Trip to Destination Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/2397298b-abcc-476e-b6ef-45c4e877e4d9)

<a name="br23"></a> 
**Pickup Passenger Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/3e85e478-329f-4dfb-84bf-b1a5b0d95a9f)

<a name="br24"></a> 
**Posting Trip Session Activity Diagram**

![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/05e08074-4c2c-49f8-96f0-eb1292b156bb)

<a name="br25"></a> 

**Database Design**
![image](https://github.com/IFMTYP2024/team13-main/assets/143531070/cef57bee-8fe8-44a3-b48f-3fedc470db46)





<hr>

# DELIVERABLE 3
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/44c9017b-1413-4579-b4c5-a77f6334bb42)

# <ins>Team Information:</ins>
- <ins>Team Name:</ins> **Innovation Quad**
- <ins>Project Name:</ins> **Carpooling**
- <ins>Team Number:</ins> **13** 
- <ins>Mentor Name:</ins> **Mr. Maluleka**
- <ins>Sponsor Name:</ins> **Lift Search(Mr. Vutivi Shivambu)**
- <ins>Team Members:</ins>
  - Twarisani Nxumalo 
  - Yingisani Honest Shivambu
  - Tylon Takaidza
  - Rishongile Tshabalala

<ins># Updated Problem Statement, Proposed Solution & Use Cases</ins>

<ins>### Problem Statement:</ins>

LiftSearch is currently struggling with inconsistent usage leading to lost revenue,as once users are used to each other they often arrange rides directly, bypassing the platform, Additionally, the accuracy of matching pickups and drop-offs is sometimes inaccurate. These issues, coupled with LiftSearch only dealing in long-distance rides (usually cross-province), reduces overall engagement; whereas South Africa is having a growing demand for affordable, reliable transportation for short regular trips.

<ins>### Proposed Solutions:</ins>

To address these challenges, we will implement the following solutions:

<ins>### Short Regular Rides:

Implement a new feature that supports short, routine travel options, such as minibus taxis for school learners and worker transportation, increasing usage frequency. Unlike existing services like Uber, Bolt, and other carpooling options which primarily cater to on-demand individual rides, the proposed solution introduces structured, routine travel options, catering to a niche market with consistent needs, rather than purely on-demand services.

The system will be implemented as follows:

**Driver Route Posting:** Allow drivers to post their starting point, destination and time. They can mention their workplace/any specific destination such as a mall etc, or just the city name if they are open to picking up anyone within the city. 

**Rider Matching:** Match riders with drivers based on distance. Prioritize the nearest drivers. If an exact match isn't found, match passengers with drivers heading in the same direction, provided the passenger is within a specified radius of the driver's route.

**Driver Availability Management:** Enable drivers to post their availability. If a driver won't be available on a certain date, they can update their status and their passengers will be allocated to a di􀆯erent driver.

**Minibus Ride Posting:** Allow minibus drivers to post their daily trips to specific locations (e.g., schools, workplaces). Based on the route, allocate passengers who fall within a certain range.

**Dynamic Passenger Allocation:** If needed, the system can reallocate passengers to a different driver on a given day, maintaining flexibility and ensuring passengers reach their destination.

<ins>### Subscription-Based Discounts:</ins>

Encourage consistent app usage through a subscription model with tiered discounts, promoting loyalty. This rewards consistent users with progressively larger discounts, creating a more robust loyalty incentive and appealing to those who need regular transportation, with the added convenience of not always needing travel cash.

The system will be implemented as follows:

**Weekly subscription:** 5% off ride cost

**Monthly subscription:** 10% off ride cost

**Yearly Subscription:** 12% off ride cost


<ins>### Enhanced Matching Algorithm:

To improve the accuracy of matching pickups and drop-offs, our implementation will be as follows:

**Google Maps** offers a **Distance Matrix API** that calculates travel distance and time between multiple origins and destinations, including various travel modes (driving, walking, cycling, etc.), We will use this API to calculate the driving distance between the driver's route and the passenger's destination, factoring in real-time traffic. By calculating distances between passenger destinations and driver routes, incorporating user-defined radius parameters, and considering factors like traffic conditions, our algorithm will optimize matching efficiency, ensuring that passengers' destinations fall within a specified distance from the driver's route, thereby enhancing user satisfaction and the overall e􀆯ectiveness of the app.

### <ins>Use Cases:</ins>

### <ins>User Authentication Subsystem</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/469930d7-ed0f-4cf2-a0dc-0a7ef4e0d0ee)
### <ins>Passenger Management System</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/a1213a70-2bc3-4464-bae7-84e5481623a0)
### <ins> Driver’s Management System</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/89283de7-ae76-4f1a-b021-105abc26cab1)

### <ins> Admin Subsystem</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/b40a1565-0bb0-44bb-a308-d5a3dbb9546c)
## <ins>Class Diagram</ins>
### <ins>Interaction Sequence Diagrams:</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/791a03b2-1cd9-46ff-b6eb-6a65092a5a55)

![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/22eef593-8d98-45ba-8dc0-550491b8b088)
### <ins>User Aunthentication Subsystem</ins>

### <ins>Login</ins>

![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/225ebeb8-8c02-4f4a-aedc-2a7430d6e775)

### <ins>Register</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/b9afdd44-5807-404d-b0f2-c8790c9fc542)

### <ins>Passenger:</ins>
### <ins>Search for Trips</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/2a2392c4-61f0-4bad-a3c1-01f4fc0a6588)

### <ins>Preferred driver</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/9ecee243-159f-4d63-b1a8-83cb82c35bca)

### <ins>Manage Profile</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/50874448-4812-4dfe-bace-03cc8aa99c05)

### <ins>Manage Subscriptions</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/69a349f4-26f8-472d-bf47-9d8cfda8a119)
### <ins>View Trips History</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/ee026e97-3eb8-43e9-b503-f1b21c9764ad)

### <ins>Rate and Review</ins>

![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/33cee888-68b8-42d3-aa3c-d4b20d947600)

### <ins>Driver:</ins>
### <ins>Offer A Ride
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/d6a5be3b-39b2-4edc-bd77-1b4117be2ad8)

### <ins>Manage Trips
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/7458faab-c756-4d8a-addc-7aceedba78d0)

### <ins>Manage Car Details
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/598a7907-5f37-4a8f-a7df-ed92a7e0339b)

### <ins>Manage Profile
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/4f04f611-cd44-419e-93b6-26b2734bf016)

### <ins> Rate and Review
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/e0cd4b73-a375-4925-9386-2d0409f6f5d9)

### <ins>Admin

### <ins>Register an Admin
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/4f193250-ad6f-4300-b19e-4ee0ac049797)

### <ins>Review Complaints
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/2132a6ff-ca3e-4b7f-95d8-0dee3b16e865)

### <ins>Suspend/Unsuspend Account
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/e61fd7ba-99b5-4072-8b83-c293f7f606cf)
### <ins>Review Documents
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/761856a1-3633-4e03-bb1a-dea09a32d1ad)

### <ins>Manage Payments
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/5bf2a8ec-1d02-4e8a-aad9-ffe067c24a3f)
### <ins>Review Emergencies
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/9b2715b6-920f-46b4-a499-486b3f4d550d)

### <ins> Review Trip Information</ins>
![image](https://github.com/TwarisaniNxumalo/web-app/assets/143531070/c60a9e7e-27ec-4b37-87f7-cc1bdf322ac8)






