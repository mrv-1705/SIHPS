# Smart India Hackathon Workshop
# Date: 16-05-24
## Register Number:21223040103
## Name: Kurapati Vishnu Vardhan Reddy
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
Create a user-friendly website dedicated to helping people locate the nearest e-waste collection and recycling facilities. The website will also provide educational resources about the dangers of improper e-waste disposal, detailing the harmful components and their environmental and health impacts. Additionally, users can input the model of their old electronic devices to earn credit points based on the estimated value of precious metals recovered when they recycle the device properly.


## Proposed Solution / Architecture Diagram
![image](https://github.com/mrv-1705/SIHPS/assets/114565075/b7b43a33-5937-4bee-a8c5-a9fba67c563f)
Solution Overview
User Interface (UI): A web-based interface where users can interact with the system.

Location Service: Integration with mapping and geolocation APIs to find the nearest e-waste recycling facilities.

Educational Module: Pop-ups and informational sections detailing harmful e-waste components and their impacts.

Credit Points System: A module to calculate and reward users with credit points based on the device model and its recyclable materials.

## Use Cases
![image](https://github.com/mrv-1705/SIHPS/assets/114565075/1c1ea9a7-e67b-43e0-bc61-65135a8a73d1)



## Technology Stack
1.Frontend:

HTML/CSS: For structuring and styling the website.
JavaScript: For interactivity and dynamic content.
React.js: For building a responsive user interface.
Bootstrap: For responsive design and UI components.

2.Backend:

Node.js: For server-side logic and handling requests.
Express.js: For building the API and managing routes.
MongoDB: For storing user profiles, credit points, and device model data.
Mongoose: For interacting with MongoDB in a structured way.
APIs:

3.Google Maps API: For geolocation and mapping services.

Recycling Facility API: To fetch data about nearby recycling centers (could be a custom API if no existing API is available).

4.Additional Services:

Authentication Service: For user login and profile management (e.g., Auth0).
Educational Content Management System (CMS): For managing and updating educational content (e.g., Contentful).






## Dependencies
NPM/Yarn: For managing project dependencies.
Webpack: For bundling JavaScript files.
Axios: For making HTTP requests to APIs.

