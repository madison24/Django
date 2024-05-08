## Exercise 2.4: Django Views and Templates

### Learning Goals

- Summarize the process of creating views, templates, and URLs
- Explain how the “V” and “T” parts of MVT architecture work
- Create a frontend page for your web application

### Reflection Questions

1. Do some research on Django views. In your own words, use an example to explain how Django views work.

   - Django views are Python functions that take http requests and return and http response (html documents). If you were building a social media project a module you could create would be a profile. Within that module you'd add a view so that when the user is on the site "yourapp.com/profile", they would see their own profile page.

2. Imagine you’re working on a Django web development project, and you anticipate that you’ll have to reuse lots of code in various parts of the project. In this scenario, will you use Django function-based views or class-based views, and why?

   - I would use class-based views because once they are created they are easy to reuse and extend while function-based views are better for customization.

3. Read Django’s documentation on the Django template language and make some notes on its basics.

   - Django template system is designed to feel comfortable if your used to working with HTML.
   - The template sytem provides tags which function similarly to some programming constructs ie. an `if` for boolean, `for` for looping and so on.
   - Tags control the logic of the template.
   - A template contains variables {{ variable }} which get replaced with values when its evaluated.
