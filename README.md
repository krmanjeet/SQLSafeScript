# SQLSafeScript

SQLSafeScript is a developer utility tool that automatically generates SQL backup and rollback scripts from user-provided SQL statements. It aims to enhance data safety and integrity during database operations by preparing recovery-ready scripts for `INSERT`, `UPDATE`, and `DELETE` statements.

Whether you're deploying changes to production or working on test environments, SQLSafeScript helps you streamline SQL operations and reduce the risk of data loss.

🔧 Features
- Supports parsing of common `INSERT`, `UPDATE`, and `DELETE` SQL statements.
- Generates corresponding `ROLLBACK` and `BACKUP` scripts dynamically.
- Provides a user-friendly web interface for input and script generation.
- Allows script export in `.txt` format with metadata like author, ticket ID, and timestamps.


⚠️ Disclaimer

SQLSafeScript is a demo/utility project built for educational and experimental purposes. It does not cover all edge cases or complex SQL syntax variations. Use caution when applying the generated scripts in live or production environments.

Always review generated scripts before execution and test them thoroughly in non-production environments.

The authors are not responsible for any data loss, corruption, or issues caused by misuse of this tool.
