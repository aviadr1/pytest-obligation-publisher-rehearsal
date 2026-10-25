# Publisher safety rehearsal

An isolated, public integration test for gigaverse-app/pytest-obligation#162.
The default branch contains the publisher. Pull requests come from a separate fork.
No repository secrets, personal tokens, deployments or paid runners are used by the workflows.
The second scenario deliberately fails a test and alters the reported outcome/revision and uploaded Markdown.
The trusted publisher must retain GitHub’s actual failure, use the API head for links, and ignore the planted Markdown.
