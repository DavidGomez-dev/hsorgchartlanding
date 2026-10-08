---
layout: single
title: "OrgChart HubSpot Setup and Usage Guide"
categories: blog
tags:
  - setup guide
  - HubSpot
  - org charts
classes: wide no_padding_top
date: 2023-01-01 16:54:38 +0100
last_modified_at: 2026-10-08
excerpt: Guide for installing, configuring, and using OrgChart in HubSpot
sidebar_resume: true
header:
  overlay_image: /assets/images/zermatt.jpg
  teaser: /assets/images/zermatt.jpg
  caption:
---

<p><strong>Updated 8 October 2026.</strong> This guide covers the current HubSpot editor and AI-assisted chart generation.</p>

<div class="row my-4">
  <div class="col-md-6 mb-3">
    <div class="border border-3 border-primary rounded">
  <iframe src="https://www.youtube.com/embed/Cl0fjPFawQ4" title="OrgChart HubSpot setup guide video" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
  </div>
</div>

<div id="accordionExample" class="accordion">
<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseInstalling" aria-expanded="true" aria-controls="collapseInstalling"><span id="start" class="pt-6-m">Getting Started</span>
</button></h3>

<div class="accordion-collapse collapse show" id="collapseInstalling" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 class="pt-6-m mb-3 text-primary" id="connect-your-hubspot-account">1. Connect Your HubSpot Account</h4>

<p>Click <strong>Install app</strong> to connect OrgChart to your HubSpot account.</p>

<p><strong>Important:</strong> OrgChart is installed at the HubSpot account level. Once an admin installs the app, the account authorization can be used by the rest of the users in that HubSpot account. Individual users may still need access to the app cards in their HubSpot views.</p>

<a class="d-flex align-items-center gap-2 btn bg-black text-white px-4 py-2 me-3 w-25" href="https://app.orgchart.work/install">
          <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path d="M10.1704 10.0886C9.08591 10.0886 8.20682 9.24967 8.20682 8.21499C8.20682 7.18014 9.08591 6.34125 10.1704 6.34125C11.2548 6.34125 12.1339 7.18014 12.1339 8.21499C12.1339 9.24967 11.2548 10.0886 10.1704 10.0886ZM10.7581 4.60775V2.94095C11.2141 2.73545 11.5334 2.29534 11.5334 1.78456V1.74609C11.5334 1.04115 10.929 0.46439 10.1903 0.46439H10.1501C9.41142 0.46439 8.80706 1.04115 8.80706 1.74609V1.78456C8.80706 2.29534 9.12637 2.73564 9.58234 2.94113V4.60775C8.90354 4.70789 8.28331 4.97506 7.7718 5.36825L2.97601 1.8083C3.00766 1.69233 3.02989 1.57295 3.03008 1.44746C3.03084 0.649214 2.35371 0.00108006 1.51684 9.346e-07C0.680322 -0.000897062 0.000943832 0.645439 9.79483e-07 1.44386C-0.000939964 2.2423 0.67618 2.89043 1.51307 2.89133C1.78568 2.89169 2.03814 2.8178 2.25932 2.69769L6.97674 6.19976C6.57563 6.77759 6.34051 7.46977 6.34051 8.21499C6.34051 8.99508 6.5988 9.71679 7.03515 10.3102L5.60065 11.6793C5.48723 11.6467 5.36967 11.6241 5.24494 11.6241C4.55746 11.6241 3.99998 12.1559 3.99998 12.8119C3.99998 13.4682 4.55746 14 5.24494 14C5.93261 14 6.4899 13.4682 6.4899 12.8119C6.4899 12.6933 6.46617 12.5809 6.43206 12.4727L7.85111 11.1185C8.49527 11.5876 9.29748 11.8695 10.1704 11.8695C12.2856 11.8695 14 10.2333 14 8.21499C14 6.38782 12.5934 4.87833 10.7581 4.60775Z" fill="#FF7A59"></path>
          </svg>
          Install app
        </a>

