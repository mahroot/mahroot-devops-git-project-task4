# DevOps Git Workflow Project

## Branch Strategy
- main → production-ready code
- dev → integration/testing
- feature/* → new features (docker, terraform, jenkins, etc.)

## Workflow
1. Create feature branch
2. Commit changes with clear messages
3. Push branch to GitHub
4. Open Pull Request → dev
5. Merge → dev → main (release)
6. Tag release versions
