# Renaizant Docs

Renaizant documentation website is based on [Docsy](https://github.com/google/docsy). Docsy is a Hugo theme for technical documentation sites, providing easy site navigation, structure, and more.

## Cloning the Renaizant Documentation Project

The following will give you a project that is set up and ready to use (don't forget to use `--recurse-submodules` or you won't pull down some of the code you need to generate a working site). The `hugo server` command builds and serves the site. If you just want to build the site, run `hugo` instead.

```bash
git clone --recurse-submodules --depth 1 https://github.com/omfgnuts/renaizant-docs.git
cd renaizant-docs
hugo server
```

The theme is included as a Git submodule:

```bash
▶ git submodule
 a053131a4ebf6a59e4e8834a42368e248d98c01d themes/docsy (heads/master)
```

If you want to do SCSS edits and want to publish these, you need to install `PostCSS` (not needed for `hugo server`):

```bash
npm install
```

## Running the website locally

Once you've cloned the site repo, from the repo root folder, run:

```
hugo server
```
