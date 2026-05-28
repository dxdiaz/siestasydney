# Siesta Sydney Guest Hub

Digital guest information hub for Siesta Sydney.

This project was created as a lightweight MVP to improve guest access to essential hostel information through QR codes and mobile-friendly landing pages.

## Features

* Mobile-first landing page
* QR code access
* Guest information hub
* Google Analytics 4 tracking
* QR location tracking
* Social media and review links
* Easy seasonal updates

## Technologies Used

* HTML
* Tailwind CSS
* JavaScript
* GitHub Pages
* Google Analytics 4

## QR Tracking System

Different QR codes can be generated for different hostel locations using URL parameters.

Example:

```url
?source=reception
?source=rooms
?source=kitchen
?source=lift
```

This allows GA4 to identify where scans are coming from.

## Event Tracking

Current tracked events:

* guest_guide_click
* review_click
* instagram_click
* book_direct_click

## Deployment

This project is deployed using GitHub Pages.

## Future Improvements

* Multi-language support
* Seasonal event banners
* HubSpot integration
* Guest feedback forms
* Direct booking campaigns

## Project Goal

The goal of this MVP is to improve guest experience, reduce repetitive reception questions, and create measurable digital engagement within the hostel environment.
