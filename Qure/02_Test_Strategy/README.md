# Qure — Test Strategy

# Purpose

The purpose of this document is to define the QA approach, testing scope, test levels, responsibilities, and quality criteria for the Qure project.

---

# Project Scope

Platforms:

- Android
- iOS
- Web Admin Panel
- Backend API

Testing covers both new functionality and regression verification before releases.

---

# Testing Types

## Functional Testing

Verification of business logic according to requirements.

Examples:

- Authorization
- Registration
- Product Catalog
- Cart
- Orders
- Profile
- Medication Reminders

---

## Regression Testing

Performed before every production release.

Regression includes:

- Critical user flows
- Authentication
- Orders
- Payments
- Notifications
- Profile
- Reminder functionality

---

## Smoke Testing

Performed after each deployment.

Smoke scope:

- Application launch
- Login
- Main screen
- Catalog
- Cart
- Checkout
- Profile

---

## UI Testing

Verification of:

- Layout
- Responsive behavior
- Icons
- Fonts
- Colors
- Navigation
- Design consistency

---

## API Testing

Backend verification includes:

- Request validation
- Response validation
- Error handling
- Authorization
- Status codes
- Business rules

---

## Localization Testing

Supported languages:

- Russian
- Kazakh

Verification includes:

- Text correctness
- Layout consistency
- Translation quality

---

# Test Levels

- Smoke Testing
- Functional Testing
- Integration Testing
- Regression Testing
- Acceptance Testing

---

# Test Environment

Platforms:

- Android
- iOS

Backend:

- Development
- Staging
- Production

---

# Entry Criteria

Testing starts after:

- Feature implementation completed
- Build delivered
- Environment available
- Requirements reviewed

---

# Exit Criteria

Testing is completed when:

- No Critical defects remain
- High priority defects are resolved or accepted
- Smoke tests pass
- Regression completed
- Test report prepared

---

# Risks

Potential risks:

- Requirement changes
- Backend instability
- Third-party integration failures
- Mobile OS differences
- Localization defects

---

# Deliverables

QA deliverables include:

- Test Cases
- Checklists
- Bug Reports
- Test Reports
- Regression Reports
- Automation Plan
- Test Metrics
