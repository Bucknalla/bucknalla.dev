---
title: "How do we prevent pipeline stalling?"
published: false
date:   2020-05-26 19:19:43
---

Take an input and an output data channel that are handshaked (signal `READY` when ready to receive data and `VALID` when they have valid data to transfer).


![Skid Buffer](/assets/diagrams/skidbuffer/skidbuffer.drawio.svg)

#### References

```bibtex
LaForest, Charles Eric. "Skid Buffers." FPGA Design Elements, 2020, fpgacpu.ca/fpga/index.html.
```

<!-- > **_NOTE:_**  These types of blog post are me attempting to practice teaching/conveying of knowledge. Let me know what is/isn't clear! -->