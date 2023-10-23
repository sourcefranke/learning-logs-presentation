---
layout: default
---

# States

<div style="text-align: center">
```mermaid {scale: 1.5}
flowchart LR
    Entered --> Started --> Finished
    
    Started -- put at rest --> Paused
    Paused -- return to learning item --> Started
    Paused -- not relevant anymore --> Aborted

    Started -- found not useful --> Aborted
    Entered -- priority too low --> Aborted
```
</div>

... please feel free to define your own state flow ...
