# Mastermind

### Setup

Setup is easy, once the git repository is cloned.

0. Make sure you are running `python 3.6.1`
1. Make sure you have permission to execute the file, using `chmod +x`.
2. Optionally, link `mastermind.py` to one of the directories in your path.
    - I will be using `/usr/local/bin`

```bash
$ ln -s "$(pwd)/mastermind.py" /usr/local/bin/mastermind
```
### Gameplay

1. Type `mastermind` into the command prompt.
    - If you did not link `mastermind.py` to part of your path, you will need
      to be in the directory of `mastermind.py`, and type `./mastermind.py`.
2. Optionally, you can select difficulty by typing `-d <num>`, where <num> is a
    number 1-9, before pressing enter.
3. Input a 4-digit number after the `> ` prompt.
4. Every asterisk printed after your inpu represents one correct number in the
    right place, but you won't know which is which.