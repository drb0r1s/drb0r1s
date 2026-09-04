# Boris (@drb0r1s)

BSc in Computer Science with 6 years of experience in software development. I started with JavaScript in 2020, moved into web frameworks (React, since 2021), and over time shifted my focus toward compiler theory, language design, and low level systems programming.

I have solid, broad web development knowledge, but these days I'm mostly interested in what happens "under the hood": how languages are tokenized, parsed, compiled, and turned into something that runs. That interest is the throughline behind both of my main projects below.

## The Most Important Projects

### Assembly Reality (ARy)
A full featured, web based assembly language simulator, built as my bachelor's thesis at UP FAMNIT and actively used by students in a university hardware course.

It's not a toy interpreter: it's a full simulation environment running entirely in the browser, no installation needed. Custom 16 bit CPU, a 58 keyword instruction set, a two pass assembler, interrupt handling, a RAM and register visualizer, and a WebGL graphical display, all built on a two threaded architecture (UI thread + a Web Worker assembler thread) communicating through SharedArrayBuffer.

**Stack:** `JavaScript`, `React`, `Manager` (my custom state-control library), `SASS`, `Monaco Editor`, `WebGL`, `Canvas 2D`, `Web Workers + SharedArrayBuffer`.

### DOKTOR
A web rendering language with its own compiler, layout engine, runtime, and renderer, built entirely from scratch, from tokenizing to pixel drawing.

DOKTOR sits between HTML/CSS and a native layout engine: no browser layout engine involved, no DOM, no CSS cascade. Source code goes through a real multi stage pipeline (tokenizer → parser → resolver → shaper → scroller → painter → packer) down to a compact binary format, then runs through a Rust/WASM runtime and hand written WebGL + Canvas 2D renderers.

It's a solo project driven by genuine curiosity about compilers, layout engines, and systems level graphics programming, not a framework wrapper.

**Stack:** `Rust`, `JavaScript`, `WebAssembly`, `WebGL`, `Canvas 2D`.

## Areas of Interest

`Compiler Theory`, `Compiler Design`, `Programming Languages`, `Systems Programming`, `Web`, `Computer Graphics`, `Parallel & Concurrent Programming`.

## Find my work

Check out my pinned repositories below for more details on each project.
