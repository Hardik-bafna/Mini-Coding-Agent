# Tars
A terminal coding agent in Go that proves every fix by running your tests
## Why this exists
Tokens used in frontier model are expensive, and local models lack reliability when it comes to
coding agency: they generate invalid calls for tools and invalid edits. The purpose of the agent below
is to help you make use of local models, and it won't tell you "done" before passing your tests.
