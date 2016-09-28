# Week 4b (9/28) Notes - Project Plan Discussions & Modules
## Topics Covered: See: week5a
* Partials [view] (in-class exercise)
* Middleware Review
* Express Router
* Modules - In-class code
* Style Guides
* SASS


## Modules
<b>What should our website look like?</b>
*Modules:* Components, or 'pieces' that can be moved around
See: Atomic Web Design by Brad Frost (available on Slides) for a rundown
* Atoms -> Molecules -> Organisms -> Templates -> Pages (data included)

See Components examples in (Slides)[#link to add later]
* Bootstrap
* edX
* LonelyPlanet

Handlebars allows us to create views and layouts. These are components of a module
**Partials**: Reusable HTML snippets that use the same HTML across multiple views
'''html
{{< my-partial}}
'''
Live in the *partials* folder of your directory

'''javascript
res.render('view', data)
'''

**Modular CSS**: CSS->SCSS
* install 'sass'