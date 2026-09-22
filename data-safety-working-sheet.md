# BLOCKVERSE — Play Console Data Safety Working Sheet

Review against the exact production build before submitting.

## Relevant data
- Email address / Firebase account identifier — account management and authentication.
- Game scores, XP, level, coins, achievements and match history — gameplay and progression.
- Chat messages — private player communication.
- Multiplayer room/battle information — matchmaking and real-time battles.

## Storage/service
BLOCKVERSE uses Firebase services for authentication and cloud data storage.

## Deletion
BLOCKVERSE provides an in-app account-deletion path and an external web deletion resource.

## Important
If an advertising SDK such as AdMob is added to the production build, revisit the Data Safety answers before uploading that build.
