# Jelastic DokuWiki Add-on

This repository provides [DokuWiki](http://www.dokuwiki.org/) add-on for Jelastic Platform.

**DokuWiki** is a simple to use and highly versatile Open Source wiki software that doesn't require a database.

**Type of nodes this add-on can be applied to**:
- apache2
- mysql5

### What it can be used for?
DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax.
The ease of maintenance, backup and integration makes it an administrator's favorite.



### What Jelastic add-on is?

Jelastic add-on represents a package with a kind of a patch, that can be applied to an environment in order to improve and complement its functionality. The full list of the available at a platform add-ons can be seen at the corresponding same-named section of [Jelastic Marketplace](https://docs.jelastic.com/marketplace#add-ons].

### How to install an add-on?
###### For Developers

In case you can’t find the desired package within the list of available ones, copy and save the content of add-on’s manifest as a *.json* file and [import](https://docs.jelastic.com/environment-export-import#import) it to the dashboard. Herewith, you can apply any necessary adjustments to an add-on through this file (if such are required) and install its customized version in the similar way.

###### For Cluster Admins

In order to add the desired add-on to your platform and make it available for users, perform the following:
- copy the content of its manifest 
- switch to the [Marketplace](http://ops-docs.jelastic.com/marketplace-46) section of your JCA panel and choose **Add > Add-on** menu option
- paste the copied strings into the appeared frame and **Save** the template
- choose your newly added add-on within the list and click on **Publish** above

Also, you are able to adjust the given add-on template according to your needs and provide its customized version.


