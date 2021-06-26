# bim
bim is a bin directory manager.

### Requirements
* Ubuntu
* git

### Usage
**install**
```bash
git clone https://github.com/3hacks/bim.git
echo "export PATH=\$PATH:/path/to/bim/bin" >> ~/.bashrc
```

**create new bin directory**
```bash
bim new <BIN DIR NAME>
```

**clone bin directory from github**
```bash
bim clone <BIN DIR NAME>
```

**pull all bin directories from github**
```bash
bim pull
```

**edit shell script in the bin directory**
```bash
bim edit <BIN DIR NAME> <SHELLSCRIPT NAME>
```

**save all bin directories**
```bash
bim save
```

**remove bin directory**
```bash
bim rm <BIN DIR NAME>
```

**show paths**
```bash
bim path
```

### LICENSE
MIT LICENSE
