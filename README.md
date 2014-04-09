# nodejs cookbook

This cookbook installs nodejs. If you are deploying a Rails app you will need a JavaScript runtime to precompile application assets.

# Requirements

This cookbook requires `apt`.

# Usage

Include this cookbook in your `Berksfile`.

````
cookbook 'nodejs', git: 'aerogami-cookbooks/nodejs'
````

Install the cookbook.

````
berks install
````

Add to your chef kitchen and use as desired.

# Author

Mohamad El-Husseini

www.aerogami.com.br
