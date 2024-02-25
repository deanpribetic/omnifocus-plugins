### clean-up-inbox.omnijs

This plug-in parses every task in the inbox and tidies up the following:

- For tasks that have wiki-style links in the name (such as those that might come from [Obsidian](https://obsidian.md) via the [obsidian-to-omnifocus](https://github.com/lizard-heart/obsidian-to-omnifocus) plug-in) it will first try to match the wikilink with an existing Tag with the same title in your vault. Wikilinks without a matching Tag are ignored.
- It will remove wiki-style links in the name
- Tasks with markdown-style url links will have the link appended as a note and remove the markdown formatting from the Task title
