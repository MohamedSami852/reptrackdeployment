# Project Overview (RepTrack)
This Django-based fitness management platform is designed to help users manage their fitness journey by offering:
- User account management.
- A community timeline for engagement.
- Workouts and progress tracking.
- Communication tools for chat and messaging.
- Leaderboards and ratings for gamified motivation.
- Notifications for updates and reminders.

# Features
## Core Features:
- Authentication: Secure user authentication with token-based login and registration.
- Users: Manage user profiles and roles.
- Community: Timeline for users to post, view, and interact with content.
- Workouts: Create, track, and manage workout plans.
- Dashboard: A central hub for progress tracking and performance metrics.
- Communication: Chat and messaging tools for user engagement.
- Leaderboard: Monthly rankings for competitive motivation.
- Ratings: Rating and reviewing system for coaches and services.
- Notifications: Personalized notifications for updates and reminders.

# Technologies Used
## Backend:
- Django: Core framework for the backend.
- Supabase: Lightweight database for development.
## Frontend:
- Django Templates: For rendering pages.
- HTML, CSS, JavaScript: For static and dynamic frontend components.
## APIs:
- Django REST Framework (DRF): For API development and management.
## Testing:
- Postman: API testing.

# Setup Instructions
1. Clone the Repository
`git clone https://github.com/abdullahyasser0/RepTrack`

`cd backend`

2. Install Dependencies
`pip install -r requirements.txt`

3. Apply Migrations
`python manage.py migrate`

4.Run the Development Server
`python manage.py runserver`

5. Access the Application
Visit `http://127.0.0.1:8000` in your browser

# API Endpoints
open the API Documentation file for a detailed list of endpoints, including their functionality, request types, and example payloads.

# RepTrack - Contributing Team

## Team Members and Roles
| Name            | Role            | Responsibilities                        |
|-----------------|-----------------|-----------------------------------------|
| Ahmed Baioumy   | Front-end Developer  / Scrum Master| Develops and maintains the UI components and handles frontend integration. |
| Ziad Moutaz     | Front-end Developer | Focuses on UI development and frontend/backend integration, ensuring usability standards. |
| Abdalla Tamer   | Back-end Developer  | Facilitates Scrum events, removes blockers, and ensures the team adheres to Scrum practices. |
| Abdullah Yasser | Back-end Developer  | Implements and tests back-end features of RepTrack. |
| Mohamed Sami    | Back-end Developer  | Manages Full Deployment (DevOps) + backend integrations and ensures Data Security,Consistency and performance + Database Management. |

## Scrum Workflow
1. **Sprint Planning**: The team discusses the scope of each sprint, selecting tasks from the product backlog based on priority and capacity.
2. **Daily Stand-ups**: A 10-minute daily meeting to sync up on progress, blockers, and planned work.
3. **Sprint Review**: Held at the end of each sprint to demonstrate completed work and gather feedback.
4. **Sprint Retrospective**: The team reviews what went well, what could be improved, and actionable steps for the next sprint.

## Sprint Documentation
Each sprint has a separate document detailing its:
- **Goal**: Specific focus or objective.
- **Backlog**: List of tasks with priorities.
- **Review**: Summary of the completed work and any changes.
- **Retrospective**: Observations and adjustments to improve future sprints.


## CI/CD 
*implemented a CI/CD pipeline to automate production deployments for the Reptrack solution, ensuring seamless updates with minimal downtime.
*Artifacts are built and stored in the Container Registry (reptrack) for version control and quick rollbacks.
*Deployed applications include Reptrack and reptrackwebsite, both running as Azure App Services.

## Load Balancing
Configured a Load Balancer (LoadBalancerreptrack) to distribute incoming traffic evenly between the two App Services, enhancing reliability and fault tolerance and for efficient management and scalability.

- ![image](https://github.com/user-attachments/assets/d4841730-eb66-4241-82bd-97d6ecf6efa8)
- ![image](https://github.com/user-attachments/assets/387b313e-2070-46cd-ac71-40f31d336633)
- ![WhatsApp Image 2025-01-07 at 14 14 34_a7ae87ef](https://github.com/user-attachments/assets/5185828b-e615-4e44-8c9a-d72db5d4d578)



## for further more details about 
-**this is a deployment Repo :** This repository is purpose-built to manage CI/CD pipelines for production deployments, ensuring the reliability, security, and stability required in a live environment. A separate repository is designated for staging deployments, reinforcing a clear segregation of environments to maintain streamlined workflows and minimize risks during the deployment lifecycle.

While combining both staging and production pipelines into a single repository might have been feasible, this separation aligns with industry best practices by promoting a higher level of abstraction, enhancing scalability, and simplifying management. This approach is particularly advantageous in enterprise environments, where maintaining strict boundaries between environments is critical for operational excellence.

for more details please check https://github.com/abdullahyasser0/RepTrack



## Tools and Boards
We use **[Trello]** for tracking progress, managing backlogs, and updating sprint tasks.

---
