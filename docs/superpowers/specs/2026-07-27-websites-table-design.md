# Websites table + Amber Console — Design

Date: 2026-07-27  
Scope: GitHub profile `README.md` only

## Goal

Surface client websites you’ve built in a dedicated section, and list Amber Console among live projects.

## Changes

### 1. Live table

Add one row after the existing Live projects:

| Field | Value |
|-------|--------|
| Project | [Amber Console](https://github.com/DutchDiederik/AmberConsole) (HTML `<a target="_blank">` + bold, same as existing rows) |
| Description | Monochrome terminal CSS framework |
| Status | `![live v1.0.1](https://img.shields.io/badge/live-v1.0.1-brightgreen)` |

### 2. Building table

Unchanged.

### 3. New Websites section

Place directly below the Building section:

- Heading: `## 🌐 Websites`
- Columns: Project | Description | Status (same as Live/Building)
- Initial row:

| Field | Value |
|-------|--------|
| Project | [Poppy Cool](https://poppycool.nl) (HTML `<a target="_blank">` + bold) |
| Description | Air conditioning installation service |
| Status | `![live](https://img.shields.io/badge/live-brightgreen)` |

## Out of scope

- Moving or removing the top-of-file personal site links
- Changing Live/Building column structure
- Adding more client sites beyond Poppy Cool in this change

## Success criteria

- Amber Console appears in Live with correct link, description, and v1.0.1 badge
- Websites section appears below Building with Poppy Cool linked and described
- Markdown/HTML style matches existing README tables
