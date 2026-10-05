# Product Loop

## Trigger
A Romanian office buyer arrives on MYOFFICESHOP to find copier paper for the office.

## Context
The user is looking for copier paper for a Romanian office and needs a direct route to the current offer details. The current repository does not verify the exact listing title, package quantity, price, stock or delivery terms.

## Core action
Open the linked eMAG page for the A4 copier paper offer, verify the product and current terms there, and continue with the marketplace purchase flow.

## One-step rule
Remove one unnecessary decision from the path: the user should not have to search for the product again after deciding what they want.

## Screen
The proof screen in `index.html` presents one A4 copier-paper offer, states that purchase happens on eMAG, and keeps the listing verification checklist beside the outbound CTA. It does not claim an unverified package size, price, stock status or delivery promise.

## Feedback
The CTA names eMAG and opens the linked listing in a new tab. Supporting copy tells the user to verify listing details and complete the purchase on eMAG.

## Stop condition
Stop the flow when the user has been sent to the correct eMAG listing. Do not simulate checkout on MYOFFICESHOP.

## Refused mechanic
Do not add a second primary CTA that creates a fake on-site checkout path. The site is currently a discovery/decision layer, not the transactional checkout.

## Review target
The screen must make the paper offer, destination and next action obvious. Quantity and product specifications must be verified on eMAG before they are presented as facts on MYOFFICESHOP.
