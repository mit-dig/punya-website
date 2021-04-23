# MIT Punya Website

This website is served using GitHub pages.

## Setup (macOS)

Prerequisites: Homebrew

1. Ensure command line buildtools are installed with:

    `sudo xcode-select --install`
    
2. Install rbenv:

    `brew install rbenv`
    
3. Enable rbenv:

    Add `eval "$(rbenv init -)"` to your shell profile and reload it with `source ~/.bash_profile`

4. Install ruby 3.0.1:

    `rbenv install 3.0.1 && rbenv global 3.0.1`

5. Install dependencies:

    `bundle install --path=vendor/bundle`

6. Run Jekyll:

    `bundle exec jekyll serve`
    
Once the server is running, the compiled versions of the pages will be available on `http://localhost:4000/`. Every time you save a file the site will be recompiled, so simply refresh your browser to see the updated changes. Once you've made your changes, `git add` the changed files, `git commit`, and then `git push` to a branch or a fork in order to make a pull request.

