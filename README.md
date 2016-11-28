```
module.exports = {
   config: {
     // default font size in pixels for all tabs
     fontSize: 11,

     // font family with optional fallbacks
     fontFamily: '"Fira Code", "Inconsolata for Powerline","Roboto Mono", "DejaVu Sans Mono", "Lucida Console", "monospace"',
 
     // Window Size
     "windowSize": [1200,800],
 
     // terminal cursor background color (hex)
     cursorColor: '#ffcc00',
 
     // color of the text
     foregroundColor: '#fff',
 
     // terminal background color
     backgroundColor: 'rgba(0,0,0,0.5)',
 
     // border color (window, tabs)
     borderColor: '',
 
     // custom css to embed in the main window
     css: '',
 
     // custom padding (css format, i.e.: `top right bottom left`)
     termCSS: '',
 
     // custom padding
     padding: '14px 18px',

     // some color overrides. see http://bit.ly/29k1iU2 for
     // the full list
     colors: [
      
     ]
   },
 
   // a list of plugins to fetch and install from npm
   // format: [@org/]project[#version]
   // examples:
   //   `hypersolar`
   //   `@company/project`
   //   `project#1.0.1`
   plugins: ["hyperterm-firewatch", "hyperterm-themed-scrollbar", "hyperterm-blink", "hyperterm-cursor"],
       // hyperterm-material
   // in development, you can create a directory under
   // `~/.hyperterm_plugins/local/` and include it here
   // to load it and avoid it being `npm install`ed
   localPlugins: []
 };
```