<p class="text-center"><img src="/assets/images/guide1.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="login-to-hubspot">2. Login and Choose the HubSpot Account</h4>

<p>Use your normal HubSpot login. If you have access to multiple HubSpot accounts, choose the account where OrgChart should be installed.</p>

<p class="text-center"><img src="/assets/images/guide2.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="/assets/images/guide3.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="approve-permissions">3. Approve Permissions</h4>

<p>Approve the requested HubSpot permissions and click <strong>Connect app</strong>. OrgChart needs access to deals, companies, and contacts so it can show cards, read associated CRM records, maintain people added in OrgChart, and generate charts from company and deal context.</p>

<p>The first user who installs OrgChart for a HubSpot account becomes an OrgChart admin by default. Additional admins can be managed later from OrgChart settings.</p>

<p class="text-center"><img src="/assets/images/guide4.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<span id="access-from-sidebar"></span>
<h4 class="pt-6-m mb-3 text-primary" id="add-cards">4. Add OrgChart Cards to HubSpot Views</h4>

<p>After installation, HubSpot admins can add OrgChart cards to Deal, Company, and Contact record pages.</p>

<p>Go to <strong>HubSpot Settings > Connected Apps > OrgChart > App cards > Manage locations</strong>. Add the cards to the views your team uses.</p>

<p>Users can also add cards from a CRM record by clicking <strong>Customize</strong>, selecting the record view, and adding OrgChart cards from the App card library.</p>

<p><strong>HubSpot permission required:</strong> users need <strong>Customize record page layout</strong> permissions or <strong>Super Admin</strong> permissions to add app cards to a record layout.</p>

<p class="text-center"><img src="/assets/images/guide5.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="/assets/images/guide6.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<p>The available cards are:</p>

<ul>
  <li><strong>Deal Org Chart</strong>: available as a middle tab card and right sidebar card.</li>
  <li><strong>Company OrgCharts</strong>: available as a middle tab card and right sidebar card.</li>
  <li><strong>Contact OrgCharts</strong>: available as a middle tab card and right sidebar card.</li>
</ul>

</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseUsing" aria-expanded="true" aria-controls="collapseUsing"><span id="using" class="pt-6-m">Using OrgChart</span>
</button></h3>

<div class="accordion-collapse collapse" id="collapseUsing" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 class="pt-6-m mb-3 text-primary" id="deal-cards">5. Deal Cards</h4>

<p>The deal card shows a preview of the chart selected for that deal. Click the preview or <strong>Open editor</strong> to work on it. You can create and generate charts from either a deal or its associated company; both use the same company-based generation workflow.</p>

<p>If the deal has no associated company, OrgChart cannot create a company-level org chart yet. In that case, the card shows an action to associate a company with the deal first.</p>

<p>If the company has multiple org charts, use the selector on the card to choose which chart should be shown for that deal.</p>

<p class="text-center"><img src="/assets/images/guide7.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="/assets/images/guide8.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="company-cards">6. Company Cards</h4>

<p>The company card lists all org charts associated with that company. Each chart shows:</p>

<ul>
  <li>The org chart preview image.</li>
  <li>The org chart name.</li>
  <li>The deals associated with that chart.</li>
  <li>An action to open the editor directly, even when no deal is associated.</li>
</ul>

<p>Company-level charts are shared across deals for the same company. This means one chart can be reused by multiple deals when the sales team is mapping the same account.</p>

<p class="text-center"><img src="/assets/images/guide9.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="contact-cards">7. Contact Cards</h4>

<p>The contact card shows org charts from the contact's associated companies. This helps reps understand where a contact appears in the account map without leaving the contact record.</p>

<p>For each chart, the card shows the company, associated deals, preview image, and an <strong>Open editor</strong> action when the chart is available to the user.</p>

<p class="text-center"><img src="/assets/images/guide10.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="editor">8. The Org Chart Editor</h4>

<p>The editor is where you create, review, and maintain org charts. It opens from the deal, company, or contact cards. The same chart can be reused across deals for one company.</p>

