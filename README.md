Shape My Idea:
Shape My Idea helps product managers pressure-test a product idea, break it into
smaller features, and turn the agreed scope into a Business Requirements
Document (BRD) and Product Requirements Document (PRD).
Start with one Markdown file
1. Open [SKILL.md](./SKILL.md). It contains the full workflow and both document templates.
2. Copy the entire file into a new AI chat or your assistant's instructions.
3. Type Shape my idea followed by your product idea.
If your platform accepts standalone Markdown skill files, import the same
SKILL.md there. If its native installer requires a ZIP, such as Claude's
custom skill uploader, use the Markdown in chat or use the
[ZIP for native installation](./shape-epic-to-brd-prd.zip).
Shape my idea: We want customers to report equipment faults and track their
resolution. Support agents need to triage reports, and we haven't agreed
on response-time targets yet.

How the workflow works
1. Discovery. Shape My Idea asks one decision per question and follows up when an
   answer could change the scope or requirements. Where your chat supports it,
   select one answer for decisions such as the launch region, or multiple answers
   for decisions such as which features to compare. Choose Other to enter a
   custom answer or Not sure yet to leave a decision open. If clickable controls
   are unavailable, reply with the option letters, such as 1B, 2A+C.
2. Feature breakdown. Shape My Idea proposes smaller features and an MVP, explains
   the trade-offs, and asks whether you want a BRD. You can revise the scope first.
3. BRD. If you choose Create BRD or reply Yes, Shape My Idea drafts the
   10-section BRD and then asks whether you want a PRD.
4. PRD. If you choose Create PRD or reply Yes to that separate question,
   Shape My Idea drafts the 9-section PRD with proposed wireframes or process flows
   and links the product requirements back to the BRD.
You can choose Stop here or decline after the feature breakdown or the BRD.
Use without installing
Open the [portable prompt](./Epic_to_Features_BRD_PRD_Portable_Prompt.txt).
Copy everything below the divider into a new AI chat, replace the placeholder
under My product idea, and send it. The prompt follows the same discovery,
MVP, BRD, and PRD workflow. If the chat doesn't offer clickable choices,
reply with option letters or plain text.
