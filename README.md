# PyHAT: Awesome Python htmx [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

Are you interested in the intersection of Python and [Hypermedia-Driven Applications](https://htmx.org/essays/hypermedia-driven-applications/)? Head on over to the [discussions tab](https://github.com/PyHAT-stack/awesome-python-htmx/discussions), [introduce yourself](https://github.com/PyHAT-stack/awesome-python-htmx/discussions/2), and let's [get to work](https://github.com/PyHAT-stack/awesome-python-htmx/discussions/1)!


## What is PyHAT? 🧐 <a name = "about"></a>

PyHAT is more than just a snake with a hat 🐍🤠. It stands for Python htmx ASGI Tailwind&mdash;a web stack that allows you to build powerful web applications using nothing more than... drumroll... Python, htmx, and Tailwind.

Quick, <a href="#tools">take me to the tools already</a>!

### Our Goal

We want to promote hypermedia driven applications. That's it. That's the goal.

Okay, well, more specifically, we want to promote htmx within the Python ecosystem.

### Why Should I Care?

Does any of this sound like you:
- I want to stick with just Python and HTML/CSS, [but not sacrifice front-end functionality](https://htmx.org/essays/when-to-use-hypermedia/).
- I don't want to have to use a [complicated front end framework](https://htmx.org/essays/a-response-to-rich-harris/).
- I don't enjoy [agonizing over CSS class names](https://tailwindcss.com/docs/utility-first#:~:text=You%20aren%E2%80%99t%20wasting%20energy%20inventing%20class%20names.).
- I want to maintain a consistent design without any bikeshedding.

If the above sounds like you then you are in the right place!

### Maybe This Isn't For Me

One of the links above goes to [When Should You Use Hypermedia](https://htmx.org/essays/when-to-use-hypermedia/) over at htmx.org, and is a pretty great read if you want to asses if this is for you. It also expounds on the following points:

Hypermedia might not be a good fit:
- …If your UI has many, dynamic interdependencies
  - i.e., Google Maps, Google Sheets
- ...If you require offline functionality
- …If your UI state is updated extremely frequently
  - i.e., Online game
- …If your team is not on board

### But Will it Work in Production?

Yes! [Here is a very good example](https://htmx.org/essays/a-real-world-react-to-htmx-port/) of a project a company underwent using HTMX with Django in production. You can also watch the original video from DjangoCon EU 2022, titled [From React to htmx on a real-world SaaS product: we did it, and it's awesome!](https://www.youtube.com/watch?v=3GObi93tjZI)
<details>
<summary>Some highlights from the article.</summary>

> - The effort took about 2 months (with a 21K LOC code base, mostly JavaScript)
> - No reduction in the application’s user experience (UX)
> - They reduced the code base size by 67% (21,500 LOC to 7200 LOC)
> - They increased python code by 140% (500 LOC to 1200 LOC), a good thing if you prefer python to JS
> - They reduced their total JS dependencies by 96% (255 to 9)
> - They reduced their web build time by 88% (40 seconds to 5)
> - First load time-to-interactive was reduced by 50-60% (from 2 to 6 seconds to 1 to 2 seconds)
> - Much larger data sets were possible when using htmx, because react simply couldn’t handle the data
> - Web application memory usage was reduced by 46% (75MB to 45MB)

</details>

## Glossary :scroll:

- **Asynchronous Server Gateway Interface (ASGI)** - A standard that allows an application to talk to a server, allowing for multiple, asynchronous events per application. <br>
- **component** - A reusable custom element. Within JavaScript, it is a self-contained element with its own properties/methods that are reusable. In this context, the term is more broadly applied to any reusable elements (which may include hypermedia or other design elements). <br>
- **dependency** - Any application (library or package) that are required to run your application. <br>
- **fragments** - Refers to partial content of a an HTML template. See also: _template fragments_ </br>
- **hypermedia** - Medium of information including graphics, audio, video, text, and hyperlinks, typically represented on the web as HTML <br>
- **Hypermedia Driven Application (HDA)** - Uses declarative, HTML embedded syntax to achieve front-end interactivity, while interacting with the server in terms of hypermedia (HTML) instead of a non-hypermedia format (JSON). <br>
- **partials** - A loose term, sometimes referring to "partial" content that can be displayed in a template, or _partial_ content to be generated from within a template block.<br>
- **Server Side Rendering (SSR)** - Generating static HTML markup on the server before it is rendered in the browser on the front-end. <br>
- **Single Page Application (SPA)** - A web app implementation that loads a single web document, and subsequently updates content through JavaScript APIs.<br>
- **template fragments** - a relatively rare SSR template library feature that allow you to render a _fragment_ or partial bit of the content within a template, rather than the entire template.


## Usage ✏️ <a name = "usage"></a>

Htmx can be used with any backend framework. Currently, there is a lot of experimentation in the Python space, which is exciting! But that also means that there are a lot of disparate approaches.

The best advice here is to get familiar with some of the core packages (htmx, tailwind). Then feel free to check out any of the packages below.


## Official Resources 📚

-   [htmx](https://htmx.org/) - htmx gives you access to AJAX, CSS Transitions, WebSockets and Server Sent Events directly in HTML, using attributes, so you can build modern user interfaces with the simplicity and power of hypertext. Htmx has no outside dependencies outside of a vanilla JavaScript file referenced in your HTML `<head>` section.
-   [tailwindcss](https://tailwindcss.com/docs/installation) - Rapidly build modern websites without ever leaving your HTML. Tailwind provides a standalone CLI tool that _does not_ require npm or any other JavaScript dependencies. (You can install it through `pip` using the [pytailwindcss](https://pypi.org/project/pytailwindcss/) library)


## Introductory Resources 🔰
- **[How to create a Django form (using HTMX) in 90 seconds 🐎](https://www.photondesigner.com/articles/submit-async-django-form-with-htmx)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a>- A simple, short guide to start using HTMX with Django very quickly 🐎
- **[Add instant database search with Django and HTMX 🕵️](https://www.photondesigner.com/articles/database-search-django-htmx)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> - Build an instant database search using Django and HTMX in 6 steps 🕵️
- **[Add infinite scroll with Django and HTMX in 60 seconds ∞](https://www.photondesigner.com/articles/infinite-scroll-htmx-django)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> - Shows how to add infinite scroll to your Django app using HTMX in a simple guide ∞
-   **[simple site](https://github.com/tataraba/simplesite)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> - Provides thorough documentation on building a site from the ground up with FastAPI, Jinja, htmx, and Tailwind.
-   **[Rapid Prototyping with Flask, htmx, and Tailwind CSS](https://testdriven.io/blog/flask-htmx-tailwind/)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> - In this tutorial, you'll learn how to set up Flask with htmx and Tailwind CSS. (testdriven.io)
- **[Django, HTMX and Alpine.js: Modern websites, JavaScript optional
](https://www.saaspegasus.com/guides/modern-javascript-for-django-developers/htmx-alpine/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> - Building a modern front end in Django without reaching for a full-blown JavaScript framework. Choosing the right tools for the job, and bringing them into your project.


## Introductory Courses 🏫

-   **[HTMX + Flask: Modern Python Web Apps, Hold the JavaScript Course](https://training.talkpython.fm/courses/htmx-flask-modern-python-web-apps-hold-the-javascript)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> - htmx is one of the hottest properties 🔥 in web development today, and for good reason. This framework, along with the libraries and techniques introduced in this course, will have you writing the best Python web apps you've ever written: clean, fast, and interactive without all that frontend overhead. (TalkPython Training)
-   **[HTMX + Django: Modern Python Web Apps, Hold the JavaScript Course](https://training.talkpython.fm/courses/htmx-django-modern-python-web-apps-hold-the-javascript)** - Similar to the course above, except with Django. (TalkPython Training)
-   **[Bugbytes Django & HTMX](https://www.youtube.com/watch?v=Ula0c_rZ6gk&list=PL-2EBeDYMIbRByZ8GXhcnQSuv2dog4JxY)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> - A phenomenal tutorial series on using Django with htmx.
-   **[Code With Stein Django Ecommerce Website Htmx and tailwind](https://youtu.be/EoYFWkxXxXM?si=ROvMhDlOWsQ3IHzQ)** - A great tutorial on building a Django ecommerce website with htmx and tailwind.


## Design, Theory, and Patterns 🧠
- **[Django + htmx patterns](https://github.com/spookylukey/django-htmx-patterns)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a><br/>
A compilation of patterns for writing Django projects that use htmx, with complete example code.
- **[htmx Essays](https://htmx.org/essays/)**<br/>
A collection of essays by Carson Gross, the creator of htmx. Some specific essays of note for those not familiar with his teachings:
    - **[Hypermedia-Driven Applications](https://htmx.org/essays/hypermedia-driven-applications/)** - This web stack could have been called PyHDA, this essay gives a great primer on how a PyHAT application should look, architecturally.
    - **[Locality of Behaviour (LoB)](https://htmx.org/essays/locality-of-behaviour/)** - A concept you will see referred to a lot around here. "The behaviour of a unit of code should be as obvious as possible by looking only at that unit of code"
    - **[Splitting Your Data & Application APIs: Going Further](https://htmx.org/essays/splitting-your-apis/)** - A great essay (responding to a [great article](https://max.engineer/server-informed-ui)).
    > If you split your API into Data and Application APIs...you should consider changing your Application API from JSON to Hypermedia (HTML) & using a hypermedia-oriented library like htmx to reap the benefits of the hypermedia model (simplicity, reliability, flexibility, etc.)
- **[Why We Should Stop Using JavaScript According to Douglas Crockford (Inventor of JSON)](https://youtu.be/lc5Np9OqDHU)**<br/>
A short video of Douglas Crockford explaining why we should stop using JavaScript.
- **[3 IRL use cases for Python and HTMX](https://www.bitecode.dev/p/3-irl-use-cases-for-python-and-htmx)** - _From the author:_ There is nothing HTMX does that you couldn't do in another way. But HTMX pairs wonderfully with traditional server side frameworks and gives you clean, correct, results quite fast. You won't get candy crush bling level with it, but you will get something practical, which is regularly all what I need.
- **[HTML First](https://html-first.com)** - HTML First is a set of principles that aims to make building web software easier, faster, more inclusive, and more maintainable by... 1) Leveraging the default capabilities of modern web browsers, 2) Leveraging the extreme simplicity of HTML's attribute syntax, 3) Leveraging the web's ViewSource affordance.
- **[You don't need JavaScript for that](https://www.htmhell.dev/adventcalendar/2023/2/)** - It's one of the core principles of web development and it means that you should Choose the least powerful language suitable for a given purpose... On the web this means preferring HTML over CSS, and then CSS over JS.
- **[Django HTMX Components](https://dhc.iwanalabs.com/)** - Live demos and code repository of common Django + HTMX patterns. They are designed to be copy-pasted into your project and customized to your needs.


## Third Party Packages 📦 <a name = "tools"></a>

### Demos

-   **[Music Binder](https://github.com/tataraba/musicbinder)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> - More advanced version of [Simple Site repo](https://github.com/tataraba/simplesite) showcasing features like active search and infinite scroll. You can open with a Codespace in GitHub without having to install anything locally.
-   **[Bulldoggy: The Reminders App](https://github.com/AutomationPanda/bulldoggy-reminders-app)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> Bulldoggy is a small demo web app for tracking reminders. Uses htmx to handle `GET`, `POST`, `PATCH` requests in a fully-functioning to-do frontend.
-   **[Owela Club](https://github.com/adamchainz/owela-club)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> - Play the Namibian game of Owela against a terrible AI. Built using Django and htmx.

### Templates

- **[falco](https://github.com/tobi-de/falco)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
Enhance your Django developer experience: CLI and Guides for the Modern Django Developer.
- **[django-cotton](https://github.com/wrabit/django-cotton)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
Create highly re-usable and configurable components. (No Jinja2 needed)  

### Helper Libraries

<!--
 STARLETTE   <a href="https://www.starlette.io/" target="_blank"><img src="https://img.shields.io/badge/-Starlette-a9bbcc?style=flat&logo=starlette&logoColor=black" alt="Starlette"></a>
 FASTAPI   <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a>
FLASK   <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a>
JINJA   <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a>
DJANGO   <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a>
TAILWIND   <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a>
-->
- **[Jinja2 fragments](https://github.com/sponsfreixes/jinja2-fragments)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> <a href="https://litestar.dev/" target="_blank"><img src="https://img.shields.io/badge/-Litestar-a9bbcc?style=flat&logoColor=black" alt="Litestar"></a> <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a><br/>
Allows rendering individual blocks from Jinja2 templates. This library was created to enable the pattern of [template fragments](https://htmx.org/essays/template-fragments/) with Jinja2. Extremely helpful when using HTMX to enable [Locality of Behavior](https://htmx.org/essays/locality-of-behaviour/)
- **[Jinja Partials](https://github.com/mikeckennedy/jinja_partials)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a><br/>
When building real-world web apps with Flask + Jinja2, it's easy to end up with repeated HTML fragments. Just like organizing code for reuse, it would be ideal to reuse smaller sections of HTML template code. That's what this library is all about.
- **[Django Render Block](https://github.com/clokep/django-render-block)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Allows rendering individual blocks from Django templates. This library was created to enable the pattern of [template fragments](https://htmx.org/essays/template-fragments/) with Django (using Django or Jinja2 templates). Extremely helpful when using HTMX to enable [Locality of Behavior](https://htmx.org/essays/locality-of-behaviour/)
- **[Flask-HTMX](https://github.com/edmondchuc/flask-htmx)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a><br/>
A Flask extension to work with HTMX.
- **[htmx-Flask](https://github.com/sponsfreixes/htmx-flask)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> <br/>
An extension for Flask that adds support for htmx to your application. It simplifies using htmx with Flask by enhancing the global 'request' object and providing a new 'make_response' function.
- **[FastAPI-HTMX](https://github.com/maces/fastapi-htmx)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br>
An opinionated extension for FastAPI to speed up development of lightly interactive web applications.
- **[FastHX](https://github.com/volfpeter/fasthx)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br>
Flexible FastAPI utility for adding HTMX support to routes using the decorator syntax. It works with any templating engine or server-side rendering library and comes with built-in Jinja2 support.
- **[asgi-htmx](https://github.com/florimondmanca/asgi-htmx)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br>
HTMX integration for ASGI applications. Works with Starlette, FastAPI, Quart -- or any other web framework supporting ASGI that exposes the ASGI `scope`. Inspired by `django-htmx`.
- **[django-htmx](https://github.com/adamchainz/django-htmx)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Extensions for using Django with htmx.
- **[django-siteajax](https://github.com/idlesign/django-siteajax)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Streamline your server and client interaction using declarative techniques in your HTML and helpful abstractions from siteajax in your Python code. Powered by htmx.
- **[hx-requests](https://github.com/yaakovLowenstein/hx-requests)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
A package to simplify the usage of HTMX with Django. Easily add HTMX requests witout needing additional urls, and reduce clutter in views by offloading all responsibility to an hx_request.
- **[django-cbv-htmx](https://github.com/mixmash11/django-cbv-htmx)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Helps connect Django Class-Based-Views with htmx.
- **[Starlette_htmx](https://github.com/lllama/starlette-htmx)** <a href="https://www.starlette.io/" target="_blank"><img src="https://img.shields.io/badge/-Starlette-a9bbcc?style=flat&logo=starlette&logoColor=black" alt="Starlette"></a><br/>
A set of extensions for using htmx with Starlette, based on `django-htmx`.
- **[django-template-partials](https://github.com/carltongibson/django-template-partials)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Reusable named inline partials for the Django Template Language. [Has a great intro talk from DjangoCon](https://www.youtube.com/watch?v=_3oGI4RC52s)! 🎥

### Frameworks
- **[Litestar](https://litestar.dev)** <a href="https://litestar.dev/" target="_blank"><img src="https://img.shields.io/badge/-Litestar-a9bbcc?style=flat&logoColor=black" alt="Litestar"></a> <br/> Litestar is a full-on ASGI web framework (think FastAPI, Sanic, Starlette, etc...) So why is it included here? With their most recent 2.0 release, the creators have included htmx support out of the box. A special `HTMXRequest` provides easier access to HX-request header objects, and an `HTMXTemplate` object that includes attributes for common htmx actions (pushing url, re_swap, re_targets, etc...)
- **[Forge Packages](https://www.forgepackages.com/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Forge is a set of Django packages that work well together, but can also be used independently. These include some htmx/tailwind specific packages highlighted below. Note that these are opinionated approaches, but they provide a robust set of features to enhance your developer experience.
    -   **[forge-htmx](https://www.forgepackages.com/docs/forge-htmx/)** -  The forge-htmx Django package adds a couple of unique features for working with HTMX. One is template fragments and the other is view actions.
    -   **[forge-tailwind](https://www.forgepackages.com/docs/forge-tailwind/)** <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a> - Use Tailwind CSS with Django without requiring JavaScript or npm.
- **[django_htmx_ui](https://github.com/nikalexis/django_htmx_ui)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a><br/>
A django app that combines and helps leverage the full-stack django framework, the frontend htmx framework, the django-htmx library, and the jinja template engine. It provides extended django Views with htmx build-in functionality, CRUD Views for django models, extra Mixins to use with your Views to make life easier, a ready-to-use jinja environment, Middlewares for automations, and extra utils and decorators for common use cases.
- **[Ludic](https://github.com/paveldedik/ludic)** <a href="https://www.starlette.io/" target="_blank"><img src="https://img.shields.io/badge/-Starlette-a9bbcc?style=flat&logo=starlette&logoColor=black" alt="Starlette"></a><br/>
Ludic is a lightweight ASGI web framework that allows the building of dynamic HTML pages using pure Python. It is based on Starlette and offers seamless HTMX integration, a component-based approach, and intuitive f-string templating for a smooth and powerful development experience.
- **[FastHTML](https://github.com/AnswerDotAI/fasthtml)** <a href="https://fastht.ml/" target="_blank"><img src="https://img.shields.io/badge/-FastHTML-a9bbcc?style=flat&logoColor=black" alt="FastHTML"></a><br/>
FastHTML is a pure-Python web framework for fast, scalable web applications with minimal, compact code. It's designed to be:
  - Powerful and expressive enough to build the most advanced, interactive web apps you can imagine.
  - Fast and lightweight, so you can write less code and get more done.
  - Easy to learn and use, with a simple, intuitive syntax that makes it easy to build complex apps quickly.

### Components

- **[Django Dashboards](https://github.com/wildfish/django-dashboards)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Tools to help you build data dashboards in Django.
- **[django-htmx-autocomplete](https://github.com/PHACDataHub/django-htmx-autocomplete)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
A client-side autocomplete component powered by htmx featuring multiselect, search and is completely extensible.

### Tools <a name = "tools"></a>

- **[django-tailwind-cli](https://oliverandrich.github.io/django-tailwind-cli/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
An integration of Tailwind CSS for Django that is based on the precompiled versions of the Tailwind CSS CLI (No JS required!)
- **[pytailwindcss](https://github.com/timonweb/pytailwindcss)** <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
Tailwind CSS is notoriously dependent on _Node.js_. If you're a Python developer, this dependency may not be welcome in your team, your Docker container, or your inner circle. Giving up _Node.js_ means you won't be able to install plugins or additional dependencies for your Tailwind CSS setup. At the same time, that might not be a dealbreaker. You can still customize Tailwind CSS via the tailwind.config.js file.
- **[HTML Form to Dict](https://github.com/guettli/html_form_to_dict)**<br/>
Do simple end-to-end testing of form handling without a real browser (like selenium/puppeteer/playwright). Supports the "action" and "method" attributes of forms and additionaly the htmx attributes hx-get, hx-post.

## Projects Using PyHAT (or similar) 🏗️

- **[Django Requests Tracker](https://github.com/bensi94/Django-Requests-Tracker)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a><br/>
A Django development tool which collects and displays information on requests, responses, SQL queries, headers, Django settings and more. The Front-end uses HTMX.
- **[IDP-Z3](https://gitlab.com/krr/IDP-Z3)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a><br/>
A software collection implementing the Knowledge Base paradigm using the FO(.) language. Uses htmx for the front end.
- **[JupySpace](https://github.com/davidbrochart/jupyspace)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br/>
A web server and client to manage conda-forge environments from the browser and access them through JupyterLab. Uses htmx on the front-end.
- **[Harfang](https://github.com/sqwxl/harfang)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a><br/>
A social content posting and discussion site with a focus on simplicity and accessibility. Inspired by Hacker News and Reddit. Built with Django, HTMX, Alpine.js and Tailwind CSS

## Further Reading 📖

- [Awesome Htmx](https://github.com/rajasegar/awesome-htmx)
- [Maximizing Productivity: PyCharm and htmx Integration ](https://oluwatobi.dev/blog/maximizing-productivity-pycharm-and-htmx-integration/)
- [unsuck.js](https://unsuckjs.com/)
