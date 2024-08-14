# AngularSupabase Starter

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.4.

- Web Application (4200)
- Admin Module (4201)

## Description

This project is a simple starter project for new Angular 18 projects using Supabase, and contains both a web application and an admin module. The web application is a simple website that allows users to login, register, configure a user profile, change application settings, setup a billing account, and view a basic list of items. The admin module is a simple website that allows administrators to manage users, application settings, view logs of user activity, and monitor the application. The project is designed to be a starting point for new Angular projects.

Although the project has a single git repository, the web application and admin module are separate Angular projects that are built and deployed independently. A traditional monorepo was considered, but as this is a starter template, it was decided that separate Angular projects would be easier to manage and deploy depending on the specific use-case.

The web application and admin module are served on separate ports, and can be deployed to separate servers if desiredm with the web application being served on port 4200 by defualt, while the admin module is served on port 4201.

## Features

- Modern Auth Workflow
- Angular Material
- Supabase Backend
- Admin Module for User Management
- Stripe Integration
- Google Maps
- Google Analytics
- Light / Dark Theme
- Mobile Responsive Design
- Custom Error / Not Found Pages

## Environment Variables

The project uses environment variables to configure the application. The environment variables are stored in the `environments` folder, and are used to manage external API connection strings.

## To Do

- [X] Add Angular Material
- [ ] Custom Environment Variables
- [ ] Add Angular Flex Layout
- [ ] Configure Application Themes
- [ ] Add Supabase Authentication
- [ ] Add Supabase Storage
- [ ] Add Stripe Integration
- [ ] Add Email Service
- [ ] Add User Settings
- [ ] Add Timezones
- [ ] Add Admin Module
- [ ] Add User Roles
- [ ] Add User Permissions
- [ ] Add Auth Guards
- [ ] Add Custom Not-Found Page
- [ ] Add Custom Error Page
- [ ] Add Loading Spinner
- [ ] Add Toast Notifications
- [ ] Add Snackbar Notifications

### Web Application

- [ ] Add Login Worklow
- [ ] Add Registration Workflow
- [ ] Add Forgot Password Workflow
- [ ] Add User Dashboard
- [ ] Add User Profile
- [ ] Add User Settings
- [ ] Add User Billing
- [ ] Add User Avatars

### Admin Module

- [ ] Add User Activity Logs
- [ ] Add User Management
- [ ] Add User Roles
- [ ] Add User Permissions
- [ ] Add User Settings
- [ ] Add Application Settings
- [ ] Add Application Logs
- [ ] Add Application Monitoring
- [ ] Database Monitoring
- [ ] Add Server Monitoring
- [ ] Add Server Logs
- [ ] User Reset Password
- [ ] User Role Impersonation
- [ ] Customize Registration Email

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Version Control

| Angular                          | Version  | Notes                       |
| -------------------------------- | -------- | --------------------------- |
| Angular CLI                      | 18.1.4   |                             |
| @angular-devkit/architect        | 0.1801.4 |                             |
| @angular-devkit/build-angular    | 18.1.4   |                             |
| @angular-devkit/core             | 18.1.4   |                             |
| @angular-devkit/schematics       | 18.1.4   |                             |
| @schematics/angular              | 18.1.4   |                             |
| Angular Material                 | 18.1.4   |                             |
| Supabase                         |          |                             |
| NestJS                           | 10.4.1   |                             |
| RxJS                             | 7.8.1    |                             |
| Node                             | 22.6.0   |                             |
| NPM                              | 10.8.2   |                             |
| TypeScript                       | 5.5.4    |                             |
| zone.js                          | 0.14.10  |                             |
