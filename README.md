Lexipython provides support for a limited amount of Markdown-esque formatting.

```
# Player: PN
# Turn: 1
# Title: Example page

This is an example page.
Some words are //italicized//,
and some words are **bolded**.
All of these sentences are part of the same paragraph.

This is a new paragraph.\\
Unlike the last paragraph, this line will be after a line break within the paragraph.

This is an [[example citation|Phantom page]]. You can also cite a [[phantom page]] with just the title.

~Dr. X. Amplepage
```

Each turn, fill out the header with your player information, the current turn, and the title of your entry. The Player field can be anything as long as it's the same for all articles you write (even when they're by different characters). Using your initials is recommended.

Two line breaks begins a new paragraph. A single line break does nothing, unless the line is ended by a double backslash (\\\\).

Text bounded by ** will be bolded: \*\*bold\*\* produces **bold**. Text bounded by // will be italicized: //italics// produces *italics*.

To cite another Lexicon entry, use double brackets. Text in double brackets will cite and link to the entry of the same name: [[README]] produces [README](README.md). Text in double brackets split with a | will alias the link as the left text and link to the entry with the name of the right text: [[this text|README]] produces [this text](README.md). You must be precise in the entry title you cite to. Citations to "Example" vs. "The Example" will point to different entries and create different phantoms, and your Editor will probably have to clean up after you.

Beginning a paragraph with ~ will right-align it and place a horizontal line above it. Use this for signing your entry with your scholar's name.
