# 1. Structure Breakdown
| Position | Symbol | Meaning |
| :--- | :---: | :--- |
| **1st Char** | `d` or `-` | **d** for Directory, **-** for Regular File |
| **Chars 2-4** | `rwx` | **User (Owner):** What the creator can do |
| **Chars 5-7** | `rwx` | **Group:** What members of the file's group can do |
| **Chars 8-10** | `rwx` | **Others:** What everyone else on the system can do |


## 2. Permission Types

Each letter represents a specific capability:

r (Read): Permission to view file contents or list directory files.

w (Write): Permission to modify/delete files or add files to a directory.

x (Execute): Permission to run a file as a program or cd into a directory.

- (None): No permission granted for that specific slot.
