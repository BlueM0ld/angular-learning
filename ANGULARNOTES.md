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


# Display a selection list

When you don't have data to display the list, you can mock the data until you can get data from a remote server.


Create a file called mock-heroes.ts in the src/app/ folder. Define a HEROES constant as an array of ten heroes and export it. The file should look like this.

src/app/mock-heroes.ts

The *ngFor is Angular's repeater directive. It repeats the host element for each element in a list.
the '*' is an important part of the repeater directive?

<li> is the host element.
heroes holds the mock heroes list from the HeroesComponent class, the mock heroes list.
hero holds the current hero object for each iteration through the list.

Angular's class binding can add and remove a CSS class conditionally. Add [class.some-css-class]="some-condition" to the element you want to style.
