# Aura privacy policy

Aura is a personal, single-user Oura data viewer operated by its owner. It is not an Oura product.

## What Aura accesses

With the owner's authorization, Aura requests Oura Cloud API V2 `daily`, `heartrate`, and `spo2` scopes to display sleep, readiness, activity, heart rate, and blood oxygen information. Oura processes ring data under its own privacy policy before Aura receives it.

## Storage and sharing

Aura stores OAuth credentials and a recent health-data snapshot in owner-only files on the owner's Mac. The owner's browser receives this data through an encrypted SSH tunnel between their PC and Mac. Aura does not transmit it to AI providers, analytics services, ad networks, or other third parties. The app uses local assets and does not sell data. The Oura API connection necessarily sends authorization and requests to Oura's servers.

Exports or backups made by the owner remain under their control. The owner controls physical access, operating-system accounts, browser extensions, and any backups of these devices.

## Retention and deletion

The owner may revoke Aura's access in their Oura account. They may delete Aura's local OAuth tokens and snapshots from `~/.config/aura/oura/` on their Mac. Aura does not maintain a separate cloud account or server-side database for Oura API data.

## Contact

For this single-user personal integration, contact the application owner via the contact email listed in the Oura developer application. This policy may be updated in this repository if Aura's behavior changes.
