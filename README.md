# FireflyIII_tools-PostFinanceCSVProcessor

a fork from https://github.com/PackElend/FireflyIII_tools-PostFinanceCSVProcessor/tree/main

## original description from author:
Basically, it looks for the subfolder "für Import", process all files in there and save them with the same name but appending "MachineReadable".
In addition, it cleans-up the description a bit and puts the original description in the note field
(src: https://www.reddit.com/r/FireflyIII/comments/it8n49/comment/gnnd5ph/)

## modifications:
- fix not breaking on first empty line which postfinance now puts between their header and the real data

## todos:
- add firefly iii config json, so not anybody needs to redo this
- implement read-out of opposite account (IBAN)
