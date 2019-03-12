# Boilerplate-EPUB-CSS

Boilerplate CSS used in EPUBs I make. Created for Japanese light novels, though I imagine these could apply elsewhere.

## Files

**epub3.css**: Catered toward EPUB3 publications. Uses some CSS3 properties, and styles some things based on [EPUB 3 Structural Semantics](https://idpf.github.io/epub-vocabs/structure/). Includes fallback measures for reading systems that only support ePub2.

**epub2.css**: Use in ePub2 or EPUB3. Stripped-down version of *epub3.css*. Uses simpler selectors and properties that are more likely to be supported. Most applications default to creating ePub2 files, so use this if you are unsure.
