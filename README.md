MXRequestManager
================

Description
-----------
**MXRequestManager** comes from a personal need. Many of my projects are based on REST APIs, I needed a powerful and reliable REST Request Manager, which would be at the same time easy, simple to use, cross-platform and cross-language. 

Unfortunately, I didn't find any.

My knowledge are essentially Web (HTML/CSS/**JS**/PHP/SQL) and System (C/C++/**Qt**), so I decided to write my own library, which is called "**MXRequestManager**" based on my nickname (**M**a**x**13).

I'm quite advanced now, I've made a _JS_ lib and a _Qt_ lib, which are powerful (since now), quite reliable if your APIs are reliable, but it's easy to use, cross-platform but not cross-language (I was limited to the language syntax and structure).

With **MXRequestManager**, you'll be able to query your APIs with overloaded methods supporting many body structures.

For example:

- With _JS_ you'll be able to construct the Manager with the needed parameters to make a request, OR you can send only a _form id_ which will make the library parse the _form_ looking for the _method_, the _action_ and the _form_ content to build the query. You can even chain the lib calls.
- With _Qt_ you'll be able to send the parameters as an already built _QByteArray_, a _QMap<QString,QString>_, a pointer to a file or a resource, and even a _QList<QPair<QString,QString> >_...

In short, the power and the flexibility I need for my REST projects, you'll have it, for free ;)

**How to download, install or use this project will be explained in the _README_ inside the corresponding directory.**

Authors
-------
- Project idea, developer and maintainer: Adnan _"Max13"_ RIHAN.

Contributors
------------
- None yet

Linked projects
---------------
Currently, the idea of this project came from my coding brother Thomas _"Dimilian"_ RICOUARD who started with his own RequestManager and released it in OpenSource. We both have decided to linked our projects in a big master project to be able to provide some close enough to each other, libraries for our projects.

- [**DMRequestManager**](https://github.com/Dimillian/DMRESTRequest-objc) (_iOS_): Thomas _"Dimilian"_ RICOUARD.