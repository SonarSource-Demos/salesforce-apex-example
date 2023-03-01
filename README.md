# Salesforce Apex Demo

## Abstract
This demo repo serves as a showcase of Sonar's analysis capabilities involving the Apex programming language for Salesforce. It's being prepared in advance of the Trailblazer DX conference in San Francisco (March 7-8, 2023).

## Storyboard
The project will have its default branch + 1 Pull Request branch under analysis. The main branch passes its QG despite issues in Overall Code. The PR will have a Quality Gate failure because it introduces problems.

The overall goal is simple: to be able to tell a basic Clean as You Code story while looking at a repository containing code familiar to the audience.

## Demo Instructions
1. Use Create Project wizard to create a new project in your SonarQube instance and configure for GitHub integration w/manual CI
2. Analyze main branch (manually and locally)
3. Analyze the PR that already exists on this repo
4. Confirm project dashboard + PR branch dashboard
5. Open the project in SonarLint in VS Code and set up Connected Mode to your SQ instance. Bind the project (which you'll likely be prompted to do).

## Background
This project is a copy of [Milestones-PM](https://github.com/SalesforceLabs/Milestones-PM). This copy of the original repo is hosted here for the sole purpose of demonstrating SonarQube APEX code analysis.

Please don't use this code, or any bytecode hosted here, for anything. Please refer to the original Force.com LAB repository for any use of the library.
