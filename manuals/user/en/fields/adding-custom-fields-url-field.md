<!-- Filename: J3.x:Adding_custom_fields/Url_Field / Display title: Adding custom fields/Url Field -->

## URL Field

Provides a URL text input field.

### Options

Special options within this field are:

- Schemes  
  The allowed schemes are HTTP, HTTPS, FTP, FTPS, MAILTO, URL and FILE.
  This custom field essentially is a text field with the type of url in
  the backend while creating an article or a contact or a third party
  component that supports custom fields. It is only possible to fill in
  a qualified url - that is one with a scheme and domain such as
  `http://example.com`. The url will be translated into
  <a href="https://en.wikipedia.org/wiki/Punycode" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">punycode</a> prior
  to saving. This assures that the url will work as intended regardless
  of environment.
- Relative  
  Use this option to determine whether or not relative URLs are allowed.

### Related Information

See [URL form field
type](https://docs.joomla.org/URL_form_field_type "Special:MyLanguage/URL form field type")

### Screenshots

#### Creating the field

Let's say you create a field with the options shown in the next figure.

<img
src="https://docs.joomla.org/images/thumb/f/f4/Url_field_create-en.png/800px-Url_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f4/Url_field_create-en.png/1200px-Url_field_create-en.png 1.5x, https://docs.joomla.org/images/f/f4/Url_field_create-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Url field create-en.png" />

#### Using the field in the backend

In the backend while creating an article or a contact you see the field
like in the following imageː

<img
src="https://docs.joomla.org/images/thumb/c/ce/URL-en.png/800px-URL-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ce/URL-en.png/1200px-URL-en.png 1.5x, https://docs.joomla.org/images/c/ce/URL-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="URL-en.png" />

#### Using the field in the frontend

In the frontend, you can see the field as you see in the following
image. The option *Automatic display* is responsible for the position of
the field and your template is responsible for the design of the
field.

Fields are only displayed in the frontend if you have filled them with
data in the article. If it is not a required field, can you forget it?

<img
src="https://docs.joomla.org/images/thumb/c/c7/Url_field_frontend-en.png/800px-Url_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c7/Url_field_frontend-en.png/1200px-Url_field_frontend-en.png 1.5x, https://docs.joomla.org/images/c/c7/Url_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Url field frontend-en.png" />
