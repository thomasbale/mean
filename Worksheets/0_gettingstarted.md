# Getting started

This worksheet is focused on making sure your development environment is setup exactly how you need. Time spent checking the basis will make sure you aren't stressing 

We develop Angular applications using the AngularCLI. AngularCLI is basically a really useful tool for quickly prototyping with bolierplate code; it saves a great deal of manual work (but you could use Angular directly if you want!!). We are also going to use a package called LoopBack to scaffold our API and speed up development here. We won't be using Loopback at first - but we need to make sure it's installed.

## Basics
npm (originally short for Node Package Manager) helps us manage JS packages and dependancies. We need it to install Angular. We will install npm via the master NodeJS package. The key steps in this session are to: 

- Ensure you have a current install of npm
- Ensure you have a current install of NodeJS
- Ensure you have a current install of Angular CLI
- Setup the new site as an upstream Git repo




'''
node --version
npm --version
#if you don't have either installed: 
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt install nodejs
'''
Then we in
'''
npm install -g @angular/cli
'''


## Boilerplate site
'''
ng new "mean_test"
cd
ng serve
'''

## Launch a site!
http://localhost:4200/


### Going further
