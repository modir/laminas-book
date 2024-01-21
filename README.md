# laminas-book

This is a "migration" of the Zend Framework 3 book by Oleg Krivtsov to the Laminas framework. The new Laminas version is now
maintained by Raffael Luthiger.

The book can be found at https://modir.github.io/laminas-book/

## Technical Information

The whole documentation is now generated with https://www.mkdocs.org/ hence the configuration file mkdocs.yml.

If you want to make bigger changes and test everything first locally then I recommend you to go through the Getting Started
guide at https://www.mkdocs.org/getting-started/ first.

## Markdown

If you want to learn more about the Markdown syntax please look at https://www.markdownguide.org/cheat-sheet/. At the top you have links to "Basic Syntax" and "Extended Syntax" which are very helpful as well.

Furthermore we have some extensions which are helpful as well. Their documentation can be found here: https://python-markdown.github.io/extensions/
See `admonition` and `footnotes` especially.

## Status

The book was in a first stage just copied and then with search/replace reworded from Zend to Laminas.
I found then several issues with the tables as Oleg used his own modfied Markdown interpreter to generate the HTML files.
I tried to resolve as many problems as I could find but there are still some. Furthermore many images are outdated
and should be updated as well. Everyone is welcome to make merge requests.

In the first step I would like to resolve as many problems as possible. In the next step I would like to modernize the code
and make everything type safe as it should be these days with PHP 8.x.

The old book had translations other languages as well but while going through it I have seen that most of them have only one or two chapters.
At the moment it is better to focus on the english version. The book can still be translated later with e.g. Google translate once
the english version is in a good stable state.

I welcome everyone to give feedback about the book. Helping hands are always welcome.