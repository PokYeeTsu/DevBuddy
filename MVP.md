# DevBuddy MVP Specification

## 🎯 Goal
Deliver a working local CLI tool that:
1. Indexes a directory
2. Stores file metadata into SQLite
3. Performs simple substring search
4. Includes basic unit tests
5. Serves as the foundation for future AI features

---

## 📁 MVP Components

### 1. File Discovery
- Recursively scan target directory
- Collect:
  - path
  - size
  - last modified time

### 2. Database Layer
- SQLite database
- `files` table
- Insert or replace metadata on re-index

### 3. CLI
Commands:
