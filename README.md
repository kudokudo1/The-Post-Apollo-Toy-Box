# Post-Apollo Toybox

A home for the deliberately playful parts of the Post-Apollo environment.

Toybox contains terminal toys, visual nonsense, screensavers, experiments,
and other things that may not be productive but are intentionally part of
the machine.

## Current toys

Locally preserved:

- `pipes.sh`
- Hollywood launcher

Externally installed:

- cbonsai
- astroterm
- cmatrix
- figlet
- Hollywood

## Ownership model

Local scripts and wrappers are preserved directly in `bin/`.

Fedora-managed applications are recorded by exact package version rather
than copying system binaries into Git.

Clean upstream source checkouts are recorded by repository and commit rather
than vendoring an entire third-party Git repository.

## Current live locations

    ~/.local/bin/pipes.sh
    ~/.local/bin/hollywood
    ~/.local/opt/hollywood

## Baseline hashes

    pipes.sh:
    59ba9cdb0620054e80fb0af981a6ecbe24478a35548dc356f0db082c3dd89de0

    hollywood launcher:
    983b97199b0ebe065b705b5e01f5703b51b475f59174181d7583645e488e84fb

## Development policy

Preserve first, clean later.

Future Toybox entries may include additional terminal art, animations,
screensavers, novelty commands, visual experiments, and small interactive
toys.
