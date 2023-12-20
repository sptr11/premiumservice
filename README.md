# `premiumservice` 

## Goal
`premiumservice` is a web app designed to enhance customer support workflows by integrating with SupportBee and Stripe. It prioritizes support for paying customers automatically.

## Functionality

### 1. Webhook Setup
- Configures a webhook with SupportBee support software.
- Listens for new support ticket notifications.

### 2. Email Verification
- Extracts the customer's email address from incoming support tickets.
- Queries Stripe API to check if the email belongs to a paying customer.

### 3. Label Assignment
- If the customer is verified as a paying customer, it invokes SupportBee's API.
- Assigns a "paying_customer" label to the corresponding support ticket.

This integration ensures that paying customers receive prompt and prioritized support assistance.
