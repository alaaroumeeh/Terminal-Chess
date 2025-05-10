Project: Terminal Chess
Objective: Play chess in the console over a network without rules.

Usage:
  python [White|Black].py [listen|connect]
  - listen: option to listen for connection first.
  - connect: option to connect to a listener first.
  To run sucessfully, run either White or Black scripts with "listen" first on one node,
  then run the other script with "connect" on another node.

  Needed input:
    - your listener IP address
    - your listener port number
    - opponent's IP address
    - opponent's port number
  and lastly:
    - column shape character

  While playing, it's important to specify the current and next piece location correctly.
  This is done using the grid notation (e.g g8 f6).
  Piece type specification doesn't matter at all.

Disclaimer:
  This is only a fun application of chess in console, it's not fit for any usage but fun,
  because it's both impractical and so technical for a user.
  Has been re-published only to be in memory of the 2021-2022 lonely computer training days.

  Alaa Roumeih. March 26, 2022 (re-published May 10, 2025).