<p>The editor has two main areas:</p>

<ul>
  <li><strong>Chart:</strong> shows people, reporting lines, and any useful unfilled roles. Optional relevance and engagement switches add visual cues to the boxes.</li>
  <li><strong>Contact list:</strong> shows HubSpot contacts and people added in OrgChart, including those not yet placed on this chart. Use it to select a manager, assign buying roles, or return a person to the chart.</li>
</ul>

<p>HubSpot contact names open the related HubSpot contact record in a new browser tab. Manual contacts stay inside OrgChart and do not link to HubSpot until they are created as HubSpot contacts.</p>

<p>Click a box to open its details panel. It shows the person's title and contact information, the current relationship, its confidence and available sources, and actions to confirm or change the placement. An <strong>Enriched</strong> marker means some displayed details came from a public or third-party source; hover over it to see the source type. Enriched details are not, by themselves, proof of a reporting line.</p>

<p>The main editor controls are:</p>

<ul>
  <li><strong>Generate with AI / Update with AI:</strong> creates or refreshes a suggested chart using the workflow explained in section 9.</li>
  <li><strong>Unsaved / Saving / Saved:</strong> shows the save state. Relationship and placement edits save automatically; you can also click the button to save or retry a failed save. Wait for <strong>Saved</strong> before closing the editor.</li>
  <li><strong>New / Delete:</strong> creates another chart or deletes the selected chart, subject to account permissions.</li>
  <li><strong>Edit / Done:</strong> enables or ends layout editing. You can also drag a person onto another person to change their manager.</li>
  <li><strong>Full screen:</strong> opens the editor in a larger browser tab when the embedded HubSpot modal is too small.</li>
  <li><strong>Download:</strong> downloads the current org chart image. If relevance or engagement switches are enabled, the downloaded image uses those same visual cues.</li>
  <li><strong>Zoom and fit:</strong> adjust the visible chart. <strong>Undo</strong> and <strong>Redo</strong> step through recent editor changes.</li>
</ul>

<p><strong>Tip:</strong> hover over the upper edge of a person's box or its incoming line to confirm the relationship with the check mark, or choose the change-manager icon. After choosing a new manager, click the destination box. Hover over the lower edge of a box and click <strong>+</strong> to add a direct report. The details panel offers the same actions.</p>

<h5 class="pt-6-m mb-3 text-primary" id="create-chart">8.1 Create or Select an Org Chart</h5>

<ul>
  <li>Create a new org chart from the editor when a company does not have one yet.</li>
  <li>Select an existing org chart when the company has multiple maps.</li>
  <li>Org chart names are limited to 40 characters.</li>
  <li>Changing the name, reporting structure, or buying roles regenerates the preview image used in HubSpot cards.</li>
</ul>

<h5 class="pt-6-m mb-3 text-primary" id="reporting-structure">8.2 Define the Reporting Structure</h5>

<p>For each person, choose a manager in the contact list or use the actions on the chart. <strong>No manager recorded (top level)</strong> leaves the person at the top of the chart; <strong>Not in org chart</strong> keeps them available in the contact list without displaying them on this chart. For an AI-suggested line, <strong>Confirm</strong> records that a user reviewed it.</p>

<p>The line styles distinguish <strong>Confirmed</strong>, <strong>Likely</strong>, <strong>Tentative</strong>, and <strong>Grouped</strong>. <strong>Grouped</strong> means the person belongs in that branch but the direct manager is not established. It should not be read as a verified reporting line. Select a box to inspect the explanation, evidence confidence, and source links when available.</p>

<p>Use <strong>Remove from chart</strong> to unplace a person without deleting them. If other people sit below that person, OrgChart keeps the branch together under an unfilled manager role until you choose a replacement. Empty placeholders can be removed; a branch with people below it can be removed as a branch after confirmation. These actions do not delete HubSpot contacts.</p>

<h5 class="pt-6-m mb-3 text-primary" id="buying-roles">8.3 Assign Buying Roles</h5>

