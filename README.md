# ⚡ C++ Architecture & Companion Code Pack

Welcome to the companion code repository for our deep-dive **C++ Mastery** video series! This repo contains clean, runnable modern C++ code, memory management templates, and high-performance architectural patterns.

---

## 🛠️ What's Inside

- 🧠 **`/01-memory-management`**: RAII wrappers, custom allocators, and smart pointer benchmarks.
- ⚡ **`/02-templates-metaprogramming`**: Compile-time evaluation, variadic templates, and `C++20` concepts.
- 🏗️ **`/03-design-patterns`**: Zero-cost abstractions, modern Factory, and Observer patterns.
- 🚀 **`/04-performance-hacks`**: Cache-friendly data structures and memory alignment.

---

## 🚀 Quick Start

### Prerequisites
- `GCC 11+`, `Clang 13+`, or `MSVC 2019+` (C++20 support required)
- `CMake 3.20+`

### Build & Run

```bash
# 1. Clone the repo
git clone [https://github.com/yourusername/cpp-architecture-mastery.git](https://github.com/yourusername/cpp-architecture-mastery.git)

# 2. Navigate to directory
cd cpp-architecture-mastery

# 3. Create build directory & compile
mkdir build && cd build
cmake ..
make

# 4. Run sample benchmark
./bin/memory_demo
