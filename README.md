# Data and Code Availability Standard (DCAS)

![Logo](https://datacodestandard.org/assets/img/logo-800.png)

[DCAS](https://datacodestandard.org/) is a standard for sharing research code and data, endorsed by [leading journals](https://datacodestandard.org/journals) in social sciences. It is maintained by the [Social Science Data Editors](https://github.com/social-science-data-editors/).

See [https://datacodestandard.org/](https://datacodestandard.org/).


## How to Add My Journal to this website


1. Adapt the journals data and code policy such that it implements all points of the [DCAS](https://datacodestandard.org/), including a link to [https://datacodestandard.org/](https://datacodestandard.org/).
2. Create fork of this repository.
3. In your fork, edit the file [`/_data/journals.csv`] by adding a new row with your journal's details.
4. File a pull request from your fork requesting inclusion.

## How to locally run this website

Using a docker client:

```
docker compose up --build
```

Then open http://localhost:4001 in browser. Livereload port maps to 35730 (host) → 35729 (container). To stop do ctrl-C first, or in another terminal execute:

```
docker compose down
```