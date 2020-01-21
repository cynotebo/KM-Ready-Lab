# Adding Skillsets

We are now going to explore how you can add some very powerful skillsets to your search index through the Azure Portal Skillsets editor.  This new capability provides a series of JSON templates that you can easily add and modify to suit your customers needs.  For the purposes of today's lab, we will be working with the **Custom Entity Lookup** skill to add a disease lookup skill to our index.

Click on *Azure Cognitive Search* and then select *Skillsets*.  You should see the **clinical-trials-small** index and can note that it currently contains 4 skills.

![](images/skillset1.png)

Click on your index and then select **Skillset Definition (JSON)** to view the skillset JSON editor in the Azure Portal.

![](images/skillset2.png)

![](images/json1.png)

On the right had side,  you see the Skill Definition Templates that are provided in the Azure Portal.  Click on the drop down arrow in *Skills* and note the variety of templates that are available.  Click on the *Custom Entity Lookup* skill.

Let's look a little deeper at this JSON template...

Now, click on the *Copy to clipboard* icon at the far bottom right of your screen.

![](images/clipboard.png)

We are now going to add this skill to your skillset JSON file.  Please your cursor, directly under **skills** , hit return to create a new line and then paste the contents of the clipboard into the JSON file.

Modify the words list....

Click Save.....
