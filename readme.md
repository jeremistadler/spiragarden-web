# Spiragården.se website 


### Under the Hood

This site is made with [Jekyll](http://jekyllrb.com), an open source static site generator. This means the Jekyll program takes the content we want to be on the site and turns them into HTML files ready to be hosted somewhere. Awesomely, GitHub provides free web hosting for repositories, called [GitHub Pages](http://pages.github.com/), and that's how this site is hosted. The content for the site is on a branch named [gh-pages](https://github.com/github/government.github.com/tree/gh-pages).


## To Set up Locally

You can take all the files of this site and run them just on your computer as if it were live online, only it's just on your machine.

#### Requirements

* [Jekyll](http://jekyllrb.com/)
* [Ruby](https://www.ruby-lang.org/en/)
* [Git](http://git-scm.com/)

_If you have installed [GitHub Desktop](https://desktop.github.com), Git was also installed automatically._

To copy the repository's files from here onto your computer and to view and serve those files locally, at your computer's command line type:

```bash
git clone https://github.com/github/government.github.com.git
cd government.github.com
script/bootstrap
script/server
```
Open `http://localhost:4000` in your browser

----

Don't see what you're looking for? Create an [issue](https://github.com/github/government.github.com/issues/new), we'll do our best to help you out.
