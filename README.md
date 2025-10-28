TicketFlow — Twig
 Overview
TicketFlow is a simple ticket management front-end built with Twig templates. It includes pages for Landing, Authentication, Dashboard, and full Ticket CRUD (Create/Read/Update/Delete) functionality.

 Tech & Libraries
PHP (minimum 7.4+)

Twig templating engine

Vanilla JavaScript (or Alpine.js for interactivity)

Tailwind CSS (or plain CSS)

localStorage for auth & ticket persistence (ticketapp_session)

Optional: JSON Server or PHP backend for mock API

 Setup
bash
git clone <repo>
cd Ticket-Management-Twig
composer install  # if using PHP dependencies
php -S localhost:8000  # start local server
👤 Test User
Email: test@ticketapp.local

Password: Test@1234

 Notes
Protected pages check for ticketFlow_session in localStorage.

Tickets are stored under the key ticketFlow_tickets.

Routing is handled via PHP or .htaccess (if applicable).

Accessibility
Semantic HTML structure

Focus states for interactive elements

ARIA roles for alerts and modals

Alt text for all images￼Enter
