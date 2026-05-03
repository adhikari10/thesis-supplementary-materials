# Supplementary Theoritical Analysys
## Trust Caliberation and Transparency Gaps: Section 5.5

This document presents the extended theoretical interpretation of the transparency gap findings reported in Section 5.5 of the 
thesis, examining implications for analyst trust calibration, alert fatigue, and SOC effectiveness.

## Trust Caliberation Theory
These explainability trends directly affect trust calibration as conceptualised by Lebiere et al. (2021) who established that calibrated trust builds progressively through repeated interaction and relies on the availability of clear and informative explanation signals. The consistent maximum of 2 on reasoning transparency across all commercial tools means that Tier-1 analysts in SME environments receive minimal or no information about how alerts were generated. This made it difficult for analysts to form accurate mental models when to trust or challenge an AI-generated alert. 
This disconnect between the inaccessibility of commercial AI reasoning and the explanatory cues analysts need to develop trust creates the conditions for both overtrust, defined as excessive reliance leading to dismissal of valid detections and undertrust, defined as insufficient reliance leading to dismissal of valid detections both of which Lebiere et al. (2021) identified as damaging to SOC effectiveness. Rastogi et al. (2025) confirmed this through evidence-based research, finding that insufficient model-level explainability was the main obstacle to analyst trust, with security professionals explicitly naming the lack of explanation for confidence scores and attack attribution as critical gaps. The low D3 scores observed across five of six commercial tools directly align with these expressed practitioner requirements. Nobles (2022) also confirmed that sustained opacity or a lack of transparency contributed to alert fatigue and even burnout. This reinforced that the transparency gaps identified in this study extended beyond tool capability gaps. They represented quantifiable operational risks tied to human performance, with direct implications for the Tier-1 SME analyst persona defined in Section 2.5. 


### References
Lebiere, Christian; Blaha, Leslie M.; Fallon, Corey K. & Jefferson, Brett. 2021. Adaptive Cognitive Mechanisms to Maintain Calibrated Trust and Reliance in Automation. Frontiers in Robotics and AI. Vol. 8, Article 652776. DOI: 10.3389/frobt.2021.652776.
Rastogi, Nidhi; Dhanuka, Devang; Saxena, Amulya; Mairal, Pranjal & Nguyen, Le. 2025. Survey Perspective: The Role of Explainable AI in Threat Intelligence. SIGIR Symposium on IR in Practice (SIRIP). Padua, Italy. July 13–18, 2025. arXiv:2503.02065.
Nobles, Calvin. 2022. Stress, Burnout, and Security Fatigue in Cybersecurity: A Human Factors Problem. Holistica Journal of Business and Public Administration. Vol. 13, No. 1, pp. 49–72.
