# Astrix Platform

## Overview
Astrix is a comprehensive ticket booking and community-building platform designed for events. It integrates multiple user roles, offering unique functionalities and engagement opportunities for each. The platform fosters collaboration and interaction among **fans**, **artists**, **organizers**, and **brands**, ensuring a seamless and rewarding event experience.

---

## Frontend Code Repository
The frontend repository contains the codebase for the user interface and experience of the Astrix platform. It is built using modern web technologies to ensure a responsive and interactive design. Key features include:
- Event browsing and ticket booking.
- User dashboards for fans, artists, organizers, and brands.
- Community engagement tools like polls, quizzes, and posts.

### Repository Link
[Frontend Repository](#) *(https://github.com/Wasserstoff-Innovation/Astrix-Frontend)*

---

## Backend Web Services
Astrix consists of multiple backend services, each dedicated to specific functionalities of the platform. Below is an overview of these services:

### **1. Astrix-Auth**
This service handles authentication and user-related queries, including:
- Login and password reset.
- User search functionality.
- Follow and unfollow actions.

#### Repository Link
[Astrix-Auth Repository](#) *(https://github.com/Wasserstoff-Innovation/Astrix-Auth)*

#### Live Links
- **Staging**: [Astrix-Auth Staging](#) *(astrix-auth-staging62d3.azurewebsites.net)*
- **Alpha**: [Astrix-Auth Alpha](#) *(astrix-auth.azurewebsites.net)*

---

### **2. Astrix-MainApi**
This service manages all User-Generated Content (UGC) on the platform, such as:
- Posts, likes, comments, and shares.

#### Repository Link
[Astrix-MainApi Repository](#) *(https://github.com/Wasserstoff-Innovation/Astrix-MainAPI)*

#### Live Links
- **Staging**: [Astrix-MainApi Staging](#) *(astrix-main-staging.azurewebsites.net)*
- **Alpha**: [Astrix-MainApi Alpha](#) *(astrix-main.azurewebsites.net)*

---

### **3. Astrix-EventApi**
This service is responsible for event management and ticketing, including:
- Creation, viewing, buying, and selling of event tickets and collectibles.

#### Repository Link
[Astrix-EventApi Repository](#) *(https://github.com/Wasserstoff-Innovation/astrix-event-api)*

#### Live Links
- **Staging**: [Astrix-EventApi Staging](#) *(astrix-events-staging.azurewebsites.net)*
- **Alpha**: [Astrix-EventApi Alpha](#) *(astrix-events.azurewebsites.net)*

---

### **4. Astrix-Analytics-Api**
This service powers the analytical dashboards for different roles, including:
- Organizers, brands, and artists.

#### Repository Link
[Astrix-Analytics-Api Repository](#) *(https://github.com/Wasserstoff-Innovation/astrix-analytics-api)*

#### Live Links
- **Staging**: [Astrix-Analytics-Api Staging](#) *(astrix-analytics-staging-gfasbzd8fga4djaj.centralindia-01.azurewebsites.net)*
- **Alpha**: [Astrix-Analytics-Api Alpha](#) *(astrix-analytics-gka0b5habpg4dufa.centralindia-01.azurewebsites.net)*

---

### **5. QR-Scan Repository**
The QR-Scan repository manages the redemption of purchased tickets and collectibles. It includes both frontend and backend functionalities for:
- Validating tickets and collectibles.
- Providing a proprietary QR scanner for seamless redemption.

#### Repository Link
[QR-Scan Repository](#) *(https://github.com/Wasserstoff-Innovation/astrix-qrscan)*

#### Live Links
- **Staging**: [QR-Scan Staging](#) *(astrix-qr-staging.azurewebsites.net)*
- **Alpha**: [QR-Scan Alpha](#) *(astrix-qr.azurewebsites.net)*

---

## Branching Strategy
Each repository follows a three-branch workflow:
1. **Dev**: Used by developers for ongoing changes and feature development.
2. **Staging**: Dedicated to testing changes before they go live.
3. **Alpha**: The live branch hosting the production-ready code.

Both **staging** and **alpha** branches are hosted to make testing and deployment efficient and seamless.

