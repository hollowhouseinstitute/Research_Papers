# Exemplar Dataset: Structural Affective Signals

## Dataset Identifier
**Name:** structural_affective_signals_v1  
**Location:** `3_DATASETS/structural_affective_signals/`

---

## Purpose
This dataset provides a **minimal, controlled set of structural signals** used to demonstrate the full research pipeline defined in this repository.

The dataset exists to support:
- Protocol validation
- Analysis method demonstration
- End-to-end paper exemplars

It is not intended to support generalization beyond its documented scope.

---

## Alignment With Canonical Theory
This dataset is governed by the canonical theory defined in `1_THEORY/theory.md`.

Specifically:
- Data contains **structure only**, not interpretation
- No attribution of emotion, intent, or internal state is made
- All labels are descriptive, not inferential

---

## Data Description

### Data Type
- Textual stimuli
- Structural annotations
- Response traces

### Units of Observation
Each record consists of:
- A stimulus identifier
- A stimulus representation
- One or more structural response traces

No record contains semantic judgments.

---

## Dataset Structure

```
structural_affective_signals/
├─ README.md
├─ stimuli/
│  ├─ stimulus_001.txt
│  ├─ stimulus_002.txt
│  └─ ...
├─ responses/
│  ├─ response_001.json
│  ├─ response_002.json
│  └─ ...
└─ metadata.json
```

---

## Stimuli

Stimuli are **synthetic and controlled**.

Properties:
- Finite length
- No embedded narrative
- No personal or identifying content

Stimuli are not designed to evoke emotion; they are designed to test **structural sensitivity**.

---

## Responses

Responses capture **observable structural changes** only.

Examples of recorded properties:
- Token count changes
- Repetition patterns
- Latency or ordering differences

No response is interpreted as affect, emotion, or intent.

---

## Metadata

`metadata.json` records:
- Dataset version
- Creation date
- Protocol reference
- Known limitations

Metadata is descriptive and immutable.

---

## Protocol Compliance

This dataset complies with protocols defined in `2_PROTOCOLS/`:
- Dataset specification precedes analysis
- Freeze occurs prior to use
- Modifications require version increment

---

## Limitations

- Small scale by design
- Synthetic inputs only
- Not representative of real-world populations

These limitations are intentional.

---

## Permitted Uses

- Demonstration of analysis methods
- Reproducibility testing
- Exemplar paper development

---

## Prohibited Uses

- Psychological inference
- Emotional attribution
- Model training for deployment
- Claims beyond structural behavior

---

## Status

This dataset is **ACTIVE** and frozen for exemplar use.

