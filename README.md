# Django-DRF-email-service
A Mail/Notifications service as a REST API in Python Django. The service will send emails through a specified mail provider (e.g., Mailjet, Brevo) and push notifications through Firebase Messaging. At first the only mail service to be integrated is Brevo, but keep in mind that we'll need to be able to integrate multiple in the future.

Key Requirements:

Set up an API endpoint for sending emails and notifications.
Integrate the API with Firebase Messaging for push notifications.
Schedule emails and notifications to be sent at specific times.
Ability to cancel scheduled notifications and emails.
Document the API endpoints for easy integration.
Stack: Python Django, Firebase Messaging, and an external email provider.
