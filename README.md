# FoodConnect: Transforming Leftovers into Hope
# Overview
FoodConnect is a Salesforce-based application designed to efficiently manage the distribution of surplus food to those in need. By leveraging Salesforce's robust capabilities, this project aims to minimize food waste and address food insecurity. The app provides a streamlined process for logistics coordination, volunteer management, and real-time reporting, ensuring effective resource distribution.
# Features
 # Custom Objects:
   Venue: Tracks locations where leftover food is available.
   
   Drop-Off Point: Identifies locations for food delivery.
   
   Volunteer: Manages details of individuals responsible for transportation.
   
   Task: Allocates assignments to volunteers with accountability.
   
   Execution Details: Logs task completion, feedback, and performance ratings.
  # User Interface:
  Developed with Lightning App Builder for an intuitive homepage.
    
  Multiple tabs for managing Venues, Drop-Off Points, Volunteers, and Reports.
  # Automated Workflows:
  Salesforce Flows automate data collection and processing.
  
  Custom Triggers ensure data integrity and automate calculations.
  # Reporting and Dashboards:
  Dynamic Reports: Provide insights into venue usage, task execution, and volunteer performance.

  Custom Dashboards: Offer visual analytics for operational efficiency.
  # Data Security:
  Sharing Rules: Define access control based on distance or user roles.
  
  Public Groups: Facilitate collaboration across user groups.
# Tech Stack
Platform: Salesforce

Languages: Apex

Tools: Lightning App Builder, Salesforce Flows, Dashboards, Reports
# Setup Instructions
# Clone the Repository:
    git clone https://github.com/username/FoodConnect.git
    cd FoodConnect
# Set Up Salesforce Environment:
Login to Salesforce and navigate to Setup.

Create necessary custom objects (Venue, Volunteer, etc.) following the object manager settings in the documentation.
# Deploy Components:
Use Salesforce Developer Console or VS Code with Salesforce CLI to deploy the provided Apex classes, triggers, and flows.
# Add Data:
Populate sample data for venues, drop-off points, and volunteers for testing.
# Run Application:
Launch the FoodConnect Lightning App to explore features.
# Impact
Reduced food waste by efficiently connecting surplus food sources with beneficiaries.

Enabled transparency and accountability through detailed reports and task tracking.

Created a scalable and user-friendly system to assist NGOs and community initiatives.
# License
This project is licensed under the MIT License.

