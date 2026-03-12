# TRQuant Server Restore Guide

## Repositories
- Core: git@github.com:ZhuTechLLC/TRQuant-202603-Core.git
- Docs: git@github.com:ZhuTechLLC/TRQuant-202603-Docs.git
- Backup: git@github.com:ZhuTechLLC/TRQuant-202603-Backup.git

## Baseline Tags
- Core: TRQ_CORE_BASELINE_20260312
- Docs: TRQ_DOCS_BASELINE_20260312

## Restore Steps
1. Clone Core, Docs, and Backup repositories into ~/trq/repo/
2. Restore Python environment from env_snapshots/requirements_lock.txt
3. Recreate SSH key and GitHub access if needed
4. Restore software installers from ~/trq/software/
5. Reconfigure local runtime paths and data directories
