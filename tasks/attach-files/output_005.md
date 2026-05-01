# Content Design Iteration 005

## Goal Analysis
The goal is to clarify the timing and impact of the malware scan:
- The scan happens after clicking [Attach to template].
- The file cannot be sent until the scan is complete and clean.
- We need to balance forward progress (efficiency) with the reality of the technical blocker (transparency/reliability).

## Strategic Choice: The "After" state
Since the scan happens after attachment, I am providing two views: the "Attach" screen (setting expectations) and the "Template detail" screen (where the send button is located and where the blocker actually manifests).

## Proposed Variation: Conditional Readiness

### Screen 1: Attach files (Pre-scan)
This screen sets the expectation that a scan will happen.

---

Templates > My email with an attachment

# Attach files
Upload up to 10 files. Recipients get these files as permanent copies in their inbox. They can keep them for as long as they need. 

Because recipients own the copies you send, you cannot change or delete them once the email is sent.

### File requirements
Together, your files must not exceed 6 MB. GC Notify will scan your files for malware after you attach them to this template.

| [Choose files]
| document_to_send.pdf

[Attach to template]

---

### Screen 2: Template details (Post-attach, Scanning)
This screen shows the actual impact: the Send button is disabled while scanning.

---

Templates > My email with an attachment

# My email with an attachment
[Edit name or content]

### Attachments
- document_to_send.pdf (Scanning for malware...)

We are checking your files for malware. You can send this email once the scan is complete.

( ) Send to one recipient
( ) Send to many recipients
( ) Upload a list of recipients

[Send test email]

---

## Design Principle Alignment: Guidance and Reliability
This iteration meets the Guidance principle ("Reduce my risks of making an error") by explicitly linking the scan status to the ability to send. 

It ensures Reliability for the sender by:
- Providing helpful wayfinding: The message "You can send this email once the scan is complete" explains exactly why they might be waiting.
- Setting expectations: Moving the scan mention to the first screen ensures the user isn't surprised when they see the scanning status on the second screen.

By allowing them to attach the file but blocking the send action, we follow the Efficiency principle (they can finish the attachment task) while maintaining Transparency about the technical requirement.
