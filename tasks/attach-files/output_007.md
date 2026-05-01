# Content Design Iteration 007

## Goal Analysis
The goal is to design a clear error state for when a file fails the malware scan:
- Inform the user that the file cannot be sent because it is unsafe.
- Provide a clear instruction on how to resolve the situation (remove and replace).
- Ensure the "Send" action remains blocked as long as an unsafe file is attached.

## Strategic Choice: Direct Guidance
Following the Guidance principle ("When errors occur, constructively suggest a solution"), the error state shouldn't just say "Failed." It needs to explain the implication (it's unsafe) and the remedy (remove it).

## Proposed Variation: Safety First

### Screen: Template details (Failed scan)
This screen shows how the UI handles a detected threat.

---

Templates > My email with an attachment

# My email with an attachment
[Edit name or content]

### Files
- (Error icon) document_with_malware.pdf — This file is unsafe and cannot be attached. (Remove x)
- report_of_safety.pdf (Remove x)

1 file failed, 1 file attached [Add files]

### Send your email
You cannot send this email while it contains unsafe files. Remove any files that failed the malware scan to continue.

( ) Send to one recipient
( ) Send to many recipients
( ) Upload a list of recipients

[Send test email]

---

## Design Principle Alignment: Guidance and Reliability
This iteration meets the Guidance principle by pointing the user toward the next step ("Remove any files that failed..."). It doesn't leave the user wondering why they are stuck.

It meets the Reliability principle by being a "tool that is error-free." By preventing the attachment of unsafe files, we protect both the sender’s reputation and the recipient’s security (Build trust with recipients).

The language is kept simple and non-technical ("unsafe" instead of "malicious signature detected") to ensure Clarity for all user mindsets. Senders in a Conservative mindset will value the certainty that the tool is keeping them in control and preventing a security breach.
