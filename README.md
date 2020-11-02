Anible-bingo
============

List of greatest WTF in Ansible.

How to play
===========
Read the code (bingo.yaml). Make written predictions for each 'bingo' before running it.

Predictions to choose from for each 'bingo':

* green/ok (prints 'hello world')
* brown/changed
* cyan/skip
* nothing (premature play termination)
* red/error: wrong module parameter
* red/error: Jinja: incorrect template
* red/error: Jinja: recursion too deep error
* red/error: Jinja: undefined variable
* red/error: module-level trace
* ansible-level crash/trace
* python segmentation fault
* reboot

Run ansible-playbook bingo.yaml --tags bingo1.
Repeat for bingo2, 3, etc.

Try to undestand 'why?'. Give up.
