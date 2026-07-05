<div align="center">

# c5ln

I am interested in building efficient execution systems:  
memory allocators, runtime-level optimization tools, code analysis engines, and secure AI execution environments.

<br>

</div>

---

## Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3>
        <a href="https://github.com/c5ln/AllocSitter">AllocSitter</a>
      </h3>
      <p>
        <b>Workload-specialized allocator optimization</b><br>
        <i>Currently in progress</i>
      </p>
      <p>
        An ongoing project that extends a custom memory allocator into a real Tree-sitter parsing workload.
        The goal is to analyze allocation behavior, compare performance against glibc malloc,
        and use benchmark data to guide workload-specific allocator optimization.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square">
        <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white">
        <img src="https://img.shields.io/badge/Tree--sitter-000000?style=flat-square">
        <img src="https://img.shields.io/badge/Benchmarking-555555?style=flat-square">
        <img src="https://img.shields.io/badge/Allocator-555555?style=flat-square">
      </p>
    </td>
    <td width="50%">
      <h3>
        <a href="https://github.com/c5ln/memory-allocator">memory-allocator</a>
      </h3>
      <p>
        <b>Custom dynamic memory allocator in C</b><br>
        malloc/free/calloc/realloc implemented from scratch.
      </p>
      <p>
        Implements 16-byte alignment, 4-byte headers, boundary tags,
        block splitting, coalescing, free-list management, and heap invariant checking.
        This project helped me understand how dynamic memory allocation works below the standard library.
      </p>
      <p>
        <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white">
        <img src="https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white">
        <img src="https://img.shields.io/badge/Memory%20Management-555555?style=flat-square">
      </p>
    </td>
  </tr>

  <tr>
    <td width="50%">
      <h3>
        <a href="https://github.com/c5ln/Telescode">Telescode</a>
      </h3>
      <p>
        <b>Zoomable codebase exploration tool</b><br>
        “Google Earth for your codebase.”
      </p>
      <p>
        Parses repositories with Tree-sitter, visualizes code structure across file/class/function/code layers,
        estimates complexity, and recommends code reading order using PageRank and Betweenness Centrality.
      </p>
      <p>
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white">
        <img src="https://img.shields.io/badge/Tree--sitter-000000?style=flat-square">
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
        <img src="https://img.shields.io/badge/ImGui-222222?style=flat-square">
      </p>
    </td>
    <td width="50%">
      <h3>
        <a href="https://github.com/c5ln/SecureTL">SecureTL</a>
      </h3>
      <p>
        <b>Secure split learning system</b><br>
        Privacy-preserving collaborative training.
      </p>
      <p>
        Dynamically builds PyTorch models from JSON configs, validates model configs inside a WASM sandbox,
        and isolates node-side processes using Linux namespace and seccomp-bpf to reduce security risks.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
        <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white">
        <img src="https://img.shields.io/badge/Linux%20Security-000000?style=flat-square&logo=linux&logoColor=white">
      </p>
    </td>
  </tr>

  <tr>
    <td width="50%">
      <h3>
        <a href="https://github.com/seojeongm/wikiKI">wikiKI</a>
      </h3>
      <p>
        <b>Real-time Wikimedia edit stream analyzer</b><br>
        Detects high-tension Wikipedia articles.
      </p>
      <p>
        Ingests live enwiki edit events, maintains Redis hot-tier and SQLite cold-tier storage,
        and detects signals such as 3RR, edit velocity spikes, and editor conflicts.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white">
      </p>
    </td>
    <td width="50%">
      <h3>Current Focus</h3>
      <p>
        <b>Runtime · Memory · Systems Performance</b>
      </p>
      <p>
        I am currently focusing on allocator internals, Linux memory behavior,
        Tree-sitter workload analysis, and runtime-level performance bottlenecks.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Runtime-222222?style=flat-square">
        <img src="https://img.shields.io/badge/Memory-222222?style=flat-square">
        <img src="https://img.shields.io/badge/Linux-222222?style=flat-square&logo=linux&logoColor=white">
        <img src="https://img.shields.io/badge/Performance-555555?style=flat-square">
      </p>
    </td>
  </tr>
</table>

---

## Tech Stack

<div align="left">

### Languages

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">

---

## Contact

<div align="left">

<a href="https://c5history.tistory.com/">
  <img src="https://img.shields.io/badge/Tech%20Blog-000000?style=for-the-badge&logo=tistory&logoColor=white">
</a>

</div>
