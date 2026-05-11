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
excerpt: Guide for installing, configuring, and using OrgChart in HubSpot
sidebar_resume: true
header:
  overlay_image: /assets/images/zermatt.jpg
  teaser: /assets/images/zermatt.jpg
  caption:
---

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

<p>Approve the requested HubSpot permissions and click <strong>Connect app</strong>. OrgChart needs access to deals, companies, and contacts so it can show cards, read associated CRM records, create manual contacts inside OrgChart, and generate organization charts from deal context.</p>

<p>The first user who installs OrgChart for a HubSpot account becomes an OrgChart admin by default. Additional admins can be managed later from OrgChart settings.</p>

<p class="text-center"><img src="/assets/images/guide4.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

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

<p>The deal card is the main place to create and work with an org chart. The card shows a preview image of the current organization chart for the deal. Click the preview image or <strong>Open editor</strong> to open the editor.</p>

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
  <li>An action to open the editor through an associated deal.</li>
</ul>

<p>Company-level charts are shared across deals for the same company. This means one chart can be reused by multiple deals when the sales team is mapping the same account.</p>

<p class="text-center"><img src="/assets/images/guide9.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="contact-cards">7. Contact Cards</h4>

<p>The contact card shows org charts from the contact's associated companies. This helps reps understand where a contact appears in the account map without leaving the contact record.</p>

<p>For each chart, the card shows the company, associated deals, preview image, and an <strong>Open editor</strong> action when there is an associated deal available.</p>

<p class="text-center"><img src="/assets/images/guide10.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="editor">8. The Org Chart Editor</h4>

<p>The editor is where you create, organize, and maintain org charts. It opens in a HubSpot modal from the deal, company, or contact cards.</p>

<p>The editor has two main areas:</p>

<ul>
  <li><strong>Contact list:</strong> shows HubSpot contacts and manual contacts available for the company.</li>
  <li><strong>Chart preview:</strong> shows the current reporting structure and buying roles.</li>
</ul>

<p class="text-center"><img src="/assets/images/guide11.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="/assets/images/guide12.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="create-chart">8.1 Create or Select an Org Chart</h5>

<ul>
  <li>Create a new org chart from the editor when a company does not have one yet.</li>
  <li>Select an existing org chart when the company has multiple maps.</li>
  <li>Org chart names are limited to 40 characters.</li>
  <li>Changing the name, reporting structure, or buying roles regenerates the preview image used in HubSpot cards.</li>
</ul>

<p class="text-center"><img src="/assets/images/guide13.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="reporting-structure">8.2 Define the Reporting Structure</h5>

<p>For each contact, select who they report to. Choose <strong>No One (Top Level)</strong> for top-level stakeholders and <strong>Not in org chart</strong> for contacts that should remain in the company contact list but not appear in the current chart.</p>

<p>You can also click <strong>Organize</strong> and drag one person onto another to create a reporting relationship visually. Click <strong>Done</strong> when finished.</p>

<p class="text-center"><img src="/assets/images/guide14.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="/assets/images/guide15.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="buying-roles">8.3 Assign Buying Roles</h5>

<p>Buying roles identify how each person influences the deal. The default roles are:</p>

<ul>
  <li>💰 Economic buyer</li>
  <li>⭐ Champion</li>
  <li>🛠️ Technical buyer</li>
  <li>👤 User</li>
  <li>🛒 Procurement</li>
  <li>⛔ Blocker</li>
  <li>📣 Influencer</li>
  <li>⚖️ Legal</li>
</ul>

<p>Admins can customize these buying roles in <strong>Settings > General > Buying Roles</strong>. Custom roles are account-wide and are used in the editor, preview images, and AI generation.</p>

<p class="text-center"><img src="/assets/images/guide16.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="manual-contacts">8.4 Add Manual Contacts</h5>

<p>You can add contacts that are relevant to the account map even if they are not HubSpot contacts yet. Manual contacts are stored in OrgChart at the company level, so they are available in other org charts and deals for the same company.</p>

<p>Manual contacts show a trash icon in the contact list and can be deleted from OrgChart. HubSpot contacts show the HubSpot icon and are not deleted from HubSpot by OrgChart.</p>

