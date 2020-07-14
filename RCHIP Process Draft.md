
# RChain Improvement Process (RCHIP Process) - Draft


    **Created by **


    **[Medha Parlikar (Unlicensed)](https://rchain.atlassian.net/wiki/people/557058:1aa9d7d9-51f2-419e-a5b0-47773dfc7e6a?ref=confluence&src=profilecard)**


    **Last updated [May 23, 2020](https://rchain.atlassian.net/wiki/pages/diffpagesbyversion.action?pageId=564068682&selectedPageVersions=18&selectedPageVersions=19) by **


    **[Dan Connolly](https://rchain.atlassian.net/wiki/people/557058:1bdbe0bb-1fbb-4602-974d-9bd6114fe760?ref=confluence&src=profilecard)**


    

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

**[Analytics](https://rchain.atlassian.net/plugins/servlet/ac/com.addonengine.analytics/com.addonengine.analytics__analytics-content-byline-item?page.id=564068682&space.key=CORE&content.id=564068682&content.version=19&page.type=page&page.title=RChain%20Improvement%20Process%20%28RCHIP%20Process%29%20-%20Draft&space.id=65714&content.type=page&page.version=19)**


**This document seeks to propose a process by which updates to the RChain blockchain are defined, approved, prioritized and released.**


**See [RCHIP issue #14](https://github.com/rchain/rchip-proposals/issues/14) for more recent discussion.**


## 
Tooling:


**The RChain feature backlog is captured in Jira at: [http://rchain.atlassian.net](http://rchain.atlassian.net/) at: [https://rchain.atlassian.net/secure/RapidBoard.jspa?projectKey=RIP&rapidView=19&view=planning.nodetail](https://rchain.atlassian.net/secure/RapidBoard.jspa?projectKey=RIP&rapidView=19&view=planning.nodetail)**


**The RChain Improvement Proposals are captured in Confluence at: [RChain Improvement Proposals](https://rchain.atlassian.net/wiki/spaces/RIP)**


## 
Actors:


<table>
  <tr>
   <td>
<strong>Role</strong>
   </td>
   <td>
<strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Feature Requestor</strong>
   </td>
   <td>
<strong>This is someone or a group of someones who have an idea for an improvement to the RChain platform.</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Editorial Committee</strong>
   </td>
   <td>
<strong>This is a committee of RChain members charged with the following for each RCHIP submitted by a Feature Requestor:</strong>
<ul>

<li><strong>Reading the RCHIP to check if it is ready: sound and complete. The ideas must make technical sense, even if they don't seem likely to get to final status.</strong>

<li><strong>The title should accurately describe the content.</strong>

<li><strong>Check the RCHIP for language (spelling, grammar, sentence structure, etc.)</strong>
<p>

<strong>If the RCHIP isn't ready, the Editorial Committee will send it back to the Feature Requestor for revision, with specific instructions.</strong>
<p>

<strong>Once the RCHIP is ready for the consideration for the next step the Editorial Committee will continue to support the RCHIP through the process.</strong>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>
<strong>Development Team PM</strong>
   </td>
   <td>
<strong>Supports the process in various roles, primarily as a liaison between others involved in the RCHIP process and the Development Team.</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Development Team</strong>
   </td>
   <td>
<strong>This is the team of developers supporting the development and maintenance of the platform.</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Approval Committee</strong>
   </td>
   <td>
<strong>This is a committee of RChain members charged approving RCHIPs for analysis and estimation, and then making a recommendation to the board of directors based on prioritization criteria and goals of the RChain Cooperative.  Recommend that this committee be comprised of individuals covering all aspects of the RChain Ecosystem, such as members, dApp Developers, Validators and Core developers.  Recommend that the approval committee be no more than 7 individuals & be an odd number.</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>RChain Cooperative Board</strong>
   </td>
   <td>
<strong>The legal board of the RChain Cooperative</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Membership</strong>
   </td>
   <td>
<strong>Members of the RChain Cooperative</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Strategic Partners</strong>
   </td>
   <td>
<strong>Individuals affiliated with with RChain's holding companies or members of partnering organizations</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Stakeholders</strong>
   </td>
   <td>
<strong>Members of the public interested in the use and functionality of the RChain platform.</strong>
   </td>
  </tr>
</table>



## 
Process:


### 
Specify the Feature 


**A feature request should be proposed in written format.  For small features, a Jira Story issue is suitable.**


**If a feature cannot be implemented within a single component (Interpreter, Consensus, Node), then an Epic is required.  An Epic should contain a link to a document that describes the feature with enough specificity that an Engineering plan can be drafted and estimation can take place.**


#### 
**Required Information:**



*   **Category for Prioritization**
*   **Score for Category from 1 → 10 (1 being lowest, 10 being greatest)**
*   **Metrics to measure success (specific goal that justifies the score)**
*   **Detailed description of the feature & benefits**
    *   **Does the feature open up new markets, if so how?**
    *   **Are users blocked from doing something without the feature? Or is this a UX change?**
    *   **Are there contractual obligations related to the feature? (This alone won't bump priority. Contracts should never be signed against un-implemented features)**

#### 
**RACI**


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Feature Requestor</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>Editorial Committee</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Development Team PM</strong>
<p>

<strong>Strategic Partners</strong>
<p>

<strong>Stakeholders</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Membership</strong>
   </td>
  </tr>
</table>



### 
Approval for Analysis


**Proposed features should be vetted for completeness appropriateness and value before being analyzed.  Analysis is a costly process, and should not be applied to all proposed features without some kind of prior vetting.**


#### 
**Criteria:**

*   **Is the request complete?**
    *   **Category present & Scored?**
    *   **Feature is described with enough detail for analysis**
    *   **Metrics to measure success are described**
    *   **Acceptance criteria are described sufficiently.**

#### 
**RACI**


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Development Team PM</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>Approval Committee</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Core Development Team</strong>
<p>

<strong>Strategic Partners</strong>
<p>

<strong>Feature Requestor</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Membership</strong>
   </td>
  </tr>
</table>



### 
Analysis & Estimation


**Once a feature has been specified and approved for analysis, the engineering team performs an analysis and proposes an implementation.  This analysis will include the following:**

*   **A review of the specification / description of the feature. **
*   **High level design.**
*   **Estimate of effort in story points.**
*   **Tickets for the work along with the estimate are linked into the wiki page as individual ticket links (for the purpose of history tracking of scope changes)**

**This part of the process will likely involve a good deal of back and forth between the requestor and the development team, until agreement on the details of the feature is reached.  Additionally, the feature may be re-scoped or re-sized as a result of these discussions.**


#### 
**RACI**


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Development Team</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>Development Team PM</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Feature Requestor</strong>
<p>

<strong>Approval Committee</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Membership</strong>
   </td>
  </tr>
</table>



### 
Approval for Implementation


**Once estimated, the feature should be approved for implementation.  If the feature presents as a hard fork, then approval from the validator pool is needed, to prevent a fork of the platform when the update is applied.**

*   **There is a way for validators to signal their approval for the feature?**
*   **There is a way for the CoOperative to signal their approval for the feature.**
*   **This mechanism should be auditable and transparent.**
*   **There needs to be some measure of a number of votes / approvals to signal consent.**
*   **The Approval Committee should set the threshold for the number of votes to signal consent.**
*   **Recommend that voting take place inside an issue, where persons can 'vote' on the approval for implementation.  The votes will be tallied & an image captured on the implementation wiki page.**

#### 
**RACI**


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Approval Committee</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>RChain Cooperative Board</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Membership</strong>
<p>

<strong>Development Team PM</strong>
<p>

<strong>Feature Requestor</strong>
<p>

<strong>Strategic Partners</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Membership</strong>
   </td>
  </tr>
</table>



### 
Prioritization 


**Once the above items have taken place, the feature will be slated into a release vehicle and the tickets will be assigned to a sprint.  The prioritization of the feature will depend on its priority relative to other items on the backlog.   Prioritization of work is a challenge.  Recommendation is that all RCHIPs be categorized into 1 of these categories, and given a relative weight in terms of value. **


#### 
**Strategic Categories**


<table>
  <tr>
   <td>
<strong>Category</strong>
   </td>
   <td>
<strong>Description</strong>
   </td>
   <td>
<strong>Examples</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Growth</strong>
   </td>
   <td>
<strong>Increase in Platform Adoption</strong>
   </td>
   <td>
<ul>

<li><strong>New Rholang feature to facilitate dApp Development</strong>

<li><strong>New features to incentivize Validators</strong>

<li><strong>Support for new platforms.</strong>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>
<strong>Reduce Risk</strong>
   </td>
   <td>
<strong>Reduce Risk for the CoOperative or the platform</strong>
   </td>
   <td>
<ul>

<li><strong>Security Fixes</strong>

<li><strong>OS Security patches</strong>

<li><strong>Security enhancements</strong>

<li><strong>Economics updates to further secure the network</strong>

<li><strong>Fixes to secure contracts</strong>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>
<strong>Tech Debt</strong>
   </td>
   <td>
<ul>

<li><strong>Refactoring to make code base more stable and performant and easier to maintain.</strong>

<li><strong>Updates/Upgrades that improve developer productivity.</strong>

<li><strong>Should be given a bit more weight when prioritizing, else tech debt doesn't make it on to the stack.</strong>
</li>
</ul>
   </td>
   <td>
<ul>

<li><strong>Upgrade to latest version of Java</strong>

<li><strong>Upgrade build system</strong>

<li><strong>Update versions of libraries & dependencies</strong>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



#### 
**Prioritization Process**


**The Board of Directors should define the goals / theme for the platform.   The goals for the platform should be set annually. Doing this more frequently isn't productive.  Examples of such goals are:**



*   **_"By the end of 2019, there will be 100 dApps & 100,000 transactions / week on the platform"_**
*   **_"By the end of 2019, there will be 1000 developers proficient in Rholang"_**
*   **_"By the end of 2019, the CoOperative membership will have grown to 100,000"_**
*   **_"By the end of 2019, all governance tools for the CoOperative will operate on the RChain platform"_**

**Recommend that no more than 2 goals be set (1 for platform, 1 for CoOperative) for any given period.  Any more than that, creates confusion.  Recommend that the goal be annual.  Any shorter than that, results in the same effect as having too many goals.**


**Using this theme, a prioritization committee can use the [https://articles.uie.com/kj_technique/#close](https://articles.uie.com/kj_technique/#close) technique to prioritize the RCHIPs and communicate the priorities to the Development Team PM.   **


#### 
**RACI**


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Approval Committee</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>RChain Cooperative Board</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Development Team PM</strong>
<p>

<strong>Strategic Partners</strong>
<p>

<strong>Feature Requestor</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Membership</strong>
<p>

<strong>Stakeholders</strong>
   </td>
  </tr>
</table>



### 
Implementation


**The feature is implemented & Tested by Development**


### 
Acceptance testing & Release readiness


**The feature is deployed to the public test net for acceptance testing.  Stakeholders have the opportunity to examine the patch on their own systems.**


**The acceptance testing process must also include release readiness criteria.  **


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Development Team</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>Development Team PM</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Feature Requestor</strong>
<p>

<strong>Approval Committee</strong>
<p>

<strong>RChain Cooperative Board</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Membership</strong>
<p>

<strong>Strategic Partners</strong>
<p>

<strong>Stakeholders</strong>
   </td>
  </tr>
</table>



### 
Release


**The feature (release package) is deployed to the public network.**


<table>
  <tr>
   <td>
<strong>RACI</strong>
   </td>
   <td>
<strong>Party</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Responsible</strong>
   </td>
   <td>
<strong>Development Team</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Accountable</strong>
   </td>
   <td>
<strong>Development Team PM</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Consulted</strong>
   </td>
   <td>
<strong>Feature Requestor</strong>
<p>

<strong>Approval Committee</strong>
<p>

<strong>RChain Cooperative Board</strong>
   </td>
  </tr>
  <tr>
   <td>
<strong>Informed</strong>
   </td>
   <td>
<strong>Stakeholders</strong>
<p>

<strong>Membership</strong>
   </td>
  </tr>
</table>

