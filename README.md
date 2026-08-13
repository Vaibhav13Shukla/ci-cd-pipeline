# CI/CD Pipeline — AWS CodeDeploy Demo

End-to-end CI/CD pipeline demo using AWS CodePipeline, CodeBuild, and CodeDeploy for automated application deployment.

## Overview

A complete CI/CD pipeline demonstration showing automated build, test, and deployment workflows using AWS developer tools. Includes a Python web application with proper deployment configurations.

## Features

- **AWS CodePipeline** — Orchestration of build and deploy stages
- **AWS CodeBuild** — Automated build and test execution
- **AWS CodeDeploy** — Zero-downtime deployment to EC2/On-prem
- **Python Web App** — Flask-based application with deployment scripts

## Project Structure

`
ci-cd-pipeline/
├── buildspec.yml        # CodeBuild configuration
├── appspec.yml          # CodeDeploy configuration
├── code.py              # Application code
├── index.html           # Frontend
├── after_install.sh     # Post-deploy script
├── install_dependencies.sh
├── start_server.sh
├── stop_server.sh
├── validate_service.sh
├── scripts/             # Reusable deployment scripts
├── CODEDEPLOY.md        # Deployment guide
└── HELP.md
`

## Setup

`ash
pip install -r requirements.txt
python code.py
`

## Deployment

See CODEDEPLOY.md for AWS CodeDeploy setup instructions.

## License

MIT
