# Google Analytics Academy

[Analytics for Beginners](https://analytics.google.com/analytics/academy/course/6?utm_medium=email&utm_source=registration)

### Introducing Google Analytics

#### Why digital analytics
Marketing basic purchase funnel

1. Acquisition - (acquire user interest, and build awareness)
2. Behaviour - user engagement
3. Conversion - when user transacts, and becomes a customer
<p>
  Online purchases - have ability to track what behaviours led to purchases<br />
  Physical purchases - not easy to track how marketing affected purchasing behaviour
</p>

<p>
  Publishers - use analytics to create loyal, highly engaged audience, and align on-site advertising<br />
  Ecommerce - use analytics to understand customers' purchasing behaviour for better marketing<br />
  Lead Generation - use ananlytics to collect user information that get distributed to sales teams on potential leads
</p>

#### How Google analytics works

Essentially a platform that collects data, and compiles into reports

1. Create account
2. Add small bit of js to each site page &lt;script&gt;, and &lt;noscript&gt;

<p>
  Collects anonymous informations about how person interacted with page<br />
  1. Click locations, and number of page visits<br />
  2. Browser, Language, device, and OS<br />
  3. Referring page eg. Search engine, or email marketing campaign (utm_source)<br />
</p>

<p>
  Each page load results in updated metrics being sent to Google. This is bundled into a particular session for that user. Session ends after thirty minutes of inactivity.
</p>

<p>
  Each session aggregates up into reports, which is initially filtered by device, or browser, but these are configurable via settings, and filters (Country, or remove internal company traffic). <b>NB</b> Once data is stored it cannot be changed - DB perms INSERT, and SELECT only. Once processing has occurred it becomes available as reports.  
</p>

#### Google analytics setup

Organisation -> Account -> Property -> View <br />
Single organisation<br />
Multiple accounts, properties, and views<br />
Large business - generally multiple accounts<br />
Medium to small business - generally one account<br />

**Goals**
Ways of tracking business objectives, or conversions

**Views**
1. Do NOT include past data (creation date onwards only)
2. Can be restored if deleted by an admin for a limited time only

**Permissions**
Top down: Account -> Property -> View
1. Manage users: Add/remove user access
2. Edit: Change config settings
3. Collaborate: Share data slices, or settings
4. Read and analyze: Read only access to data - can create new dashboards
<p>
  <b>NB</b> Be careful on how you setup accounts, properties, and views. Can impact data collection. Align properties, and views with overall business structure
</p>

#### How to set up views with filters

**NB** View filters are applied in order that they are added to a view - be mindful here.<br />
Good idea to have the following views
1. Raw Data (All Website data (raw unfiltered stuff))
2. Test View (Use this to apply filters, as a test of process before applying to Main View)
3. Main View (Live production reporting with any filters as applied from Test View)


### The Google Analytics Interface

#### Navigating Google analytics
1. Real Time - live user behaviour
2. Audience - characteristics about your users (age, gender, location, engagement, etc.)
3. Acquisition - what brought user to site
  * Organic (unpaid search)
  * Cost per Click (paid search)
  * Referral
  * Social (eg Facebook)
  * Other (low volume)
4. Behaviour - what pages were interacted with (landing|exit pages etc.)
5. Conversion - track website goals based on buisness objectives

#### Understanding overview reports
Provide high level overview in one place<br />
Audience overview - aggregate audience metrics (bounce rate, avg. session length, no. of pages visited)<br />
Date range selector - affects all reports in current view<br />
Audience overview line graph is number of users in date range<br />
Metrics > Dimensions - a dimension is finer grained than a metric - eg colour of shirt sold

#### Understanding full reports
- Summary view: Selected dimension split by Acquisition, Behaviour, and Conversion - simple to interpret as part of basic marketing funnel
- Site usage: Behaviour metrics like user, pages per session, and session duration
- Goals: Tracked goals. Only displayed if goals set up
- Ecommerce: Transaction metrics, if ecommerce set up in GA

Available views
- Data table (default) - tabular data
- Pie chart -compare percentage of whole
- Performance - side by side comparison (bar chart)
- Comparison view - red/green perfomance indicator v site average (bar chart)
- Pivot - pivot table (rows and columns can show different dimensions) eg bounce rate by country

#### How to share reports
- Save: Link to report under Customization -> Saved Reports
- Export: Save to PC in different file formats (csv|pdf)
- Share: Email report to x@y.tld. Can be scheduled
- Edit: Customize report content (metric groups|filters|additional views). Adds new report under Customization

Badge next to report name allows you to change sampling rate. Can be an estimate rather than true reflection based on data set size. Options are:
- Faster response (estimate based)
- Greater precision (uses data, but takes longer to process)
