# INNOVATIA

This repository contains the frontend code for IINOVATTIA a Fiverr/Upwork-like application. 

## Project Overview

This project aims to bridge the gap between freelancers and employers by providing a platform for short-term and project-based job opportunities. Inspired by platforms like Upwork, our solution offers a seamless experience for freelancers and employers, including profile management, job marketplace, and secure financial transactions.

## Features

- **Freelance Job Marketplace**: Find and apply for short-term jobs, gig work, and project-based opportunities.
- **Freelancer Profile & Portfolio Management**: Create detailed profiles, showcase skills, and receive feedback through ratings and reviews.
- **Advanced Search & Analytics**: Perform extensive searches and receive AI-based recommendations for job opportunities and talent.
- **Escrow Account Creation**: Securely hold funds until job completion and facilitate smooth transactions through integrated payment gateways.
- 
## Installation

To set up and run the project locally, follow these steps:





## Common Errors and Solutions
If you encounter any error while installing dependencies ffollow the steps:
Solutions:

1.Use the --legacy-peer-deps Flag:
To bypass peer dependency conflicts, run:
```bash
npm install --legacy-peer-deps
```
2.Use the --force Flag:
Force the installation of dependencies (this may result in an inconsistent dependency tree, but the dependencies will be installed):
```bash
npm install --force
```
3.Use Compatible Versions of Dependencies:
Option A: Downgrade React to a version compatible with infinite-react-carousel:
```bash
npm install react@16 react-dom@16
```
Option B: Find an alternative package that provides the same functionality as infinite-react-carousel and supports React 18.x.

# Run
```bash
npm run dev
```
