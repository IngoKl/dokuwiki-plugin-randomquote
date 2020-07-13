# randomquote Plugin for DokuWiki

This is a very (!) simple syntax plugin for DokuWiki that allows you to show random quotes on your DokuWiki page.
The plugin is file-based and relies on a list of quotes stored in a `quotes.txt` file.

## Usage

After installing the plugin, all instances of `<randomquote>` will be replaced with a random quote. 

To add new quotes or to change the style, please edit the `quotes.txt` and `style.css` files in your `/lib/plugins/randomquote`
directory directly.

## Development

This plugin initially was not intended for public use. Therefore it is very bare-bones and, for example, does not have
the option of making settings via the admin pages. Feel free to make it better!
