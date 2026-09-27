StorePro Management System
==================================

Firebase Setup Guide
====================

This software is a single business management system.
Each buyer must connect their own Firebase project.

The seller/developer does not store or access business data.

STEP 1: Create Firebase Project
--------------------------------
1. Go to:
https://console.firebase.google.com

2. Login with your Google account.

3. Create a new Firebase project.

STEP 2: Enable Firestore Database
---------------------------------
Firebase Console:
Build > Firestore Database > Create Database

Choose Production Mode.

STEP 3: Add Web App
-------------------
Go to:

Project Settings
> General
> Your Apps
> Add Web App

Copy the Firebase configuration.

STEP 4: Add Firebase Config
---------------------------
Open:

js/firebase-config.js

Replace:

YOUR_API_KEY
YOUR_PROJECT_ID
YOUR_MESSAGING_SENDER_ID
YOUR_APP_ID

with your Firebase details.

STEP 5: Run Software
--------------------
Open:

index.html

Your management system is ready.

Features
--------
- Customer Management
- Sales Tracking
- Due Management
- Expense Tracking
- Dashboard
- Reports

Note:
Every buyer should use a separate Firebase project.


Currency
========
All amounts are displayed in US Dollar ($) format.
