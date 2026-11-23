Nocturne Circuit Display — Original Gothic-Cyberpunk Font Style System
======================================================================

Public Download Links (GitHub Release v1.0.0):
- Working OpenType Font (.otf): https://github.com/Etlhbhv/nocturne-circuit-font/releases/download/v1.0.0/NocturneCircuit-Display.otf
- Full Type Specimen & Style System Sheet (.png): https://github.com/Etlhbhv/nocturne-circuit-font/releases/download/v1.0.0/nocturne-circuit-specimen.png
- Repository (with CSS @font-face hero + clean heading usage snippet): https://github.com/Etlhbhv/nocturne-circuit-font

(Both NocturneCircuit-Display.otf and nocturne-circuit-specimen.png are also attached directly to this submission.)

Design Choices:
Nocturne Circuit fuses blackletter architecture (3:1 vertical-to-horizontal stroke contrast, 45° pointed lancet arches, and diamond spearhead spurs) with cyberpunk PCB geometry (repeating 45° chamfered joints and circuit-split crossbars on A, E, F, and H) so the typeface feels like a medieval manuscript etched into obsidian circuit boards. To keep headings genuinely legible on phones, every bowl and counter is deliberately beveled wide open with a generous x-height (520/1000) and stripped of muddy filigree, letting the letterforms scale cleanly from a glowing chrome-neon hero wordmark down to crisp 20–36px mobile headings. All 79 glyphs are 100% original algorithmic CFF vector outlines compiled from scratch—no existing typeface was traced.

Supported Character Set (Partial Basic Latin Display Font — 79 Glyphs):
- Uppercase: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z (26)
- Lowercase: a b c d e f g h i j k l m n o p q r s t u v w x y z (26)
- Numerals: 0 1 2 3 4 5 6 7 8 9 (10)
- Punctuation & Symbols: space . , : ; ! ? - _ / & ' " ( ) · (16 + .notdef)
- Note on completeness: This is a working Basic Latin display release (79 glyphs); accented Latin-Extended characters, currency symbols, and alternate weights are not yet included.

Quick Web Usage (@font-face):
@font-face {
  font-family: 'NocturneCircuit';
  src: url('NocturneCircuit-Display.otf') format('opentype');
  font-display: swap;
}
/* Clean web heading */
h1 { font-family: 'NocturneCircuit', sans-serif; letter-spacing: 0.04em; }
/* Expressive hero neon-chrome treatment */
.hero { text-shadow: -3px 0 #00f0ff, 3px 0 #ff2aa4, 0 0 26px rgba(0,240,255,0.55); }
