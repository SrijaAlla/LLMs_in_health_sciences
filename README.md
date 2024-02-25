# NLP_LLM
NLP Project

##Training Data CTR
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

###Training Data Labels
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
    },
```
