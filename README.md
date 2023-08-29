# Multi-Cloud Serverless Collaborative Trivia Challenge Game

This project aims to develop a multi-cloud serverless online trivia game that offers users the ability to form teams, compete in real-time against other teams, and track their performance on global and category-specific leaderboards. The game provides a personalized experience by adapting to user preferences and offering a diverse mix of questions tailored to their interests and skill levels. Administrators have access to analytics tools to monitor game performance and user engagement, enabling data-driven decisions for enhancing the gaming experience.

## Hypothetical Scenario

John, Sarah, and their friends discover the "Trivia Titans" online game, allowing them to form teams and compete in real-time. After signing up using different methods, they create user profiles and choose profile pictures. Using 2-factor authentication, they register the second factor with three questions and answers.

John forms a team named "The Quizzards" and invites Sarah and friends. They explore the game lobby, find a trivia game about science and technology, chat in real-time, and participate in the game. The team answers multiple-choice questions, receives hints, and monitors scores in real-time.

## Project Specification

### Front End

- Build a front-end application using React or other suitable frameworks.
- Host the front-end on GCP Cloud Run as a microservice.

### Back End

1. **User Authentication:**
   - Sign up and log in using social media accounts or email addresses.
   - Password recovery and reset if provided by the cloud service.
   - Register the second factor (3 pre-defined questions and answers) to a NoSQL database and validate answers.

2. **User Profile Management:**
   - Edit personal information, view user statistics, manage team affiliations, and compare achievements.
   - Utilize cloud services like GCP Firestore and Cloud Functions.

3. **Team Management (AI-Generated Team Names):**
   - Create a team with AI-generated team names.
   - Invite other users using Pub/Sub, accept/decline invitations, and manage team members.
   - Utilize GCP Firestore, Cloud Functions, and ChatGPT (Open AI).

4. **Trivia Game Lobby:**
   - Browse and join trivia games, filter by category, difficulty, or time.
   - View game details using AWS DynamoDB, Lambda, SQS, SNS, and GCP Firestore.

5. **In-Game Experience:**
   - Answer questions, view real-time scores, communicate with team members through chat.
   - Request and share hints, track performance, and view correct answers.
   - Use AWS DynamoDB, Lambda, SQS, SNS, GCP Firestore, Cloud Functions, Pub/Sub, and analytics tools.

6. **Leaderboards:**
   - View global and category-specific leaderboards, filter by time frame.
   - Utilize AWS DynamoDB, Lambda, SQS, SNS, GCP Firestore, Cloud Functions, Pub/Sub, and analytics tools.

7. **Trivia Content Management (Administrators):**
   - Add, edit, delete trivia questions, manage trivia games with custom settings.
   - Monitor and analyze gameplay data and user engagement.
   - Utilize AWS DynamoDB, Lambda, SQS, SNS, GCP Firestore, Cloud Functions, Pub/Sub, and analytics tools.

8. **Notifications and Alerts:**
   - Receive notifications for game invites, team updates, achievements, and leaderboard rank changes.
   - Use AWS DynamoDB, Lambda, SQS, SNS, GCP Firestore, Cloud Functions, Pub/Sub.

9. **Automated Question Tagging:**
   - Automatically tag trivia questions with relevant categories based on content.
   - Use AWS Comprehend, Lambda, DynamoDB/Firestore, or GCP Natural Language API, Cloud Function.

10. **Virtual Assistance:**
    - Implement chatbots for navigation support and dynamic database search for scores.
    - Use AWS Lambda, DynamoDB/Firestore.

## Installation and Usage

- Clone the repository.
- Set up your chosen cloud services as per the project specification.
- Run the front-end application using React or your chosen framework.
- Deploy the front-end to GCP Cloud Run for user-facing interface.
- Monitor game performance and user engagement through analytics tools.

## Contributors

- Harsh Srivastava
- Dhanesh Walte
- Ashutosh Sagar
- Alis Sanjaybhai
- Harsh Kathiria

