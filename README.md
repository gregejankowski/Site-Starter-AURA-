# Experience Cloud Site Starter (AURA)
The Experience Cloud Site Starter (AURA) is a mobile 1st site design for a self-service site using best practices (e.g., flexible pages), using no-code, low-code,  CSS, and HTML components.

This package contains:
* **Site Starter (AURA) Template**
    This template provides a clean theme (minimal pages) using flexible layouts for all pages.
    Templates are selected when creating a new site or changing the Template. This will overwrite all site pages and the theme. 

* **Builder Notes**
    The site includes builder notes as an aide to help setup and configure the pages. These notes should be removed before publishing the site.
   
* **Page Template**
    When creating or update a non-object and non-CMS page types, a page layout called **Template** is included to get a new page started. 


## Installation and Setup

**Notes:**
1. **Read the instructions carefully** and complete the tasks before publishing. There are additional instructions and details 
2. This package is **supplied as-is** and is not supported by Salesforce.
3. CSS files are included as static resources and referenced in the Head Markup. CSS can change from release to release and has the potential to visually impact other components within the Experience Cloud site. The site CSS is reviewed for each release, but is *supplied as-is*.
4. No CMS or Knowledge content included.

**Installation**

1. Enable and setup Experience Cloud on your site (if it is not already enabled).
2. Install the package
   [Experience Cloud - Site Starter (AURA)](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t5f000000irO6) Spring '22 v1.2

**Create a New Site**

1. Open the **Digital Experiences** app and then open the **All Sites** tab.
2. Click **New**.
3. Select **Site Starter (AURA)**.
4. Add the site **Name** and site **URL** (optional).
5. Complete the site configuration steps.

*Note*: Creating a new site in larger orgs can take a long time, and may timeout. A workaround for this is to create a new site with the desired name, select the BYO (AURA) templace. Once created, go to Workspace / Administration / Settings / Change Template.  
*Warning* - This will completely overwrite the site, only use this method when creating a new site.

**Update an Existing Site**

*Warning* - This will completely overwrite the existing site (all pages and theming).

1. Go to Workspace / Administration / Settings / Change Template.
2. Select *Site Starter (AURA)*.
3. Add the site *Name* and site *URL* (optional).
4. Complete the site configuration steps.


## Site Configuration

1. Update the sites' Head Markup (Experience Builder / Settings / Advanced / Edit Head Markup) from [Head-Markup.html](./Head-Markup-Site-Starter.html) and paste it into the sites’ Head Markup.
2. Review the Head Markup and update the site markup and allow (optionally) for icon use. 
    1. To add a site favicon, upload a static resource, share it publicly, and update the file name in the head markup.
    2. Allows for the use of Font Awesome icons in HTML components (examples; info boxes, builder notes, section headings with tooltips, etc.). 
        Add *http://cdnjs.cloudflare.com* to *Setup* / *CSP Trusted Site Definition*, and *Allow for* font-src and style-src.
    3. Three different CSS files are included as static resources and are referenced with the Head Markup:
        - ExpCloudCSSBuilderComponents - CSS overrides to make Builder components styling more consistent.
        - ExpCloudCSSFonts - CSS CSS related font and button styling.
        - ExpCloudCSSforHTML - CSS used on HTML components within the site.
    3. Complete site branding and the additional configuration and setup steps listed in the Instructions page of the site.
    4. Configure Knowledge and Salesforce CMS (as needed).
    5. Complete pages based on user journeys and provide content, links, and components where applicable.


## Pages

The following pages have been included and updated in this theme. The theme can be used to update an existing site (Workspace / Administrator / Settings / Template, or create a new site. 

1. *Account Detail* - Flexible and improved layout.
2. *Article Detail* - Flexible and improved layout. Uses CSS to hide all but the 1st section of the knowledge article page layout to hide unwanted fields.
3. *Case Detail* - Flexible and improved layout.
4. *Create Record* - Flexible and improved layout.
5. *Contact Support* - Flexible layout.
6. *Error* - Updated error page with improved message.
7. *Groups* - Non-object page for displaying active and my groups lists.
8. *Group Details* - Flexible and improved layout.
9. *Home* - Flexible and improved layout. **
10. *Instructions* - Builder tasks to complete before publishing your site.
11. *Learning* - Add CSM, Trailhead, or tasks for onboarding.
12. *Login* - Includes a new LoginWide theme layout and all loing related pages were update.
    1. All login pages - Login, Check Password, Forgot Password, Login Error, and 
13. *Messages* - Flexible and improved layout.
14. *Page Template* - Used as a starting point when creating a new page or updating an existing page to a flexible layout. 
    Note: After the page is creates, also change the page SEO title name. 
15. *Question Detail* - Flexible and improved layout.
16. *Search* - Add a new theme layout (Search) used to display a hero search.
17. *Support* - Non-object page for displaying FAQs, and Cases.
18. *Topic Catalog* - Titled the page Help Center, and added a theme layout Help Center to display a hero search.
19. *Topic Detail* - Flexible and improved layout.
20. *User Detail* - Flexible and improved layout.
21. *User Settings* - Flexible and improved layout.

Note: Review the layout and content for all pages listed. Address and remove all builder notes from pages before publishing.


## Recommended Apps and Components 

The following Salesforce Labs apps from the AppExchange that can help enhance your site experience:

1. Launch Flow in Modal (https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000FMYinUAH)
2. Events Calendar for Experience Cloud - Salesforce Labs (https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3u00000ONzaqEAD)
3. Knowledge Article Body Content for Experience Cloud (https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3u00000MBbGUEA1)
4. Spring '21 Salesforce Community Management Package for Sites with Chatter (https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3000000B5XHsEAN)
5. Salesforce CRM Dashboards (https://appexchange.salesforce.com/appxListingDetail?listingId=a0N30000004g316EAA)


