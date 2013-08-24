Archetype-Utilities
===================

Utility functions and mixins built in Sass and Compass. Archetype-Utilities was
specifically designed to supplement
[Archetype](https://github.com/kwaledesign/Archetype) but it can just as easily
be used within any Compass project.

Formal documentation hasn't yet been tackled, but the code is fairly well
commented. Many code snippets have been borrowed from other developers. Links to original
repositories are included inline.

## Installation
Archetype-Utilities is automatically included when installing Archetype via
[Compass Extension](https://github.com/kwaledesign/Archetype-Compass).

Install the Archetype-Utilities gem (you may need to run as sudo depending on your Ruby environment).

```
$ gem install archetype-utilities
```

Edit your project's config.rb file adding:

```
$ require 'archetype'
```

Then you can include all of Archetype-Utilities within your main Sass partial:

```
$ @import 'archetype-utilities';
```

Or, you can include a specific component:

```
$ @import 'archetype-utilities/clearfix';
```

<hr>
### License
© Kwale Design - Original source code dual licensed under [MIT license](http://www.opensource.org/licenses/mit-license.php) / [GPL2 license](http://www.gnu.org/licenses/gpl-2.0.html). Open-sourced projects used within this project retain their original licenses.

