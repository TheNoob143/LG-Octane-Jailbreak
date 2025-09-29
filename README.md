# LG Octane (VN530) — Research & Analysis Repository

**Purpose:**  
This repository collects archival resources, research notes, analysis tool outputs, and non-destructive guidance for people researching the LG Octane (VN530) and other BREW-era feature phones. It is *not* a how-to for bypassing device/carrier protections or flashing unsigned firmware.

**Scope & Intent**
- Collect and preserve links to old firmware archives, forum threads, and tooling (for historical/research purposes).
- Provide reversible, non-destructive analysis examples (binwalk, strings, metadata extraction).
- Host community notes, write-ups, and safe experiments (filesystem exploration, media extraction, hidden menus).
- **Do not** include or request step-by-step instructions to circumvent carrier locks, flash unsigned firmware, modify IMEI, or otherwise bypass security protections.

> ⚠️ **Safety & Legal Disclaimer**  
> Tinkering with phone firmware can brick devices permanently and may violate terms of service or local laws in some jurisdictions. This repository **does not** provide instructions for bypassing protections. Contributors and readers are responsible for ensuring their activities are legal where they live. Use sacrificial hardware and keep backups.

---

## Recommended workflow (non-destructive, research-first)
- **Windows (device-facing):** for running legacy tools that require Windows drivers (BitPim, QPST for read-only diagnostics, vendor tools). *Use only to pull archives or permissioned exports — do not push untrusted firmware.*  
- **Linux (analysis):** use Arch/Ubuntu for detailed analysis: `binwalk`, `radare2`, `ghidra`, `strings`, `hexdump`, `xxd`. Keep all dumps immutable and checksummed.

---

## Repo layout (suggested)
