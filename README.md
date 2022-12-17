# spwn-lzw
The LZW compression algorithm implemented in SPWN.

# Usage
```ts
let encoded = lzw_encode(' Hello, World! ' * 15);
$.print(encoded) //   Hello, World!ĀĂĄĆĈĊČĎāăąćĉċčďĘĒěĕĞđĚĔĝėĤēĜĖĐęĪĢĨĮġħĭĠĦĬğĥīģĲķļĶĻıŀİĵĺńĹįĝ
$.print(lzw_decode(encoded)) //   Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  Hello, World!  
```
