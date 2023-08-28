<!-- Filename: J3.x:Adding_custom_fields/Media_Field / Display title: Adding custom fields/Media Field -->

## Media Field

Provides modal access to the media manager for insertion of images with
upload for users with appropriate permissions.

### Options

Special options within this field are:

- Directory  
  The default image directory for this field. The Media field inherently
  defaults to the main /images folder, so anything entered into the
  Directory field is assumed to be inside the images folder. So if you
  wish your default folder to be https://docs.joomla.org/images/myimages
  you would simply enter myimages into the Directory field.
- Preview  
  Shows or hides the preview of the selected image.
- image class  
  The class which is added to the image.

### Related Information

See [Media form field
type](https://docs.joomla.org/Media_form_field_type "Special:MyLanguage/Media form field type")

### Screenshots

#### Creating the field

Let's say you create a field with the options shown in the next figure.

<img
src="https://docs.joomla.org/images/thumb/a/a0/Media_field_create-en.png/800px-Media_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a0/Media_field_create-en.png/1200px-Media_field_create-en.png 1.5x, https://docs.joomla.org/images/a/a0/Media_field_create-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Media field create-en.png" />

#### Using the field in the backend

In the backend while creating an article or a contact you see the field
like in the following imageː

<img
src="https://docs.joomla.org/images/thumb/3/35/Media-en.png/800px-Media-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/35/Media-en.png/1200px-Media-en.png 1.5x, https://docs.joomla.org/images/3/35/Media-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Media-en.png" />

And if you click on it, a modal window will open and you can select an
image in here. <img
src="https://docs.joomla.org/images/thumb/5/57/Media_2-en.png/800px-Media_2-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/57/Media_2-en.png/1200px-Media_2-en.png 1.5x, https://docs.joomla.org/images/5/57/Media_2-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Media 2-en.png" />

#### Using the field in the frontend

In the frontend, you can see the field as you see in the following
image. The option *Automatic display* is responsible for the position of
the field and your template is responsible for the design of the
field.  
Fields are only displayed in the frontend if you have filled them with
data in the article. If it is not a required field, can you forget it?

<img
src="https://docs.joomla.org/images/thumb/e/e9/Media_field_frontend-en.png/800px-Media_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e9/Media_field_frontend-en.png/1200px-Media_field_frontend-en.png 1.5x, https://docs.joomla.org/images/e/e9/Media_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Media field frontend-en.png" />
