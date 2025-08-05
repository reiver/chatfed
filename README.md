# chatfed

**chatfed** is a chat (i.e., instant messaging) application for the Social Web and the Fediverse.

## Technology

**chatfed** is a cross-platform mobile app and progressive-web-app (PWA).

It is written in the Go programming-language (Go) and is compiled to WebAssembly (WASM).
The Go code creates the UI by adding HTML and CSS using DOM manipulation.

## Running

To run **chatfed** you need to run it from an HTTP server, and then open up `main.html` from web-browser.

## Building

To build **chatfed** run a command similar to the following:

```
GOOS=js GOARCH=wasm go build -o main.wasm
```

## Author

Software **chatfed** was written by [Charles Iliya Krempeaux](http://reiver.link)
