# Setup and Deployment Instructions

## Setup
To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/JBRphotos/workout.git
   ```

2. Navigate to the project directory:
   ```
   cd workout
   ```

3. Install the necessary dependencies:
   ```
   npm install
   ```

## Deployment
- To deploy the **dev** branch to staging, use the following GitHub Actions workflow:

- To deploy the **main** branch to live, ensure you merge changes into the main branch and push:
   ```
   git checkout main
   git merge dev
   git push origin main
   ```

That's it! Your applications should be deployed to the respective environments.