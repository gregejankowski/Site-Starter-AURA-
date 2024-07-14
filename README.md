## Experience Cloud Site Starter (AURA)

The Experience Cloud Site Starter (AURA) is a responsive site design for a self-service site using best practices (e.g., flexible pages), no-code (out of the box components), CSS, and HTML components.

This package contains:

*   **Site Starter (AURA) Template** This template provides a clean theme (minimal pages) using flexible layouts for all pages. Templates are selected when creating a new site or changing the Template. This will overwrite all site pages and the theme.
*   **Page Template** When creating or update a non-object and non-CMS page types, a page layout called **Template** is included to get a new page started.

**Notes:**

1.  **Read the instructions carefully** and complete the tasks before publishing. There are additional instructions and details
2.  This package is **supplied as-is** and is not supported by Salesforce.
3.  CSS files are included as static resources and referenced in the Head Markup. CSS has the potential to visually impact other components within the Experience Cloud site. The site CSS is reviewed for each release, but is _supplied as-is_.
4.  No CMS or Knowledge content included. This template and some pages require Knowledge to be configured in your org.
5.  **Create additional pages** - Only the minimum pages needed have been created. Create additional pages based on your needs and requirements.
6.  **Audiences** - Create audiences to personalize content and support guest user menu, home page, etc. The guest user profile name and link is found under Settings / General. Set the guest audience to User > Profile > Name equals: \<Gust user profile name>.

---

### Installation and Setup

**Installation**

1.  Enable and setup Experience Cloud on your site (if it is not already enabled).
2.  Install the package _(coming soon…)_.

**Create a New Site**

1.  Open the **Digital Experiences** app and then open the **All Sites** tab.
2.  Click **New**.
3.  Select **Site Starter (AURA)**.
4.  Add the site **Name** and site **URL** (optional).
5.  Complete the site configuration steps.

**Update an Existing Site**

_**Warning**_ - This will completely overwrite the existing site (all pages and theming).

1.  Go to Workspace / Administration / Settings / Change Template.
2.  Select _Site Starter (AURA)_.
3.  Add the site _Name_ and site _URL_ (optional).
4.  Complete the site configuration steps.

---

### Site Configuration

