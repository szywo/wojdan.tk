# My personal website
## wojdan (dot) tk

At the beggining it is supposed to show some bio and my [GitHub][ref-gh] public repos using [GitHub Api][ref-ghapi] running (if tests will be positive) on server-side (data caching and conditional requests). Next step is to use server-side data only for first connection and AJAX for returning. There is also plan to use [Bootstarp][ref-bs] to make it responsive and nice looking.

### Here is a sketch of goals:

- [ ] Basic Git Api (server-side?)
  - [ ] Read user info
  - [ ] Read repos info
  - [ ] Show repos
  - [ ] Convert to conditional requests
- [ ] Split API request (php/js)
  - [ ] Check if ETags stored in cookie/session (php)
  - [ ] If not init with server-siide data (php)
  - [ ] Else use stored ETag via jQuery
- [ ] Extensions (js)
  - [ ] Show repo `README.md`
  - [ ] Show repo commits
  - [ ] ... _ideas?_
- [ ] Bootstrap framework
  - [ ] [Jumbotron?][ref-bsjumbo]/[Jumbotron-narrow?][ref-bsjumbon] Template
  - [ ] Git repos
  - [ ] Bio
  - [ ] Banner (static/Git?/FB)
  - [ ] Avatar (static/Git/FB)
  - [ ] Solarized (dark) palette
- [ ] [Mini blog][ref-bsblog]
  - [ ] Static
  - [ ] REST API

<!-- Links -->
[ref-gh]: https://github.com/szywo/
[ref-ghapi]: https://developer.github.com/v3/
[ref-bs]: http://getbootstrap.com/getting-started/#examples
[ref-bsjumbo]: http://getbootstrap.com/examples/jumbotron/
[ref-bsjumbon]: http://getbootstrap.com/examples/jumbotron-narrow/
[ref-bsblog]: http://getbootstrap.com/examples/blog/
