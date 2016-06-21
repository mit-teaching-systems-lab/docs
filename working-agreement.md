# Working agreement
This is the working agreement for doing software engineering work in the Teaching Systems Lab.

If you have questions, comments or improvements, please share them!  Open a pull request or come talk to @kevinrobinson or anyone else in the lab.

#### Use source control
Check all projects into GitHub or MIT GitHub, so that everyone on the team has access to your work.

#### Keep master green
The master branch should always be deployable and pass all tests.  If master is broken, consider reverting immediately and fixing the underlying issue in a separate pull request.

#### Make changes through pull requests from forks
Use pull requests from your own fork to make any changes, and do this regularly as you're making progress.  All pull requests should be approved before merging, even if they are self-approved.  For more information check out https://help.github.com/articles/using-pull-requests/ or the guides in https://guides.github.com/.

#### Ask for feedback
Every developer has commit access, and it’s up to them to decide how to get approval on pull requests.  Sometimes explicit review is appropriate, sometimes an after-the-fact review is appropriate, and sometimes self-approval is appropriate.  If you’re not sure, default towards asking someone to review before merging.
If you're looking to learn more about how to give helpful feedback in a code review, you can start with looking at https://github.com/thoughtbot/guides/tree/master/code-review.

#### Describe pull requests succinctly
Describe pull requests in 1-3 paragraphs, and attach screenshots if the change is user-facing or visual.

All commits merged to master should have clear commit messages that would be understandable to any developer on the team.  Squashing commits in a pull request can help make this simpler.

Name branches with a prefix indicating what kind of work it is.  Some examples include: feature/new-challenge-page, patch/saving-comment-bug,  refactor/extract-comment-component or experiment/visual-challenge-map.
