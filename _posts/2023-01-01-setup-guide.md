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

<p class="text-center"><a href="https://app.orgchart.work/install" target="_blank" class="btn btn--primary">Install OrgChart</a></p>

<p><strong>Image needed:</strong> Screenshot of the OrgChart install button or HubSpot Marketplace install screen.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="login-to-hubspot">2. Login and Choose the HubSpot Account</h4>

<p>Use your normal HubSpot login. If you have access to multiple HubSpot accounts, choose the account where OrgChart should be installed.</p>

<p><strong>Image needed:</strong> Screenshot of the HubSpot account selection screen during OAuth installation.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="approve-permissions">3. Approve Permissions</h4>

<p>Approve the requested HubSpot permissions and click <strong>Connect app</strong>. OrgChart needs access to deals, companies, and contacts so it can show cards, read associated CRM records, create manual contacts inside OrgChart, and generate organization charts from deal context.</p>

<p>The first user who installs OrgChart for a HubSpot account becomes an OrgChart admin by default. Additional admins can be managed later from OrgChart settings.</p>

<p><strong>Image needed:</strong> Screenshot of the HubSpot OAuth permission approval screen for OrgChart.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="add-cards">4. Add OrgChart Cards to HubSpot Views</h4>

<p>After installation, HubSpot admins can add OrgChart cards to Deal, Company, and Contact record pages.</p>

<p>Go to <strong>HubSpot Settings > Connected Apps > OrgChart > App cards > Manage locations</strong>. Add the cards to the views your team uses.</p>

<p>Users can also add cards from a CRM record by clicking <strong>Customize</strong>, selecting the record view, and adding OrgChart cards from the App card library.</p>

<p><strong>HubSpot permission required:</strong> users need <strong>Customize record page layout</strong> permissions or <strong>Super Admin</strong> permissions to add app cards to a record layout.</p>

<p><strong>Image needed:</strong> Screenshot of HubSpot Connected Apps > OrgChart > App cards > Manage locations.</p>
<p><strong>Image needed:</strong> Screenshot of adding an OrgChart card from the HubSpot card library.</p>

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

<p><strong>Image needed:</strong> Screenshot of the Deal Org Chart card with a preview image, chart selector, usage text, and Open editor button.</p>
<p><strong>Image needed:</strong> Screenshot of the no-associated-company state with the action to associate a company.</p>

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

<p><strong>Image needed:</strong> Screenshot of the Company OrgCharts card showing multiple charts and their associated deals.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="contact-cards">7. Contact Cards</h4>

<p>The contact card shows org charts from the contact's associated companies. This helps reps understand where a contact appears in the account map without leaving the contact record.</p>

<p>For each chart, the card shows the company, associated deals, preview image, and an <strong>Open editor</strong> action when there is an associated deal available.</p>

<p><strong>Image needed:</strong> Screenshot of the Contact OrgCharts card showing one or more org charts related to the contact.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="editor">8. The Org Chart Editor</h4>

<p>The editor is where you create, organize, and maintain org charts. It opens in a HubSpot modal from the deal, company, or contact cards.</p>

<p>The editor has two main areas:</p>

<ul>
  <li><strong>Contact list:</strong> shows HubSpot contacts and manual contacts available for the company.</li>
  <li><strong>Chart preview:</strong> shows the current reporting structure and buying roles.</li>
</ul>

<p><strong>Image needed:</strong> Full editor screenshot showing the contact list on the left/top and the org chart preview.</p>

<h5 class="pt-6-m mb-3 text-primary" id="create-chart">8.1 Create or Select an Org Chart</h5>

<ul>
  <li>Create a new org chart from the editor when a company does not have one yet.</li>
  <li>Select an existing org chart when the company has multiple maps.</li>
  <li>Org chart names are limited to 40 characters.</li>
  <li>Changing the name, reporting structure, or buying roles regenerates the preview image used in HubSpot cards.</li>
