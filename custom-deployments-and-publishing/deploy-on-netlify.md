---
description: Learn how to configure & deploy your website built with Codelessly on Netlify.
cover: ../.gitbook/assets/Netlify + Stackbit post banner 2.png
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Deploy on Netlify

This guide is about deploying and publishing your project as a website on [Netlify](https://www.netlify.com/) using a Github repository linked to your project. If you haven't done so already , checkout our guide on [Linking your project to a Github Repository](https://app.gitbook.com/o/rXXdMMDhFOAfV2g6j8A1/s/x4NeiXalJWaOaV6tsK5f/\~/changes/21/custom-deployments-and-publishing/linking-with-github-repository).

> [Netlify](https://www.netlify.com/) is the modern development platform that allows you to build and deploy your websites from a Github repository. You must have an active account on [Netlify](https://www.netlify.com/) before starting this guide.

1. If you haven't done so already,  [Link your project to a Github Repository](https://app.gitbook.com/o/rXXdMMDhFOAfV2g6j8A1/s/x4NeiXalJWaOaV6tsK5f/\~/changes/21/custom-deployments-and-publishing/linking-with-github-repository).
2. Open [Netlify](https://www.netlify.com/) and login.
3. Based on whether you have used [Netlify](https://netlify.com) before or this is your first project, Either go to `Sites>Add new site>Import an existing project` or `Sites>Import from Git`. \
   If you are using Netlify for the first time, you will be asked to deploy your first project. If you are in signup phase then you will be presented with **Deploy your first project** screen. Skip this step in that case.
4. Click on `Deploy with Github` option and authenticate & link with [Github](https://github.com) if it asks to.
5. Select the **owner** and **repository name** for the repository you that [Codelessly](https://codelessly.com) automatically created for you. This must match the **owner** and **repository name** you specified in **Codelessly's publish settings**.
6. Click on Deploy button and wait for it to deploy. 🎉

At this point, your deployment should be ready with a URL to access your website. Follow this guide to [use custom domain for your website on Netlify](https://docs.netlify.com/domains-https/custom-domains/#assign-a-domain-to-a-production-site).

> [Netlify](https://netlify.com) automatically builds your website when it detects updates to your linked repository. Its all automatic, you don't have to worry about it.

