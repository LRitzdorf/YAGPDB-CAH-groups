# YAGPDB-CAH-groups
Make groups of card packs for YAGPDB Cards Against Humanity games!

## Setup
This repo contains a set of custom commands for use with [Yet Another General Purpose Discord Bot (YAGPDB)](https://yagpdb.xyz).

Each command has a corresponding text file. To set up the command system, follow these steps:
1. Find the Custom Commands section of the YAGPDB Control Panel (under `Core > Custom Commands` in the left sidebar).
1. (Optional but recommended) Create a new custom command group (by clicking the plus icon next to the `Ungrouped` tab). Set the desired permissions for this group of commands.
1. Hit `Save group settings`, then `Create a new Custom Command` (the two big green buttons at the bottom of the page).
1. Pick a text file from this repository to start with.
 1. Choose `Command (mention/cmd prefix)` as the `Trigger type`.
 1. Set the command's trigger to the name of the file you just chose (without the `.txt` ending).
 1. Paste the contents of the file into the command's `Response` box.
1. Repeat for all other text files in this repo.
1. Test it out!

## Troubleshooting
Since this is premade code, it should "just work."
However, if things go wrong or don't work at all, try rechecking the permissions (for the group as well as the individual command), or re-paste the code into the `Response` box.
