# git-training-with-pipeline
| tollgate |
| ------------- |
![integration status](https://concourse.bosh.praqma.cloud/api/v1/teams/main/pipelines/git-training-pipeline/jobs/build/badge) |

Welcome to git training, with a real repository. 

This repository runs with the Praqmatic Workflow as [described here](http://www.praqma.com/stories/a-pragmatic-workflow/).
In turn, this means that pushing a ready branch will have a build engine pick up the branch, build the jekyll site and then commit to master if everything succeeds. 
 
A failed build will leave a wip/your-branch-name for you to clean up, which lets you experience git in a more functional mode - recovering from discaster! :wink: 

Enjoy the training session and have fun! 
