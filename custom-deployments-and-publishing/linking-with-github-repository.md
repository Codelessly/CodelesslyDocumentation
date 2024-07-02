---
description: >-
  Learn about linking a Codelessly project with a Github repository for custom
  deployment and publishing.
cover: ../.gitbook/assets/Github + Codelessly.png
coverY: 0
---

# Linking with Github Repository

[Codelessly](https://codelessly.com/) supports Cloud UI publishing and deployments with a [Github](https://github.com/) Repository. You can link your [Github](https://github.com/) account with [Codelessly](https://codelessly.com/) and allow [Codelessly](https://codelessly.com/) to create a repository on your behalf and push starter code for website publishing.

### Benefits

* You can choose your own deployment pipeline and third-party provider for it.
* This enables you to use a custom domain for your website (if your third-party provider allows it)
* Includes pre-built website so you just have to publish and you're done.
* Also includes Flutter code if you wanna build it and then deploy on different platforms including web.

### What this repository will include?

The repository we create will contain&#x20;

1. **A fully configured Flutter project:**  You can then integrate it into your build pipeline (e.g. [CodeMagic](https://codemagic.io/), [Github Actions](https://github.com/features/actions), [Bitrise](https://bitrise.io/), etc) to build the Flutter project and publish your app/website.&#x20;
2. **A pre-built bundle of your website:** You can use it directly to publish on services that support static website publishing like [Netlify](https://netlify.com), [Vercel](https://vercel.com/), or any other third-party service you want to use.

## Get Started

Let's get you set up with [Github](https://github.com/) repository for your project.

### Connecting with [Github](https://github.com/)

1. Open [Codelessly](https://codelessly.com/) editor and head to `Settings>Github Integration`. and
2. Click on `Connect to Github` button. It will open a webpage for you to authenticate your [Github](https://github.com/) account with Codelessly.
3. Once you authenticate, it will ask you to Install our [Github](https://github.com/) app: `Codelessly App`. Please finish the installation.
4. Once finished, head back to [Codelessly](https://codelessly.com/) editor and you will see that you're authenticated now. It will show your **user name** and **avatar** instead of `Connect to Github` button.

You have successfully connected your [Github](https://github.com/) account with Codelessly. 🎉\


> Note: Codelessly Github App is required for this to work. Avoid uninstalling it changing its permissions unnecessarily.

### Linking Project with [Github](https://github.com/) Repository

After you connect [Codelessly](https://codelessly.com/) with your [Github](https://github.com/) account, you need to link your project to a specific repository on [Github](https://github.com/) so we can push code and updates and set everything up for you.

1. Open a project that you want to connect to a [Github](https://github.com/) repository.
2. Click on arrow button<img src="../.gitbook/assets/image (1) (1).png" alt="" data-size="line"> next to publish button and click on `Go to Settings`.

<figure><img src="../.gitbook/assets/image (19).png" alt="" width="375"><figcaption><p>Opening publish settings for a project.</p></figcaption></figure>

3. Go to `Website` tab. You will see `Link Project with Github` section.
4. Select owner of the repository from the dropdown. You can add organizations by clicking on `Add Another Organization` button in the selection dropdown and it will prompt you to install our [Github](https://github.com) app for the organization you want to use for this.
5. Specify a repository name for your project. [Codelessly](https://codelessly.com/) will take care of creating the repository and pushing code for you.
6. Hit `Save & Link` button to let [Codelessly](https://codelessly.com/) create the repository and link it with your project.
7. Once it succeeds, you can click on <img src="../.gitbook/assets/image (2) (1).png" alt="" data-size="line"> button next to repository name input to open your linked repository.

See deployment docs for proceeding further with your [Github](https://github.com/) repository.
