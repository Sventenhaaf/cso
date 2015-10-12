# CodeSven
Software Tools in Javascript

[CodeSven Link][CodeSven]
[CodeSven]: https://radiant-sea-1408.herokuapp.com/

## Minimum Viable Product

CodeSven is a tool to play around with Javascript in the browser. It is inspired by CodePen / Repl.it

CodeSven allows users to:

- [ ] Create and read javascript snippets
- [ ] Execute these javascript snippets in the browser
- [ ] Create an account
- [ ] Log in and log out
- [ ] Sign up or log in to save, edit and delete snippets


## Design Docs
* [View Wireframes][view]
* [DB schema][schema]

[view]: ./docs/views.md
[schema]: ./docs/schema.md

## Implementation Timeline

### Phase 1: User Authentication, Snippet Model and JSON API (1.5 days)

I will start out with User Authentication. Snippets will first be modeled as plain text blocks that users can later create, share etc.

### Phase 2: Flux and Snippet CRUD (2 days)

Users must be able to create Snippets, but not be allowed to save them unless they are signed in. I will build a dummy button for the snippet (to show the snippet in an alert message for now). Later on, this button will execute the snippet as javascript in a separate window in the browser


### Phase 3: Javascript execution in the browser (3 days)

A user should be able to hit a 'run' button below their snippet, and as a result the javascript evaluation of the snippet should be displayed at a second window in the screen, much like [Repl.it][replit]
This is the more unique part of my app, and I want to make sure to make this work as well as possible. I think it is feasible to do with good preparation, a weekend in between, and help from mentor and TAs.

[replit]: https://repl.it/languages/javascript

### Phase 4: Syntax Highlighting (1 day)

Using something like [CodeMirror][codemirror] or [Highlight][highlight], 
[codemirror]: https://codemirror.net/
[highlight]: https://highlightjs.org/
