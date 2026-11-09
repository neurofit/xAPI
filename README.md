# neuroFit xAPI
neuroFit xAPI profile (v0)

## Verbs
Convention is that verbs are few, generic, reusable, and all past tense:
- Attended

In v0, the only verb is attended.

## Object
An object is a required element of an xAPI statement that accepts:
- Activity
- Agent
- Group
- StatementRef
- SubStatement

In v0, all objects are untyped activities.

# Standards
This project uses W3C standards: 
- W3 ID
  - w3id.org
- JSON-LD 1.1 (2020, w3.org/TR/json-ld11) that allows profile, path expansion
  - json-ld.org/playground lets you see how a document expands
- SKOS, the vocabulary for glossaries and controlled terms
  - inScheme
  - prefLabel
  - definition
  - exactMatch
- DoW's ADL (advanced distributed learning), vocabulary profile
  - https://adlnet.github.io/
  - github.com/adlnet/xapi-authored-profiles
- ILER (individual longitudinal exposure record)  / DOEHRS - IH
  - https://health.mil/iler
  - 
- VA Public Health Exposure Topics A-Z
  - https://www.publichealth.va.gov/exposures/topics
- Exposure Ontology (ExO)
  - Root classes: event, stressor, receptor, outcome
  - https://obofoundry.org/ontology/exo