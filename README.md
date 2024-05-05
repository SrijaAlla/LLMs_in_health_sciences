# CSE 635
NLP Project

## Training Data CTR
```json
{
    "Clinical Trial ID": "NCT01537029",
    "Intervention": [
        "INTERVENTION 1: ",
        "  Doxorubicin and Cyclophosphamide",
        "  Doxorubicin: Dosed by the patient's treating physician according to local standard of care.",
        "  Cyclophosphamide: dosage form: IV, Dosage, frequency, and duration: According to local standard of care"
    ],
    "Eligibility": [
        "Inclusion Criteria:",
        "  WHO performance status 0 or 1",
        "Exclusion Criteria:",
        "  Participants unwilling to comply with study procedures.",
        "  CrCl < 10 ml/min"
    ],
    "Results": [
        "Outcome Measurement: ",
        "  Clearance (Cl) for Doxorubicin and Cyclophosphamide",
        "  Time frame: 0-48 hours",
        "Results 1: ",
        "  Arm/Group Title: Doxorubicin and Cyclophosphamide",
        "  Arm/Group Description: Doxorubicin: Dosed by the patient's treating physician according to local standard of care."
        
    ],
    "Adverse Events": [
        "Adverse Events 1:",
        "  Total: 0/15 (0.00%)"
    ]
}
```

## Training Data Labels
### Single
```json
   "40f1d3ce-2ff8-4177-9b11-0bf10b7f6591": {
        "Type": "Single",
        "Section_id": "Results",
        "Primary_id": "NCT00259090",
        "Statement": "the primary trial studies the impact of Fulvestrant, Anastrozole on Oestrogen Receptor H-score.",
        "Label": "Entailment",
        "Primary_evidence_index": [
            1
        ]
    }
```

### Comparison
```json
  "20545360-b2a1-4be9-997a-97040866b239": {
        "Type": "Comparison",
        "Section_id": "Eligibility",
        "Primary_id": "NCT00880464",
        "Secondary_id": "NCT00458237",
        "Statement": "Patients with AIDS are eligible for both the secondary trial and the primary trial.",
        "Label": "Contradiction",
        "Primary_evidence_index": [
            14,
            18
        ],
        "Secondary_evidence_index": [
            12,
            26
        ]
    }
```
