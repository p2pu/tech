Basic process is that latest dev branch is master on p2pu/learningcircles
Tests are run on TravisCI and a docker image is built.

When making a release
- Create a PR from master into release
- Call the PR Release YYYY-MM-DD
- Put the list of changes in the PR description
- Wait for tests to pass (docker image won't be uploaded for PR)
- Merge PR
- Wait for TravisCI to build release docker image
- Follow steps below to deploy latest release docker image

To deploy a new version of learning circles:

1. Install ansible
1. Grab the latest playbooks from p2pu/marvin
1. Copy the encrypted hosts_vars and vars from AWS S3
1. Run ansible-playbook