<p>Buying roles identify how each person influences the deal. OrgChart uses HubSpot's native <strong>Buying role</strong> contact property as the source of truth. The default HubSpot buying-role options are:</p>

<ul>
  <li>⛔ Blocker</li>
  <li>💰 Budget Holder</li>
  <li>⭐ Champion</li>
  <li>✅ Decision Maker</li>
  <li>👤 End User</li>
  <li>🤝 Executive Sponsor</li>
  <li>📣 Influencer</li>
  <li>⚖️ Legal & Compliance</li>
  <li>● Other</li>
</ul>

<p>When you assign a buying role in OrgChart, OrgChart updates the HubSpot contact's <strong>Buying role</strong> value. This keeps HubSpot and OrgChart coordinated instead of maintaining a separate app-only role list.</p>

<p>To add, rename, remove, or reorder buying roles, update the <strong>Buying role</strong> contact property options in HubSpot. Admins can use <strong>Settings > General > Buying Roles > Manage buying roles in HubSpot</strong> to open the HubSpot property settings page. After a new role is added in HubSpot, it normally appears in OrgChart after the short property cache refresh, usually within about five minutes.</p>

<p>OrgChart settings are only for changing the icons shown next to each HubSpot buying role. The role names and internal values come from HubSpot and should be managed there.</p>

<h5 class="pt-6-m mb-3 text-primary" id="contact-intelligence">8.4 Review Contact Intelligence</h5>

<p>OrgChart calculates deterministic contact intelligence scores for each contact in the company org chart. The scores are designed to help the team quickly scan who looks commercially relevant and who has recent engagement, without changing HubSpot data.</p>

<p>The contact list shows compact <strong>Rel</strong> and <strong>Eng</strong> badges. The contact sidebar shows <strong>Total</strong>, <strong>Rel</strong>, <strong>Eng</strong>, and associated deal badges in one row. Click the <strong>Intelligence</strong> title in the sidebar to expand the explanation, including the main reasons and source facts used for the score.</p>

<p>The org chart boxes do not show intelligence badges by default. Use the <strong>Relevance</strong> switch to show relevance badges, background tint, and a small size cue. Use the <strong>Engagement</strong> switch to show engagement badges, border strength, border color, and shadow. Low engagement has no shadow so stale or unknown contacts do not look visually over-emphasized.</p>

<p><strong>Total score:</strong> <code>round((relevanceScore * 0.6) + (engagementScore * 0.4))</code>. Scores are grouped as <strong>High</strong> from 75 to 100, <strong>Medium</strong> from 45 to 74, and <strong>Low</strong> from 0 to 44.</p>

<p><strong>Relevance score:</strong> starts from a neutral baseline and increases or decreases from account-map signals. Strong buying roles such as decision maker, executive sponsor, budget holder, and champion add the most weight. Influencer, end user, legal and compliance, and custom roles add smaller weight. Blocker reduces the score unless other strong deal signals are present. Associated deal count and open deal amount add points relative to the other contacts in the same company org chart, so the score is company-relative. Lifecycle stage, lead status, and title signals such as C-level, VP, Head, Director, Procurement, Legal, Finance, Security, and IT add limited extra context.</p>

<p><strong>Engagement score:</strong> also starts from a neutral baseline. Recent HubSpot engagement is the strongest signal: activity within 7 days is high, 8 to 30 days is medium, 31 to 90 days is weak, and older activity is stale. Sales activity count and contacted count add capped points so noisy contacts do not dominate the score. Email replies add more weight than email clicks or opens. If HubSpot has no recent activity date and no activity counts, OrgChart shows <strong>No recent engagement data</strong> instead of treating the contact as a proven zero-engagement stakeholder.</p>

<p>OrgChart reads available HubSpot contact properties such as last contacted, last activity, last engagement, number of sales activities, number of times contacted, email open/click/reply dates, buying role, associated deal count, recent deal amount, and total revenue. If a HubSpot portal does not expose one of those properties, OrgChart retries safely without it and calculates the score from the remaining available signals.</p>