</ul>

<p><strong>Image needed:</strong> Screenshot of the org chart selector and org chart name edit field.</p>

<h5 class="pt-6-m mb-3 text-primary" id="reporting-structure">8.2 Define the Reporting Structure</h5>

<p>For each contact, select who they report to. Choose <strong>No One (Top Level)</strong> for top-level stakeholders and <strong>Not in org chart</strong> for contacts that should remain in the company contact list but not appear in the current chart.</p>

<p>You can also click <strong>Organize</strong> and drag one person onto another to create a reporting relationship visually. Click <strong>Done</strong> when finished.</p>

<p><strong>Image needed:</strong> Screenshot of the reporting selector in the contact list.</p>
<p><strong>Image needed:</strong> Screenshot or short GIF of drag-and-drop organize mode.</p>

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

<p><strong>Image needed:</strong> Screenshot of the buying role selector for a contact.</p>

<h5 class="pt-6-m mb-3 text-primary" id="manual-contacts">8.4 Add Manual Contacts</h5>

<p>You can add contacts that are relevant to the account map even if they are not HubSpot contacts yet. Manual contacts are stored in OrgChart at the company level, so they are available in other org charts and deals for the same company.</p>

<p>Manual contacts show a trash icon in the contact list and can be deleted from OrgChart. HubSpot contacts show the HubSpot icon and are not deleted from HubSpot by OrgChart.</p>

<p><strong>Image needed:</strong> Screenshot of the Add contact form in the editor.</p>
<p><strong>Image needed:</strong> Screenshot showing the HubSpot icon for synced contacts and trash icon for manual contacts.</p>

<h5 class="pt-6-m mb-3 text-primary" id="preview-images">8.5 Preview Images in HubSpot Cards</h5>

<p>OrgChart renders a preview image for each org chart so it can be displayed directly inside HubSpot cards. HubSpot does not allow iframes inside cards, so the editor is opened only when the user clicks the image or button.</p>

<p>Preview images are regenerated when the chart is saved, when reporting relationships change, when buying roles change, when the org chart name changes, and when AI generates or updates a chart.</p>

<p><strong>Image needed:</strong> Before/after screenshot showing an editor change and the updated card preview.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="ai-generation">9. Generate Org Charts with AI</h4>

<p>OrgChart can generate a suggested org chart from the deal record, associated contacts, associated company, buying roles, titles, and recent engagements recorded in HubSpot.</p>

<p>Click <strong>✨ Generate AI</strong> in the editor. While the process runs, the button shows a generating state. When the chart is created, it is marked with the note <strong>✨ Generated with AI. Check for mistakes.</strong> in the editor and preview image.</p>

<p>AI may also identify people mentioned in engagements who are not yet HubSpot contacts. If enabled in settings, OrgChart can create them as manual contacts so they can be included in the chart.</p>

<p><strong>Image needed:</strong> Screenshot of the Generate AI button before clicking.</p>
<p><strong>Image needed:</strong> Screenshot of the generating state.</p>
<p><strong>Image needed:</strong> Screenshot of an AI-generated org chart with the AI warning text at the bottom.</p>

<p><strong>Important:</strong> AI-generated org charts are suggestions. Review reporting lines, missing contacts, and buying roles before using the chart in a sales process.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="home-page">13. OrgChart Home Page</h4>

<p>The OrgChart home page lists org charts created in the account. It is useful for admins and managers who want to review account maps without opening each HubSpot deal.</p>

<p>From the home page, users can:</p>

<ul>
  <li>View paginated org charts.</li>
  <li>Open the editor for a selected chart.</li>
  <li>Download the preview image.</li>
  <li>Delete an org chart.</li>
</ul>

<p><strong>Image needed:</strong> Screenshot of the OrgChart home page list with Open, Download, and Delete actions.</p>

</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSettings" aria-expanded="true" aria-controls="collapseSettings"><span id="settings" class="pt-6-m">Settings and Administration</span>
</button></h3>

