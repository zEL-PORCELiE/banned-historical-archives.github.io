# C++ LocalFirst Framework

> A C++ framework for building local-first, offline-capable applications with seamless synchronization.

## Quick Start

```bash
git clone https://github.com/cpp-localfirst/framework.git
cd framework
vcpkg install localfirst-cpp
```

## Features

- Offline-First: Work without internet connection
- Auto-Sync: Smart conflict resolution  
- Cross-Platform: Windows, Linux, macOS
- Privacy-Focused: Data stays local first

## Architecture

```
Local Storage → Conflict Resolution → Cloud Sync
```

## Installation

```bash
# Via package manager
vcpkg install localfirst-cpp

# Or build from source  
git clone https://github.com/cpp-localfirst/framework.git
cd framework && make install
```

## Configuration

```yaml
# localfirst.config
storage:
  engine: "sqlite"
sync:
  strategy: "optimistic" 
  interval: 300s
```

## Documentation

- API Reference: https://docs.localfirstcpp.dev
- Examples: https://github.com/cpp-localfirst/examples  
- Tutorials: https://learn.localfirstcpp.dev

**Version**: 2.3.1 | **Last Update**: 2025-10-15

## License

MIT
