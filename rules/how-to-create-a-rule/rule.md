---
type: rule
archivedreason: Moved to GitHub - https://github.com/SSWConsulting/SSW.Rules.Content/wiki/How-to-Create-Rules
title: SharePoint - Do you know how to create a rule? (internal only)
guid: fb70a2dd-5d5d-47cc-bbd8-1a6d954fce20
uri: how-to-create-a-rule
created: 2014-02-21T20:16:54.0000000Z
authors:
- title: Adam Cogan
  url: https://ssw.com.au/people/adam-cogan
- title: Tiago Araujo
  url: https://ssw.com.au/people/tiago-araujo
related: []
redirects:
- do-you-know-how-to-create-a-rule-(internal-only)
- sharepoint-do-you-know-how-to-create-a-rule-internal-only
- sharepoint-do-you-know-how-to-create-a-rule-(internal-only)

---

This is how you create a rule at  **rules.ssw.com.au** . 
<!--endintro-->

1. Log in to [http://rules.ssw.com.au/admin/Pages/default.aspx](/admin/Pages/default.aspx)
2. Click on “Add a page” 
![](create-rule1.jpg)  
 **Note:** Each rule will be a “page” on SharePoint – with its own URL - differently from old aspx, where rules were sections on a single page.
3. Add the URL 
![](create-rule2.jpg)  
    **Note:** We use only the most important words of a rule title. The words in  **purple**  are typically not used.
    E.g. #1 “ **HTML/CSS - Do you know how to create spaces in a web page?** ” should be “http://rules.ssw.com.au/WebSites/RulesToBetterWebsitesLayout/Pages/<mark>How-to-create-spaces-in-a-web-page</mark>.aspx”
    E.g. #2 “ **Do you use "list" tags for lists only?** ” should be “http://rules.ssw.com.au/WebSites/RulesToBetterWebsitesLayout/Pages/<mark>Use-list-tags-for-lists-only</mark>.aspx”

Note: Friendly URL should be automatically generated like:
 <img src="auto-generate-friendlyurl.jpg" alt="auto-generate-friendlyurl.jpg" style="margin:5px;width:550px;"> 
4. Add the rule title  <img alt="Create Rule" src="create-rule3.jpg" style="margin:5px;"> 
5. Add the rule category (so that it will be shown on the summary page):  <img src="add-rule-category.jpg" alt="add-rule-category.jpg" style="margin:5px;width:650px;"> 
6. **IMPORTANT** – Adding rule intro + content    You have three options:

    1. **Option 1** – Start from scratch - Write content down on the fields
    2. **Option 2** - Paste the content from another place - a HTML page on the browser or a Word document         Warning: Select the “ **Paste Plaintext** ” when pasting or you will have a lot of work later


::: bad  
![Figure: Terrible example of a HTML generated by pasting normally – not plaintext. All the margins, font family, external images aren’t necessary](create-rule5.jpg)  
:::


::: good  
![Figure: Good Example - If you don’t select this, SharePoint will generate a lot of inline styling, which will cause triple work to fix](create-rule4.jpg)  
:::
        Since you have pasted the plain text, you’ll need to manually add the styling - headings, links, captions etc.

![Figure: Add the styles. In SharePoint is very similar to Microsoft Word. The custom styles will have pretty much everything you'll need without having to touch the HTML code](create-rule6.jpg)  

    3. **Option 3**- Paste the HTML code (recommended if you already have the content in the internet and the HTML is neat enough)
        1. Open up and copy the HTML code (from “view source” on a browser)
        2. Go back to SharePoint (where you are adding the rule)
        3. Click in the field you are going to edit
        4. In the “Format Text” ribbon, click “Edit Source” 
![](create-rule7.jpg)  

        5. Paste the HTML there 
![](create-rule8.jpg)  

        6. Now fix up the images – This part is a bit painful
            * Firstly you will need to save all the images to your local drive
            * We don’t use the "Insert &gt; Picture" on the ribbon because it doesn’t generate the HTML code we use as default as per [Do you use the right HTML/CSS code to add the useful figure/caption?](http://www.ssw.com.au/ssw/Standards/Rules/RulestoBetterWebsiteslayout.aspx#AddFigureWithRightCode)
            * Instead, upload them to the Images folder - http://rules.ssw.com.au/<mark>PublishingImages</mark>/
                * Go to “Site Contents” 
![](create-rule9.jpg)  

                * Click on “Images” 
![](create-rule10.jpg)  

                * Drag the images from your local drive to the Images folder in SharePoint: 
![](create-rule11.jpg)  

                * Make sure you “Check In” all the images (otherwise they won’t be visible for anonymous users) 
![](create-rule12.jpg)  

                * On the screen above you can see the path for each image. Copy it so you can paste into the HTML.
E.g. &lt;img src=”<mark>http://rules.ssw.com.au/Communication/RulesToBetterBlogging/PublishingImages/RulesBloggingAcknowledgeBad.jpg</mark>"&gt;
        7. Double check the links – you might have got a relative link E.g.  **&lt;a href=”<mark>../</mark>company/Offices.aspx”&gt;** which will not work because it’s now on a different site.
So you will nee d to make it absolute E.g.  **&lt;a href=”** [**<mark>http://www.ssw.com.au/</mark>ssw/company/Offices.aspx**](http://www.ssw.com.au/ssw/) **”&gt;**
7. Add the rule intro    Try to have a catch at the end so the user will want to read the rest of the rule. E.g. “ To reply to a bug effectively and efficiently in your emails, you need to include:”

![](create-rule13.jpg)  

![Figure: The “Brief Blurb” should clearly explain what the rule is about and have a catch at the end](create-rule14.jpg)  

8. Add the rule content 
![](create-rule15.jpg)  

9. [Add the acknowledgements](/do-you-add-acknowledgements-to-every-rule) 
![](create-rule16.jpg)  

10. Hit “Publish”, add your comments and “Continue” 
![](create-rule17.jpg)  
    **Note:** "Check in a major version"  **equals** "Publish", so you can choose to "Check in a major version" instead of "Publish".
11. Test on a browser you aren’t logged in. 
 **Tip:** In Chrome, select “New Incognito Window” 
![](create-rule18.jpg)  

12. Check on the summary page (e.g. http://rules.ssw.com.au/<mark>RulesToBetterSomething</mark>/ ) if the order is correct 
If not it’s not correct, you can change the order of rules by following the instructions as per the section below:

![](create-rule19.jpg)  
**Tip:** You might need to refresh the cache – See “Rule Cache Management” also on the section above.


Congratulations, you’ve just added a rule!

To increase traction in the community you should now tweet and Facebook it.


::: greybox
E.g. “I just added a rule on http://rules.ssw.com.au/Communication/RulesToBetterSomething/Pages/How-to-do-something-right.aspx@SSW\_TV #SSWRules”  
:::
