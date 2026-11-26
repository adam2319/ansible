Initial bare-OS setup, including my dotfiles and the tools I’ve created or collected.

## Usage

Run the playbook with sudo privileges using the following command:

```bash
ansible-playbook main.yml --ask-become-pass
```

## Tools

### General & Active Directory
* **kerbrute** [repo](https://github.com/Solo-Hacking/kerbrute) *(built from source with Go)*
* **gcc-mingw-w64** *(installed via apt for cross-compiling Windows binaries)*

### Web & Reverse Shells
* `iis-reverse-shell.aspx`
* `php-reverse-shell.php`
* `php-webshell`
* `windows-php-reverse-shell.php`
* `revshell_jenkins.groovy`

### Windows Tools

#### Exploits & Privilege Escalation
* **JuicyPotato** (`JuicyPotato.exe`) - [repo](https://github.com/Solo-Hacking/juicy-potato)
* **SweetPotato** (`SweetPotato.exe`) - [repo 1](https://github.com/Solo-Hacking/SweetPotato) | [repo 2](https://github.com/Solo-Hacking/SweetPotato_2)
* **RoguePotato** (`RoguePotato.exe`)
* **PrintSpoofer** (`PrintSpoofer.exe`)

#### PowerShell
* **nishang** - [repo](https://github.com/Solo-Hacking/nishang)
* **PowerSploit** - [repo](https://github.com/Solo-Hacking/PowerSploit)

#### Reverse Shells & Binaries
* **Netcat** (`nc.exe`, `nc64.exe`) - [download page](https://eternallybored.org/misc/netcat/)
* `windows-revshell.ps1`

#### Reconnaissance
* **Windows Exploit Suggester** (`windows-exploit-suggester.py`)
* **WES-NG** (Next-Gen Windows Exploit Suggester) - [repo](https://github.com/Solo-Hacking/wesng)
