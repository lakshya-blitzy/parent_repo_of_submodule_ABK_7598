# Parent Repository — Submodule Scan Fixture

..

This repository is intentionally metadata-only. It contains no application source and no tests of its own.

The application code lives in two independent Git submodules:
- `services/customer-orders-api` — Python/FastAPI customer and orders service
- `services/warehouse-catalogue-api` — JavaScript/Express inventory and shipment service

Expected scan behaviour: analyse this parent as a repository with no directly owned testable application behaviour, while discovering the two submodule gitlinks and analysing each child repository at the exact commit pinned by the parent.
