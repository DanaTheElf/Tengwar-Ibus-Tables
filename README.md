# Tengwar-Ibus-Tables
Ibus Input Method tables for typing with Tengwar on a Latin-Alphabet keyboard.

Currently contains a General Mode solution only.

# Installation
Ensure Ibus is installed with

  sudo apt install ibus ibus-table

You can add or update the Tengwar table with

  sudo ibus-table-createdb -n /usr/share/ibus-table/tables/IM-Tengwar-General.db -s **/PATH/TO/FILE/**IM-Tengwar-General.txt
  
  ibus restart
