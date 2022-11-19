# Interactive Text Maker

The goal of this project is to make texts in TextView clickable and also translatable easily.

User separates each special word with separator characters like `"__"`
and then when tapping all the custom words inside the TextView The `.setOnTextClickListener`(InteractiveTextMaker) or 
`addOnSpecialWordClickListener`(InteractiveTextView) function is called with the index of the touched word. 
In this way, sentences can be translated into other languages more easily and The locations of tactile sentences
remain fixed in all languages.

Apply From Medium Article: https://medium.com/p/2b70e2072453
