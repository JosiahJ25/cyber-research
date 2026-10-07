# Knowledge Base: AI Security

## Chunk: ai-security-p1-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 1 | **Chunk Index:** 1

OWASP PDF v4.2.0a 20241114-202703
OWASP Top 10 for
LLM Applications 2025
Version 2025
November 18, 2024

---

## Chunk: ai-security-p2-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 2 | **Chunk Index:** 1

LICENSE AND USAGE
This document is licensed under Creative Commons, CC BY-SA 4.0. You are free to:
Share — copy and redistribute the material in any medium or format for any purpose,
even commercially. Adapt — remix, transform, and build upon the material for any purpose,
even commercially. The licensor cannot revoke these freedoms as long as you follow the license terms. Under the following terms:
Attribution — You must give appropriate credit, provide a link to the license, and indicate
if changes were made. You may do so in any reasonable manner, but not in any way
that suggests the licensor endorses you or your use. ShareAlike — If you remix, transform, or build upon the material, you must distribute
your contributions under the same license as the original. No additional restrictions — You may not apply legal terms or technological measures
that legally restrict others from doing anything the license permits. Link to full license text: https://creativecommons.org/licenses/by-sa/4.0/legalcode
The information provided in this document does not, and is not intended to constitute
legal advice. All information is for general informational purposes only. This document contains links to other third-party websites. Such links are only for
convenience and OWASP does not recommend or endorse the contents of the third-party
sites. REVISION HISTORY
2023-08-01 Version 1.0 Release
2023-10-16 Version 1.1 Release
2024-11-18 Version 2025 Release

---

## Chunk: ai-security-p3-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 3 | **Chunk Index:** 1

Table of Contents
Letter from the Project Leads  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
What’s New in the 2025 Top 10  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
Moving Forward  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2
LLM01:2025 Prompt Injection  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3
Types of Prompt Injection Vulnerabilities . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p3-c2
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 3 | **Chunk Index:** 2

. . . . . . . . . . . . . . . . . . . . 5
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6
Related Frameworks and Taxonomies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6
LLM02:2025 Sensitive Information Disclosure  . . . . . . . . . . . . . . . . . . . . . . . . . . 7
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
Common Examples of Vulnerability  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p3-c3
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 3 | **Chunk Index:** 3

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
LLM03:2025 Supply Chain  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
Common Examples of Risks . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
Prevention and Mitigation Strategies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
Sample Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p3-c4
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 3 | **Chunk Index:** 4

. . . . . . . . . . 15
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
LLM04: Data and Model Poisoning . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16
Common Examples of Vulnerability  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
LLM05:2025 Improper Output Handling  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p3-c5
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 3 | **Chunk Index:** 5

. . . . . . . . . . . . . . . 18
LLM05:2025 Improper Output Handling  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
genai.owasp.org

---

## Chunk: ai-security-p4-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 4 | **Chunk Index:** 1

Common Examples of Vulnerability  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
LLM06:2025 Excessive Agency  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
Common Examples of Risks  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p4-c2
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 4 | **Chunk Index:** 2

. . . . . . . 23
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 25
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 25
LLM07:2025 System Prompt Leakage  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
Common Examples of Risk  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 27
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p4-c3
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 4 | **Chunk Index:** 3

. . . . . . . . . . . . . . . . . . . . . . . . . . . 28
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28
LLM08:2025 Vector and Embedding Weaknesses . . . . . . . . . . . . . . . . . . . . . . . 29
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29
Common Examples of Risks  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31
LLM09:2025 Misinformation  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
Description  . . . . . . . . . . . . . . . . . . . . . . . . .

---

## Chunk: ai-security-p4-c4
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 4 | **Chunk Index:** 4

. . . . . . . . . . . . . . . . . . . . . . . 32
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
Common Examples of Risk  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 33
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
LLM10:2025 Unbounded Consumption  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35
Description  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35
Common Examples of Vulnerability . . . . . . . .

---

