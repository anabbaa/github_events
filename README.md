# github_events

# activity types

- enter then indent then reserved named types then enter and indent then its types for example pull-request has a type closed or opened as a note pull request event it is be default openor reopened you can add another event by press enter and back to the same level for the first one and this last one need semi colon for example workflow_dispatch:

# Filter

- enter indent then add reserved wor branches then enter indent then your targeted branches for example - main also you can add this for types so you limit event more and more
- another filter path: it can be added to pull request and push events
  - path: here you say a workflow will be triggered if a file in acertain path changed
    -path-ignore: opposite triggered this workflow for any changes without this one

# cnelling skipping

- by failing
- skipping by adding something to your message when you are commiting
  - git commit -m"addded [skip ci]"another ke< word to skip
    [ci skip] [skip actions] [actions skip] [no ci]
