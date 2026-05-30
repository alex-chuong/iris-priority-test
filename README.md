# Iris Priority Test Repository

**WARNING: TEMPORARY TEST REPOSITORY**

This repository is used for testing priority-based role selection in the Iris Gateway.
It will be deleted after testing is complete.

## Structure

roles/
├── common/
│   └── AGENTS.md          # Common fallback role (always included)
└── prism_engineer/
    └── AGENTS.md          # High-priority role (priority: 30)

## Testing

This repository is referenced in iris-gateway test configuration to verify:
1. Single role returns that role + common
2. Multiple roles return only highest priority + common
3. Priority-based selection works correctly

## Cleanup

This repository will be deleted once testing is verified.
