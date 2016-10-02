# Openshift Quickstart
One click quickstart to make your website/app online in openshift cloud server.

OpenShift is Red Hat's Platform-as-a-Service (PaaS) that allows developers to quickly develop, host, and scale applications in a cloud environment. You can host your own website on OpenShift and even set it a custom domain if you want. This quick start will help you to deploy your HTML or PHP website to open shift easily with the cick of a button.

##### Contents
* PHP 5.4
* MySQL Database
* PHPMyadmin
* eXtplorer file manager

### How to use
1. Create an account at http://openshift.redhat.com/
2. Log into the account 
3. Click on the picture below<br/>
<a href="https://openshift.redhat.com/app/console/application_types/custom?cartridges[]=php-5.4&cartridges[]=mysql-5.5&cartridges[]=php-5.4&cartridges[]=phpmyadmin&initial_git_url=https://github.com/gautamkrishnar/openshift-quickstart&name=website" target="_blank">
![Deploy now](http://launch-shifter.rhcloud.com/launch/light/Click to install.svg)</a>

5. Scroll to the bottom and click on the button below. You can also chose to enable scaling: ![create](https://cloud.githubusercontent.com/assets/8397274/19016968/81500152-8847-11e6-9235-cab5967d37cc.png)
6. Wait for a minute and you will be redirected to the screen below:![continue](https://cloud.githubusercontent.com/assets/8397274/19018820/064c747c-888d-11e6-818a-d565e6f30e68.png) Click on the **continue to the application overview page** link
7. You can see the following page:![page](https://cloud.githubusercontent.com/assets/8397274/19018884/0af920a4-888f-11e6-81a5-ce19ded2fffe.png)
You can now visit your website by clicking on that link. Follow the instructions given on the website to get started.![quickstart](https://cloud.githubusercontent.com/assets/8397274/19018890/6d80d226-888f-11e6-95c9-52f6ad951790.png)
8. You can set a custom comain to your website by clicking on the **change** link in the application overview page. See more info [here](https://developers.openshift.com/managing-your-applications/domains-ssl.html).

## How to use
After deploying, visit your website to get started.

* You can login to file manager at http://your_app_name-yourdomain.rhcloud.com/fileman/

     username:admin
     password:admin

Don't forget to change your password after logging in  for the first time.

You can use PHPMyadmin at http://your_app_name-yourdomain.rhcloud.com/phpmyadmin/. See the default index page for database credentials.

If you are getting 404 while visiting your app, please wait for some minutes and retry. If you are experiencing any other problems, please don't forget to open a [new issue](https://github.com/gautamkrishnar/openshift-quickstart/issues/new) in this repository.

### Why Openshift Quickstart
Openshift is a great platform to host your website and applications. It is least used by non tech savvy users. To deploy an application in OpenShift, normally users have to deal with a command line interface. New users usually find it difficult  in getting familiarized with the command line interface of OpenShift. This quickstart is for them, for people who want to deploy their application/website to Redhat's cloud without typing a single command.
### Spread the word
Liked using opensift quickstart! Don't forget to spread the word by starring this repo. :star:
