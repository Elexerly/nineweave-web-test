Lexerly TEST CLIENT only. Do not replace the production website with this folder.

At Patrick's explicit request, this separate test client connects to the working LIVE Nineweave API and database at https://nineweave.grok.me. Existing email-code sign-in and existing player accounts are used. Account changes and match results are real shared game data, not disposable isolated test data.

The client pack/source and all video assets are unchanged by this routing update. The explicit HTTPS API configuration is read before Godot starts. No production site files, database credentials or migrations were changed.

Pending server compatibility: live API must accept jb_circuit/jb_rocker and Prof26/JB2026 before testing those new character unlocks online. Existing characters/accounts remain supported.
