# Corporate-site

## 🏢 Project Overview
This project is a modern, responsive **Single Page Application (SPA)** designed as a corporate landing page. It is structured to showcase a company's profile, services, team, and pricing all on one continuous scrolling page.

## 🛠️ Tech Stack & Dependencies
*   **Core Framework:** React (v18.2.0)
*   **UI / Styling:** React Bootstrap (v2.5.0) and standard Bootstrap CSS (v5.2.0). 
*   **Build Tool:** Create React App (`react-scripts` v5.0.1)
*   **Testing:** Jest and React Testing Library

## 🏗️ Architecture & Component Structure
The application is highly modularized. The main layout is controlled by `App.js`, which vertically stacks several independent React components. All of these components are neatly organized in the `src/components/` directory.

Here is the top-to-bottom layout of the website based on the rendered components:
1.  **Header (`header.js`)**: The top navigation bar, likely containing the company logo and scrollable anchor links to different sections of the page.
2.  **Hero (`hero.js`)**: The main introduction banner at the very top of the site. It usually features a bold headline, subtitle, and a primary Call-To-Action (CTA) button.
3.  **About (`about.js`)**: A section dedicated to the company's background, mission statement, or core values.
4.  **Services (`services.js`)**: Highlights what the company does, likely using a grid layout with icons to list different services provided.
5.  **Works (`works.js`)**: A portfolio or project showcase section, displaying past client work or case studies.
6.  **Teams (`teams.js`)**: Introduces the leadership or core team members, typically featuring names, roles, photos, and social media links.
7.  **Testimonials (`testimonials.js`)**: Features client reviews and quotes to build trust and social proof.
8.  **Pricing (`pricing.js`)**: Displays available pricing tiers or subscription plans in a structured card format.
9.  **Blog (`blog.js`)**: A section showcasing recent articles, company news, or updates.
10. **Contact (`contact.js`)**: The bottom-most interactive section, likely containing a contact form, company address, email, and possibly a map integration.
11. **Footer (`footer.js`)**: The base of the website containing copyright information, secondary navigation links, and social media icons.


