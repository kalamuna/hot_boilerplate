HotBoilerplate!
==============

HotBoilerplate! provides some core files to help construct HotApps! At this point
it does not prescribe any set structure, but has some helpful files to configure
the development experience, such as...

- bower.json/Gemfile/package.json to install any necessary third-party dependencies.
- coffeelint.json/.jshintrc for intelligent JS linting
- .gitignore/.gitattributes to ease version control
- .editorconfig to standardize editor configurations of those working on HotApps!

### How to Cook with the HotBoilerplate!

Most HotApps! will be created using Drupal Features. For these, the most efficient workflow is to...

1. Clone a copy of hot_boilerplate.
2. Create your feature with the Drupal config necessary for your hot app. This will be the template for your new HotApp!
3. Copy over all the "dot" files: cp -R .* [your-new-hot-app]
4. Copy over necessary dependency files and edit them to load in your required dependencies.

In the future you can always come back to HotBoilerplate! to pick up any extra files you need
for your HotApp!
