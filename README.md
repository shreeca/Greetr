# Greetr

Greetr is a open source framework which helps users to create greetings on the fly using JS.

Languages supported now:
  - English
  - Spanish


### Tech

Greetr uses these open source projects to work properly:

* [jQuery](https://github.com/jquery/jquery) - jQuery is a JavaScript library designed to simplify HTML DOM tree traversal and manipulation, as well as event handling, CSS animation, and Ajax.

And of course Greetr itself is open source with a [public repository][dill] -> on GitHub.

### Installation
Download compressed folder from GitHub or clone directly.

### How to use?
1. Include JQuery
2. Include Greetr.js
 
Then Greetr.js can be used like this;

```html
<h1 id='greeting'></h1>
```

```javascript
// create a new 'Greetr' object
    var greetingObj = G$('John', 'Doe');
    
/** 
fire off an HTML greeting, passing the '#greeting' as the selector and the chosen language, and log the welcome as well

Here "en" is for English language
and #greeting is the selector(here h1 tage with id "greeting")
We are also console loging the greeting using log() method.
**/

    greetingObj.setLang("en").HTMLGreeting('#greeting', true).log();
    
```

### Development
Want to contribute? Great!

### Todos
 - Add more languages
 - Add more methods to use

License
----

MIT


**Free Software, Hell Yeah!**