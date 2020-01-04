# Gitbook Action Template For Everyone

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/bestony/gitbook-action-template/build-book?style=for-the-badge)

This is an template for people **who need automate publish his/her book to the Internet**.

**[DEMO](https://bestony.com/gitbook-action-template/)**|**HOWTO**|**GUIDE**

> IF YOU WANT TO USE THIS TEMPLATE, BUT DON'T WANT TO LEARN HOW TO USE, YOU CAN BUY MY SERVICE WITH MY EAMIL xiqingongzi@gmail.com with $20.

## Feature

- Base on Gitbook legacy
- No Code Need (Just some config need you change)
- Speed Build (Cache npm)
- Every change will be publish to website
- Every tag will be publish by File (just like pdf, mobi, epub)
- No git needed

## How To

1. Login or Signup with your github account.
2. Click **Use this Template** at this page
3. Setup your repository name and description. 
4. Click **"Create repository from template"**
5. Create a new Personal Access Token from [Here](https://github.com/settings/tokens/new),input name ,check repo access (repo:status,repo_deployment,public_repo,repo:invite), then Click **"Generate Token"**. ![](https://postimg.aliavv.com/mbp/dvait.png)
6. Copy the new generate token.
7. Go to Your repo settings, and Click **"Secrets"**, ![](https://postimg.aliavv.com/mbp/x85bo.png)
8. Create a new Secret with name `PERSONAL_TOKEN` , value is your personal access token. ![](https://postimg.aliavv.com/mbp/digvv.png)
9. Edit the [`book.json`](book.json) 、 [README](README.md) and [SUMMARY.md](SUMMARY.md)
10. Save, and wait for reDeploy.


## How to Publish PDF, Mobi, Epub

1. Click **"Release"** in your repository home
2. Click **"Create a new Release"** or **"Draft a new Release"**
3. set a version, title, and description.
4. save, and wait for new pdf,mobi,epub.

## Changelog

### v1.0.0

1. template init
2. github pages deploy
3. github release deploy
4. npm speed up 
5. publish a demo

## LICENSE

MIT LICENSE