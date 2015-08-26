# Criteria

The initial phase of the project led to the development of a broad set of criteria that impact end-user security and privacy.

The current phase of the project now aims to develop the metrics that can support the evaluation of such criteria and more broadly, support the esatablishment of ground truth about software that can be used to support evaluation of end-user security and privacy and other aspect regarding decision support around software.

The criteria below are referenced in the [ongoing development of the new open integrity metrics](/METRICS.md).

## {T} Policy

### {PV} Publicly Verifiable

 - {OPE} Open Source License [Yes/No - Link to the licence] / Software + Hosted Platform
   - The system has an open source license as defined by OSI (http://opensource.org/licenses/) or FSF (https://www.gnu.org/philosophy/license-list.html).

 - {DET} Deterministic build process [Yes/No - Link to the build instructions] / Software + Hosted Platform
   - The system can be compiled or built and consistently create the same binary files.

 - {OAU} Open audit agreement [Yes/Under NDA/No - Link to the agreement] / Software + Hosted Platform
   - The system developers allow any organisation to perform and publish an audit of their code.

 - {NDA} Audit with NDA [Yes/No - Link to the agreement]
   - The tool developers allow organisations to audit their tool under an non disclosure agreement.

### {TD} Transparent Development

 - {COD} Public code repository [Yes/No - Link to the repository or request]
   - The source code is publicly available on the internet.

 - {COR} Code available on Request [Yes/No - Link to the repository or request]
   - The source code is available on request.

 - {TRA} Public issue tracker - [Yes/No - Link to issue tracker]
   - There is an issue tracker publicly available to follow the development of the tool.

 - {ATR} Activity of issue tracker - [Yes/No < 6 months - Link to last issue post]
   - The most recent activity on the issue tracker occured in the past 6 months, as a reflection of the activity of issue posting and resolution.

 - {BUG} Bug releases - [Yes / No - Link to recent bug releases]
   - Regular publication of bug and bug fixes with new releases such as a changelog.

 - {ROA} Roadmap available - [Yes / No - Link to roadmap]
   - Availability of a roadmap indicating the priorities and schedule of the resolution of certain issues or the implementation of certain features.

### {ER} Externally Reviewed

 - {AUD} Audited - [Yes/No < 2 years - Link to audit announcement]
   - An audit has been known to be accomplished within the past 2 years.

 - {AUA} Audit available - [Yes/No - Link to audit document]
   - The audit document is publicly available on the internet.

 - {AUE} Experienced Auditor - [Yes/No - Link to auditor credentials]
   - The auditing organisation is reputed and experienced.

 - {AUA} Automated Audit - [Yes/No - Link to auditing tool]
   - The audit was performed by an automated process.

 - {AUR} Response to audit - [Yes/No - Link to fixes]
   - Have significant vulnerabilities, having an impact on security or privacy, identified during the audit been addressed through a fix or a published workaround?

 - {AUT} Timely response to audit - [Yes/No < 2 months - Link to fixes dates]
   - Have significant vulnerabilities, having an impact on security or privacy, identified during the audit been addressed within 2 months of the audit (through a fix or a published workaround)?

### {EP} Enforced Policies

 - {DOC} Significant policies documentation - [Yes/No - Link to policy documentation] / Platforms
   - Are the terms of use of the tool or the platform clearly documented and available?

 - {NOT} Notification of policy changes - [Yes/No - Link to policy change documentation] / Platforms
   - Are users of the tool or platform clearly informed about changes in the policy?

 - {TRA} Transparency report - [Yes/No - Link to transparency report] / Platforms
   - Is the organisation releasing a transparency report on government surveillance and interventions (indicating for example requests by LEA, third parties to take down, or disclose data or meta-data).

 - {JUR} Government compliance disclosure - [Yes/No - Link to disclosure] / Platforms
   - Is the organisation disclosing that they are subject to formal or informal jurisdictional liability to comply with government requests?

 - {BRE} Policy breach reports - [Yes/No - Link to breach report] / Platforms
   - Are breaches of policy documented?

### {NN} Net Neutral

 - {MIN} Minimal compliance with content filtering law - [Yes/No - Link to filtering policy or evidence] / Software + Platforms
   - Is the system filtering content that is not required by law in the jurisdiction where its operating?

 - {FNO} No opt-in content filtering - [Yes/No - Link to filtering policy or evidence] / Software + Platform
   - Is the system offering additional content filtering options not required by law?

 - {THR} No throttling and capping - [Yes/No - Link to throttling or capping policy or evidence] - Software + Platform
   - Does the system enforce data transfers throttling or throughput cap without user action?

 - [PRI] No content prioritisation - [Yes/No - Link to documentation] / Platforms
   - Does the platform accept or require payment for the prioritisation or placement of specific content, tiered pricing on the user side or paid SLAs? (This doesn't include payment for access to different performance tiers)

 - {NND} Non-neutrality Disclosure - [Yes/No - Link to disclosure or notifications] / Software + Platform
   - Is the content filtering documented and available? Are user notified of filtering updates?

### {SU} Sustainable Service Provision /

 - {BUI} Functional build tree - [Yes/No - Link to build tree] / Software + Platform
   - Availability of functional build tree.

 - {PRA} Practical to replicate - [Yes/No - Link to build instructions] / Software + Platform
   - Documentation for building binaries.

 - {ESC} Code escrow agreement - [Yes/No - Link to code escrow agreement] / Software + Platform
   - Commitment to release the code if the organisation fails to allow continuation of service provision.

 - {LRE} Legally replicable - [Yes/No - Link to license] / Software + Platform
   - Legally possible to replicate the platform.

 - {CON} Continuing Development [Yes/No < 6 months - Code Repo Last Commit] / Software + Platform
   - Last commit submitted within 6 months indicating an ongoing development of the tool.

## {S} Security

### {SD} Secure Distribution

 - {TLS} Secure Distribution by Default - [Yes/No - Link to TLS implementation documentation] / Software
   - The tool and any updates are distributed via encrypted channels by default.

 - {BIN} Binary authentication - [Yes/No - Link to binary authentication implementation documentation] / Software
   - The tool's integrity can be verified (through checksums…)

 - {UPD} Automatic updates - [Yes/No - Link to automatic updates] / Software
   - The tool automatically updates by default.

 - {SSL} SSL by default - [Yes/No - Link to implementation documentation] / Platform
   - The tool automatically uses encrypted channels for distribution of code and content.

 - {SSC} Correct SSL Implementation - [Yes/No - Link to implementation documentation] / Platform
   - The tool correctly implements SSL.

 - {PIN} HSTS or pinned SSL - [Yes/No - Link to implementation documentation] / Platform
   - The tool uses the HSTS protocol or uses SSL certificate pinning for distribution of code and content.

### {RM} Risk Management

 - {RIS} Visible risk disclosure - [Yes / No - Link to visible risk disclosure material] / Software + Platform
   - The tool alerts its users about risks associated with the tool's use.

 - {VUL} Visible vulnerability disclosure - [Yes / No - Link to recent vulnerability disclosure] / Software + Platform
   - The tool alerts its users about disclosed vulnerabilities.

 - {BUG} Bug reporting system - [Yes/No - Link to open bug reporting system] / Software + Platform
   - Users can submit bugs about the tool.

 - {TIM} Timely response to vulnerabilities - [Yes/No - Link to vulnerability disclosure and fix dates] / Software + Platform
   - Disclosed and significant vulnerabilities where fixed within 2 months.

 - [THR] Documented Threat Model - [Yes/No - Link to threat model documentation] / Software + Platform
   - Is there documentation of the threat model the tool is designed for?

### {FM} Failure Behavior

 - {FAO} Fail Closed - [Yes/No - Link to documentation on failure mode]
   - Does the system fail closed?

 - {FAI} Notification of security failure modes - [Yes/No - Link to notification implementation or examples] / Software + Platform
   - Users are alerted when security features are not in operation or failing.

 - {SDI} Disclosure of Insecure Distribution / Software + Platform
   - The tool notifies user when the distribution or updates are not secure or binaries don't authenticate.

### {DC} Documentation

 - {DOC} User Documentation / Software + Platform
   - Link to user documentation or user forum request about basic operation.

 - {LOC} Availability of localisation / Software + Platform
   - Link to localized user documentation and localised user interface for supported languages.

 - {SUP} Public user support / Software + Platform
   - Availability of a forum or email to request support.

 - {RES} Responsive to user help requests / Software + Platform
   - User support requests where addressed within 2 weeks.

### {UX} User Experience

 - {USA} Usability - [Yes/No - Link to usability reports] / Software + Platform
   - Target user base is able to successfully complete tasks.

 - {DUS} Documented usability design - [Yes/No - Link to usability documentation] / Software + Platform
   - Documentation of the approach to interface or user experience design indicating an effort to provide good user experience.

 - {PER} Sufficient Performance / Software + Platform
   - Indication of performance being satisfying for operating the tool under normal conditions.

### {DC} Security Posture

 - {DFC} Defensive coding - [Yes/No - Link to defensive coding implementation documents] / Software + Platform
   - Documentation of the approach to code defensively.

 - [DEP] Defence in Depth - [Yes/No - Link to defence in depth implementation documents] / Software + Platform
   - Does the system provide multiple layers of defence against potential threats?

 - [SED] Secure by Default - [Yes/No - Link to secure default implementation documentation] / Software + Platform
   - Does the tool have sensible secure defaults without needing additional hardening.

 - {DEC} Decentralised Architecture [Yes/No - Link to Decentralised architecture documentation] / Software + Platform
   - Platform or tool uses a decentralised architecture.

## {P} Privacy

### {IC} Identity Control

 - {OBS] End point obfuscation - [Yes/No - Link to end-point obfuscation strategy] / Software + Platform
   - Does the tool allow its user to not be identifiable through their network location?

 - {PER} Minimal personal data requirements - [Yes/No - Link to policy or documentation] / Software + Platform
   - Does the tool requires reasonable personal data?

 - {DEF} Private by default / Software + Platform
   - Does the tool provide privacy by default?

 - {TRF} Traffic analysis mitigation - [Yes/No - Link to traffic analysis mitigation documentation] / Software + Platform
   - Link to approach to resist traffic analysis.

### {DM} Data Minimization

 - {LOG} Aggregated anonymized logging - [Yes/No - Link to policy or documentation] / Software + Platform
   - Does the tool or platform logs aggregated anonymised data.

 - {DMF} Minimal logging by default / Software + Platform
   - Does the tool logs minimal amounts of data by default?

 - [RET] - Data retention compliance - [Yes/No - Link to policy or documentation] / Platform
   - Is the platform subject to data retention law.

 - [RED] - Data retention disclosure - [Yes/No - Link to policy or documentation] / Platform
   - Is the platform disclosing its data retention policy to its users. Does the organisation documents the data, meta-data that is being kept for technical or regulatory reasons.

 - {DMD} Public availability of aggregated anonymized logging / Software + Platform
   - Does the tool or platform publish aggregated anonymised data?

### {DS} Data Protection

 - {SHA} Personal data protected - [Yes/No - Link to policy or documentation] / Software + Platform
   - Does the tool protects personal data, i.e. does not share or disclose personal data?

 - {SHG} Aggregated data protected - [Yes/No - Link to policy or documentation] / Software + Platform
   - Does the tool protects aggregated data, i.e. does not share or disclose data in aggregates?

 - {SHD} Documented protection of user data - [Yes/No - Link to user data sharing documentation] / Software + Platforms
   - Does the organisation disclose how, when and for which purpose user data or meta-data will be shared with third parties (including monetization)

 - {MON} No monetization of user data - [Yes/No - Link to user data monetisation documentation] / Software + Platforms
   - Does the organisation refrain from selling user data to third parties?

### {CO} Confidentiality

 - {CRY} End to end encryption - [Yes/No - Link to implementation documentation] / Software + Platform
   - Does the tool encrypt communications end to end?

 - {PFS} Forward secrecy - [Yes/No - Link to implementation documentation] / Software + Platform
   - Does the tool provide forward secrecy.

 - {COF} Confidential by Default - [Yes/No - Link to implementation documentation] / Software + Platform
   - Does the tool offer confidentiality by default?

 - {COD} Disclosure of confidentiality failure modes. - [Yes/No - Link to implementation documentation] / Software + Platform
   - Does the tool alerts the user when confidentiality is not available?
