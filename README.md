# Awesome Opensource Graph Library

> collection for Feakin only. inspired by: [https://github.com/anvaka/graph-drawing-libraries](https://github.com/anvaka/graph-drawing-libraries)

## Graph App

- [Drawio](https://github.com/jgraph/drawio) this project, is a configurable diagramming/whiteboarding visualization application. draw.io is owned and developed by JGraph Ltd, a UK based software company.
- [Excalidraw](https://github.com/excalidraw/excalidraw)  Virtual whiteboard for sketching hand-drawn like diagrams.
- [ourboard](https://github.com/raimohanska/ourboard)  An online whiteboard.

## Graph Drawing Library

- [MaxGraph](https://github.com/maxGraph/maxGraph) is a TypeScript library which can display and allow interaction with vector diagrams. 
- [VivaGraph](https://github.com/anvaka/VivaGraphJS)is designed to be extensible and to support different rendering engines and layout algorithms. Underlying algorithms have been broken out into ngraph.
- [Sigma.js](https://github.com/jacomyal/sigma.js) is an open-source JavaScript library aimed at visualizing graphs of thousands of nodes and edges.

Others:

- [Alchemy](https://github.com/GraphAlchemist/Alchemy)  is a graph drawing application built in d3. Alchemy.js was built so that developers could easily get up and running with Graph visualization applications, and not much over head. 

## Layout Algorithm

- [cola.js](https://github.com/tgdwyer/WebCola) JavaScript constraint based layout for high-quality graph visualization and exploration using D3.js and other web-based graphics libraries.
- [ELK](https://github.com/kieler/elkjs)  Eclipse Layout Kernel (ELK) implements an infrastructure to connect diagram editors or viewers to automatic layout algorithms. This library takes the layout-relevant part of ELK and makes it available to the JavaScript world. 
	- [KLayJS](https://github.com/kieler/klayjs) is a layer-based layout algorithm that is particularly suited for node-link diagrams with an inherent direction and ports (explicit attachment points on a node's border). 
- [Dracula](https://github.com/strathausen/dracula) is a set of tools to display and layout interactive graphs, along with various related algorithms.
- [dagre](https://github.com/dagrejs/dagre) is a JavaScript library that makes it easy to lay out directed graphs on the client-side.
- [Springy](https://github.com/dhotson/springy) is a force directed graph layout algorithm in JavaScript.
- [ngraph](https://github.com/anvaka/ngraph) is a set of graph related algorithms. It can be used in a browser or on the server side. This repository is a collection of examples, which show how to use some of them or build your own.

Cytoscape.js related:

 - [cytoscape.js-cise](https://github.com/iVis-at-Bilkent/cytoscape.js-cise) iSE(Circular Spring Embedder) is an algorithm based on the traditional force-directed layout scheme with extensions to move and rotate nodes in the same cluster as a group. 
 - [SyBLaRS](https://github.com/iVis-at-Bilkent/syblars) Systems Biology Layout & Rendering Service (SyBLaRS) is a web service to lay out graphs in SBGNML, SBML, GraphML and JSON formats and/or produce corresponding images (in JPG, PNG or SVG formats) of the layouts with an option to highlight results from various graph queries in the backend.
 - [avsdf](https://github.com/iVis-at-Bilkent/cytoscape.js-avsdf) An implementation of the Circular Drawing Algorithm by Hongmei He & Ondrej Sýkora.
 - [fcose](https://github.com/iVis-at-Bilkent/cytoscape.js-fcose) is a faster version of our earlier compound spring embedder algorithm named CoSE, implemented as a Cytoscape.js extension by i-Vis Lab in Bilkent University.

D3.js realted:

- [D3 Force](https://github.com/d3/d3-force)  Force-directed graph layout using velocity Verlet integration. 
	- [cytoscape-d3-force](https://github.com/shichuanpo/cytoscape.js-d3-force)  d3-force for cytoscape 

Framework related: 

- [vis-network](https://github.com/visjs/vis-network)  is a visualization to display networks and networks consisting of nodes and edges. The visualization is easy to use and supports custom shapes, styles, colors, sizes, images, and more. 


## Render Styled

- [Rough](https://github.com/rough-stuff/rough) is a small (<9 kB) graphics library that lets you draw in a sketchy, hand-drawn-like, style. The library defines primitives to draw lines, curves, arcs, polygons, circles, and ellipses. It also supports drawing SVG paths.

## Render 

- [Konvajs](https://github.com/konvajs) is an HTML5 Canvas JavaScript framework that extends the 2d context by enabling canvas interactivity for desktop and mobile applications.
	- [react-konva](https://github.com/konvajs/react-konva) JavaScript library for drawing complex canvas graphics using React.
- [Raphael](https://github.com/DmitryBaranovskiy/raphael)  Cross-browser vector graphics the easy way.

## Model

- [https://github.com/graphology/graphology](https://github.com/graphology/graphology) is a robust & multipurpose Graph object for JavaScript and TypeScript.

Cinco:

- [Cinco](https://gitlab.com/scce/cinco-cloud) Cinco SCCE Meta Tooling Framework.

[Meta Graph Language](https://gitlab.com/scce/cinco/-/wikis/Usage/Meta-Graph-Language), The root element of every mgl file is the MGL model object. It can contain several model elements like graphmodels, nodes, edges, and more. Beside of that, it also contains some mandatory meta data that will be considered upon generation.


## Geometric Algebra

- [https://github.com/enkimute/ganja.js](https://github.com/enkimute/ganja.js) Javascript Geometric Algebra Generator for Javascript, c++, c#, rust, python. (with operator overloading and algebraic literals) - refs to [https://bivector.net/lib.html](https://bivector.net/lib.html)

### Collision Detection

 - [SAT.js](https://github.com/jriecken/sat-js) A simple JavaScript library for performing 2D collision detection
 - [RBush](https://github.com/mourner/rbush) is a high-performance JavaScript library for 2D spatial  indexing of points and rectangles.
 - [JSTS](https://github.com/bjornharrtell/jsts) is an ECMAScript library of spatial predicates and functions for processing geometry conforming to the Simple Features Specification for SQL published by the Open Geospatial Consortium.

## Server


### JavaScript

- [Hypermerge](https://github.com/automerge/hypermerge) is a Node.js library for building p2p collaborative applications without any server infrastructure. It combines Automerge, a CRDT, with hypercore, a distributed append-only log.
- [automerge](https://github.com/automerge/automerge)  A JSON-like data structure (a CRDT) that can be modified concurrently by different users, and merged again automatically. 
- [yjs](https://github.com/yjs/yjs) is a CRDT implementation that exposes its internal data structure as shared types. Shared types are common data types like Map or Array with superpowers: changes are automatically distributed to other peers and merged without merge conflicts.
    - [SyncedStore](https://github.com/yousefed/SyncedStore) is an easy-to-use library for building collaborative applications that sync automatically. It's built on top of Yjs, a proven, high performance CRDT implementation.
    - [y-monaco](https://github.com/yjs/y-monaco) binding maps a Y.Text to the Monaco editor (the editor that power VS Code). 
- [ShareDB](https://github.com/share/sharedb/)  is a realtime database backend based on Operational Transformation (OT) of JSON documents. It is the realtime backend for the DerbyJS web application framework.
- [Teletype](https://github.com/atom/teletype) An Atom package that lets developers share their workspace with team members and collaborate on code in real time.
    - [teletype-crdt](https://github.com/atom/teletype-crdt)
    - [teletype-server](https://github.com/atom/teletype-server)
    - [teletype-client](https://github.com/atom/teletype-client)
- [Swarm](https://github.com/gritzko/swarm)  is a JavaScript client for the Swarm database. Swarm is like "git for data" except it's real-time and never has a merge conflict. 
- [Etherpad](https://github.com/ether/etherpad-lite)  Etherpad: A modern really-real-time collaborative document editor. 

### Rust

- [Automerge RS](https://github.com/automerge/automerge-rs) is a Rust library implementation of the Automerge file format and network protocol. Its focus is to support the creation of Automerge implementations in other languages, currently; WASM, JS and C. A libautomerge if you will.
- [Diamond Types](https://github.com/josephg/diamond-types) contains a high performance rust CRDT for text editing. This is a special data type which supports concurrent editing of lists or strings (text documents) by multiple users in a P2P network without needing a centralized server.
- [Ropey](https://github.com/cessen/ropey) is a utf8 text rope for Rust, designed to be the backing text-buffer for applications such as text editors. Ropey is fast, robust, and can handle huge texts and memory-incoherent edits with ease.

### Golang

- [Redwood](https://github.com/redwood/redwood) is a highly-configurable, distributed, realtime database that manages a state tree shared among many peers. Imagine something like a Redux store, but distributed across all users of an application, that offers offline editing and is resilient to poor connectivity.

## Documents

for more: [CRDTs tech](https://crdt.tech/)

### CRDT

Conflict-free replicated data type -> [wiki](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)

- ★★★★★ Hacker News: [Faster CRDTs: An Adventure in Optimization (josephg.com)](https://news.ycombinator.com/item?id=28017204)
- CRDT Primer
    - [A CRDT Primer Part I: Defanging Order Theory](http://jtfmumm.com/blog/2015/11/17/crdt-primer-1-defanging-order-theory/)
    - [A CRDT Primer Part II: Convergent CRDTs](http://jtfmumm.com/blog/2015/11/24/crdt-primer-2-convergent-crdts/)
- ★★★★★ [Data Laced with History: Causal Trees & Operational CRDTs](http://archagon.net/blog/2018/03/24/data-laced-with-history/)

Resources:

- [Xi Editor CRDT](https://github.com/xi-editor/xi-editor/blob/master/docs/docs/crdt.md)，Actions：Deletion; tombstones; intervals;Undo;Recap。
    - [An Undo Framework for P2P Collaborative Editing](https://hal.archives-ouvertes.fr/inria-00432373/document)
    - [Tombstone Transformation Functions for Ensuring Consistency in Collaborative Editing Systems](http://www.loria.fr/~urso/uploads/Main/oster06collcom.pdf)
    - [Real time group editors without Operational transformation](https://hal.inria.fr/inria-00071240/document)
    - [A comprehensive study of Convergent and Commutative Replicated Data Types](http://hal.upmc.fr/inria-00555588/document)


### OT

Operational transformation -> [wiki](https://en.wikipedia.org/wiki/Operational_transformation)

### Others

- [Multiplayer Editing in Figma](https://www.figma.com/blog/multiplayer-editing-in-figma/)
