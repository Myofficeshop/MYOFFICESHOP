# Connectors

## Project folder
Access: read/write
May do: read and update project files, skills, specs and design documentation.
Must never do: add secrets, credentials or irreversible production changes without review.

## Website / index.html
Access: read/write
May do: edit the static website when changes are traceable to the current principles and specs.
Must never do: publish invented product facts, pricing, stock or legal claims.

## eMAG
Access: read-only for design work unless a separate integration task explicitly requires a write.
May do: use verified listing information as source data.
Must never do: change live offers, customer data or marketplace settings as part of a design pass.

## TeoShip
Access: read-only for design work.
May do: reference the intended operational flow and terminology.
Must never do: send live orders, change stock or create AWBs during a design task.

## Live customer data
Access: never.
May do: use anonymized examples.
Must never do: expose names, addresses, phone numbers, payment data or other personal data.

## Rule
Use the weakest permission that still allows the task. A screenshot is enough for critique. A live connection is only justified when something must actually be changed.
