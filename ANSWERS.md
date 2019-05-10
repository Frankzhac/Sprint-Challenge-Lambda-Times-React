1. What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

prop-types are used to declare or define what props your component needs and what type(s) they should be.

It is important to type check because it gives you more context around runtime errors with types and it improves code editor tooling. You can see errors immediately inline when you use a variable or method incorrectly. You also get autocomplete for object fields, methods etc. (including for libraries you import from npm/yarn if they have types available).


2. Describe a life-cycle event in React?

It is a simple set of phases in a component’s life: Birth/Mounting, Growth/Updating and Death/Unmounting


3. Explain the details of a Higher Order Component?

HOC's have various uses depending on how a React application is structured. The key idea here is that using HOC's allows for reusing component logic. This means that developers will repeat themselves less often ('DRY'-er code).

Bundling components together in a HOC also allows for sharing of information and combined functionalities. To name a few uses, developers can use them for added logic in conditional rendering and making alterations to the usual behaviors of components. There is also the bonus of adding clarity (and arguably, traceability) to code by virtue of the more defined component structure.


4. What are three different ways to style components in React? Explain some of the benefits of each.

Vanilla CSS
-This simply involves using CSS stylesheets that will be imported into Javascript files.
-The simplest method, which does not rely on any additional syntax or functionalities. 'Plug-and-play' upon importing.
-Preprocessors can optionally be utilized for more efficiency.

ReactStrap
-A convenient library based off of Bootstrap that is optimized to work with React.
-Easy for developers to hone existing knowledge of Bootstrap in the React environment.
-There are predefined classes for quick templates (that look good nonetheless).

Styled Components
-A library for adding syntactically-optimized styling code into Javascript.
-Eliminates the need for any CSS files for the application.
-Conveniently placed inside the same Javascript files where React components are used.
-Easier to apply logic into styling, especially with how prop values can be combined with conditional logic
