# TextMate Bundle for XML Schema Development (XSD)

## To install with Git:

```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git@github.com:mmorga/XSD.tmbundle.git "XSD.tmbundle"
osascript -e 'tell app "TextMate" to reload bundles'
```

## Prereqs

* Ruby 1.8.7 or greater is required.
* [xmllint](http://xmlsoft.org/xmllint.html) is used for validation against the XML Schema Schema.

## What does it do?

* Provides a number of snippets for easier completion.
* Provides validation via xmllint ctrl-shift-V
* Provides element help links to the w3.org XML Schema 1.1 documentation ctrl-H

Mark Morga
markmorga@gmail.com
