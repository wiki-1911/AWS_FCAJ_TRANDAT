---
title: "Week 11 Worklog"
date: 2026-07-13
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

{{% notice info %}}
📅 **Duration:** 13/07/2026 – 19/07/2026
{{% /notice %}}

### Week 11 Objectives

- Implement real-time gameplay using WebSocket.
- Develop an Elo-based matchmaking system.
- Improve the Amazon Cognito registration flow by supporting OTP resending for unconfirmed users.
- Integrate Amazon DynamoDB as the primary database for the web game.
- Develop AWS Lambda functions to support core game operations.

### Tasks to be carried out this week

| Day | Task                                                                                                                                                                                  | Start Date | Completion Date | Reference Material     |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ---------------------- |
| 1   | Implement real-time communication for the game using WebSocket technology.                                                                                                            | 13/07/2026 | 14/07/2026      | Project Source Code    |
| 2   | Develop an Elo-based matchmaking system and implement Elo rating calculation after each match.                                                                                        | 15/07/2026 | 16/07/2026      | Project Documentation  |
| 3   | Improve the Amazon Cognito registration process by implementing the OTP resend feature for users in the **UNCONFIRMED** state.                                                        | 17/07/2026 | 17/07/2026      | Amazon Cognito         |
| 4   | Integrate Amazon DynamoDB into the project and create AWS Lambda functions, including **Start Match**, **Process Game Engine**, **Save Deck**, **Handle Timeout**, and **End Match**. | 18/07/2026 | 19/07/2026      | AWS Management Console |

### Week 11 Achievements

- Successfully implemented **WebSocket** communication, enabling real-time gameplay between players.
- Developed an **Elo-based matchmaking system** that pairs players with similar skill ratings and updates their Elo scores after each match.
- Enhanced the **Amazon Cognito** authentication flow by allowing users in the **UNCONFIRMED** state to request a new OTP for account verification.
- Integrated **Amazon DynamoDB** as the primary database for storing game-related data, providing low-latency access and cost-effective scalability for the web application.
- Developed multiple **AWS Lambda** functions to support the game backend, including:
  - **Start Match**
  - **Process Game Engine**
  - **Save Deck**
  - **Handle Timeout**
  - **End Match**
- Improved the overall backend architecture by adopting AWS serverless services, making the system more scalable, maintainable, and suitable for real-time multiplayer gameplay.