<p class="text-center"><img src="/assets/images/guide17.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="/assets/images/guide18.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="preview-images">8.5 Preview Images in HubSpot Cards</h5>

<p>OrgChart renders a preview image for each org chart so it can be displayed directly inside HubSpot cards. HubSpot does not allow iframes inside cards, so the editor is opened only when the user clicks the image or button.</p>

<p>Preview images are regenerated when the chart is saved, when reporting relationships change, when buying roles change, when the org chart name changes, and when AI generates or updates a chart.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="ai-generation">9. Generate Org Charts with AI</h4>

<p>OrgChart can generate a suggested org chart from the deal record, associated contacts, associated company, buying roles, titles, and recent engagements recorded in HubSpot.</p>

<p>Click <strong>✨ Generate AI</strong> in the editor. While the process runs, the button shows a generating state. When the chart is created, it is marked with the note <strong>✨ Generated with AI. Check for mistakes.</strong> in the editor and preview image.</p>

<p>AI may also identify people mentioned in engagements who are not yet HubSpot contacts. If enabled in settings, OrgChart can create them as manual contacts so they can be included in the chart.</p>

<p class="text-center"><img src="/assets/images/guide19.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<p><strong>Important:</strong> AI-generated org charts are suggestions. Review reporting lines, missing contacts, and buying roles before using the chart in a sales process.</p>

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
  <li><strong>General:</strong> user access, AI provider, automation, subscription, account deletion, and buying roles.</li>
  <li><strong>Users:</strong> user plan and admin management.</li>
</ul>

<p class="text-center"><img src="/assets/images/guide21.png" alt="troubleshooting" class="mt-5 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="settings-general">12. General Settings</h4>

<h5 class="pt-6-m mb-3 text-primary" id="user-access">12.1 User Access</h5>

<ul>
  <li><strong>Allow manual contacts:</strong> lets users add non-HubSpot contacts to company org charts.</li>
  <li><strong>Allow AI-created contacts:</strong> lets AI generation create manual contacts when a person appears in engagement evidence but is not already a contact.</li>
</ul>

<h5 class="pt-6-m mb-3 text-primary" id="ai-provider">12.2 AI LLM Provider</h5>

<p>Admins can enable or disable AI features and choose the AI provider used to generate org charts. The AI workflow uses available deal information, contacts, company context, and engagement records.</p>

<p>If Azure OpenAI is selected, provide the Azure resource name or base URL and API key. API keys are stored encrypted.</p>

<p class="text-center"><img src="/assets/images/guide22.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="deal-properties">12.3 Deal Properties and Engagement Lookback</h5>

<p>Admins can control how many days of engagements AI should consider and whether to include all deal properties or only selected deal properties. This is useful when your HubSpot account has many custom properties that are not relevant to account mapping.</p>

<p class="text-center"><img src="/assets/images/guide23.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="automations">12.4 Automations</h5>

<p>Automations are enabled by default. Depending on settings, OrgChart can:</p>

<ul>
  <li>Generate an org chart automatically when a deal is first loaded and no chart exists yet.</li>
  <li>Create org charts for new deals.</li>
  <li>Create org charts when a company is associated with a deal.</li>
</ul>

<h5 class="pt-6-m mb-3 text-primary" id="buying-roles-settings">12.5 Buying Roles</h5>

<p>Buying roles are account-wide. Admins can edit the icon, label, and value for each role, add new roles, remove unused roles, or restore the defaults.</p>

<p>Changing buying roles affects the editor, AI generation, and future preview image generation. Existing contacts that already have a removed role may need to be updated manually.</p>

<p class="text-center"><img src="/assets/images/guide24.png" alt="troubleshooting" class="w-50 mt-5 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="subscription">12.6 Manage Subscription</h5>

<p>Free accounts can create up to five free org charts. OrgChart lets free users create a sixth chart, then shows the paywall and requires an upgrade before more charts can be created.</p>

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

<p>AI generation can fail if AI is disabled in settings, the selected provider is not configured, the deal has no contacts, or HubSpot engagement data cannot be read. The editor shows an error message when generation fails.</p>

<p>Check:</p>

<ul>
  <li>The account has AI enabled.</li>
  <li>The selected LLM provider is configured.</li>
  <li>The deal has an associated company and contacts.</li>
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
