# Content Design Iteration 009: French Translations

## Goal Analysis
The goal is to provide accurate and contextually appropriate French translations for the "Attach files" feature, following the terminology used in the existing [fr.csv](../../fr.csv).

## French Translations

| English (Source) | French (Target) |
| --- | --- |
| Templates | Gabarits |
| My email with an attachment | Mon courriel avec une pièce jointe |
| Add files | Ajouter des fichiers |
| Upload up to 10 files. Recipients get these files as permanent copies in their inbox. They can keep them for as long as they need. | Téléchargez jusqu'à 10 fichiers. Les destinataires reçoivent ces fichiers en tant que copies permanentes dans leur boîte de réception. Ils peuvent les conserver aussi longtemps qu'ils le souhaitent. |
| File attachments must be: | Les pièces jointes doivent être : |
| Text documents (.pdf, .doc, .docx, .odt, .rtf, txt) | Documents texte (.pdf, .doc, .docx, .odt, .rtf, txt) |
| Spreadsheets and data (.xlsx, .csv, .json) | Feuilles de calcul et données (.xlsx, .csv, .json) |
| Images (.jpeg, .jpg, .png) | Images (.jpeg, .jpg, .png) |
| Max 6 MB for all files combined. | Maximum de 6 Mo pour tous les fichiers combinés. |
| Choose files | Choisir des fichiers |
| 2 files selected | 2 fichiers sélectionnés |
| Filename.pdf | Nomdufichier.pdf |
| Remove | Supprimer |
| GC Notify will scan your files for malware after you attach them to this template. | Notification GC analysera vos fichiers pour détecter les logiciels malveillants après que vous les aurez joints à ce gabarit. |
| Attach to template | Joindre au gabarit |
| 1 file preparing, 1 file attached | 1 fichier en préparation, 1 fichier joint |
| This file is unsafe and was not attached. | Ce fichier n’est pas sûr et n’a pas été joint. |
| 1 file unsafe, 1 file attached | 1 fichier non sûr, 1 fichier joint |

## Design Principle Alignment: Clarity (Clarté)
- **Familiar concepts**: Used "Gabarits" as established in the existing codebase for consistency.
- **Direct instructions**: Translated technical terms like "malware" into "logiciels malveillants" and "unsafe" into "n’est pas sûr" to maintain clarity for all users.
- **Measurement**: Converted "MB" to "Mo" (mégaoctets) to follow French Canadian standards.
