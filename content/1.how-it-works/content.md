How it Works        {#intro}
============
Stacey stores all of its content using flat text files & folders rather than a traditional database. So installation is as simple as copying the application files onto your server. No install file, no database setup and it will run on any standard php server.

Content             {#content-management}
-------
A new project or page is added by creating a new folder, placing your assets inside and making a .txt file. ![Screenshot of /content folder](/images/folders-view.png)

The content file follows a simple format, where each chunk of content specific to the page or project is written out in plain text or html. ![Screenshot of an example content file](/images/content-view.png)

Templates           {#template-management}
---------
![Screenshot of /templates folder](/images/templates-list.png)

The templating system uses vanilla html with a simple variable system. No php knowledge is required to build a site.  
Some knowledge of html & css will be enough to build a completely custom website. Otherwise, the default templates should be enough to get started with.
![Screenshot of an example template](/images/template-view.png)

Partials are used to manage all of your sets of navigation, pages or assets. If you want to change the way the navigation is built, you don’t need to mess around in some random php file, you just find (or create) the appropriate partial.
![Screenshot of an example partial](/images/partial-view.png)

RSS/Atom            {#rss-atom-support}
--------
Stacey supports RSS/Atom straight out of the box.
![Screenshot showing safari recognising an RSS feed](/images/rss-view.png)

The [stacey installation](/installation/) process is just as easy.