<h5 class="pt-6-m mb-3 text-primary" id="manual-contacts">8.5 Add Manual Contacts</h5>

<p>You can add people who are relevant to the account map even if they are not HubSpot contacts yet. A company-level manual person can be reused across charts and deals for that company. You can also create a person in the chart editor and, when appropriate, add that person to HubSpot.</p>

<p>Manually added people can be deleted from OrgChart where the delete action is offered; this does not delete a HubSpot contact. Use <strong>Remove from chart</strong> instead when you only want to unplace someone. Unfilled roles that have been filled or removed are hidden from the active contact and manager choices so they do not keep appearing as duplicates.</p>

<p><strong>Unfilled roles:</strong> when the chart has a meaningful missing manager or leader, it may show a lightly shaded role box instead of inventing a person's name. Select it and choose <strong>Fill this role</strong> to pick an available person or create one. Filling a role is a manual decision, so its new person-to-person reporting line is marked confirmed. Remove an empty role if it is not useful.</p>

<h5 class="pt-6-m mb-3 text-primary" id="preview-images">8.6 Preview Images in HubSpot Cards</h5>

<p>OrgChart renders a preview image for each org chart so it can be displayed directly inside HubSpot cards. HubSpot does not allow iframes inside cards, so the editor is opened only when the user clicks the image or button.</p>

<p>Preview images are regenerated when the chart is saved, when reporting relationships change, when buying roles change, when the org chart name changes, and when AI generates or updates a chart.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="ai-generation">9. Generate Org Charts with AI</h4>

<p>Click <strong>✨ Generate with AI</strong> for a new chart, or <strong>✨ Update with AI</strong> for an existing one. You can start from a company record or a deal with an associated company. Both routes use the same company-based generation workflow; a deal also supplies relevant deal context and links the chart to that deal.</p>

<h5 class="pt-6-m mb-3 text-primary" id="ai-workflow">9.1 How a Chart Is Built</h5>

<ol>
  <li><strong>Understand the account:</strong> OrgChart gathers the company's identity and available HubSpot contacts, titles, buying roles, and permitted deal and engagement context. It also checks for duplicates and for people whose company affiliation is uncertain.</li>
  <li><strong>Find useful context:</strong> when appropriate, it checks public company information and available enrichment sources for leadership, roles, locations, and organizational clues. Public information is especially useful for larger companies; a small team or department chart may rely much more on CRM evidence. Outside information can be missing, old, or mismatched, so it is assessed rather than accepted automatically.</li>
  <li><strong>Build a people-first structure:</strong> where credible public leaders and relationships exist, they form the top-level backbone. OrgChart then places CRM people into the most plausible function, region, and seniority level using all available evidence. For smaller or focused charts, it builds around the people and scope actually present rather than forcing a whole-company CEO hierarchy.</li>
  <li><strong>Handle gaps and uncertainty:</strong> confirmed relationships remain distinct from likely or tentative ones. If the appropriate manager is unknown, OrgChart can group someone under a branch or show an unfilled role with people below it. It does not need to invent a named manager or make every contact a direct report of the CEO. Contacts with too little reliable context may remain available but unplaced.</li>
  <li><strong>Review and refine:</strong> the chart appears with line styles, available sources, and quality indicators. You can confirm a line, choose another manager, fill a role, or add a direct report. Manual corrections are carried forward when you update the chart with AI.</li>
</ol>

<p>While generation runs, the editor shows an approximate sequence of progress messages. Research and reconciliation can take longer for complex companies; the messages describe the stage of work, not a guaranteed completion time. Depending on account settings, AI can also add a real person found in engagement evidence as a manual contact.</p>

<h5 class="pt-6-m mb-3 text-primary" id="chart-quality">9.2 Read the Result</h5>

<p><strong>Chart quality</strong> is an overall score that combines evidence confidence, contact coverage, structural plausibility, contact role information, and leadership placement. It is a guide to how usable the chart is, <strong>not a guarantee that every reporting line is correct</strong>. Open the quality details to see the component scores and explanations. Evidence confidence is shown separately because a plausible hierarchy may still contain inferred relationships.</p>

