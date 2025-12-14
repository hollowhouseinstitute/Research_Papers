# Text Extraction Scripts

This document specifies best practices for extracting text from source materials for analysis.

Extraction is a *lossy operation* and must be treated as such.

---

## 1. Acceptable Sources

Text may be extracted from:
- Documents
- Transcripts
- Logs
- Structured datasets

Extraction from private or sensitive materials must follow ethical guidelines.

---

## 2. Extraction Principles

Scripts should:
- Preserve ordering
- Preserve segmentation
- Avoid normalization unless specified
- Log all transformations

---

## 3. Required Metadata

Every extracted file must include:
- Source identifier
- Extraction method
- Timestamp
- Operator

---

## 4. Validation

After extraction:
- Compare random samples to source
- Check for truncation
- Check for encoding errors

Extraction errors invalidate downstream analysis.

---

## 5. Non-Goals

Extraction does not:
- Interpret meaning
- Assign labels
- Clean “undesirable” content

All interpretation occurs later.