<div class="accordion-collapse collapse" id="collapseSettings" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 class="pt-6-m mb-3 text-primary" id="settings-overview">10. Settings Overview</h4>

<p>Only OrgChart admins can manage account settings. Settings are available from the HubSpot app settings page and from OrgChart cards when the user has access.</p>

<p>The main settings areas are:</p>

<ul>
  <li><strong>General:</strong> user access, AI provider, automation, subscription, account deletion, and buying roles.</li>
  <li><strong>Users:</strong> user plan and admin management.</li>
</ul>

<p><strong>Image needed:</strong> Screenshot of the OrgChart settings page with the General and Users tabs.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="settings-general">11. General Settings</h4>

<h5 class="pt-6-m mb-3 text-primary" id="user-access">11.1 User Access</h5>

<ul>
  <li><strong>Allow manual contacts:</strong> lets users add non-HubSpot contacts to company org charts.</li>
  <li><strong>Allow AI-created contacts:</strong> lets AI generation create manual contacts when a person appears in engagement evidence but is not already a contact.</li>
</ul>

<h5 class="pt-6-m mb-3 text-primary" id="ai-provider">11.2 AI LLM Provider</h5>

<p>Admins can enable or disable AI features and choose the AI provider used to generate org charts. The AI workflow uses available deal information, contacts, company context, and engagement records.</p>

<p>If Azure OpenAI is selected, provide the Azure resource name or base URL and API key. API keys are stored encrypted.</p>

<p><strong>Image needed:</strong> Screenshot of the AI LLM Provider settings box.</p>

<h5 class="pt-6-m mb-3 text-primary" id="deal-properties">11.3 Deal Properties and Engagement Lookback</h5>

<p>Admins can control how many days of engagements AI should consider and whether to include all deal properties or only selected deal properties. This is useful when your HubSpot account has many custom properties that are not relevant to account mapping.</p>

<p><strong>Image needed:</strong> Screenshot of engagement lookback and included deal properties settings.</p>

<h5 class="pt-6-m mb-3 text-primary" id="automations">11.4 Automations</h5>

<p>Automations are enabled by default. Depending on settings, OrgChart can:</p>

<ul>
  <li>Generate an org chart automatically when a deal is first loaded and no chart exists yet.</li>
  <li>Create org charts for new deals.</li>
  <li>Create org charts when a company is associated with a deal.</li>
</ul>

<p><strong>Image needed:</strong> Screenshot of the Automations settings box.</p>

<h5 class="pt-6-m mb-3 text-primary" id="buying-roles-settings">11.5 Buying Roles</h5>

<p>Buying roles are account-wide. Admins can edit the icon, label, and value for each role, add new roles, remove unused roles, or restore the defaults.</p>

<p>Changing buying roles affects the editor, AI generation, and future preview image generation. Existing contacts that already have a removed role may need to be updated manually.</p>

<p><strong>Image needed:</strong> Screenshot of the Buying Roles settings box at the bottom of the General tab.</p>

<h5 class="pt-6-m mb-3 text-primary" id="subscription">11.6 Manage Subscription</h5>

<p>Free accounts can create up to five free org charts. OrgChart lets free users create a sixth chart, then shows the paywall and requires an upgrade before more charts can be created.</p>

<p>Admins can upgrade to an individual plan or team plan from the card paywall or from Settings. Paid admins can open the Stripe customer portal from Settings to manage billing.</p>

<p><strong>Image needed:</strong> Screenshot of the paywall showing the one-user and team plans.</p>
<p><strong>Image needed:</strong> Screenshot of the Settings subscription box with Manage subscription.</p>

<h5 class="pt-6-m mb-3 text-primary" id="delete-account">11.7 Delete Account</h5>

<p>Deleting an account permanently removes OrgChart data stored by the app, including users, deals, companies, contacts, org charts, preview images, and local billing records. It does not delete your HubSpot account.</p>

