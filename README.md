# Epic Docs - Epic to Features, BRD & PRD

Epic Docs helps product managers pressure-test a product idea, break it into
smaller features, and turn the agreed scope into a Business Requirements
Document (BRD) and Product Requirements Document (PRD).

## Install and start

1. [Download the skill ZIP](./shape-epic-to-brd-prd.zip). Keep it zipped.
2. Upload it to your AI platform:
   - **Claude:** Go to **Customize → Skills** and select **Upload a skill**.
   - **ChatGPT:** If your workspace supports native Skills, go to
     **Plugins → Skills → Create → Upload from your computer**.
3. Enable the skill, open a new chat, and type **Epic Docs** followed by your idea.

> **Epic Docs.** We want customers to report equipment faults and track their
> resolution. Support agents need to triage reports, and we haven't agreed
> on response-time targets yet.

## How the workflow works

1. **Discovery.** Epic Docs asks one decision per question and follows up when an
   answer could change the scope or requirements. Where your chat supports it,
   select one answer for decisions such as the launch region, or multiple answers
   for decisions such as which features to compare. Choose **Other** to enter a
   custom answer or **Not sure yet** to leave a decision open. If clickable controls
   are unavailable, reply with the option letters, such as `1B, 2A+C`.
2. **Feature breakdown.** Epic Docs proposes smaller features and an MVP, explains
   the trade-offs, and asks whether you want a BRD. You can revise the scope first.
3. **BRD.** If you choose **Create BRD** or reply **Yes**, Epic Docs drafts the
   10-section BRD and then asks whether you want a PRD.
4. **PRD.** If you choose **Create PRD** or reply **Yes** to that separate question,
   Epic Docs drafts the 9-section PRD with proposed wireframes or process flows
   and links the product requirements back to the BRD.

You can choose **Stop here** or decline after the feature breakdown or the BRD.

## Copy-and-paste fallback

If your AI platform doesn't support skill installation, use the
[earlier portable prompt](./Epic_to_Features_BRD_PRD_Portable_Prompt.txt).
Paste it into a chat and replace the example input with your epic.
The installed skill has the newer interview and confirmation workflow.
