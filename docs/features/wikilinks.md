---
type: foam-docs
---
# Wikilinks

Wikilinks are the internal links that connect the files in your knowledge base. (Also called `[[MediaWiki]]` links).

## Creating and navigating wikilinks

To create a wikilink, type `[[` and then start typing the name of another note in your repo. Once the desired note is selected press the `tab` key to autocomplete it. For example: [[graph-visualization]].

`Cmd` + `Click` ( `Ctrl` + `Click` on Windows ) on wikilink to navigate to that note (`F12` also works while your cursor is on the wikilink). If the file doesn't exist it will be created in your workspace based on your default [[note-templates]] settings.

## Placeholders

You can also create a [[placeholder]]. <!--NOTE: this placeholder link should NOT have an associated file. This is to demonstrate the concept-->
A placeholder is a wikilink that doesn't have a target file and a link to a placeholder is styled differently so you can easily tell them apart.
They can still be helpful to highlight connections.

Open the graph with `Foam: Show Graph` command, and look at the placeholder node.

Remember, with `CTRL/CMD+click` on a wikilink you can navigate to the note, or create it (if the link is a placeholder).

## Support for sections

Foam supports autocompletion, navigation, embedding and diagnostics for note sections. Just use the standard wiki syntax of `[[resource#Section Title]]`.

## Markdown compatibility

The [Foam for VSCode](https://marketplace.visualstudio.com/items?itemName=foam.foam-vscode) extension automatically generates [[link-reference-definitions]] at the bottom of the file to make wikilinks compatible with other Markdown tools and parsers.

## Read more

- [[foam-file-format]]
- [[note-templates]]
- See [[link-reference-definition-improvements]] for further discussion on current problems and potential solutions.

