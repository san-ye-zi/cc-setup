# CC Setup

<a id="quick-start"></a>
## Quick Start

### Option 1: Direct Installation (Recommended)
Simply add command files directly to your project's `.claude/commands/` folder:

```bash
# Create the commands directory in your project
mkdir -p .claude/commands

# Download specific commands you need
curl -o .claude/commands/<namespace>:<command>.md https://raw.githubusercontent.com/san-ye-zi/cc-setup/main/.claude/commands/<namespace>:<command>.md

```

### Option 2: Install All Commands
Use our installation script to set up all commands at once:

```bash
git clone https://github.com/san-ye-zi/cc-setup.git
cd cc-setup
chmod +x install.sh
./install.sh
```
