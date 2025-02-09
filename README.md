# Simple Personal Website

This is a minimalistic personal website that serves an "About" page along with a few links. There are no posts on this website.

- Built with Jekyll using the Minima theme.
- Features a hand-crafted language switcher.

To build and view my website locally, run:

```sh
bundle exec jekyll serve -w
```

If you'd prefer to develop the website in a Docker container (e.g., to avoid having to install Ruby and dependencies on your host machine), run:

```sh
docker compose up --build
```

Then, navigate to <http://localhost:4000> on your host machine to view the website. Jekyll will re-build the website as you make changes to files.

> The instructions above and the configuration files of Docker are slightly modified based on [missing-semester](https://github.com/missing-semester/missing-semester), the website of a wonderful course at MIT.