<p>The relationship details panel shows whether a particular line is confirmed, likely, or tentative, with its explanation and source links where available. A confirmed line may come from an explicit source or from a user's manual review; check the details when that distinction matters. <strong>Grouped</strong> indicates branch placement, not a known direct manager. If sources disagree, OrgChart may keep a relationship tentative or leave a person unplaced rather than present a conflict as fact.</p>

<p><strong>Important:</strong> AI-generated charts are best-effort starting points. Review important reporting lines, current titles, affiliations, missing contacts, and buying roles before relying on the chart in a sales process. For a small or department-only chart, do not assume it represents the entire company.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="home-page">10. OrgChart Home Page</h4>

<p>The OrgChart home page lists org charts created in the account. It is useful for admins and managers who want to review account maps without opening each HubSpot deal.</p>

<p>From the home page, users can:</p>

<ul>
  <li>View paginated org charts.</li>
  <li>Open the editor for a selected chart.</li>
  <li>Download the preview image.</li>
  <li>Delete an org chart.</li>
</ul>

<p class="text-center"><img src="/assets/images/guide20.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSettings" aria-expanded="true" aria-controls="collapseSettings"><span id="settings" class="pt-6-m">Settings and Administration</span>
</button></h3>

<div class="accordion-collapse collapse" id="collapseSettings" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 class="pt-6-m mb-3 text-primary" id="settings-overview">11. Settings Overview</h4>

<p>Only OrgChart admins can manage account settings. Settings are available from the HubSpot app settings page and from OrgChart cards when the user has access.</p>

<p>The main settings areas are:</p>

<ul>
  <li><strong>General:</strong> user access, AI usage, automation, subscription, account deletion, and buying-role icons.</li>
  <li><strong>Users:</strong> user plan and admin management.</li>
</ul>

<p class="text-center"><img src="/assets/images/guide21.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="settings-general">12. General Settings</h4>

<h5 class="pt-6-m mb-3 text-primary" id="user-access">12.1 User Access</h5>

<ul>
  <li><strong>Allow non-admin users to delete org charts:</strong> lets non-admin users permanently delete org charts. When disabled, only OrgChart admins can delete charts.</li>
  <li><strong>Allow non-admin users to manage manual contacts:</strong> lets non-admin users add and delete manual contacts in company org charts. When disabled, only OrgChart admins can manage manual contacts.</li>
  <li><strong>Allow AI-created contacts:</strong> lets AI generation create manual contacts when a real person appears in engagement evidence but is not already a HubSpot contact.</li>
</ul>

<h5 class="pt-6-m mb-3 text-primary" id="ai-provider">12.2 AI Usage</h5>

<p>Admins can enable or disable AI features and configure the available AI provider. Generation uses the company and CRM context described in section 9, with public information and enrichment where available and appropriate. Availability of outside sources depends on the service configuration and the company being researched.</p>

<p>If Azure OpenAI is selected, provide the Azure resource name or base URL and API key. API keys are stored encrypted. If AI usage is disabled, AI generation and AI automation are not available to users.</p>

<p class="text-center"><img src="/assets/images/guide22.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="deal-properties">12.3 Deal Properties and Engagement Lookback</h5>

<p>Inside AI Usage, admins can control how many days of engagements AI should consider. They can also choose whether AI sees all available deal properties or only selected deal properties. This is useful when a HubSpot account has many custom properties that are not relevant to account mapping.</p>

<p class="text-center"><img src="/assets/images/guide23.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="automations">12.4 Automations</h5>

<p>Automations are enabled by default. Depending on settings, OrgChart can:</p>

<ul>
  <li>Allow AI org-chart automation globally for the account.</li>
  <li>Create org charts for new deals.</li>
  <li>Create org charts when a company is associated with a deal.</li>
</ul>

<p>The main automation switch must be enabled for the new-deal and company-association automation switches to have an effect.</p>

