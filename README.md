Tailwind CSS Autocomplete for Sublime Text 3
=============

Tailwind CSS Autocomplete plugin for [Tailwind CSS](https://tailwindcss.com/) (v2.1.1).

Note: This plugin only autocompletes based on the default Tailwind CSS class names. It does not extend autocomplete based on your customized `tailwind.config.js`.

![screenshot](screenshot.png)

You may want to remove the `:` character in your `word_separators` setting in your user **Preference.sublime-settings** file. This will prevent autocomplete from breaking on breakpoint and pseudo classes used within Tailwind.

    // Characters that are considered to separate words
    "word_separators": "./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}`~?",


### Credits
Forked from [Tachyons Autocomplete for Sublime Text 3](https://github.com/webchun/tachyons-sublime-autocomplete) by [@webchun](https://github.com/webchun)

Created based on [UIKit Plugin](https://github.com/uikit/uikit-sublime)
