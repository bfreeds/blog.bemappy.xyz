# Headless GhostCMS  

This repository is the code for deploying and managing a self-hosted headless GhostCMS for publishing blog posts.  

GhostCMS is made "headless," meaning it's just leveraging the admin interface and rest api without the default frontend.  This is done by configuring the cms in "private" mode.  

## Deployment  
- Host : **Digital Ocean**
- Method: **Docker**
- Provisioning:  **Terraform**

#### Process  
1.  Provision Digital Ocean Docker Droplet  
1.  Configure GhostCMS w/Docker Compose  
1.  Deploy Docker-Compose to Droplet  
1.  Setup DNS with `blog.bemappy.xyz`

## Reason for Ghost  
- Great Admin UI / Publishing Experience
- Mobile app for travel blogging
- API / data model for blogs is based on an open standard, which should make the content produced flexible and transportable in the future, if desired
- Rich media, customizable and extendable (future thinking about creating custom content types for Glitch apps or Observable notebooks)
- Ghost is a sustainable open source project
- Great community support & organizational values  
- Not Medium, self publishing to maintain ownership and control over content
- Host:  Digital Ocean 

## Resources  
- [GhostCMS Config File Doc](https://docs.ghost.org/concepts/config/)
- [GhostCMS Docker Image](https://github.com/docker-library/ghost)
- [*Disable frontend when using GhostCMS*](https://forum.ghost.org/t/disable-frontend-when-using-ghost-as-a-headless-cms/5915)
- [*Use Ghost as a Static Page Headless CMS with Gatsby and Netlify*](https://hooshmand.net/how-to-headless-cms-static-page-gatsby-netlify-ghost/)