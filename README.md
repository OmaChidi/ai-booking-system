 AI-Powered Appointment Booking & Client Management System

An end-to-end automation system for beauty businesses that handles appointment booking, AI-generated client communication, and database management, all without manual intervention.


 Overview

This system automates the entire booking workflow for a makeup artist or hairdresser. A customer fills out a booking form, and the system:

- Creates a Google Calendar event with all details
- Generates professional AI-written confirmation messages, thank-you notes, and preparation instructions
- Sends a confirmation email to the customer
- Sends an alert to the business owner
- Updates a central database with all booking data and AI-generated content

---

 How It Works

1. **Customer submits booking form** (Airtable Forms)
2. **System detects new submission** (Make.com Airtable Watch trigger)
3. **Google Calendar event created** with customer as guest
4. **Database updated** with Event ID and status
5. **Gemini AI generates** professional client communication
6. **Router splits into three paths:**
   - Confirmation email to customer
   - Alert email to business owner
   - AI summary saved to database

---

## Tools Used

Airtable- Booking database & customer-facing form 
Make.com- Automation engine 
Google Calendar- Appointment scheduling 
Google Gemini AI- Client communication generation
Gmail- Automated emails 


---

## Key Features

- Zero manual data entry after setup
- AI-generated personalized client messages
- Automatic calendar event creation with guest invites
- Centralized booking database
- Instant alerts to business owner
- Professional preparation instructions for each service

---

## Setup Guide

### Prerequisites
- Make.com account
- Airtable account
- Google account (Calendar + Gmail)
- Google AI Studio API key

### Steps
1. Clone the Airtable base from the template in this repository
2. Import the Make.com scenario blueprint
3. Connect your Google and Airtable accounts in Make.com
4. Configure your Gemini API key
5. Share the Airtable form link on your website

---

## Future Improvements

- WhatsApp/SMS confirmations via Twilio
- 24-hour reminder automation
- AI review follow-up after appointments
- Stripe payment integration
- Reschedule and cancellation handling

---