<p>Cancel paid subscriptions before deleting the account.</p>

<p><strong>Image needed:</strong> Screenshot of the Delete Account confirmation field.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="users-settings">12. User Management</h4>

<p>The Users tab lets admins manage OrgChart users for the account.</p>

<ul>
  <li><strong>Plan:</strong> change a user between free, premium, unregistered, or deleted states.</li>
  <li><strong>Admin:</strong> make a user an OrgChart admin or remove admin access.</li>
  <li><strong>Remove:</strong> remove a non-admin user from the OrgChart account.</li>
</ul>

<p>Changing a user's plan does not cancel or change the Stripe subscription by itself. Billing must be managed from the customer portal.</p>

<p><strong>Image needed:</strong> Screenshot of the Users settings table.</p>

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

<p><strong>Image needed:</strong> Screenshot of HubSpot app installation permission error, if available.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="cannot-add-cards">15. I Cannot Add Cards to My View</h4>

<p>You need <strong>Customize record page layout</strong> permissions or <strong>Super Admin</strong> permissions in HubSpot to add cards to record views.</p>

<p>If you can see OrgChart in Connected Apps but cannot add cards, ask a HubSpot admin to add the cards to the shared record layout.</p>

<p><strong>Image needed:</strong> Screenshot of HubSpot record customization permissions or card library.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="reauthorize">16. The Card Says OrgChart Must Be Reauthorized</h4>

<p>If the HubSpot token expires, is revoked, or required scopes change, OrgChart will show a reauthorization message on the card. Click the install or reauthorize action and approve the permissions again.</p>

<p><strong>Image needed:</strong> Screenshot of the card reauthorization state.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="no-company">17. The Editor Does Not Open for a Deal</h4>

<p>Org charts are company-based. If a deal has no associated company, OrgChart cannot create or open the editor. Associate a company with the deal first, then refresh the card.</p>

<p><strong>Image needed:</strong> Screenshot of the deal card state that asks the user to associate a company.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="preview-not-updating">18. The Preview Image Is Not Updating</h4>

<p>Preview images are regenerated when changes are saved. If the HubSpot card still shows an older image, close the editor and refresh the card or record. The card appends a refresh token to preview image URLs to avoid stale cached images.</p>

<p>If the issue continues, open the editor, make a small change, and save again to force regeneration.</p>

<p><strong>Image needed:</strong> Screenshot showing an updated editor chart and refreshed card preview.</p>

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

<p><strong>Image needed:</strong> Screenshot of a friendly AI generation error message in the editor.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="ai-email-access">20. AI Autofill Is Not Taking Information from My Emails</h4>

<p>To enable AI Autofill from email activity, you may need to reauthorize the app so OrgChart can use the newer permissions required to read email engagement data.</p>

<p class="text-center"><a href="https://app.orgchart.work/install" target="_blank" class="btn btn--primary">Install</a></p>

<p>In all cases, the information extracted from emails is limited to the initial portion of each email. This helps avoid processing repetitive long threads, legal disclaimers, and other non-essential content.</p>

<p>If critical deal information is buried deep within email threads or other engagements, AI might not capture or interpret it accurately. AI can also hallucinate, so always check important facts before relying on the generated org chart.</p>

<p><strong>Image needed:</strong> Screenshot of the reauthorization prompt or install page used to approve email engagement permissions.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="billing">21. Billing or Subscription Issues</h4>

<p>Admins can manage billing from <strong>Settings > General > Manage Your Subscription</strong>. The customer portal opens in a new tab because Stripe blocks the portal inside some embedded contexts.</p>

<p>If the portal cannot find your subscription, contact support with the HubSpot account name and the email used for purchase.</p>

<p><strong>Image needed:</strong> Screenshot of the Manage subscription button opening the Stripe customer portal in a new tab.</p>

</div>
</div>
</div>
</div>
