# tra-slovnik-sk

A slovnik.sk from command line

## Description

Uses API calls of webpage [slovnik.sk](https://slovnik.aktuality.sk/) to translate between slovak and english.

## Example of use

- open terminal
- write and confirm your query `tra plethora` or `tra bahno`
- get result

```
> tra plethora
EN-SK -- (plethora):
plethora - nadbytok červených krviniek, nadbytok

> ta bahno
SK-EN -- (bahno):
bahno - clarts, dirt bed, scurf, sleech, slop, morass, bog, mud, pulp, scum
```

## Installation

### MAC

```
git clone https://github.com/kamildemocko/tra-slovnik-sk.git
```

```
cd ./tra-slovnik-sk
```

```
pip3 install -r ./requirements.txt
```

```
sudo chmod +x ./tra
```

```
cp ./tra /usr/local/bin/tra
```

### WINDOWS

Add root folder, where the program will be cloned to PATH (start -> edit system env variables -> environment variables -> Path -> Add -> Path to folder)

```
git clone https://github.com/kamildemocko/tra-slovnik-sk.git
```

```
pip install -r ./requirements.txt
```

```
"@echo off && cd /d "D:\progs" && python tra-slovnik-sk\tra %*" > ..\tra.cmd
```

Now you can use command tra INPUT_WORD from cmd, powershell or terminal
