---
layout: default
---

# States

<div style="text-align: center">
```mermaid {scale: 1.5}
flowchart LR
    Entered --> Started --> Finished
    
    Started --> Paused
    Paused --> Started
    Paused --> Aborted

    Started --> Aborted
    Entered --> Aborted
```
</div>

... please feel free to define your own state flow ...
