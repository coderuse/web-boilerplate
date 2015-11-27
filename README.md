# Web Boilerplate
A simple boilerplate for web project with support for SASS and Grunt

To use this boilerplate the work-station need to have Ruby installed with the gem `sass`. Simply after installing [Ruby](https://www.ruby-lang.org/en/downloads/), run this command:

```bash
gem install sass
```

It also requires NodeJs to be installed, along with `grunt-cli` & `bower` in your work-station. After installing [NodeJs](https://nodejs.org/en/download/) run this command:

```bash
npm install -g grunt-cli bower
```

Navigate to the root folder of downloaded source code. Run the following commands one-by-one.

```bash
bower install
npm install
```

If all are set, run the command:

```bash
grunt
```

This will open your default browser with index.html. And as this is `livereload` enabled, whatever change you make in the html folder, the browser will reload to show the changes *automatically*.
