[![hugo](https://user-images.githubusercontent.com/43764894/223559747-e9d7f19d-91bf-46a9-a0cb-8d6a40d3cfa3.png)](https://ntl.fyi/3P9w1mr)

# Hugo Quickstart Template   

This is a bare-bones Hugo project that has everything you need to quickly deploy it to [Netlify](https://netlify.com). 

Hate reading, here's a video: https://youtu.be/t-tsRxxYdpk

Love reading, here's blog post: https://www.netlify.com/blog/deploy-your-hugo-app-quick/

## Table of Contents:

- [Quick Setup + Deploy Option](#quick-setup--deploy-option)
- [Regular Setup](#regular-setup)
  - [Cloning + Install Packages](#1-cloning--install-packages)
  - [Deploying](#2-deploying)
- [Styling](#styling)
  - [Notes on Styling](#notes-on-styling)
  - [Remove Styling](#remove-styling)
- [Hugo + Netlify Resources](#hugo--netlify-resources)
- [Testing](#testing)
  - [Included Default Testing](#included-default-testing)
- [Want to learn more?](#want-to-learn-more)

## Quick Setup + Deploy Option

Click this button and it will help you create a new repo, create a new Netlify project, and deploy!

[![Deploy to Netlify Button](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/hugo-quickstart)

## Regular Setup

 ### 1. Cloning + Running Locally

  - Clone this repo with one of these options:

    - Click the 'Use this template' button at the top of the page
    - Or via the command line `git clone https://github.com/netlify-templates/hugo-quickstart`

 - Start the Hugo sever & check it out:

   - `hugo server -D`
   - go to [http://localhost:1313/](http://localhost:1313/)

  > Alternatively, you can run this locally with [the Netlify CLI](https://docs.netlify.com/cli/get-started/)'s by running the `netlify dev` command for more options like receiving a live preview to share (`netlify dev --live`) and the ability to test [Netlify Functions](https://www.netlify.com/products/functions) and [redirects](https://docs.netlify.com/routing/redirects/). 

  ### 2. Deploying
  - Install the Netlify CLI globally `npm install netlify-cli -g`
    
  - Run `hugo`

  - Then use the `netlify deploy` for a deploy preview link or `netlify deploy --prod` to deploy to production

  Here are a few other ways you can deploy this template:
    
  - Use the Netlify CLI's create from template command `netlify sites:create-template hugo-quickstart` which will create a repo, Netlify project, and deploy it
    
  - If you want to utilize continuous deployment through GitHub webhooks, run the Netlify command `netlify init` to create a new project based on your repo or `netlify link` to connect your repo to an existing project

## Styling

We've added some modern styling to this template using Sass within an external stylesheet, this will allow you to easily remove our styling and add in your own. 

If you decide that you want to keep our styling you can review our style notes below. 

### Notes on Styling

The variables below give you the ability to change the gradient colors of the blobs and are interpolated into the URL string of the background-img within the body. 

```css
// Controls the blob blur gradient colors within the main tag's svg
--top-right-blur-1: #2ebc92;
--top-right-blur-2: #ecbb50;
--bttm-left-blur-1: #ff3e89;
--bttm-left-blur-2: #0095cc;
```

## Remove Styling

If you decide that our styling is not for you, all you'll need to do is remove the [demo-styling.css](https://github.com/netlify-templates/hugo-quickstart/blob/main/themes/netlify-basic/static/css/demo-styling.css) file. 

## Hugo + Netlify Resources

Here are some resources to help you on your Hugo + Netlify coding fun!

- [Hugo on Netlify Integration Page](https://ntl.fyi/3P9w1mr)


Hope this template helps :) Happy coding 👩🏻‍💻!

---
