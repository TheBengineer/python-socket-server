# Python Game Server (Chess)

## Abstract

A Python approach for a small game server I made specificly for chess. Two proposed methods:

- The client-server approach: implementing Python ```socket```
- The local approach: a much more simpler method, by creating a basic game's handler using the same logic of the client-server approach.

## Method's detail

### Online:

1. Implementing socket communication method between three 'instance' or 'computer'
2. Available globally using: 
* Public IP address with Port Forwarding feature. 
Note that this method **requires** your ISP allowing Port Forwarding service for your router.
* VPN (such as ZeroTier)

### Offline:

- Just a game handler (with custom logic, rules, etc...) using normal Python or Jupyter.


## Dependencies

- `chess`: a Python-chess lib just making everything so much easier.
- `chess-board`: a library used for displaying chess game using PyGame.
- Installation using Pip
```
pip install chess
pip install chess-board
```00000000000000000
0112

12......................
## Usage

### Online
- Reconfigure setting (IP addresses, Port numbers) to your preferences
- Run the `socket_server.py` script then `socket_client.py`
- After the game's finished connection handling'll clear up by itself

### Offline
- Applied the two 'player' using custom Class or Library/ Package in its dedicated code cell.
- Run (using `Google Colab Notebook` or `Jupyter Notebook` will need slight changes)