## Chunk: ai-security-p4-c5
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 4 | **Chunk Index:** 5

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35
Common Examples of Vulnerability . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35
Prevention and Mitigation Strategies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 36
Example Attack Scenarios  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37
Reference Links  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
Related Frameworks and Taxonomies  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
Appendix 1: LLM Application Architecture and Threat Modeling . . . . . . . . . . . . . 39
Project Sponsors  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40
Supporters . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41
genai.owasp.org

---

## Chunk: ai-security-p5-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 5 | **Chunk Index:** 1

OWASP Top 10 for LLM Applications v2.0
1genai.owasp.org
Letter from the Project Leads
The OWASP Top 10 for Large Language Model Applications started in 2023 as a community-driven
effort to highlight and address security issues specific to AI applications. Since then, the
technology has continued to spread across industries and applications, and so have the
associated risks. As LLMs are embedded more deeply in everything from customer interactions to
internal operations, developers and security professionals are discovering new
vulnerabilities—and ways to counter them. The 2023 list was a big success in raising awareness and building a foundation for secure LLM
usage, but we've learned even more since then. In this new 2025 version, we’ve worked with a
larger, more diverse group of contributors worldwide who have all helped shape this list. The
process involved brainstorming sessions, voting, and real-world feedback from professionals in
the thick of LLM application security, whether by contributing or refining those entries through
feedback. Each voice was critical to making this new release as thorough and practical as possible. What’s New in the 2025 Top 10
The 2025 list reflects a better understanding of existing risks and introduces critical updates on
how LLMs are used in real-world applications today. For instance, Unbounded Consumption
expands on what was previously Denial of Service to include risks around resource management
and unexpected costs—a pressing issue in large-scale LLM deployments. The Vector and Embeddings entry responds to the community’s requests for guidance on securing
Retrieval-Augmented Generation (RAG) and other embedding-based methods, now core practices
for grounding model outputs. We’ve also added System Prompt Leakage to address an area with real-world exploits that were
highly requested by the community. Many applications assumed prompts were securely isolated,
but recent incidents have shown that developers cannot safely assume that information in these
prompts remains secret. Excessive Agency has been expanded, given the increased use of agentic architectures that can
give the LLM more autonomy. With LLMs acting as agents or in plug-in settings, unchecked
permissions can lead to unintended or risky actions, making this entry more critical than ever.

---

## Chunk: ai-security-p6-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 6 | **Chunk Index:** 1

OWASP Top 10 for LLM Applications v2.0
2genai.owasp.org
Moving Forward
Like the technology itself, this list is a product of the open-source community’s insights and
experiences. It has been shaped by contributions from developers, data scientists, and security
experts across sectors, all committed to building safer AI applications. We’re proud to share this
2025 version with you, and we hope it provides you with the tools and knowledge to secure LLMs
effectively. Thank you to everyone who helped bring this together and those who continue to use and improve
it. We’re grateful to be part of this work with you. Steve Wilson
Project Lead
OWASP Top 10 for Large Language Model Applications
LinkedIn: https://www.linkedin.com/in/wilsonsd/
Ads Dawson
Technical Lead & Vulnerability Entries Lead
OWASP Top 10 for Large Language Model Applications
LinkedIn: https://www.linkedin.com/in/adamdawson0/

---

## Chunk: ai-security-p7-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 7 | **Chunk Index:** 1

