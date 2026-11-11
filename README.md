# Epic Docs — Epic to Features, BRD & PRD

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

1. **Discovery.** Epic Docs asks targeted questions about the users, the current
   workflow, the evidence behind the problem, and what success looks like.
   It follows up when an answer could change the scope or requirements.
2. **Feature breakdown.** It proposes smaller features and an MVP, explains
   the trade-offs, and asks if you want a BRD. You can revise the scope first.
3. **BRD.** After you say yes, it drafts the BRD using a 10-section format
   that covers objectives, scope, RACI, business processes, requirements,
   costs and benefits, and sign-off. It then asks if you want a PRD.
4. **PRD.** After a separate yes, it drafts the PRD using a 9-section format
   that covers user journeys, product requirements, acceptance criteria,
   risks, and decisions. It includes proposed wireframes or process flows
   and links the product requirements back to the BRD.

You can stop after the feature breakdown or the BRD. Review the drafts with
your team and confirm open decisions before using them for delivery planning.

## Copy-and-paste fallback

If your AI platform doesn't support skill installation, use the
[earlier portable prompt](./Epic_to_Features_BRD_PRD_Portable_Prompt.txt).
Paste it into a chat and replace the example input with your epic.
The installed skill has the newer interview and confirmation workflow.
