## TF-IDF

**TF** : Abbreviation of the *term frequency*. It counts how much the word occurs in the doc.

However, there is a problem that you can not only use it to judge the word as important.

For example, word 'is' appears a lot in not only in the doc, but also in other docs.

So the concept **TF-IDF** comes out.

**DF** : Abbreviation of the *document frequency*. However, we usually use **inverse document frequency** rather than the document frequency.

**TF-IDF** : Abbreviation of the *term frequency - inverse document frequency*. This is the value of multiplication between **TF** and **IDF**.

The meaning of **TF-IDF** is that it appears lot in *that doc* but not in *other doc*.

With this value, you can know how this word is important in the doc.
