# deploy-codedeploy-action

## GitHub integration

* [x] POC github action based on branch name
* [x] trigger deployment by PR comment
* [x] PR commands based on https://github.com/peter-evans/slash-command-dispatch - implemented but discatded becase of exposing PAT token
* [x] Public reusable deploy action https://github.com/theinnercircle/deploy-codedeploy-action - dirty but workable implementation, demo: https://github.com/theinnercircle/imagick/pull/4#issuecomment-1124558968
* [ ] independant python environment without using user-wide pip3 libraries
* [ ] ? tweak github action to avoid calling `pip install` every time
* [x] make deployment action/script reusable over node/imagick/backend repos
* [x] provide a way to deploy master branch to test1/2 - can be done via `/deploy test1` from any issue
* [ ] provide mode details as codedeploy version description: who triggered the build, pull request, commit