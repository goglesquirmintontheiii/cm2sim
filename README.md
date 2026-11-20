# CircuitSim
CircuitSim is a highly performant pygame based Circuit Maker 2 emulator, built (mostly) for absolute performance.
CircuitSim is built primary using PyGame, with OpenGL for boosting rendering. It thrives on single-core speeds, so expect lower performance if you're running a low-end CPU.
All testing was done on a system with 96GB DDR5, an RTX 3060, and an AMD Ryzen 7 9850X3D, running Linux Nobara 44.

Current features:
- Full support for *every* building type (from doors to screens)
- Extreme performance (tested to over 75,000TPS with simple circuits and 40,000TPS with an entire computer)
- Quick, easy loading of memory dumps in or out of memories
- Building I/O monitoring
- CircuitScript editing

Controls:
- WASD: Camera movement (in/left/out/right)
- Q/E: Camera movement (up/down)
- Arrow keys: Camera rotation
- R-Click and drag: Camera rotation
- L-Click and drag: Camera pan
- Scroll wheel: Zoom in/out
- Shift+scroll: Adjust camera speed
- B: Toggle blocks
- L: Toggle wires
- R-Click: Show context menu
- Ctrl+L-Click and drag: Select blocks (you can then right click them to view them in a separate viewport)

### NOTICE:
CircuitSim is not built by the official Developers of Circuit Maker 2; it is fully fan-built and maintained.
CircuitSim is *not open source yet* though there are plans for it to be open source soon, once it's further in its development cycle.
The CircuitSim Windows binaries have been tested primarily through Wine (A windows emulator/translator) and have *not* been tested on a real Windows system. Your mileage may vary.
