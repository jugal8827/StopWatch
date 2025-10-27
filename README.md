# React Stopwatch Application
A high-precision stopwatch built with React utilizing modern hooks (useState, useEffect, and useRef) for optimized performance and accurate time tracking. The application provides a clean and intuitive interface to Start, Stop, and Reset the timer.

## Key Features
- High-accuracy timer with millisecond precision
- Robust state management using React Hooks
- Maintains elapsed time on resume
- Efficient interval handling using useRef
- Modular and reusable stopwatch component

## Technologies Used
- React : Frontend UI Framework
- Javascript : Logic and component functionality
- CSS : Basic styling and layout
- HTML/JSX : Component structure

## Component Overview
The stopwatch uses Date.now() to compute real-time differences rather than relying solely on interval counts, which ensures accurate timing.
- useState manages running state and elapsed duration
- useRef persists interval ID and starting timestamp across renders
- useEffect handles creation and cleanup of the timing interval
Time is formatted into the standard format:
- MM:SS:MS → Minutes : Seconds : Milliseconds

## Getting Started
- Clone the repository
- Navigate to project directory
- Install Dependencies
  - npm install
- Start development server
  - npm start
