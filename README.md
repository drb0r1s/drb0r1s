# Boris (@drb0r1s)

BSc in Computer Science with 6 years of experience in software development. I started with JavaScript in 2020, moved into web frameworks (React, since 2021), and over time shifted my focus toward compiler theory, language design, and low level systems programming.

I have solid, broad web development knowledge, but these days I'm mostly interested in what happens "under the hood": how languages are tokenized, parsed, compiled, and turned into something that runs. That interest is the throughline behind both of my main projects below.

## The Most Important Projects

### Assembly Reality (ARy)
A full featured, web based assembly language simulator, built as my bachelor's thesis at UP FAMNIT and actively used by students in a university hardware course.

It's not a toy interpreter: it's a full simulation environment running entirely in the browser, no installation needed. Custom 16 bit CPU, a 58 keyword instruction set, a two pass assembler, interrupt handling, a RAM and register visualizer, and a WebGL graphical display, all built on a two threaded architecture (UI thread + a Web Worker assembler thread) communicating through SharedArrayBuffer.

**Stack:** `JavaScript`, `React`, `Engineer` (my custom state-control library), `SASS`, `Monaco Editor`, `WebGL`, `Canvas 2D`, `Web Workers + SharedArrayBuffer`.

### DOKTOR
A web rendering language with its own compiler, layout engine, runtime, and renderer, built entirely from scratch, from tokenizing to pixel-drawing, with no browser layout engine involved. DOKTOR is the subject of my Master's thesis at UP FAMNIT, carried out in the HICUP lab.

DOKTOR is a system of six projects: DOKTOR Compiler, DOKTOR Runtime, DOKTOR Web, DOKTOR Scripts, DOKTOR Server, and the planned DOKTOR Code (interactivity). Source code runs through a multi-stage pipeline (tokenizer → parser → resolver → shaper → scroller → painter → packer) and is compiled to a compact binary format. A Rust/WASM runtime then renders it with hand-written WebGL shaders and a Canvas 2D text layer, supported by a CLI and a live-reload dev server.

The language is a deliberate design experiment: a small, closed set of block types, a closed set of properties, and exactly one way to solve each layout problem.

**Research value:** Few resources exist on designing a language together with its entire execution pipeline, especially for the web, where existing approaches are mostly commercial and poorly documented. The thesis asks whether a purpose-built pipeline, with no DOM, no CSS cascade, and no general-purpose layout solver, can deliver expressive, performant UIs. It is evaluated on expressiveness across a reference set of interfaces, non-redundancy of properties, and performance compared to HTML/CSS.

**Future work:** interactivity via multi-language scripting (JavaScript, Rust, and DOKTORScript (a future work idea of developing custom scripting language)), optimization, and thorough testing.

**Stack:** `Rust`, `JavaScript`, `WebAssembly`, `WebGL`, `Canvas 2D`, `Node.js`.

## Areas of Interest

`Compiler Theory`, `Compiler Design`, `Programming Languages`, `Systems Programming`, `Web`, `Computer Graphics`, `Parallel & Concurrent Programming`.

## Find my work

Check out my pinned repositories below for more details on each project.
