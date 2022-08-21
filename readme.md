# tra-slovnik-sk

A slovnik.sk from command line

## Description

Uses API calls of webpage [slovnik.sk](https://slovnik.aktuality.sk/) to translate between slovak and english.

## Example of use

### MAC

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
pip3 install -r ./requirements.txt
```

```
cd ./tra-slovnik-sk
```

```
sudo chmod +x ./tra
```

```
cp ./tra /usr/local/bin/tra
```
