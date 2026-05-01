# Content Design Iteration 004

## Goal Analysis
The goal is to inform senders about the malware scan process without slowing them down:
- Files must pass a malware scan before being sent.
- The scan happens after upload but shouldn't block the user from proceeding with the form.
- Informing them early helps set expectations (Transparency).

## Strategic Choice: Where to show this information
Following the Efficiency principle ("Help me be fast and efficient"), the information is placed as a status update rather than a pre-requisite block. This allows the user to click "[Attach to template]" while the scan is potentially still running in the background.

## Proposed Variation: Process Transparency
This version adds a scanning status to the file list, ensuring the user is reassured they are on the right path (Guidance) without being blocked.

---

Templates > My email with an attachment

# Attach files
Upload up to 10 files. Recipients get these files as permanent copies in their inbox. They can keep them for as long as they need. 

Because recipients own the copies you send, you cannot change or delete them once the email is sent.

### File requirements
Together, your files must not exceed 6 MB. GC Notify scans all files for malware before they are sent to your recipients.

| [Choose files]
| document_to_send.pdf
| [ Scanning... ]

[Attach to template]

---

## Design Principle Alignment: Efficiency and Transparency
This iteration meets the Efficiency principle by not forcing the user to wait for the scan to finish before clicking the primary action button. We "only ask what is necessary" at each step.

It meets the Transparency principle by:
- Giving immediate feedback: The "Scanning..." status shows the system is working.
- Setting realistic expectations: By mentioning the scan in the requirements section, we explain a potential delay or a reason why a file might eventually fail to send.

By placing the scan mention near the file requirements, we provide context of use (Guidance) without creating a "stop" moment in the user's flow.
