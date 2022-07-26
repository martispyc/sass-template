## My current SASS/SCSS template

Usage:

```
git clone https://github.com/martispyc/sass-template.git

mv sass-template/sass .
rm -rf sass-template
```

And add the following script to 'package.json':

``"compile:sass": "node-sass sass/main.scss css/style.css -w"``