1.  Update the sites' Head Markup (Experience Builder / Settings / Advanced / Edit Head Markup) from [Head-Markup.html](https://github.com/gregejankowski/Site-Starter-AURA-/blob/main/Head-Markup-Site-Starter.html) and paste it into the sites’ Head Markup. References to Google Icons and CSS static resources are included.
2.  **Before installing** the package, configure your site (e.g., Knowledge, user profiles, permissions sets, etc.). Review these help articles **before starting**; [Understand the Basics](https://help.salesforce.com/s/articleView?id=sf.exp_cloud_basics.htm&language=en_US&type=5), [Plan & Prepare](https://help.salesforce.com/s/articleView?id=sf.exp_cloud_plan.htm&language=en_US&type=5), and [Setup Checklist](https://help.salesforce.com/s/articleView?id=sf.networks_napili_template_setup_checklist.htm&language=en_US&type=5). 
3.  Review the Head Markup and update the site markup and allow (optionally) for icon use.
    1.  To add a site favicon, upload a static resource, share it publicly, and update the file name in the head markup.
    2.  Allows for the use of Google icons, the external stylesheet is referenced with default icon formatting.
    3.  Three different CSS files are included as static resources and are referenced with the Head Markup:
        *   ExpCloudCSSBuilderComponents - CSS overrides to make out of the box Experience Cloud components styling more consistent.
        *   ExpCloudCSSFonts - CSS related font, button, and icon styling. This sets the base font size for desktop and mobile.
        *   ExpCloudCSSforHTML - CSS used on HTML components within the site.
    4.  Update the site branding (e.g., font, logo, color, etc.).
    5.  Update or change the site navigation, tile menu for calls to action, and the quick links.
    6.  Review all pages for layout, content, and remove any builder notes or assign them to an audience that will not show on the published site (e.g., Show when Employee Id = 0).
    7.  Update the home page (content, hero calls to action).
    8.  Update the footer content for all theme layouts.
    9.  Configure Knowledge and Salesforce CMS (as needed).
    10.  Review, edit, and add pages based on user journeys and provide content, links, and components where applicable.  
        Note: If you need to create a non-record/CMS page, use the page template named **Page Template**. When you create a record page, or are editing an existing, non-flexible page, always update these (see [Using Flexible Layouts to Improve Your Site Experience](https://www.learnexperiencecloud.com/article/Using-Flexible-Layouts-to-Improve-Your-Site-Experience)).

---

## Pages

The following pages have been included with this page. They are available via the theme (used to create a new site) or as pages templates (used to update existing sites).

1.  **Account** List and Detail - Flexible layout, update common layout for all record pages.
2.  **Article Detail** - Flexible and improved layout. Uses CSS to show all but the last section of the knowledge article page layout to hide unwanted fields.
3.  **Case** List and Detail - Flexible layout, update common layout for all record pages.
4.  **Contact** List and Detail - Flexible layout, update common layout for all record pages.
5.  **Contact Support** - Flexible and improved layout.
6.  **Create Record** - Flexible and improved layout.
7.  **Error** \- Updated error page with improved messaging and Home page link.
8.  **Flow** \- Flexible page layout with a flow that is set based on the link parameters (see [Set Variable Values](https://help.salesforce.com/s/articleView?id=sf.flow_distribute_internal_url_variable.htm&language=en_US&type=5) for details).
9.  **Group** List and Detail - Flexible layout, update common layout for all record pages.
10.  **Groups -** Non-object page for display group lists.
11.  **Home** - Flexible page layout with example sections that are used as a starting point. 
12.  **Instructions** \- Builder tasks to complete before publishing your site.
13.  **Learning** - Add CSM, Trailhead, or tasks for onboarding and on-going learning.
14.  **Login** - Updates to all login pages - Login, Check Password, Forgot Password, Login Error, and Register.
15.  **Messages** - Flexible and improved layout.
16.  **News Details** - Flexible layout for the default News CMS content type.
17.  **Page Template** \- Used as a starting point when creating a new page or updating an existing page to a flexible layout. Select the page template when creating a non-object/CMS pages. **Note**: After the page is creates, also change the page SEO title name.
18.  **Question Detail** \- Flexible and improved layout.
19.  **Search** - Add a new theme layout (Search) used to display a hero search.
20.  **Support** - Non-object page for displaying FAQs, and Cases.
21.  **Task** List and Detail - Flexible layout, update common layout for all record pages.
22.  **Topic Catalog** - Titled the page Help Center, and added a theme layout Help Center to display a hero search.
23.  **Topic Detail** - Flexible and improved layout.
24.  **User Detail** \- Flexible and improved layout.
25.  **User Settings** \- Flexible and improved layout.

**Note**: Review the layout and content for all pages listed. Address and remove all builder notes from pages (or assign them to a Builder only audience) before publishing.

---

## References

*   [Trailhead Community](https://trailhead.salesforce.com/today) - Trailhead learning and community groups.
    *   [Greg's Learn Experience Cloud Trailmix](https://trailhead.salesforce.com/users/gjankowski1/trailmixes/learn-experience-cloud) - Learn more about Experience Cloud.
    *   [Greg's Flow Trailmix](https://trailhead.salesforce.com/users/gjankowski1/trailmixes/gregg-flow-trailmix) - Learn more about Flow.
*   [Learn Experience Cloud](https://www.learnexperiencecloud.com/s/) - Resource library and best practices for Experience Cloud.
*   AppExchange Apps for Experience Cloud (AURA):
    *   [Launch Flow in Modal](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000FMYinUAH) (AURA)
    *   [Events Calendar for Experience Cloud (Aura/LWR)](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3u00000ONzaqEAD)
    *   [Spring '21 Salesforce Community Management Package for Sites with Chatter](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3000000B5XHsEAN) 
    *   [Salesforce CRM Dashboards](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N30000004g316EAA) 
*   [Help Experience Cloud](https://help.salesforce.com/s/articleView?id=sf.networks_overview.htm&type=5) - Salesforce help for Experience Cloud.
*   [SLDS (Salesforce Lightning Design System)](https://www.lightningdesignsystem.com/) - Component blueprints and CSS classes for HTML components.
*   [W3Schools](https://www.w3schools.com/css/default.asp) - HTML and CSS references.
