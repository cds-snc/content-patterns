# Content Design Iteration 006

## Goal Analysis
The goal is to align the design with the newly added template screen section:
- Integrate the file list section (with scanning spinner and remove option).
- Show the summary of files preparing/attached.
- Ensure the permanent ownership message is still clear.
- Explicitly block the "Send" action while files are "preparing" (scanning).

## Proposed Variation: Balanced Resource View

### Screen 1: Add files
This screen handles the initial selection and sets expectations for what happens next.

---

Templates > My email with an attachment

# Add files
Upload up to 10 files. Recipients get these files as permanent copies in their inbox. They can keep them for as long as they need. 

Because recipients own the copies you send, you cannot change or delete them once the email is sent.

File requirements:
- Together, your files must not exceed 6 MB.
- GC Notify scans your files for malware after you attach them.

| [Choose files]
| No files selected

[Attach to template]

---

### Screen 2: Template details (Scanning in progress)
This screen incorporates the new section layout and manages the "blocker" state.

---

Templates > My email with an attachment

# My email with an attachment
[Edit name or content]

### Files
- (Scanning spinner) document_to_send.pdf (Remove x)
- report_full_v1_final_final_3_version_final.pdf (Remove x)

1 file preparing, 1 file attached [Add files]

### Send your email
You cannot send this email while files are preparing. You can continue once the malware scan is complete.

( ) Send to one recipient
( ) Send to many recipients
( ) Upload a list of recipients

[Send test email]

---

## Design Principle Alignment: Clarity and Guidance
This iteration uses the Guidance principle ("Reassure me I am on the right path") by using clear labels for the file status:
- Using "preparing" to describe the scanning phase helps senders understand that the system is doing necessary work before a file is ready.
- Providing a specific reason why the "Send" section is inactive ("You cannot send this email while files are preparing") prevents confusion and reduces the need for support calls.

It meets the Transparency principle by:
- Showing the "Remove x" option: Giving senders immediate control if they accidentally attach the wrong file before it's even sent.
- Giving immediate feedback: The summary line "1 file preparing, 1 file attached" provides a quick snapshot of the template's state for skimmers (Efficiency).
