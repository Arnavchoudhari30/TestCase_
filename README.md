🧪 Ludo Game – Test Case Suite
This repository contains a comprehensive set of manual test cases for a Ludo Game application. The objective is to test the core game mechanics, user interface, multiplayer functionality, and edge-case behaviors of a digital version of the classic Ludo board game.

✅ About the Project
Ludo is a popular turn-based board game where 2–4 players race to move their tokens from base to home using dice rolls. This test suite is built to validate the functional correctness, user experience, game logic, and multiplayer behavior of a Ludo game developed as a mobile or web app.

📑 Test Case Format
Each test case includes the following fields:

Test Case ID – A unique identifier for tracking

Test Scenario – A brief description of what is being tested

Test Steps – The steps to execute the test

Expected Result – The expected behavior of the application

Test Type – Type of testing (e.g., Functional, UI, Boundary, Negative)

🔍 Test Modules Covered
This suite covers the following major modules:

Game Launch & Setup

Verify the game loads correctly

Game modes (Single, Multiplayer, Online)

Player color selection and lobby joining

Dice Mechanics

Dice rolls, values between 1–6

Re-rolls on 6 and three consecutive 6s rule

Token Movement

Releasing tokens on 6

Moving tokens as per dice value

Capturing opponent tokens and handling safe zones

Game Logic & Turn Handling

Turn switching

Double turn on 6

Declaring winner when all tokens reach home

Ending game correctly

Multiplayer & Sync

Real-time synchronization in online matches

Reconnection handling

Chat/emote features (if any)

User Interface & UX

Responsive layout on different screen sizes

Pause/resume functionality

Sound/music settings

Edge Case & Negative Testing

Invalid token movements

Moving without dice roll

Maximum limits and rule boundaries

