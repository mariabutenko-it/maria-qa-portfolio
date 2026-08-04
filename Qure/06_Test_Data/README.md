# 06. Test Data

## Purpose

This folder contains test data used for manual and automated testing of the Qure mobile application.

The purpose of test data management is to provide stable, reusable, and predictable datasets for QA activities.

---

# Test Data Categories

The following types of test data are used:

- User accounts
- Authentication data
- Personal profile information
- Delivery addresses
- Products
- Orders
- Shopping cart
- Bonuses
- Medication reminders
- Notifications
- API test data

---

# User Accounts

Examples:

- New User
- Existing User
- User with completed profile
- User without profile
- User with active orders
- User without orders
- User with bonus balance
- User without bonuses

---

# Authentication Data

Test scenarios include:

- Valid email
- Invalid email
- Valid OTP
- Invalid OTP
- Expired OTP
- Session restoration
- Logout

---

# Product Data

Data required for testing:

- Available products
- Out-of-stock products
- Discounted products
- Favorite products
- Recommended products

---

# Order Data

Order scenarios include:

- New order
- Paid order
- Unpaid order
- Delivered order
- Cancelled order
- Failed payment

---

# Medication Reminder Data

Test data includes:

- Existing medication
- New medication
- Reminder with one intake
- Reminder with multiple intakes
- Daily reminder
- Weekly reminder

---

# Localization Data

Supported languages:

- Russian
- Kazakh

Verification includes:

- UI text
- Date formats
- Time formats

---

# API Test Data

The following data will be prepared for API testing:

- Authentication tokens
- Test users
- Orders
- Products
- Notifications
- Medication reminders

---

# Test Data Management

Test data should:

- Be reusable
- Be independent between test runs
- Be easy to update
- Support both manual and automated testing

---

# Future Improvements

Planned enhancements:

- API-based test data generation
- Automatic cleanup of test data
- Dynamic data creation during Appium test execution
- Environment-specific datasets

---

# Current Status

Test data strategy is under continuous improvement as the automation framework evolves.
