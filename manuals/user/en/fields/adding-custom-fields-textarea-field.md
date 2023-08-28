<!-- Filename: J3.x:Adding_custom_fields/Textarea_Field / Display title: Adding custom fields/Textarea Field -->

## Textarea Field

Provides a text area for entry of multi-line text.

### Options

Special options within this field are:

- Rows  
  The height of the visible text area in lines. If omitted the height is
  determined by the browser. The value does not limit the number of
  lines that may be entered. The rows are active in the backend while
  creating an article or a contact or a third party component that
  supports custom fields. This option has no impact on the size of the
  field in the frontend.
- Columns  
  The width of the visible text area in characters. If omitted the width
  is determined by the browser. The value does not limit the number of
  characters that may be entered. The cols are active in the backend
  while creating an article or a contact or a third party component that
  supports custom fields. This option has no impact on the size of the
  field in the frontend.
- Maximum Length  
  The maximum number of characters that can be entered.
- Filter  
  Allow the system to save certain html tags or raw data.

### Related Information

See [Textarea form field
type](https://docs.joomla.org/Textarea_form_field_type "Special:MyLanguage/Textarea form field type")

### Screenshots

#### Creating the field

Let's say you create a field with the options shown in the next figure.

<img
src="https://docs.joomla.org/images/thumb/f/f2/Textarea_field_create-en.png/800px-Textarea_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f2/Textarea_field_create-en.png/1200px-Textarea_field_create-en.png 1.5x, https://docs.joomla.org/images/f/f2/Textarea_field_create-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Textarea field create-en.png" />

#### Using the field in the backend

In the backend while creating an article or a contact you see the field
like in the following imageː

<img
src="https://docs.joomla.org/images/thumb/d/dc/Textarea-en.png/800px-Textarea-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/dc/Textarea-en.png/1200px-Textarea-en.png 1.5x, https://docs.joomla.org/images/d/dc/Textarea-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Textarea-en.png" />

#### Using the field in the frontend

In the frontend, you can see the field as you see in the following
image. The option *Automatic display* is responsible for the position of
the field and your template is responsible for the design of the
field.

Fields are only displayed in the frontend if you have filled them with
data in the article. If it is not a required field, can you forget it?

<img
src="https://docs.joomla.org/images/thumb/4/4e/Textarea_field_frontend-en.png/800px-Textarea_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4e/Textarea_field_frontend-en.png/1200px-Textarea_field_frontend-en.png 1.5x, https://docs.joomla.org/images/4/4e/Textarea_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Textarea field frontend-en.png" />
