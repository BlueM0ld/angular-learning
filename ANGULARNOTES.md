Run your server/application 

ng serve --open

the --open flag runs it on local host port 4200


"{{}}" curly braces are interpolation binding syntax within the html template file 

src/styles.css 

This file in the src folder creates application wide style themes

You always import the Component symbol from the Angular core library and annotate the component class with @Component.

It has 3 metadata properties
- selector : matches the name of the HTML element that identifies this component within a parent component's template.
- templateUrl : the location of the component template file
- styleUrls : the location of the component private CSS styles

@Component is a decorator function !

*What is the decorator pattern*

It is a wrapper that when applied to the object is it wrapping changes its behaviour!


Within the ./heroes/heroes.components.ts file there is the ngOnInit() lifecycle hook. You can apply initalization logic there.

You can export and the import the module similar to this 
export class AppModule { }

The word *uppercase* in the *interpolation binding*, right after the pipe operator ( | ), activates the built-in UppercasePipe.

*Pipes* are a good way to format strings, currency amounts, dates and other display data. Angular ships with several built-in pipes and you can create your own.