<style>
 p img{height:100px;width:auto}
</style>
# Creating a Clause

The "Clause" in ContractStandards is the umbrella page to organize and provide general guidance for the Clause's underlying Clause Alternatives. This is where users will provide general information that applies to that type of Clause. Think key points like a common heading name, general description, and in-depth discussion/guidance.

Clauses will have Clause Alternatives, or the context-specific variants of a Clause. For instance, a library may have a "Definition of Confidential Information" Clause that has three Clause Alternatives to be used in different scenarios. One Alternative may be used when the Confidential Information is technical information. Another might be used when the dealing with business information.

This article will illustrate how to create a Clause and some Clause Alternatives from scratch or import data from the ContractStandard Public Library.

## From Scratch
1. Login to your ContractStandards Account.

2. Navigate to the Admin View. ![user menu][user-name]

3. Navigate to the Clause table in the Admin View. ![nav sidebar][nav-sidebar]

4. Select the green "New Clause" button above the Clause table.

5. In the dropdown menu, select "Add New Clause". This will take you to the New Clause screen ![nav sidebar][nav-sidebar]

6. Fill out the New Clause Form. Note that Heading, Filename, Description, and Clause Language are required fields.

  * "Heading" should be something descriptive but generic. Users will have an opportunity to specify contract or context-specific alternatives later. Here, you are providing a name for the general Clause.

  * "Filename." Click on the magic wand icon to generate a filename based on the Heading. Although the filename is editable, it should mirror the Heading. ContractStandards will automatically prepend the Private Library name to any filename. So, a Clause called "Governing Law" in the Acme Library will have a filename "acme-governing-law." Keep this in mind when creating content.

  * "Description." The Description should be a general overview of the purpose of the Clause and maybe a few lines on the differences between the Clause Alternatives. This should be nothing more than a few sentences. Users will have an opportunity to add in-depth analysis in the "Discussion" section.

7. Fill in optional fields.

   * "Clause Taxonomy." Use the ContractStandards Clause Taxonomy to tag clauses by type.

   * "Discussion." This is a free-form where users can add in-depth analysis of this Clause. For Private Libraries, this section was intended to serve as a way to share institutional knowledge about a Clause. When is this Clause appropriate? Are there certain considerations that would guide the use of different Clause Alternatives? Have you had experiences with specific vendors or clients that might guide Clause Alternative choice?

   * "Key Question." Provide a central question that will help users choose between Clause Alternatives. For instance, with a "Definition of Confidential Information" Clause, the Key Question might be "What kind of information is being exchanged?". When the user creates different Clause Alternatives, they will label each Alternative with an Answer to that question (e.g., "Technical Information").

8. Click the "New Alternative" button to add a Clause Alternative ![new alternative button][new-alternative-btn]

9. A window will appear with a New Clause Alternative Form ![new alternative form][new-alternative-form]

10. The New Clause Alternative Form

  * "Answer." This is the Clause Alternative's label. It should generally be an answer to the Key Question.

  * "Contract Type." Tag the Clause Alternative to a specific type of Contract. This is helpful when users want to provide guidance on the appropriate context for this Alternative.

  * "Party-Weight." Choose from five preset party weights. A Clause Alternative can be "Pro-Provider," meaning it favors the party providing the services, license, goods, information, etc, "Pro-Providee," meaning the recipient of whatever is provided, and "Neutral."

  * "Standard." Check this box if this Clause Alternative is considered the Standard version of this type of Clause. This is a useful way to set the organization's default, preferred Alternative. Users must mark at least one Clause Alternative as "Standard."

  * The Clause Alternative Language. Enter the Clause Alternative's text.

11. Publish the Clause Alternative

12. Scroll back up to the top of the page and Publish the Clause

[user-name]: img/user-menu.png
[nav-sidebar]: img/nav-sidebar.png
[new-clause-btn]: img/new-clause-btn.png
[new-alternative-button]: img/new-alternative-btn.png
[new-alternative-form]: img/new-alternative-form.png
