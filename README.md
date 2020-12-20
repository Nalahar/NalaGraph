# NalaGraph
WPF Simple Graph

* The software is not in useful stage.

* For interested party NalaGraph will:
  - Parse XML files for graph strcuture of NODE/EDGE. This feature will be extendable with plugins.
  - Use its own custom algorythm for layout. The algorythm is unlayered, flow oriented suitable for non circular graphs. Extendable layouts are possible too.
  - The drawing will rely on WPF shapes, D3X or GDI systems. Since graph componenets are modular, the drawing part can be exchanged too (mostly for linux, or java integration).
  - The data received from XML file or files are graph structure (node edges, directions etc) and Symbols to draw nodes with. At start symbol definitions will be NalaGraph XML model descriptions, but future integrations with other symbol script definitions will be possible.
  
  * The main Purpose of NalaGraph is to be presentation of my skills nad experiences. in thar regarding, it is mainly by unit tests. The licence is open sourced, donations are more than welcome, once the NalaGraph reaches certain maturity and delivers its promises.
  
  * The main reason it was git hub hosted is to enable ease of forking. I would love to see other peoples ideas inspired by this software. 
  
  * Why did I want to write this software? I wanted to have generalised simple graph capabilities with schematic type layout. Something like freemind software, but I want custom layout, i want my own symbol profiles and templates. With modable core written it will be possible to gradually built on these ideas.