OWASP Top 10 for LLM Applications v2.0
3genai.owasp.org
LLM01:2025 Prompt Injection
Description
A Prompt Injection Vulnerability occurs when user prompts alter the LLM’s behavior or output in
unintended ways. These inputs can affect the model even if they are imperceptible to humans,
therefore prompt injections do not need to be human-visible/readable, as long as the content is
parsed by the model. Prompt Injection vulnerabilities exist in how models process prompts, and how input may force
the model to incorrectly pass prompt data to other parts of the model, potentially causing them to
violate guidelines, generate harmful content, enable unauthorized access, or influence critical
decisions. While techniques like Retrieval Augmented Generation (RAG) and fine-tuning aim to
make LLM outputs more relevant and accurate, research shows that they do not fully mitigate
prompt injection vulnerabilities. While prompt injection and jailbreaking are related concepts in LLM security, they are often used
interchangeably. Prompt injection involves manipulating model responses through specific inputs
to alter its behavior, which can include bypassing safety measures. Jailbreaking is a form of
prompt injection where the attacker provides inputs that cause the model to disregard its safety
protocols entirely. Developers can build safeguards into system prompts and input handling to
help mitigate prompt injection attacks, but effective prevention of jailbreaking requires ongoing
updates to the model's training and safety mechanisms. Types of Prompt Injection Vulnerabilities
Direct Prompt Injections
Direct prompt injections occur when a user's prompt input directly alters the behavior of the
model in unintended or unexpected ways. The input can be either intentional (i.e., a malicious
actor deliberately crafting a prompt to exploit the model) or unintentional (i.e., a user
inadvertently providing input that triggers unexpected behavior). Indirect Prompt Injections
Indirect prompt injections occur when an LLM accepts input from external sources, such as
websites or files. The content may have in the external content data that when interpreted by

---

## Chunk: ai-security-p8-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 8 | **Chunk Index:** 1

OWASP Top 10 for LLM Applications v2.0
4genai.owasp.org
the model, alters the behavior of the model in unintended or unexpected ways. Like direct
injections, indirect injections can be either intentional or unintentional. The severity and nature of the impact of a successful prompt injection attack can vary greatly and
are largely dependent on both the business context the model operates in, and the agency with
which the model is architected. Generally, however, prompt injection can lead to unintended
outcomes, including but not limited to:
• Disclosure of sensitive information
• Revealing sensitive information about AI system infrastructure or system prompts
• Content manipulation leading to incorrect or biased outputs
• Providing unauthorized access to functions available to the LLM
• Executing arbitrary commands in connected systems
• Manipulating critical decision-making processes
The rise of multimodal AI, which processes multiple data types simultaneously, introduces unique
prompt injection risks. Malicious actors could exploit interactions between modalities, such as
hiding instructions in images that accompany benign text. The complexity of these systems
expands the attack surface. Multimodal models may also be susceptible to novel cross-modal
attacks that are difficult to detect and mitigate with current techniques. Robust multimodal-
specific defenses are an important area for further research and development. Prevention and Mitigation Strategies
Prompt injection vulnerabilities are possible due to the nature of generative AI. Given the
stochastic influence at the heart of the way models work, it is unclear if there are fool-proof
methods of prevention for prompt injection. However, the following measures can mitigate the
impact of prompt injections:
1. Constrain model behavior
Provide specific instructions about the model's role, capabilities, and limitations within the
system prompt. Enforce strict context adherence, limit responses to specific tasks or topics,
and instruct the model to ignore attempts to modify core instructions. 2. Define and validate expected output formats
Specify clear output formats, request detailed reasoning and source citations, and use
deterministic code to validate adherence to these formats. 3. Implement input and output filtering
Define sensitive categories and construct rules for identifying and handling such content. Apply semantic filters and use string-checking to scan for non-allowed content. Evaluate
responses using the RAG Triad: Assess context relevance, groundedness, and
question/answer relevance to identify potentially malicious outputs.

---

## Chunk: ai-security-p9-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 9 | **Chunk Index:** 1

