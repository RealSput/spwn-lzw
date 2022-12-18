# spwn-lzw
The LZW compression algorithm implemented in SPWN.

# Usage
```ts
let lzw = import "lzw.spwn"
let encoded = lzw.compress(' Hello, World! '*15);
$.print('---')
$.print('COMPRESSED: ' + encoded)
$.print('---')
$.print('DECOMPRESSED: ' + lzw.decompress(encoded))
$.print('---')
```
