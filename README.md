]
### What you need !!

1. Git acccount (Ex: Github, Gitlab etc ) . In our case we use github.
2. [Netlify](https://bit.ly/netlify-account) account to host files and add custom domain .
3. [Forestry](https://bit.ly/forestry-account) account to maintain whole project without code.


### Step 1 : Fork or Clone repository

First we will fork this [alaje store](https://github.com/Mileba/Alaje-Store) template.

### Step 2 : Add your repository in Forestry

Go to your [forestry](https://bit.ly/forestry-account)  account and click on `import your site now`. declare your config.toml file [`exampleSite`] and fill up basic settings .


Now mark everything as done, then go to configuration to change the base url . You can put any url but this have to similar as netlify . So for now put a name which you are going to put in netlify as netlify subdomain.

### Step 3 : Setup and host website with Netlify

Here comes the last step . Go to your [netlify](https://bit.ly/netlify-account) account and click add new site . Choose your git repository to import your website in netlify .  And now you can see the forked `vex hugo` theme. select it and follow the steps. Then go to `site settings` for change the site name and put your subdoamin name here what you puted on forestry as base url. save it and go to `deploy` from top menu, Wait a while and click on `site preview` or just simply go to the subdomain you puted as base url. **BOOM! Your site is live.** Now you can go to forestry and add, remove or customize every setting and content.

> If you face any issue regarding the installation feel free to open [open a new issue](https://github.com/Mileba/Alaje-Store/issues)



## Installation
At the top we have shown an easy hugo installation. but still if you think you want to go with the traditional way then use the following commands:

```
$ git clone git@github.com:Mileba/Alaje-Store.git
$ cd Alaje-Store/exampleSite/
$ hugo server --themesDir ../..
```


## Main features

* Fully Responsive Ready.
* Multilingual Support.
* Powered by bootstrap 4 framework.
* Product Showcase.
* Product Details Page.
* Snipcart Included.
* Blog Post.
* Contact Form.
* Email Subscription Section.
* Documented codes.

## What's New

* Multilingual Support.
* Product Details Page.
* Snipcart Included.
* Blog Post.
* Contact Form.

