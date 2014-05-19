An iterator which steps through a string and moves the pen position (in pixels) forward based on the glyph kerning and horizontal advance. This is also used to compute a bounding region for a series of glyphs, to the given available width.

This class is mostly used internally by `fontpath` modules, but it may be useful for an advanced or custom renderer.