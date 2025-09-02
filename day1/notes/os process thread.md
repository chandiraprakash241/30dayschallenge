
---

## 📘 OS_Process_Threads.md
```markdown
# OS: Process vs Threads

## 📌 What I Learned Today
1. **Process**:
   - An independent program in execution.
   - Has its own memory space (code, data, stack, heap).
   - Example: Chrome Browser, VS Code.

2. **Thread**:
   - A lightweight unit of execution inside a process.
   - Shares memory with other threads of the same process.
   - Example: Chrome tabs (each tab is a thread under the Chrome process).

3. **Differences**:
   | Process | Thread |
   |---------|--------|
   | Heavyweight | Lightweight |
   | Separate memory | Shared memory |
   | Context switching is costly | Context switching is faster |

## 📝 Notes
- Multiple threads inside one process make programs faster.  
- If one process crashes → it doesn’t affect others.  
- If one thread crashes → it may affect the whole process.  

## ✅ Evaluation
- I understood the difference with real-life examples (Chrome, Notepad).  
- I drew a flow diagram of process → thread.  
