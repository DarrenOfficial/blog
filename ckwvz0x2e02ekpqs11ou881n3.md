## How I setup my Website for free with Cloudflare pages

# Hello 👋, 
Today we will learn how to set up your website on the cloud ☁️ for free!
First, I will introduce to you [Cloudflare](https://www.cloudflare.com/en-ca/) and how we can use [Cloudflare](https://www.cloudflare.com/en-ca/) to deploy a website for free.

## What is [Cloudflare](https://www.cloudflare.com/en-ca/)?
According to [Cloudflare](https://www.cloudflare.com/en-ca/):
> [Cloudflare](https://www.cloudflare.com/en-ca/) is one of the most extensive networks operating on the Internet. People use [Cloudflare](https://www.cloudflare.com/en-ca/) services to increase the security and performance of their websites and services.

tl;dr they are a [CDN provider](https://www.cloudflare.com/en-ca/cdn/), [DDoS Migration provider](https://www.cloudflare.com/en-ca/ddos/), and many more. Anything you need to make your website more secure and faster.


### [Cloudflare](https://www.cloudflare.com/en-ca/) Pages 📄
[Cloudflare](https://www.cloudflare.com/en-ca/) recently introduced a service called [Cloudflare Pages](https://pages.dev/), which is what this guide will guide you on how to use it to its fullest potential!

Now [Cloudflare pages](https://pages.dev/) are not a new concept. For example, [Netlify](https://www.netlify.com/), [Verel](https://vercel.com/), [Github Pages](https://pages.github.com/) & [Gitlab Pages](https://docs.gitlab.com/ee/user/project/pages/).
Why did I pick [Cloudflare](https://pages.dev/) instead of all those things I mentioned above?

Well, the answer is simple. They have the advantages that other providers don't have; simply because they have over [200+ data centers worldwide](https://www.cloudflare.com/en-ca/network/), no matter where your potential viewers are, they will be guaranteed to load your website fast 💨!

**plus, they have a free tier, which is fantastic 👏**

## Setting up [Cloudflare pages](https://pages.dev/)!
Now, this is the fun part. here's how you set up [Cloudflare pages](https://pages.dev/) and make your website from 🐌 to 🔥

### Setup [Cloudflare](https://www.cloudflare.com/en-ca/) account 🔑

First, you need to make a [Cloudflare](https://www.cloudflare.com/en-ca/) account, head over to [https://pages.cloudflare.com/](https://pages.cloudflare.com/) and click on [Sign Up](https://dash.cloudflare.com/sign-up/pages)

Once you sign up, you can add your domain to [Cloudflare](https://www.cloudflare.com/en-ca/) via the add site button.

<details>
<summary>Add site button</summary>
<br>
![addsite](https://cdn.hashnode.com/res/hashnode/image/upload/v1638866792637/CtGcuh6M5.jpeg)
</details>

Next, add your site to [Cloudflare](https://www.cloudflare.com/en-ca/); once you do that, click next.

<details>
<summary>domain setup</summary>
<br>
![next](https://cdn.hashnode.com/res/hashnode/image/upload/v1638866869736/rRhp80Rj7.jpeg)
</details>

Select the free tier; then, it will scan your current DNS settings and migrate them to Cloudflare; after that, click continue.


<details>
<summary>DNS migration</summary>
<br>
![dnsscandone](https://cdn.hashnode.com/res/hashnode/image/upload/v1638866991762/ZJYduS8dL.jpeg)
</details>


After that, It should prompt you to move your current name server to Cloudflare free name server. once you've done that, you should be greeted with this screen.


<details>
<summary>domain transfer</summary>
<br>
![domain transfer done](https://cdn.hashnode.com/res/hashnode/image/upload/v1638867111605/ADVADI6v6.jpeg)
</details>


### Pages setup
Almost there!

Next, all you need to do is click on the pages button @ your [Cloudflare dashboard](https://dash.cloudflare.com)

<details>
<summary>Pages Create</summary>
<br>
![pagessswowiw](https://cdn.hashnode.com/res/hashnode/image/upload/v1638867367086/dMS-c_u8r.jpeg)
</details>

Then create a new project.

<details>
<summary>Creating Pages Project</summary>
<br>
![new proj](https://cdn.hashnode.com/res/hashnode/image/upload/v1638867507609/8Ne0rSOqy.jpeg)
</details>

Once you've clicked that button, it should prompt you to connect to your [GitHub](https://github.com/) account; you want to do that, then authorize it to either your main [GitHub](https://github.com/) account or your organization [GitHub](https://github.com/) account.
After you've linked your [GitHub](https://github.com/), you can click the repository you want to host, then click begin setup! 

#### Extra settings

Next, you can set your project name, the branch you want to use, and your build settings.

If you want to host a static HTML file, you can set the framework preset to none, then put the build command as `exit 0.`


<details>
<summary>Page build settings</summary>
<br>
![settings](https://cdn.hashnode.com/res/hashnode/image/upload/v1638867726277/BmA46uwC1.jpeg)
</details>


And that's it! Click deploy, and your site should be ready in no time!
*it may take 2 - 5 min for it to build your site depending on the site*

**Thank you for reading, have a great day!**

- Website: [darrennathanael.com](https://darrennathanael.com)
- Socials: [link.darrennathanael.com](https://link.darrennathanael.com)