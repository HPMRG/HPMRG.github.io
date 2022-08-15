# UCLA branded academic website

This template for [my personal website](http://www.stat.ucla.edu/~handcock/) is based on the [Hugo Academic theme](https://github.com/wowchemy/starter-hugo-academic). It is based on the work of of [Qingyuan Zhao](http://www.statslab.cam.ac.uk/~qz280) who deserved the credit for both creating the template and also publishing it so that others can benefit from it. Thank you, Qingyuan Zhao! See [his post](http://www.statslab.cam.ac.uk/~qz280/post/migrating/) for a guide.

## The Hugo framework {#the-hugo-framework}

Based on Qingyuan's work, I decided to use Hugo. It is renowned as "the world's fastest framework for building
websites". I use the Academic theme for Hugo as it implements many features for academic researchers.

It helps to have Hugo installed locally as you can compile the website and see what you will get. Installing Hugo in Mac OS X is straightforward with [homebrew](https://brew.sh/). Simply run

```sh
brew install hugo
```
### Creating a local website

First, clone this repository. I put mine in "handcockc.github.io".
You can preview the website by running

```sh
hugo server --baseURL http://localhost:1313/
```

from the website directory (i.e., "handcockc.github.io"). This builds the website and creates a
local web server to host it. It generates a link (the default is <http://localhost:1313/>)
which can be pasted into a web browser. In the background, the hugo
server also detects any change to the content and updates the website
automatically.

### Creating a public website

Commit your website as a repository on github (with \<git hub ID\>.github.io as a name).

After successfully committed, go to your repository and click on the “Settings” on the top right, then scroll down to the Github Pages section. Then  click on the published link.

