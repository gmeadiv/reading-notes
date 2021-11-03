# Cascadia JS: Wednesday

## Jessica Campos: Window.open

- works at instabase

- discovered this feature by making a typo and then logging the surprising result

- inside the < a > tag you'd include a handleClick function which prevents the default behavior of navigating to a new page

- instead, you'd run window.open and as arguments you'd pass in the tab name and a uuid

- my takeaway:

  - this has been my favorite presentation, even including the career power hours

  - her process of encountering an unexpected result and then logging stuff to see how the code is working was v familiar to me

  - it's encouraging to hear that the logging skills I've been developing here will continue to help me on the job

## Leonardo Faria: Using lighthouse in the real world

- unsure what lighthouse is!

## Andrew Hao: Let's go fast! Creating a culture of front-end performance

- was networking with Jessica Campos (and applying to Instabase!) during this talk but it seemed interesting and I wish I had paid more attention

- don't overburden yourself

## Aaron Turner: Enter the sandbox: JS on Wasm

- codefi = lowfi + hip hop

- what is WebAssembly?
  - universal lowe-level btytecode on the web
  - better than JS for data-heavy apps
  - more reliable and supportable

- why are there so many languages?
  - I wish I knew more about what a "language" was
  - what is a polyfill? Heard it a couple of times already

- Linear Memory
  - good for security

- WebAssembly relies on capabilities
  - only has access to JS functions which we allow it to access
  - also good for security

- WASI is a system interface for webassembly
  - the equivalent of a web API for JS

- using WASI with JS
  - Performance improvements (saves space and time)
    - the less powerful the device is, the bigger the performance gap between JS and WASI
  - code portability
  - feature polyfilling

- madewithwebassembly.com

- will WASM kill JS?
  - No. it was designed to compliment JS not replace it