<h5 class="pt-6-m mb-3 text-primary" id="buying-roles-settings">12.5 Buying Roles</h5>

<p>Buying roles are account-wide because they come from HubSpot's <strong>Buying role</strong> contact property. OrgChart settings show the HubSpot buying-role names and let admins choose the icon OrgChart displays for each one.</p>

<p>Use <strong>Manage buying roles in HubSpot</strong> to add a new role or change the role options themselves. Use <strong>Save icons</strong> to save OrgChart icon changes, or <strong>Restore default icons</strong> to return to the default icon mapping. Changing icons affects the editor, AI generation display, and future preview image generation; it does not rename or create HubSpot buying-role options.</p>

<p class="text-center"><img src="/assets/images/guide24.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="subscription">12.6 Manage Subscription</h5>

<p>Free accounts can create up to 10 free org charts. OrgChart warns admins as the account approaches the free limit and requires an upgrade before an 11th chart can be created.</p>

<p>Admins can upgrade to an individual plan or team plan from the card paywall or from Settings. Paid admins can open the Stripe customer portal from Settings to manage billing.</p>

<p class="text-center"><img src="/assets/images/guide25.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="/assets/images/guide26.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="delete-account">12.7 Delete Account</h5>

<p>Deleting an account permanently removes OrgChart data stored by the app, including users, deals, companies, contacts, org charts, preview images, and local billing records. It does not delete your HubSpot account.</p>

<p>Cancel paid subscriptions before deleting the account.</p>

<p class="text-center"><img src="/assets/images/guide27.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="users-settings">13. User Management</h4>

<p>The Users tab lets admins manage OrgChart users for the account.</p>

<ul>
  <li><strong>Plan:</strong> change a user between free, premium, unregistered, or deleted states.</li>
  <li><strong>Admin:</strong> make a user an OrgChart admin or remove admin access.</li>
  <li><strong>Remove:</strong> remove a non-admin user from the OrgChart account.</li>
</ul>

<p>Changing a user's plan does not cancel or change the Stripe subscription by itself. Billing must be managed from the customer portal.</p>

<p class="text-center"><img src="/assets/images/guide28.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTroubleshooting" aria-expanded="true" aria-controls="collapseTroubleshooting"><span id="troubleshooting" class="pt-6-m">Troubleshooting</span>
</button></h3>

<div class="accordion-collapse collapse" id="collapseTroubleshooting" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 class="pt-6-m mb-3 text-primary" id="cannot-install-app">14. I Cannot Install the App</h4>

<p>You may not have permission to install apps in HubSpot. Ask a HubSpot Super Admin to install OrgChart or grant you permission to install marketplace apps.</p>

<p class="text-center"><img src="/assets/images/trouble1.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="cannot-add-cards">15. I Cannot Add Cards to My View</h4>

<p>You need <strong>Customize record page layout</strong> permissions or <strong>Super Admin</strong> permissions in HubSpot to add cards to record views.</p>

<p>If you can see OrgChart in Connected Apps but cannot add cards, ask a HubSpot admin to add the cards to the shared record layout.</p>

<p class="text-center"><img src="/assets/images/trouble2.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="/assets/images/trouble3.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="reauthorize">16. The Card Says OrgChart Must Be Reconnected</h4>

<p>If the HubSpot token expires, is revoked, or required scopes change, OrgChart will show a reauthorization message on the card. Click the Reconnect action and approve the permissions again.</p>

<p class="text-center"><img src="/assets/images/trouble4.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="no-company">17. The Editor Does Not Open for a Deal</h4>

<p>Org charts are company-based. If a deal has no associated company, OrgChart cannot create or open the editor. Associate a company with the deal first, then refresh the card.</p>

<p class="text-center"><img src="/assets/images/guide8.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="preview-not-updating">18. The Preview Image Is Not Updating</h4>

<p>Preview images are regenerated when changes are saved. If the HubSpot card still shows an older image, close the editor and refresh the card or record. The card appends a refresh token to preview image URLs to avoid stale cached images.</p>

