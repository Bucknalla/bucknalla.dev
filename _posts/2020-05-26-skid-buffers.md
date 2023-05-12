---
title: "How do we prevent pipeline stalling?"
published: false
date:   2020-05-26 19:19:43
---
<script src="/assets/js/mermaid.min.js"></script>

Take an input and an output data channel that are handshaked (signal `READY` when ready to receive data and `VALID` when they have valid data to transfer).

![Skid Buffer](/assets/diagrams/skidbuffer/skidbuffer.drawio.svg)

<div class="mermaid">
graph TD;
A-->B;
A-->C;
B-->D;
C-->D;
<div class="mermaid">

#### References

```bibtex
@misc{laforest, 
    title={Pipeline Skid Buffer}, 
    url={http://fpgacpu.ca/fpga/Pipeline_Skid_Buffer.html}, 
    journal={Pipeline skid buffer}, 
    author={LaForest, Charles Eric}
} 
```

<!-- > **_NOTE:_**  These types of blog post are me attempting to practice teaching/conveying of knowledge. Let me know what is/isn't clear! -->