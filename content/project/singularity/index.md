---
title: "AI Assistant to Find and Retrieve Patient Cohorts"
summary: "Helping AI developers find and access medical data 10x faster: an agentic search system that identifies patient cohorts across hospital systems from a natural-language query. Secured a partnership with an imaging informatics company."
tags:
  - AI
  - Agents
  - Entrepreneurship

authors:
  - William Bolton

date: "2025-07-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: "Smart"

url_video: "https://youtu.be/UtO0tg4Q4Vo"
---

AI developers need large volumes of specific, high-quality medical data to train and validate their models and to get them through regulatory approval. Hospitals hold that data, but often do not know exactly what they have or how good it is, so finding the right patient cohort turns into lengthy, expensive and opaque negotiations that serve neither side well.

This system tackles that problem with an LLM-driven agent that searches across a hospital's information systems, including imaging archives (PACS), electronic medical records and unstructured free-text reports, from a single natural-language query. A request such as "female, BMI under 25, more than two scans, subdural intracranial haemorrhage" is decomposed by a query planner into iterative DICOM and FHIR searches, grounded in clinical vocabularies such as SNOMED CT. The agent reconciles the results, validates every patient against the full set of constraints, and returns the cohort together with information on the quantity and quality of the available data.

Once suitable data is identified, developers can request access. Approved requests are extracted, de-identified and shared securely, with the healthcare provider keeping oversight of its data through a CRM-style view of requests. The aim is to cut the workload on hospital admin and IT teams while letting institutions make proper use of their data assets. The initial focus is radiology, where most medical AI development is concentrated, with plans to expand to other types of medical data.

A working prototype built on a hybrid synthetic and public dataset was used by potential customers, and a partnership was secured with an imaging informatics company.
