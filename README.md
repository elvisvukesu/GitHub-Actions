# sonarqube integration
Use the action in: https://github.com/marketplace/actions/sonarqube-quality-gate-check

Create a file in the root of the project called "sonar-project.properties" and add the following entries.
sonar.projectKey=<replace with the key generated when setting up the project on SonarQube>
sonar.sources=.