OWASP Top 10 for LLM Applications v2.0
5genai.owasp.org
4. Enforce privilege control and least privilege access
Provide the application with its own API tokens for extensible functionality, and handle these
functions in code rather than providing them to the model. Restrict the model's access
privileges to the minimum necessary for its intended operations. 5. Require human approval for high-risk actions
Implement human-in-the-loop controls for privileged operations to prevent unauthorized
actions. 6. Segregate and identify external content
Separate and clearly denote untrusted content to limit its influence on user prompts. 7. Conduct adversarial testing and attack simulations
Perform regular penetration testing and breach simulations, treating the model as an
untrusted user to test the effectiveness of trust boundaries and access controls. Example Attack Scenarios
Scenario #1: Direct Injection
An attacker injects a prompt into a customer support chatbot, instructing it to ignore
previous guidelines, query private data stores, and send emails, leading to unauthorized
access and privilege escalation. Scenario #2: Indirect Injection
A user employs an LLM to summarize a webpage containing hidden instructions that cause
the LLM to insert an image linking to a URL, leading to exfiltration of the the private
conversation. Scenario #3: Unintentional Injection
A company includes an instruction in a job description to identify AI-generated applications. An applicant, unaware of this instruction, uses an LLM to optimize their resume,
inadvertently triggering the AI detection. Scenario #4: Intentional Model Influence
An attacker modifies a document in a repository used by a Retrieval-Augmented Generation
(RAG) application. When a user's query returns the modified content, the malicious
instructions alter the LLM's output, generating misleading results. Scenario #5: Code Injection
An attacker exploits a vulnerability (CVE-2024-5184) in an LLM-powered email assistant to
inject malicious prompts, allowing access to sensitive information and manipulation of email
content. Scenario #6: Payload Splitting
An attacker uploads a resume with split malicious prompts. When an LLM is used to evaluate
the candidate, the combined prompts manipulate the model's response, resulting in a
positive recommendation despite the actual resume contents. Scenario #7: Multimodal Injection
An attacker embeds a malicious prompt within an image that accompanies benign text. When

---

## Chunk: ai-security-p10-c1
**Source:** [NIST AI 100-2 E2025: Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf) | **Page:** 10 | **Chunk Index:** 1

OWASP Top 10 for LLM Applications v2.0
6genai.owasp.org
a multimodal AI processes the image and text concurrently, the hidden prompt alters the
model's behavior, potentially leading to unauthorized actions or disclosure of sensitive
information. Scenario #8: Adversarial Suffix
An attacker appends a seemingly meaningless string of characters to a prompt, which
influences the LLM's output in a malicious way, bypassing safety measures. Scenario #9: Multilingual/Obfuscated Attack
An attacker uses multiple languages or encodes malicious instructions (e.g., using Base64 or
emojis) to evade filters and manipulate the LLM's behavior. Reference Links
1. ChatGPT Plugin Vulnerabilities - Chat with Code Embrace the Red
2. ChatGPT Cross Plugin Request Forgery and Prompt Injection Embrace the Red
3. Not what you’ve signed up for: Compromising Real-World LLM-Integrated Applications
with Indirect Prompt Injection Arxiv
4. Defending ChatGPT against Jailbreak Attack via Self-Reminder Research Square
5. Prompt Injection attack against LLM-integrated Applications Cornell University
6. Inject My PDF: Prompt Injection for your Resume Kai Greshake
8. Not what you’ve signed up for: Compromising Real-World LLM-Integrated Applications
with Indirect Prompt Injection Cornell University
9. Threat Modeling LLM Applications AI Village
10. Reducing The Impact of Prompt Injection Attacks Through Design Kudelski Security
11. Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations
(nist.gov)
12. 2407.07403 A Survey of Attacks on Large Vision-Language Models: Resources, Advances,
and Future Trends (arxiv.org)
13. Exploiting Programmatic Behavior of LLMs: Dual-Use Through Standard Security Attacks
14. Universal and Transferable Adversarial Attacks on Aligned Language Models (arxiv.org)
15. From ChatGPT to ThreatGPT: Impact of Generative AI in Cybersecurity and Privacy
(arxiv.org)
Related Frameworks and Taxonomies
Refer to this section for comprehensive information, scenarios strategies relating to
infrastructure deployment, applied environment controls and other best practices. • AML.T0051.000 - LLM Prompt Injection: Direct MITRE ATLAS
• AML.T0051.001 - LLM Prompt Injection: Indirect MITRE ATLAS
• AML.T0054 - LLM Jailbreak Injection: Direct MITRE ATLAS

---

