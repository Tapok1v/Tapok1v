# RobloxTool

RobloxTool is a simple Python-based utility to manage the Roblox game process.  
It allows you to freeze, unfreeze, simulate lag, restart Roblox, and more — all via easy commands.

---

## Features

- Automatically detect and store the Roblox game process ID (PID)  
- Freeze and unfreeze the Roblox process to pause and resume the game  
- Simulate CPU lag on Roblox to create performance slowdowns  
- Restart Roblox directly from the tool  
- Clear stored PID and show current process info  
- Simple command-line interface with helpful command list  

---

## Usage

1. Run the program (`RT.exe` if compiled)  
2. Use commands to control Roblox:

| Command   | Description                          |
|-----------|------------------------------------|
| `sh`      | Automatically detect and store PID |
| `freeze`  | Freeze Roblox process               |
| `unfreeze`| Unfreeze Roblox process             |
| `lag`     | Simulate CPU load on Roblox        |
| `restart` | Kill and restart Roblox             |
| `clear`   | Clear stored PID                    |
| `info`    | Show stored PID                    |
| `help`    | Show list of commands               |
| `exit`    | Exit the tool                      |

---

## Requirements

- Python 3.x (if running from source)  
- [psutil](https://pypi.org/project/psutil/) library (automatically installed if missing)

---

## Installation

If you want to run from source:

```bash
pip install psutil
python RT.py
