# Introduction

This document outlines the requirements for the software "Spread the World." In this software, the administrator can post advertisements while users can view these ads and communicate with the administrator through a messaging channel. The software will have features that allow users to create and manage ads, interact with users, and integrate payments. The document is intended for the development team, stakeholders, and any other parties involved in this project.

# Functional Requirements:

## Admin Functionality

- The admin should be able to create ads with details such as titles, descriptions, tags, and images.
- The admin should be able to edit, delete and pause ads.
- The admin should be able to manage users by blocking or unblocking them.
- The admin can act as the user.

## User Functionality

- Users should be able to browse and search for ads based on different criteria, such as category, location, or keywords.
- Users should be able to view detailed information about each ad, including ad description, images, pricing, and contact information.
- Users should be able to connect with the admin for ad publishing by submitting their contact details or initiating communication through the system.
- Users should be able to log in using an email or a WeChat account.

# Non-functional Requirements:

**Non-functional Requirements:**

- Performance  

- The system should load content and execute searches within 3 	seconds to maintain an efficient user experience.

- Security 	

  The system should implement encryption to secure user data.

- Scalability 	

  The system should be capable of handling 500 users and 50 ads at 	launch, with the capacity to scale up as growth is anticipated.

- Mobile Responsiveness  

  The WeChat mini-program should be mobile responsive and function optimally on various screen sizes and resolutions.

- Error Handling and Reporting  

  The system should handle errors gracefully, with minimal disruption 	to the user. Detailed error logs should be generated for developers to identify and fix issues.

# Constraints and Assumptions:

## Constraints:

- ​	The system will be developed within a specified budget and timeline.
- ​	The system will be hosted as a WeChat mini-program.

## Assumptions:

- ​	Users will have a stable internet connection to access the system.

## Dependencies:

- ​	The system will integrate with a payment gateway for secure payment processing.

## Acceptance Criteria:

- The admin can successfully create, edit, and delete ads.
- Users can browse and search for ads based on different criteria.
- Users can view detailed ad information and initiate communication with the admin for ad publishing.

# User story

1. **Login to Account**

    **As a** registered user or admin,

    **I want to** log into my account on "Spread the World"

    **So that I can** access the platform's features and manage my activities.



2. **Publish Ads**

    **As an** admin

    **I want to** post ads with text and images

    **So that I can** let users see our business



3. **Manage Ads**

    **As an** admin

    **I want to** delete, modify ads

    **So that I can** ensure all information is updated and correct.



4. **Manage users**

    **As an** admin

    **I want to** block users without good manners 

    **So that** I can ensure the platform is a green one.

    **I also want to** remove users from the blocking list 

    **So that** I can redo my mistake. 



5. **Communication with the users**

    **As an** admin

    **I want to** reply to the users

    **So that** I can find potential clients. 



6. **Browse posts**

    **As a** user 

    **I want to** read the posts

    **So that** I can know the company.



7. **Communicate with the company manager** 

    **As a** user

    **I want to** create a communication channel to talk with a manager 

    **So that** I can know more about their business and let them help me spread my business 



8. **Payment method** 

    **As a** user

    **I want to** pay for the service in a very safe way 

    **So that** I know the company is not a fraud. 
