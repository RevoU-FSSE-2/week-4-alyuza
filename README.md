<!-- [![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/isPhTOcA) -->

# Week-4 RevoU Assignment 👨‍💻

## How to Deploy GitHub Project to Netlify and connect it to Domain with Cloudflare

This project will explain how to deploy GitHub to Netlify and connect it to `.site` that have been purchased at NiagaHoster using Cloudflare. In this project I will explain several parts :
1. How to register an account on Netlify and Deploy GitHub project on Netlify
2. Connecting project to a `.site` on NiagaHoster using CloudFlare

### Website
This is an E-Commerce website focused on selling Taekwondo martial arts equipment.

### Deployment
You can access the production version of the website by following this [https://alyuza.site/](https://alyuza.site/)
### How to register an account on Netlify and Simple Deploy
Step 1 : Go to [Netlify Website](https://www.netlify.com/) and click Sign Up button
![Netlify website](readme-img/net/net1.jpg)

Step 2 : Sign Up using GitHub
![Netlify Registration](readme-img/net/net4.png)

Step 3 : Click on 'add new site' and choose 'Import an existing project'
![Netlify Home](readme-img/net/net5.png)

Step 4 : Click GitHub
![Git Repository](readme-img/net/net6.png)

Step 5 : Pick a repository from GitHub, here I pick week 4
![Import Repository](readme-img/net/net7.png)

Step 6 : Make it default and click Deploy site
![Deploy Site](readme-img/net/net8.png)

Step 7 : Click on Site configuration
![Site Configuration](readme-img/net/net9.png)

Step 8 : Change site name
![Change Site](readme-img/net/net10.png)

Step 9 : Input your site name and click save
![Input Site Name](readme-img/net/net11.png)

Step 10 : Finally your project has been deployed on Netlify
![The Result](readme-img/net/net12.png)

### Connecting Project on NiagaHoster using CloudFlare
Step 1 : You have to register on Niagahoster and activate your email

Step 2: Sign Up Cloudflare
![CloudFlare Home](readme-img/flare/flare1.png)

Step 2: Go to CloudFlare Website, Websites > Add Site
![Add site](readme-img/flare/flare2.png)

Step 3: Copy site name from NiagaHoster, paste it here and click Add site button
![Input site name](readme-img/flare/flare3.png)

Step 4: Scroll down > choose Free > Click Continue
![Free site](readme-img/flare/flare4.png)

Step 5: Click DNS, Add Record button
![Add DNS](readme-img/flare/flare5.png)

Step 6: Copy 2 name servers below, and paste it to NiagaHoster
![Copy site](readme-img/flare/flare6.png)

Step 7: Click 'Ubah Server'
![NiagaHoster Home](readme-img/flare/flare7.png)

Step 8: Paste name server from CloudFlare here and click 'Simpan'
![Change Name Server](readme-img/flare/flare8.png)

Step 9: Name server successfully changed
![Success](readme-img/flare/flare9.png)

Step 10: Back to CloudFlare and Click Done, check name server
![Done](readme-img/flare/flare10.png)

Step 11: Click Get started and next until finish
![Quick Guide](readme-img/flare/flare11.png)

Step 12: Go to Netlify and copy Netlify deployment link
![Copy Netlify Site](readme-img/flare/flare13.png)

Step 13: Go to CloudFlare > DNS > Records
![CloudFlare Menu](readme-img/flare/flare12.png)

Step 14: Type : CNAME || Name : @ || Target : (add your netlify deployment link here)
![DNS Settings](readme-img/flare/flare14.png)

Step 15: Go to Netlify > Site Configuration > Domain Management > Domains. Click Add a domain
![Netlify Domain](readme-img/flare/flare16.png)

Step 16: Copy your site on NiagaHoster and paste here, Click Verify
![Input domain](readme-img/flare/flare17.png)

Step 17: Your project is successfully connected to `.site` on NiagaHoster
![Site Active](readme-img/flare/flare19.png)

Step 18: You'll get email from CloudFlare
![Email From CloudFlare](readme-img/flare/flare20.png)

The Result
![Result](readme-img/flare/flare21.png)



