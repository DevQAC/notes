# CI Task Brief

## Tools
For following research and decide on a tool:
- Version Control System
- Project Tracking and Task Management System
- Email server for automated emails
- CI Server
- Artefact Repository

The reasons for deciding on a tool should include proof of concepts. For example, if you decided to have Jenkins as a CI server and Nexus 3 as an artifact repository, prove how you would be able to push an artifact from a Jenkins server to a Nexus 3 repository and demo it, if possible, when presenting.

## Infrastructure
You must decide on, and architect, what your infrastructure will look like for your CI setup, based on the tools that you have chosen.
Things to focus on while designing your infrastructure are:
- Cost
- Application Environments:
    How easy would it be in your setup to configure a new test environment (for example, testing a feature branch)?
- Setup Overhead:
    How much of the CI environment can you automate? If you set it up once, how easy would it be to configure it again elsewhere?

Your ideas and plans for infrastructure should also include proof of concepts and maybe even demos where possible.
One example would be running Jenkins in a Kubernetes cluster; how would that be possible? What configuration is needed?

