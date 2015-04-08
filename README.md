![JS.ORG Logo](http://logo.js.org/png/github_header.png)

Have a look at [JS.ORG](http://dns.js.org) [(branch: gh-pages)](https://github.com/js-org/dns/tree/gh-pages)

To get a short and sleek subdomain for you own GitHub Page or follow these 4 Steps:

### Step 1
If you haven't already, now it's time to log in to your GitHub account and set up your GitHub Page following the instructions [here](https://pages.github.com/). To get a head start you can simply use the generator and one of the provided themes.

### Step 2
Now determine your js.org subdomain: either choose your username or the name of your repo according to the existing GitHub Pages URL (for http://foo.github.io/bar, either "foo.js.org" or "bar.js.org" would be possible). More details in the [wiki](https://github.com/js-org/dns/wiki).

### Step 3
Add a file named "CNAME" to your repo with a single line matching the domain you have chosen (e.g. "foo.js.org" without quotes). If you face problems, check out the section [Custom URLs](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/#creating-and-committing-a-cname-file) at GitHub Pages Help.

### Step 4
To finish the procedure, make a pull request in this GitHub repository that adds your subdomain to the [list](https://github.com/js-org/dns/blob/master/cnames_active.js) of exisiting JS.ORG domains. Your new URL should go live within 24 hours (keep an eye on your pull request in case of a naming conflict).