<p>If the issue continues, open the editor, make a small change, and save again to force regeneration.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="ai-error">19. AI Generation Fails</h4>

<p>AI generation can fail if AI is disabled, the configured service is unavailable, the HubSpot connection needs attention, or there is too little reliable company information to build a chart. A company with no CRM contacts may still be eligible if verifiable public leaders are found; an empty company record does not guarantee a chart can be generated. The editor shows an error when generation fails.</p>

<p>Check:</p>

<ul>
  <li>The account has AI enabled.</li>
  <li>The AI service is configured and available.</li>
  <li>The company name or domain is correct and the company has useful CRM contacts or verifiable public information. A deal must be associated with a company.</li>
  <li>The app is still authorized in HubSpot.</li>
</ul>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="ai-email-access">20. AI Autofill Is Not Taking Information from My Emails</h4>

<p>To enable AI Autofill from email activity, you may need to reauthorize the app so OrgChart can use the newer permissions required to read email engagement data.</p>

<a class="d-flex align-items-center gap-2 btn bg-black text-white px-4 py-2 me-3 w-25" href="https://app.orgchart.work/install">
          <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path d="M10.1704 10.0886C9.08591 10.0886 8.20682 9.24967 8.20682 8.21499C8.20682 7.18014 9.08591 6.34125 10.1704 6.34125C11.2548 6.34125 12.1339 7.18014 12.1339 8.21499C12.1339 9.24967 11.2548 10.0886 10.1704 10.0886ZM10.7581 4.60775V2.94095C11.2141 2.73545 11.5334 2.29534 11.5334 1.78456V1.74609C11.5334 1.04115 10.929 0.46439 10.1903 0.46439H10.1501C9.41142 0.46439 8.80706 1.04115 8.80706 1.74609V1.78456C8.80706 2.29534 9.12637 2.73564 9.58234 2.94113V4.60775C8.90354 4.70789 8.28331 4.97506 7.7718 5.36825L2.97601 1.8083C3.00766 1.69233 3.02989 1.57295 3.03008 1.44746C3.03084 0.649214 2.35371 0.00108006 1.51684 9.346e-07C0.680322 -0.000897062 0.000943832 0.645439 9.79483e-07 1.44386C-0.000939964 2.2423 0.67618 2.89043 1.51307 2.89133C1.78568 2.89169 2.03814 2.8178 2.25932 2.69769L6.97674 6.19976C6.57563 6.77759 6.34051 7.46977 6.34051 8.21499C6.34051 8.99508 6.5988 9.71679 7.03515 10.3102L5.60065 11.6793C5.48723 11.6467 5.36967 11.6241 5.24494 11.6241C4.55746 11.6241 3.99998 12.1559 3.99998 12.8119C3.99998 13.4682 4.55746 14 5.24494 14C5.93261 14 6.4899 13.4682 6.4899 12.8119C6.4899 12.6933 6.46617 12.5809 6.43206 12.4727L7.85111 11.1185C8.49527 11.5876 9.29748 11.8695 10.1704 11.8695C12.2856 11.8695 14 10.2333 14 8.21499C14 6.38782 12.5934 4.87833 10.7581 4.60775Z" fill="#FF7A59"></path>
          </svg>
          Install app
        </a>

<p>In all cases, the information extracted from emails is limited to the initial portion of each email. This helps avoid processing repetitive long threads, legal disclaimers, and other non-essential content.</p>

<p>If critical deal information is buried deep within email threads or other engagements, AI might not capture or interpret it accurately. AI can also hallucinate, so always check important facts before relying on the generated org chart.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="billing">21. Billing or Subscription Issues</h4>

<p>Admins can manage billing from <strong>Settings > General > Manage Your Subscription</strong>. The customer portal opens in a new tab because Stripe blocks the portal inside some embedded contexts.</p>

<p>If the portal cannot find your subscription, contact support with the HubSpot account name and the email used for purchase.</p>

<p class="text-center"><img src="/assets/images/trouble5.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

</div>
</div>
</div>
</div>
