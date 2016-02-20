
## Git Time Tracker

This is a proof of concept for a git time tracking system. Once installed it will write the repo / branch name along with a time stamp to a csv file using git's `post-checkout` hook. That file can then be processed to produce the amount of time spent on each branch over some time period.

As a convention, switch to your master branch whenever you're not actively working on something. That way you won't have extra time tracked toward a a task that you're not working on.

This thing is in it's early stages, so bare with me.
