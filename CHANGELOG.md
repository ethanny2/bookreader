# 3.0.0 Major Release
- Make BookReader easier to use, by adding `options` to the constructor, and adding new `options.data` option. The old way of overriding properties should still work, but it is deprecated.  
- Factor out extra features into plugins. See `plugins` directory. Example plugins include:  
    - plugins.chapters.js - render chapter markers  
    - plugins.search.js - add search ui, and callbacks  
    - plugins.tts.js - add tts (read aloud) ui, sound library, and callbacks  
    - plugins.url.js - automatically updates the browser url  
    - plugins.resume.js - uses cookies to remember the current page  
- Clean up code: Remove a lot of commented-out code. Remove some unused methods.  
- Change some, but not all, CSS ids to classes.  

# 2.1.0
- Add auto mode to 1up autosize (in addition to height and width)  
- Remove the old responsiveAutofit (which is not needed anymore)  

# 2.0.2
- Fix regex issue when searching  
- Make the search api endpoint configurable  

# 2.0.1
- Add package.json and CHANGELOG  
- Remove more IA-specific code  

# 2.0.0
- Major release  
- Many changes from updated Archive.org bookreader brought back to this open source project.  