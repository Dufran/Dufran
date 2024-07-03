# 👋 Hello! I'm Oleksandr

## About me

I am a Python Backend Developer with substantial commercial industry experience, specializing in the development of applications using Django/FastAPI. I am recognized for my adaptability, honesty, accountability, organizational skills, punctuality, and strong problem-solving aptitude. I have successfully designed, developed, and implemented robust backend solutions that adhere to project requirements and industry best practices throughout my career. Furthermore, I possess a comprehensive understanding of technological frameworks and my track record includes consistently delivering high-quality solutions

## Commercial projects

### Fulfillment [February 2024 - March 2024]

#### Role: Python Full-stack Developer

#### Team size: 3

#### Description

Fulfillment is a portal for clients of logistic company. It allows clients to streamline common operations. With vdh-fulfillment clients can effortlessly track incoming and outgoing orders, access detailed order information, and receive real-time notifications from the internal ERP system. Plus, our user-friendly interface includes a range of convenient features such as customizable reports and seamless integration with external API (https://frends.com/). We created a dedicated authorization service that enables Single Sign-On (SSO) across all existing portals. So the clients can enjoy a seamless and uninterrupted login experience across all 3 existing portals

#### Goals

- Develop a fulfillment portal prioritizing on delivery of clients’ order information, stock status, report requests, and notifications via webhook from external ERP system
- Develop an order planning feature (Trello-like UI ) for staff users to plan orders for specific teams in each facility.
- Establish a dedicated authorization service integrated for seamless login across all three existing portals
- Integrate external API to enhance system functionality by adding the ability to view and manage resources from the internal ERP system via API
- Employ existing themes and styling to create a cohesive and familiar visual experience across all portals.

#### Technologies

`Python` `Docker` `Docker compose` `django-oauth-toolkit` `Nginx` `Certbot` `Django` `Bootstrap` `HTMX` `Digital Ocean` `Oauth` `hyperscript`

### Property listing automation [November 2023 - February 2024]

#### Role: Python Full-stack Developer

#### Team size: 3

#### Description

The Property Listing Automation tool is a powerful internal tool designed to enhance the analysis of the real estate market in the UK. It leverages a vast amount of data(For example 9 GB table with historical data for calculating KPI) from two of the most popular real estate websites, Zoopla and Rightmove, to provide comprehensive insights and automation capabilities(For example: Finding UK area with the lowest rent price for last 12 month, automatically generate offer price for all listings in this area code, and send offer to each of them)

#### Goals:

- Implement KPI analysis feature: This feature allows for deep analysis of key performance indicators, enabling users to gain valuable insights into the real estate market. (For example, Find the UK area where properties have the highest rent for potential investment)
- Implement a Heatmap: A visual representation of the KPI analysis data, the Heatmap provides an intuitive and easy-to-understand overview of market trends and patterns.
- Implement a pricing algorithm: The advanced pricing algorithm takes into account underlying historical data and provides accurate pricing suggestions for each property listing, aiding in effective pricing strategies.
- Implement Selenium automation: By leveraging the power of Selenium, the tool automates the process of submitting offers on both Zoopla and Rightmove, saving time and effort. The main steps are : Login, Navigate to the listing page, Fill form according to settings, submit the offer, and Bypass CAPTCHA protection using a browser extension.
- Implement offer management: The tool allows users to efficiently manage offers, keeping track of submitted offers, negotiations, and outcomes all in one place.
- Implement scenarios feature: To enhance user flexibility, the tool includes a scenarios feature that enables users to save different sets of KPI and pricing settings as separate scenarios. This allows for easy comparison and analysis of various scenarios and strategies.

#### Technologies

`Python` `Docker` `Docker compose` `Redis` `Caddy` `Sentry` `Django` `Bootstrap` `HTMX` `Selenium` `Leaflet` `Celery` `AWS EC2 RDS S3`

### Antique Seller CRM/Shop [December 2022 - November 2023]

#### Role: Python Backend developer / React Frontend developer

#### Team size: 6

#### Description

One of the leading antique marketplaces in the UK, renowned for its user-friendly search and filtering tools, exceptional flexibility, and cutting-edge features tailored for sellers, accompanied by outstanding SEO performance.

#### Goals:

- Deliver top-notch security and performance for existing and new features
- Constantly improve and add new features to dealers/admin portal (DRF and React related)
- Migrate from elastic search to Algolia for better user search (multi-index queries/facet filters)
- Implement social authorization for quick and easy user joining
- Implement Instagram/Facebook marketplace integration
- Implement Yellow pages feature (Recurring payment integration/Premium&non premium feature separation)
- Optimize sitemap generation for items/categories/dealers

#### Technologies

`Django` `DRF` `Celery` `Redis` `AWS RDS|SQS|S3` `Twilio` `Google Auth` `Facebook Auth` `Instagram API` `Stripe` `Paypal` `React` `AntD` `Elasticsearch` `Algolia`

### Mental health/lifestyle platform [December 2022 - November 2023]

#### Role: Python Backend developer / React Frontend developer

#### Team size: 3

#### Description

Revolutionizing personal health and wellness, our groundbreaking platform offers tailored lifestyle solutions to enhance your well-being. Easily connect with medical experts, receive personalized recommendations directly in your calendar, and track your progress effortlessly. Our innovative algorithm showcases your advancements in different areas based on your consistent efforts, motivating you with vibrant achievements along the way.

#### Goals:

- Improve score algorithm to take into account user's previous activity, diminished return on continuous streaks, and motivating when returning to streak
- Integrate social authorization via Google
- Implement text translation via Google Translate API with efficient caching
- Implement weekly newsletter emails, with new articles for each user
- Implement seamless integration with Google Calendar for setting up reminders/events from the app
- Implement a reference program for partners and a dynamic/live partner statistic feature

#### Technologies

`Django` `DRF` `Celery` `Redis` `AWS RDS|S3` `Twilio` `Google Auth` `Facebook Auth` `Instagram API` `Stripe` `Paypal` `React` `Mui` `Fastapi`

### Net Worth Tracker [June 2022 - December 2022]

#### Role: Python Backend developer / React Frontend developer

#### Team size: 4

#### Description

Comprehensive Social & Financial platform that enables users to simulate expenditure and income outcomes via the powerful Monte Carlo algorithm. The platform will seamlessly integrate with Yahoo Finance to access real-time currency pricing and historical data for ticker assets. Moreover, it will offer a range of robust methods for asset analysis such as CAPM, Historical Mean, and Custom models. The backend will be powered by FastAPI for executing complex mathematical calculations and running the Monte Carlo model efficiently, while the frontend will be supported by Django DRF for managing all other aspects including social networking features, saving and versioning of scenarios, and creating customizable templates for users.

#### Goals:

- Refactor existing Monte Carlo algorithm with new functions
  - Selling of illiquid assets with complete handling of capital gain taxes
  - Implement robust cache for historical ticker data, improved performance of large portfolio sets calculation from 4s to 0.5
- Implement the public template feature and the ability to incorporate this template into your scenario
- Implement asset tag feature for building pie charts of portfolios based on domain/ticker type
- Implement US cash being a part of an emergency fund

#### Technologies

`Django` `DRF` `Celery` `Redis` `AWS RDS|S3` `Paypal` `React` `Fastapi` `MongoDB` `Pandas` `Numpy` `Mailgun` `Elasticsearch`

### VR subscription service [July 2021 - March 2022]

#### Role: Python Backend developer

#### Team size: 5

#### Description

Enhanced VR video platform offering subscription-based access with multiple quality options, including a free tier for users to enjoy.

#### Goals:

- Implement a subscription payment feature
- Implement flexible promotions system (personal/time bound/ one time/ promo codes)
- Implement video and video playback feature
  - Various qualities
  - AWS CDN
  - Track current video progress for resuming later
- Implement CMS-like features for static pages (CKEditor, slugs, etc)
- Implement background process of auto-encoding videos to various qualities

#### Technologies

`Django` `DRF` `Celery` `Redis` `AWS RDS|S3` `Stripe` `Mailgun` `django-video-encoding`

### Material Requests Manager [January 2021 - May 2022]

#### Role: Python Backend developer / React Frontend developer

#### Team size: 1

#### Description

The Material Request Manager is a comprehensive system designed to streamline the process of ordering materials, including wires, semi-finished goods, and other components, directly from the workplace. In addition, it offers a user-friendly API for accessing floor and area plans, providing precise workplace locations for various services. This integration significantly reduces the time required to add materials to workplaces and minimizes associated labor costs.
The system is comprised of three main modules:

- Client Interface:
  ▪ Allows workplaces to access material suggestions for current orders and view their material request history.
- Material Provider Interface:
  - Displays workplace locations with new material requests, indicating the quantity of materials available in production/logistic areas and guiding users on where to locate them.
- Planning Page:
  - Enables users to create new workplaces or modify existing ones on the map, and update floor area layouts for optimal material placement and workflow efficiency.

By providing these features, the Material Request Manager enhances the efficiency of material management processes, ultimately improving productivity and reducing operational costs.

#### Goals:

- Design and implement mechanism for workplace suggestion based on existing production databases for separate locations in the country
- Design and implement material requests for clients for workplaces
- Design and implement interactive layout drawing tool, with the ability to place/move/ workplaces
- Implement easy-to-use API for showing the floor/area of the workplace and its location for other internal services

#### Technologies

`Django` `DRF` `Celery` `Redis` `Redux` `MUi` `React`

### Blocked assemblies checker [April 2021 ]

#### Role: React Frontend developer

#### Team size: 1

#### Description

Tool for the logistic department designed to be used on mobile handheld devices Zebra EC30 to check for blocked assembly before sending it to conveyor line, to eliminate wasted time for 40+ on conveyor workplaces

#### Goals:

- Using `Production API` service implement page for checking assembly for blocking via barcode scanning

#### Technologies

`Redux` `MUi` `React`

### Production API [March 2021 - October 2021]

#### Role: Python Backend developer

#### Team size: 1

#### Description

This project serves as a client for multiple databases (Microsoft SQL, IBM db2, Proprietary in memory storage on ERP systems). It allows other projects to use connections for these sources as API, and developers to create custom queries, and set caching for endpoints. It have site-level authorization with an API token.

#### Goals:

- Create a robust docker image with all needed client libraries for various DB types
- Create a mechanism for developers to declare the query that will be runed and other parameters for the endpoint where to get it (caching, route)

#### Technologies

`Django` `DRF` `Celery` `Docker` `IBM DB2` `Microsoft SQL`

### Stock Tracking [September 2020 - May 2022]

#### Role: Python Backend developer

#### Team size: 1

#### Description

This project enables the planning department to monitor stocks of semi-finished goods and other components, allowing them to set quantity thresholds for alerts to be sent to the relevant personnel. It also provides insights into the consumption history of components. Data is sourced from the external legacy ERP system AS400.

#### Goals

- Develop a data extraction task from the ERP system
- Design and implement custom alerting logic tailored to multiple locations, various warehouse types, and distinct groups of responsible individuals

#### Technologies

`Django` `DRF` `Celery` `Docker` `AS400`

### SysAid Reporter [September 2020 - August 2021]

#### Role: Python Backend developer

#### Team size: 1

#### Description

The goal of this project is to create a notification system for the SysAid ticketing system, which was missing in the current version, also to create scheduled reports, and inject extra metadata to notifications (location of workplace that submitted incident by `Material request manager API` ) As notification channel Telegram API was used.

#### Goals

- Add missing notification feature for current SysAid implementation
- Add weekly reports and corresponding business logic (locations/branches/ support teams)

#### Technologies

`Django` `Celery` `Docker` `Telegram API` `Ngnix`

### Deray-acp-v-client [February 2020 - March 2021]

#### Role: Python Backend developer/ HTM/JS Frontend developer

#### Team size: 1

#### Description

Service to provide a custom client for ACPV workplaces (electronic wire shrinking workplace) with features like:

- Reimplementation of login system from another production system (using already created users and permission)
- Check each element for the corresponding status to prevent faulty/not completed parts from being processed
- Change status in the corresponding production system when the process is finished

#### Goals

- Add a connection to the existing production system for getting/changing data (later migrated to `Production API`)
- Create a login/logout flow
- Create a multistep form with live validation of each product that is scanned.

#### Technologies

`Django` `Bootstrap` `jquery` `Docker` `Nginx`

### Linux/Windows system administrator [August 2017 - February 2020]

#### Description

Was working as a system administrator in the [SWS](https://sumitomoelectric.com/)
Time in this position allowed me to get a strong understanding of networking hardware/software. Administrating Windows and Linux servers, getting a solid grasp on the inner workings of ERP systems in full-cycle manufacturing plants, and deep knowledge of how logistics and warehouse storage are organized in production areas. Also, I was able to start learning PHP (most of the legacy codebase was on PHP) to modify existing automation scripts and internal tools, after some time I was able to deliver a stand-alone internal application using the PHP Laravel framework

- **Referral Tracking System:** This innovative service streamlined the registration process for employee referrals. By allowing employees to scan physical advertisement materials and attach them to their profiles, the system automatically awarded referral bonuses when new hires came from those specific ads.
- **Spare Parts Inventory Management:** I developed a service to track spare parts inventory across various departments. This system facilitated efficient management of critical components like cartridges, RAM, power supply units (PSUs), and network switches.

#### Technologies

`Linux` `Windows` `Windows Server` `DHCP` `LDAP` `PHP` `Laravel` `Active Directory` `SMTP` `IP PBX`

## Pet projects/Open-source contributions

_When you have a problem and a bit of time to make a solution for it._

### [Media server](https://github.com/HomeLabHQ/homelab)

Media server with Jellyfin, Jellyseer

### [Expiration tracker](https://github.com/HomeLabHQ/expiration-tracker)

Application for keeping track of expiration dates for food in your pantry, and medications in your first aid kit. Add or search for products with your phone camera

### [Checklist manager ](https://github.com/HomeLabHQ/checklist-manager)

App to run manual QA regression tests based on a checklist, track spend time, fails.

### [Selfhosted github runner ](https://github.com/HomeLabHQ/runner)

Docker compose stack for self-hosted runner to fit all your CI/CD needs

### [django-db-schema-renderer](https://pypi.org/project/django-db-schema-renderer/)

Django admin application that allows you to see ERD diagrams for all projects, specific apps, or a couple of models. The main goal is to reduce the time it takes to onboard a developer on the project, without having extensive project documentation

### [drf-payments](https://pypi.org/project/drf-payments/)

Set of utils models/mixins for handling online payment with various payment gateways

## Hobbies

- 📚 Audio book/podcast addict (WIP series)
  - WH40K Horus Heresy 15/54(Prospero Burns)
  - WH40K Siege of Terra 6/8 (Warhawk)
  - WH40K Eisenhorn 3/4 (Hereticus)
  - The Expanse 9/9 (Leviathan Falls)
- 🛠️ Recently 3D printing enthusiast
- 👨‍🍳 Cooking amateur
- 🍿 Movies/TV series addict

## Language proficiency

- English Upper-Intermediate
- Ukrainian Native

## Contact info

[![Linkedin: oleksandr.korol](https://img.shields.io/badge/-oleksandr.korol-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/oleksandr-korol/)](https://www.linkedin.com/in/oleksandr-korol/)

![GitHub followers](https://img.shields.io/github/followers/dufran?label=Follow&style=social)

<a href="mailto:korol.oleksandr.work@gmail.com">korol.oleksandr.work@gmail.com</a>
![Codewars](https://www.codewars.com/users/Dufran/badges/large)
