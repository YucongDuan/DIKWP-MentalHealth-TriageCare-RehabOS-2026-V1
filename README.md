# DIKWP MentalHealth TriageCare RehabOS 2026 V1

A standalone offline-first reference prototype for mental-health triage preparation, care coordination, and recovery planning.

## Core workflow

Consent and privacy → red-flag safety gate → symptom/function evidence ledger → DIKWP case closure → 3-No diagnosis → action-level triage → professional care coordination → recovery and relapse prevention → family/community support → AI governance → Human Review Ticket → Care Passport.

## Critical boundary

This is not a diagnostic, prescribing, therapy, hospitalization, or emergency-response system. It never replaces psychiatrists, psychotherapists, emergency services, legal procedures, or local crisis resources.

## Quick start

Open `index.html` in a modern browser. No server, database, API key, model endpoint, or network is required.

Optional CLI:

```bash
python tools/run_triagecare.py examples/sample_case_crisis.json --out outputs
```

## Chinese name

DIKWP心理与精神疾病分诊、治疗协同与康复支持工作台
