# StickyWall

StickyWall is a browser-based visual note-taking application that allows users to create, organize, and connect ideas on an infinite canvas.

## Overview

The application provides a flexible workspace where notes can be freely positioned, resized, and linked together to represent relationships between ideas. It is designed to support non-linear thinking and quick visual organization.

User data is persisted using Firebase, with authentication handled through Google Sign-In.

## Features

- Free-form note creation and editing
- Drag and resize interactions
- Visual connections between notes
- Multi-select and bulk deletion
- Color customization
- Pinning to lock notes in place
- Zoomable canvas for large workspaces
- Persistent storage with Firebase Firestore
- User authentication via Firebase Auth

## Tech Stack

- HTML, CSS, JavaScript
- Firebase Authentication
- Firebase Firestore
- Netlify (deployment)

## Live Demo

https://bucolic-klepon-ac6ddf.netlify.app

## Architecture

The application is built as a client-side system without a traditional backend server. All state management and interactions are handled in the browser, while Firebase is used for authentication and data persistence.

Each user’s data is stored independently in Firestore and scoped through authentication-based security rules.

## Security

- Access to data is restricted to authenticated users
- Firestore rules ensure users can only read and write their own data
- API key usage is limited to authorized domains

## Notes

This project focuses on interaction design, real-time UI behavior, and client-side data handling in a dynamic visual environment.

## License

For educational and personal use.
