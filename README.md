# PyHAT: Awesome Python htmx [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

**THIS IS A WIP, BUT WE ARE VERY OPEN TO CONTRIBUTIONS**

## Table of Contents

- [About](#about)
- [Usage](#usage)

## What is PyHAT 🧐 <a name = "about"></a>

PyHAT is more than just a snake with a hat 🐍🤠. It stands for Python htmx ASGI Tailwind&mdash;a web stack that allows you to build powerful web applications using nothing more than... drumroll... Python, htmx, and Tailwind.

### Why Should I Care
Does any of this sound like you:
- I want to stick with just Python and HTML/CSS, [but not sacrifice front-end functionality](https://htmx.org/essays/when-to-use-hypermedia/).
- I don't want to have to use a [complicated front end framework](https://htmx.org/essays/a-response-to-rich-harris/).
- I don't enjoy [agonizaing over CSS class names](https://tailwindcss.com/docs/utility-first#:~:text=You%20aren%E2%80%99t%20wasting%20energy%20inventing%20class%20names.).
- I want to maintain a consistent design without any bikeshedding.

If the above sounds like you then you are in the right place!

### But Will it Work in Production
Yes! [Here is a very good example](https://htmx.org/essays/a-real-world-react-to-htmx-port/) of a project a company underwent using HTMX with Django in production. Some highlights from the article:
> - The effort took about 2 months (with a 21K LOC code base, mostly JavaScript)
> - No reduction in the application’s user experience (UX)
> - They reduced the code base size by 67% (21,500 LOC to 7200 LOC)
> - They increased python code by 140% (500 LOC to 1200 LOC), a good thing if you prefer python to JS
> - They reduced their total JS dependencies by 96% (255 to 9)
> - They reduced their web build time by 88% (40 seconds to 5)
> - First load time-to-interactive was reduced by 50-60% (from 2 to 6 seconds to 1 to 2 seconds)
> - Much larger data sets were possible when using htmx, because react simply couldn’t handle the data
> - Web application memory usage was reduced by 46% (75MB to 45MB)


## Usage ✏️ <a name = "usage"></a>

Htmx can be used with any backend framework. Currently, there is a lot of experimentation in the Python space, which is exciting! But that also means that there are a lot of disparate approaches.

The best advice here is to get familiar with some of the core packages (htmx, tailwind). Then feel free to check out any of the packages below.


## Official Resources

-   [htmx](https://htmx.org/) - htmx gives you access to AJAX, CSS Transitions, WebSockets and Server Sent Events directly in HTML, using attributes, so you can build modern user interfaces with the simplicity and power of hypertext. Htmx has no outside dependencies outside of a vanilla JavaScript file referenced in your HTML `<head>` section.
-   [tailwindcss](https://tailwindcss.com/docs/installation) - Rapidly build modern websites without ever leaving your HTML. Tailwind provides a standalone CLI tool that _does not_ require npm or any other JavaScript dependencies. (You can install it through `pip` using the [pytailwindcss](https://pypi.org/project/pytailwindcss/) library)

## Introductory Resources

-   [simple site](https://github.com/tataraba/simplesite) - Provides thorough documentation on building a site from the ground up with FastAPI, Jinja, htmx, and Tailwind.
-   [Music Binder](https://github.com/tataraba/musicbinder) - More advanced version of above repo showcasing features like active search and infinite scroll. You can open with a Codespace in GitHub without having to install anything locally.
-   [Rapid Prototyping with Flask, htmx, and Tailwind CSS](https://testdriven.io/blog/flask-htmx-tailwind/) - In this tutorial, you'll learn how to set up Flask with htmx and Tailwind CSS. (testdriven.io)


## Introductory Courses

-   [HTMX + Flask: Modern Python Web Apps, Hold the JavaScript Course](https://training.talkpython.fm/courses/htmx-flask-modern-python-web-apps-hold-the-javascript) - htmx is one of the hottest properties 🔥 in web development today, and for good reason. This framework, along with the libraries and techniques introduced in this course, will have you writing the best Python web apps you've ever written: clean, fast, and interactive without all that frontend overhead. (TalkPython Training)


## Third Party Packages
### Templates
- **[fuzzy-couscous](https://tobi-de.github.io/fuzzy-couscous/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
A cli tool based on django's `startproject --template` to bootstrap your django projects with a PyHAT stack.

### Helper Libraries
<!--
 FASTAPI   <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a>
FLASK   <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> 
JINJA   <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a> 
DJANGO   <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a>
TAILWIND   <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a>
-->

- **[Flask-HTMX](https://github.com/edmondchuc/flask-htmx)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a><br/>
A Flask extension to work with HTMX.

### Frameworks
- **[Forge Packages](https://www.forgepackages.com/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Forge is a set of Django packages that work well together, but can also be used independently. These include some htmx/tailwind specific packages highlighted below. Note that these are opinionated approaches, but they provide a robust set of features to enhance your developer experience.
    -   **[forge-htmx](https://www.forgepackages.com/docs/forge-htmx/)** -  The forge-htmx Django package adds a couple of unique features for working with HTMX. One is template fragments and the other is view actions.
    -   **[forge-tailwind](https://www.forgepackages.com/docs/forge-tailwind/)** <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a> - Use Tailwind CSS with Django without requiring JavaScript or npm.

### Components
- **[Django Dashboards](https://github.com/wildfish/django-dashboards)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Tools to help you build data dashboards in Django.

### Tools
- **[django-tailwind-cli](https://oliverandrich.github.io/django-tailwind-cli/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
An integration of Tailwind CSS for Django that is based on the precompiled versions of the Tailwind CSS CLI (No JS required!)

## Further Reading
- [Awesome Htmx](https://github.com/rajasegar/awesome-htmx)
