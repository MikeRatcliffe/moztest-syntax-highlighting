moztest-syntax-highlighting
===========================

Mozilla test log syntax highlighting for Sublime Text 3.


##Installation

 1. In Sublime Text 3 click "Preferences" > "Browse Packages..."
 2. Copy MozillaTest.tmLanguage into that folder and you are done.

This syntax highlighting will be applied to *.test. If your test logs do not have this extension simply change the syntax to "Mozilla Test Output."


##NOTE
The colors are currently selected from the Monokai color scheme so if you are using a different scheme you will probably want to change them.

If you want to change any colors e.g. support.function.dom.js then:

 1. Install ScopeHunter
 2. Toggle Instant Scoper on in your command palette.
 3. Move the cursor to a word that is in the color you like in your current theme such as a keyword.
 4. The scope you need to use in order to obtain that color will be displayed in the ScopeHunter panel.
