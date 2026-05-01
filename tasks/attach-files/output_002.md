# Content Design Iteration 002

## Goal Analysis
The goal is to inform senders about critical facts before they attach files:
- Files are sent "as is" and cannot be revoked/updated (recipient ownership).
- Technical constraints: 10 files max, 6 MB total limit.
- Supported file types.

## Proposed Variations

### Variation 1: Conventional Mindset
Focus: Clear instructions, standards, and in-task guidance. Focuses on the "how-to" and immediate constraints.

---

Templates > My email with an attachment

# Attach files to your email
Upload up to 10 files to send as attachments. Recipients get these files directly in their inbox.

### Before you upload
You cannot revoke or update files after they are sent. The recipient will keep the copy in their inbox indefinitely.

File requirements:
- Limit: Up to 10 files, maximum 6 MB in total.
- Documents: .pdf, .doc, .docx, .odt, .rtf, .txt
- Data: .xlsx, .csv, .json
- Images: .jpeg, .jpg, .png

| [Choose files]
| No files selected

[Attach to template]

---

### Variation 2: Conservative Mindset
Focus: Certainty, control, and reliability. Emphasizes the permanence of the action to ensure the sender is certain.

---

Templates > My email with an attachment

# Upload attachments
Ensure your files are final before uploading. Once sent, attachments cannot be deleted or changed because they are delivered directly to the recipient’s inbox.

### Requirements for your files
- Total size: All files must be under 6 MB combined.
- Quantity: Maximum of 10 files.
- Supported formats: PDF, Word (.doc, .docx), ODT, RTF, Text (.txt), Excel (.xlsx), CSV, JSON, JPEG, JPG, PNG.

| [Choose files]
| No files selected

[Attach to template]

---

### Variation 3: Explorative Mindset
Focus: Understanding the "why" and "how". Provides context about the recipient experience and the technical framework.

---

Templates > My email with an attachment

# Adding files to your notification
When you attach files, GC Notify delivers them as permanent copies to your recipients’ inboxes. This means you won’t be able to revoke access or update the files once the email is sent.

### Technical constraints
To ensure successful delivery, your attachments must meet these criteria:
- Total weight: Max 6 MB for all files combined.
- File count: Up to 10 individual files.
- Accepted types: 
  - Text: .pdf, .doc, .docx, .odt, .rtf, .txt
  - Data: .xlsx, .csv, .json
  - Images: .jpeg, .jpg, .png

| [Choose files]
| No files selected

[Attach to template]

---

## Design Principle Alignment: Transparency
All variations meet the Transparency principle by:
- Showing all steps/purpose: Explicitly stating that files are delivered "as is" and become the recipient's property.
- Helping facilitate dialogue: By warning that updates aren't possible, we help senders avoid errors that would require follow-up "correction" emails.
- Being clear about the purpose: The instructions move from just "how to upload" to "what happens when you do", setting realistic expectations for the sender.

Specifically, Variation 1 (Conventional) provides context of use by placing the "Before you upload" warning right before the action, reducing the risk of making an error (Guidance/Transparency).
