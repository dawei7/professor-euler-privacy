# Privacy policy - Professor Euler

Last updated: 19 September 2026

## Who provides the app
Professor Euler is a free, non-commercial mathematics study app for adults aged 18 and older, created by David Schmid. Contact: ai.professor.euler@gmail.com. This policy describes the Android app; Google Play and services you choose to use have their own policies.

## Work stored on your device
The app stores local profile names, reading progress, review notes, exercise drafts, handwriting, drawings, PDF annotations, submitted answers, AI feedback, chats, settings and a daily AI request count. Profiles are local and do not create an online account. The developer does not receive this work automatically. Avoid putting personal or sensitive information in work you intend to send to an AI service.

## Optional AI features: Google Gemini and DeepSeek
Reading, drawing and local progress do not need an AI connection. You choose Google Gemini or DeepSeek in Settings and supply your own API key for that provider. When you use Grade all, AI solutions or chat, the app sends relevant questions or textbook excerpts, messages, selected handwritten work/images, and conversation or grading context directly to the selected provider over HTTPS. Applying a provider/key choice also sends synthetic sample images and test prompts to check suitability. The provider receives connection metadata such as your IP address. The developer does not operate an intermediary grading server.

Google processes Gemini requests under its API terms and privacy policies. The app requires Google's eligibility and active-billing declaration while Gemini is selected; this declaration is not a requirement for DeepSeek. Retention, human review and use to improve models depend on the provider's service terms, account and location. Consult https://ai.google.dev/gemini-api/terms and https://policies.google.com/privacy before using Gemini.

DeepSeek requires a paid API key. DeepSeek processes the content sent to its API under the terms applicable to your account. Review https://platform.deepseek.com/ and its linked service and privacy terms before enabling it. DeepSeek's published privacy policy describes processing and storage in the People's Republic of China: https://cdn.deepseek.com/policies/en-US/deepseek-privacy-policy.html . Do not submit personal or sensitive information in your study work. The app cannot verify your provider billing or regional eligibility, control provider retention or training practices, or delete copies retained by a provider.

Each provider's eligibility, regional restrictions and charges apply. Availability of this offline app in a country does not guarantee that either AI provider can be used there. AI can make mistakes and is not a formal assessment authority.

## Adult eligibility
Before entering the app, you are asked to confirm that you are 18 or older. While Gemini is selected, an additional declaration covers Google's age, regional and active-billing requirements. These declarations are stored locally. The app does not collect a birth date or identity document and does not claim to verify your age. It is not intended for children or other users under 18.

## Reporting an AI response
If you choose Report AI response and then Send report, the selected AI response (up to 32,000 characters), reason, optional note, app version and a random report reference are sent over HTTPS to David's reporting service for safety and quality review. The report does not attach your API key, profile, handwritten images, source PDFs, user prompts or other chat messages. The response itself may repeat something personal you previously included; review the included response and avoid personal information in your note.

The reporting service uses Cloudflare Workers and D1. Cloudflare processes connection metadata, including your IP address, under its policies. The service uses a daily salted value derived from the IP address for short-term abuse limiting; IP addresses are not written to the reports table. Reports have no public viewing endpoint and are accessible to the developer through the hosting account. Active reports are removed within 90 days. Limited hosting recovery copies may persist for the provider's recovery period afterward. See https://www.cloudflare.com/privacypolicy/ . To request earlier deletion, contact David with your report reference. Sending a report is optional and does not change your work or grades.

## API key and request count
Each provider has a separate saved API key, encrypted using Android Keystore, tied to your device, and excluded from the app's ZIP backup and configured Android backup rules. You can remove saved keys in Settings. Request counts stay on the device and are not a provider quota or billing measurement.

## Backups and sharing
You can save a ZIP backup to Downloads and share it using an app you choose. It can contain profile names and all saved study work and is not password-encrypted. Anyone with access to it can read its contents. Restoring creates separate local profiles. Exported backup files remain until you delete them, including after uninstalling the app. Your Android settings and device manufacturer may also enable system cloud backup or device transfer of eligible local data; API keys and replaceable textbook caches are excluded by the app's backup configuration.

You can also export a book in three separate PDFs: the unchanged original textbook, the textbook with annotations from the selected local profile, or that profile's latest graded exercise submissions with feedback and review notes. Export runs on the device without sending this work to the developer or an AI service. PDFs are not password-encrypted. They are saved to Downloads on Android 10 and newer, or to app-private storage on Android 8/9; use Share to keep a copy elsewhere. Anyone you share the PDF with can read the included work. PDF exports cannot be restored into the app and app-private export copies are excluded from Android system backup and device transfer. Delete exported and shared copies separately when no longer wanted.

## Feedback and external links
Feedback buttons open your email app. A message is sent only if you choose to send it. David receives your email address and whatever you include, and uses it to respond and investigate the reported issue. Do not include API keys or private student information. LinkedIn, GitHub, Google, DeepSeek and other external destinations apply their own privacy policies. Contact David to request deletion of feedback correspondence, subject to any applicable retention obligations.

## Advertising and analytics
The app includes no advertising SDK, analytics SDK, subscription service or automatic developer telemetry. Optional AI processing, Android backup and user-directed sharing are described above and are not a claim that the app never transmits data.

## Your controls and deletion
Use the app's profile and data-management controls to remove local work, or clear Android app storage/uninstall to remove the app's private data. These actions do not delete ZIPs you saved to Downloads, shared copies, email correspondence, system backups, submitted AI reports or data held by your AI provider. Delete those separately through their respective services. Keep a separate backup of important work; no device or software can guarantee permanent storage.

## Permissions
Internet access supports optional direct requests to the selected AI provider and reports you choose to submit to the developer. Network-state access supports connection handling. Backup files use Android's scoped storage or temporary content-URI access; the app does not request broad access to all your files, location, contacts, microphone or camera.

## Changes and questions
This policy will be updated if the app's data handling changes. For privacy questions, corrections or deletion of correspondence, email ai.professor.euler@gmail.com.
