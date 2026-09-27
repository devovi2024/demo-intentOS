# IntentOS demo

## Project overview
IntentOS is a frontend only prototype for planning software requirements and connected system specifications. It runs entirely in the browser with mock AI behavior and local storage.

## Features
Interactive project dashboard, idea analysis simulation, requirements, clarifications, roles, features, business rules, workflows, ERD entities, API endpoints, permission matrix, user stories, test cases, architecture cards, global search, edit and delete dialogs, JSON/Markdown export, and responsive workspace navigation.

## Technology
HTML5, CSS3 and vanilla JavaScript. No backend, external API, credentials, or build step.

## Folder structure
- `index.html`: application entry point
- `css/main.css`: interface and responsive styling
- `js/data.js`: structured demo data model
- `js/app.js`: state, navigation, rendering, interactions and export

## How to run
Open `intentos-demo/index.html` in a modern browser. For best browser storage behavior, use a simple static file server.

## Demo account
`demo@intentos.local` / `demo123`. Authentication is simulated in the browser.

## How demo AI works
Analysis actions show a short staged progress dialog and update mock project state. No AI provider is contacted.

## How localStorage works
Projects are saved in `intentOS_projects`; current account and project use `intentOS_currentUser` and `intentOS_currentProject`. Refreshing the page keeps edits in the same browser.

## How to reset demo data
Open Settings and choose Reset Demo Data. The action restores Food Delivery Platform and E-Commerce Platform.

## Production upgrade plan
- HTML/CSS/JS → Next.js frontend
- Mock AI → real AI provider
- localStorage → PostgreSQL
- Demo authentication → JWT authentication
- Mock generation → NestJS AI services
- Static workflow → persistent workflow engine

This prototype does not implement those production services.
