
# Appendix A — Evaluation Codebook
## XAI Cybersecurity Thesis — Bibek Adhikari & Tanya Jha
## Metropolia University of Applied Sciences, 2026

The following tables present the full scoring rules, evidence criteria, and worked examples for each of the five explainability 
dimensions used in this study. Each dimension is scored on a three-point scale where 1 indicates absent or weak explainability, 2 indicates partial explainability, and 3 indicates strong 
explainability.

**Evidence weighting rule:** 
Where vendor documentation and practitioner reviews provided conflicting evidence, greater weight was assigned to practitioner reviews as they reflect real deployment 
experience rather than intended design. Where documentation did not describe a specific feature or capability, whether related to explanation format, visualisation, confidence scoring, contextual 
enrichment, or model reasoning, the absence of that information was recorded as evidence that the feature was not disclosed to analysts, 
rather than as a gap in the evaluation process.

## D1: Textual Explanations

| Score | Verdict | Evidence Criteria | Worked Example |
|---|---|---|---|
| 1 | Absent or Weak | No plain-language explanation present. Output consists of raw log data, rule IDs, or technical codes only. | Wazuh displays rule ID 5710 and a raw syslog string. No natural language description is provided. |
| 2 | Partial | A short label or category name is present but lacks sufficient detail to act without further investigation. | A tool displays "Brute Force Detected" with no description of affected assets, attack context, or recommended response. |
| 3 | Strong | Complete plain-language explanation identifying affected assets, describing suspicious behaviour, and suggesting a next action, all presented within a single view. | Darktrace Cyber AI Analyst produces a full narrative identifying the device, the anomalous behaviour, and a recommended action. |

## D2: Visual Explanations

| Score | Verdict | Evidence Criteria | Worked Example |
|---|---|---|---|
| 1 | Absent or Weak | No incident-specific visualisation present. Interface is text-only or displays only raw log tables. | Wazuh alert detail view shows a table of log fields with no accompanying diagram, timeline, or graph. |
| 2 | Partial | Basic charts showing alert counts or severity distribution are present but do not depict the progression of a specific attack. | Microsoft Defender for Cloud displays a Secure Score dashboard and compliance charts but does not show the sequence of an active incident. |
| 3 | Strong | Incident-specific visualisation showing attack flows, affected assets, or event timelines comprehensible to a Tier-1 analyst. | Darktrace displays an interactive attack timeline connecting the initial anomaly, lateral movement, and data exfiltration stages. |

## D3: Confidence Information

| Score | Verdict | Evidence Criteria | Worked Example |
|---|---|---|---|
| 1 | Absent or Weak | Binary or unexplained severity labels only. No numeric score or justification provided. | Proofpoint assigns a message disposition of "malicious" or "clean" with no accompanying score or explanation. |
| 2 | Partial | A numeric score or severity rating is present but the tool does not explain what drives it or what threshold should prompt action. | Darktrace displays a threat score of 78/100 but does not disclose which behavioural signals contributed to this value. |
| 3 | Strong | Well-defined confidence score accompanied by an explanation of contributing factors and thresholds. | CrowdStrike Falcon discloses four contributing factors for each verdict, allowing the analyst to understand why the score was assigned. |

## D4: Contextual Information

| Score | Verdict | Evidence Criteria | Worked Example |
|---|---|---|---|
| 1 | Absent or Weak | Alerts presented in isolation with no asset identity, user history, or environment-specific relevance. | A tool displays an alert with only an IP address and no information about whether the asset is critical or its history. |
| 2 | Partial | Basic context such as a hostname or generic MITRE ATT&CK tag is present but is not environment-specific. | A tool maps an alert to MITRE T1110 but provides no information about the specific asset's role or history within the organisation. |
| 3 | Strong | Rich environment-specific context including identification of known assets, their roles, historical behaviour, and exposure. | Darktrace identifies the affected device by hostname, flags it as a previously unseen connection pattern, and links it to the device's historical behaviour baseline. |

## D5: Reasoning Transparency

| Score | Verdict | Evidence Criteria | Worked Example |
|---|---|---|---|
| 1 | Absent or Weak | Complete black box. The analyst cannot determine what features, rules, or thresholds caused the alert. Vendor documentation confirms model logic is proprietary. | Proofpoint's whitepaper explicitly states that its detection models are closed and scoring logic is not disclosed. |
| 2 | Partial | The tool identifies the detection type or references a threat framework but does not expose specific feature signals, model weights, or detection thresholds. | Darktrace references its unsupervised self-learning model but does not disclose which specific features or thresholds triggered any individual alert. |
| 3 | Strong | Full model reasoning visible. The tool discloses which features influenced the detection, how normal behaviour was defined, and why the specific event crossed the detection threshold. | No evaluated tool achieved Score 3. This score is retained as a theoretical benchmark. Its absence across all six commercial tools is the primary finding of this study. |
