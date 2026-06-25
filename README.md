### Hi there, I'm Nguyen An Vinh! 👋

I'm a final-year Information Security student focused strictly on Windows Internals, native x64 C++ programming, and low-level system mechanics. I love analyzing operating system boundaries, reverse engineering binary structures, and building standalone system-level tools.

- 🚀 **I’m currently working on:** Advanced PE structural manipulation and memory safety tools.
- 📚 **I’m currently learning:** Windows Kernel Architecture & Driver Development basics.
- 🎓 **Background:** Information Security | Academy of Cryptography Techniques (KMA).
- ✉️ **How to reach me:** navinh2k4@gmail.com

---

### 🛠️ Featured Research Projects

#### 📂 [Advanced Static PE Parser Engine](https://github.com/navinh2k4/PE-Parser)
- **Objective:** Built a lightweight, standalone command-line engine to parse and extract structural data from Windows PE binaries without wrapper libraries.
- **Key Logic:** Developed an `RVA to File Offset` translation matrix to map virtual memory addresses to physical raw disk offsets via alignments.

#### 📂 [Windows Subsystem Information Tools Clone](https://github.com/navinh2k4/SysTools-Clone)
- **Objective:** Re-engineered core utilities (cloning `tasklist`/`systeminfo`) with a strict focus on memory safety and exact byte-size dynamic allocation.
- **Key Logic:** Eliminated vulnerable static array structures, managing resource lifecycles by explicitly tracking and closing system handles (`CloseHandle`).

#### 📂 [Advanced PE Manipulation Labs: PE08 & PE10](https://github.com/navinh2k4/PE-Manipulation-Labs)
- **PE08_Process_Hollowing:** Injected payloads by creating a suspended process, unmapping remote memory via `NtUnmapViewOfSection`, and rewriting its image.
- **PE10_AddressOfEntryPoint_Code_Injection:** Hijacked target execution flows by directly modifying the `AddressOfEntryPoint` fields within the Optional Header.
