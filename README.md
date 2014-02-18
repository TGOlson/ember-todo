# Ember Todo MVC

A client-side todo list, built using [Ember](http://emberjs.com/)

Example built from the [Ember Getting Started Guide](http://emberjs.com/guides/getting-started/). The app can also been seen at [TodoMVC](http://todomvc.com/) under the [Ember app section](http://todomvc.com/architecture-examples/emberjs/).

## Notes and Takeaways

* Very opinionated - for example: [naming conventions](http://emberjs.com/guides/concepts/naming-conventions/).
* Does a lot for you out of the box. Builds default routes and controllers, links up a default ArrayController.
* Very similar to Rails MVC structure.
* Client side MVC seems less intuitive - that is, it seems to be forced into a mold rather than fitting into it.
* A lot of dependencies - jQuery, Handlebars & Ember, plus Ember-data for this project.
* Forces namespacing, which helps keep code clean.
* Todos and Todo controller is an odd nomenclature - doesn't make sense to me yet.
* Adding custom actions like ```isCompleted``` is not intuitive - seems like these belong in the model, not the controllers.
* Very powerful for creating slick UI components, like a ```clear completed``` button that only pops up once some todos are completed. This would be very hard to do in Rails.