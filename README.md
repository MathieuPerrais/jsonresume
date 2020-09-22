## Description
This repository contains my resume in a json format as well as a custom theme to export it in a custom way to easily integrate with my personal jekyll website.  
The custom template generates a "Jekyll _layout" `resume.html` that is used in https://github.com/MathieuPerrais/mathieuperrais.github.io (template only, no content)

Use the `$ make` command in the root folder to generate the resume html page in the `output` folder according to the custom theme in `/template`.

## Files 
My resume in the jsonresume format `resume.json`   
The modified template: `resume.template`, `package.json`, `style.css`, `index.js` are all contained in the `/template` sub folder.
A script to export locally an HTML version based on the local template: `export.js`  is added and is conveniently launched by the Makefile.

## Output
The `resume.html` layout file is generated in the `/output` folder, this file is to be copied in the jekyll `_layout` folder if changes are made.

## Theme
This uses a jsonresume theme to export a custom HTML page that easily integrates to my personal jekyll website.

## Credits
This theme is based on and forked from: https://github.com/erming/jsonresume-theme-flat  
This is a modified version for my need but most of the work was done by Mattias Erming.

## License
Available under [the MIT license](https://opensource.org/licenses/mit-license.php).
