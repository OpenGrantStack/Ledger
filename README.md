📘 Ledger Repository

This is the core engine behind OpenGrantStack's contribution tracking system. It powers the normalization, ingestion, and mapping of GitHub events into structured, audit-ready ledger entries.

🔧 Purpose

Ingest GitHub events from the Master App

Normalize contribution data

Map contributions to grants, teams, and workflows

Provide APIs for internal services

Maintain ledger integrity and audit logs

📁 Structure

ledger/
├── schema/              # Ledger data models and validation
├── ingestion/           # Event ingestion logic
├── mapping/             # Grant and contributor mapping
├── api/                 # Internal API endpoints
├── tests/               # Unit and integration tests
├── ci/                  # Continuous integration configs
└── README.md            # This file

🔐 Security

All ledger entries are immutable

Events are signed and timestamped

Internal access only via secure APIs

📄 License

Apache 2.0

🤝 Maintainers

See CODEOWNERS for current maintainers and reviewers.

# Ledger
