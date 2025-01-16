# Marketplace Technical Foundation - Comforty

## About File:
This README file contains the information about the Technical planning and system architecture of my marketplace. This file also contains the Data Schemas, API Endpoints and a screeshot of the workflow.

## Technical Requirements
### Frontend Requirements:
- User-Friendly Interface: Browsing products should be intuitive.
- Responsive Design: Ensure compatibility with both mobile and desktop users.

### Essential Pages
- Home
- Product Listing
- Product Details
- Cart
- Checkout
- Order Confirmation

### Backend Requirements
- Sanity CMS:
- Manage product details, customer information, and order records.
- Acts as the database for the marketplace.
- Third-Party APIs Integration Needs: Shipment tracking, Payment gateways.

## System Architecture Design
The Picture below represents the visual representation of the General E-Commerce system architecture.
![image alt](https://github.com/AliBariz/Documentation/blob/c469dfd69398fe018d6a12425ee6fc2c0f088bf6/SystemArchitecture_Day2/Hackathon-3%20Day-2(Copy%20with%20watermark).png)

## Purpose and Methods of API Endpoints
API Endpoints, their purposes and methods are listed below:

### Products

- Endpoint: /products
- Method: GET
- Purpose: Fetch all product details from Sanity CMS.
  
### Categories
- Endpoint: /categories
- Method: GET
- Purpose: Get all product categories.
- 
### Users
- Endpoint: /users
- Method: GET
- Purpose: Get user information.
### Shipment Tracking
- Endpoint: /shipment
- Method: GET
- Purpose: Fetch shipment status from a third-party API.