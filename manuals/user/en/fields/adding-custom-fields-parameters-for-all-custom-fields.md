<!-- Filename: J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields / Display title: Adding custom fields/Parameters for all Custom Fields -->

## Parameters for all Custom Fields

The Custom Fields list will be empty initially. Click on **New** to add
a field.

- Title  
  The title of the field. The title will display in the field manager
  page where you can open the field for editing by clicking on the
  title. The title is not displayed when you create an article or an
  contact nor in the frontend.

### General tab

**In the left panel:**

- **Type**  
  If you create a field you can choose one of the 16 field types. When
  you save the field this type is permanent. You can not change it later
  on.
- **Name**  
  The name will be used to identify the field. Leave this blank and
  Joomla will fill in a default value from the title.
- **Label**  
  Use a descriptive text of the field for the label of the field. This
  text is not translatable. If you do not enter any text for a label the
  title text will also used as label text.
- **Description**  
  The description of the field. A text that will be shown as a tool tip
  when the user moves the mouse over the text box while he use it in the
  backend creating an article or a contact or a third party component
  that supports custom fields. This text is not translatable. You do not
  see this description in the frontend.
- **Required**  
  Is this a mandatory custom field? In this case the field has to be
  filled before submitting an article or a contact or a third party
  component that supports custom fields. You can choose the options
  *Yes* or *No*.
- **Only Use In Subform**  
  Explanation required
- **Default Value**  
  Here you can set a default value for the custom field. This text is
  not translatable. Note that in some list fields you have to enter the
  value as default and in others the index.
- **Filter**  
  Choose one of the available options from the dropdown list.
- **Maximum Length**  

**In the right panel:**

- **Status**  
  You can set a publication state. Is the field *Published*,
  *Unpublished*, *Archived* or *Trashed*?
  - Published: The field is visible while editing an article or an
    contact. And it is visible in the Frontend.
  - Unpublished: The field is will not be visible to users while editing
    an article or an contact.
  - Archived: The field will no longer show on edition an article or an
    contact. You can open it in the field manager when you set the
    filter to archived.
  - Trashed: The field is deleted but still in the database. It can be
    permanently deleted from the database with the Empty Trash function
    in Field Manager.
- **Field Group**  
  You can assign a custom field to one or more field groups.
- **Category**  
  You can assign a custom field to one or more field categories. Note
  that the default 'All' does not include 'uncategorised' articles.
- **Access**  
  The viewing [Access
  Level](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/en "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/en")
  for this field.
- **Language**  
  Select the language for this custom field. If you are not using the
  multi-language feature of Joomla, keep the default of *All*.
- **Note**  
  An optional field to make your personal notes for the field.

### Options tab

- **Placeholder**  
  A placeholder text which will appear inside the custom field as a hint
  for the input. The placeholder is active in the Backend while creating
  an article or a contact or a third party component that supports
  custom fields. You do do not see it in the Frontend.
- **Field Class**  
  The class attributes of the field when the field is rendered. If
  different classes are needed, list them with spaces.
- **Edit Class**  
  The class attributes of the field in the edit form. If different
  classes are needed, list them with spaces.
- **Editable In**  
  On which part of the site should the field be shown. In the Backend,
  in the Frontend or both.
- **Label**  
  Show or Hide the label when the field renders.
- **Automatic Display**  
  Joomla offers some content events which are triggered during the
  content creation process. This is the place to define how the custom
  fields should be integrated into content. You can choose 'After
  Title', 'Before Display Content', 'After Display Content' or 'Do not
  automatically display'.
- **Disabled**  
  Should the field be disabled in the edit form.
- **Read only**  
  Should the field be read-only in the edit form.

### Publishing tab

Self-explanator set of fields.

### Permissions tab

Self-explanator set of fields.


