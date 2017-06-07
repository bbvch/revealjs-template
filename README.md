# reveal.js template project
Allows to create reveal.js presentations similar to the PowerPoint template

## Files 
- index.html
- slide-detail.md
- slide-overview.md
- css/theme/source/bbv.sass
- css/theme/assets/Logo_bbv_neu.PNG

The index html contains 4 sample slides:
- slide one is a demo of a section with a thick red bar in pure html
- slide two is a demo of a detail section in pure html
- slide three is a demo of a detail section with external markdown
- slide four is a demo of a section with thick red bar and external markdown

# Usage
In order to use the template, you have to 
- clone and install reveal.js following https://github.com/hakimel/reveal.js#installation
- clone the revealjs-template into a separate directory
- copy the files from the revealjs-template directory into the reveal.js directory with
```
git clone https://github.com/hakimel/reveal.js.git
cd reveal.js
npm install
cd ..
git cloe https://github.com/bbvch/revealjs-template.git
cp --parents --recursive revealjs-template/* reveal.js/
```
