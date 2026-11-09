# Operating Systems (III-I, SNIST) — Unit-wise Notes

| Unit | File | Topics |
|---|---|---|
| I | [Unit-1_Introduction_to_Operating_Systems.md](Unit-1_Introduction_to_Operating_Systems.md) | OS definition, kernel, types of OS, architecture, services, system calls & programs, OS structures, threads |
| II | [Unit-2_Process_Management_and_CPU_Scheduling.md](Unit-2_Process_Management_and_CPU_Scheduling.md) | Process, states, PCB, context switch, schedulers, CPU scheduling (FCFS, SJF/SRTF, priority, RR, MLQ, MLFQ) with solved problems, Windows/Linux |
| III | [Unit-3_Process_Synchronization_and_IPC.md](Unit-3_Process_Synchronization_and_IPC.md) | Race condition, critical section, Peterson, TSL, semaphores, classical problems, monitors, IPC (pipes, FIFOs, message queues, shared memory) |
| IV | [Unit-4_Deadlocks_and_Memory_Management.md](Unit-4_Deadlocks_and_Memory_Management.md) | Deadlock conditions, RAG, prevention, Banker's algorithm (solved), detection, recovery; paging, TLB, segmentation, virtual memory, page replacement, thrashing |
| V | [Unit-5_File_System_and_Disk_Scheduling.md](Unit-5_File_System_and_Disk_Scheduling.md) | File concept, access methods, directory structures, allocation methods, free space, disk scheduling (FCFS to C-LOOK, solved), DFS |
| VI | [Unit-6_IO_Systems_and_Protection.md](Unit-6_IO_Systems_and_Protection.md) | I/O hardware, polling, interrupts, DMA, protection, access matrix & implementation, revocation, security threats, cryptography |

**How to read:** ★★★ = high-priority exam topic · ★★ = medium · ★ = short answer. Each unit ends with a **one-page summary** table for last-minute revision.

**Diagrams:** slide figures are in `media/` (whole slides were rendered where the original figure was a Windows metafile); flowcharts, sequence/state diagrams, Gantt charts and mind maps are written in **Mermaid** — they render on GitHub, Obsidian, Typora and in VS Code (Markdown Preview Mermaid Support extension).

**Sources:** The unit PPTs (*OS-Unit-1* = *Unit 1*; *Unit-2* and *OS-unit-2-uodated* merged), *CPU-Scheduling-and-Algorithm-.pdf*, *OSC – Practice Questions (Units 4–6).pdf* and the Mid-1 important-questions docx. Numericals were re-worked; where a slide's answer was wrong (e.g. Banker's smallest-x question, LRU fault count, RR waiting time) the notes give the corrected value and flag it.
