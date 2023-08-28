<!-- Filename: J3.x:Adding_custom_fields/Sql_Field / Display title: Adding custom fields/Sql Field -->

## Sql Field

Provides a drop down list of entries obtained by running a query on the
Joomlaǃ Database. The first results column returned by the query
provides the values for the drop down box.

### Options

Special options within this field are:

- Multiple  
  Allow multiple values to be selected - if activated.
- Query  
  The SQL query which will provide the data for the dropdown list. The
  query must return two columns; one called 'value' which will hold the
  values of the list items; the other called 'text' containing the text
  in the drop-down list.

### Related Information

See [SQL form field
type](https://docs.joomla.org/SQL_form_field_type "Special:MyLanguage/SQL form field type")

### Screenshots

#### Creating the field

Let's say you create a field with the options shown in the next figure.

<img
src="https://docs.joomla.org/images/thumb/c/cf/Sql_field_create-en.png/800px-Sql_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/cf/Sql_field_create-en.png/1200px-Sql_field_create-en.png 1.5x, https://docs.joomla.org/images/c/cf/Sql_field_create-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Sql field create-en.png" />

#### Using the field in the backend

In the backend while creating an article or a contact you see the field
like in the following imageː

<img
src="https://docs.joomla.org/images/thumb/4/4a/Sql-en.png/800px-Sql-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4a/Sql-en.png/1200px-Sql-en.png 1.5x, https://docs.joomla.org/images/4/4a/Sql-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Sql-en.png" />

#### Using the field in the frontend

In the frontend, you can see the field as you see in the following
image. The option *Automatic display* is responsible for the position of
the field and your template is responsible for the design of the
field.

Fields are only displayed in the frontend if you have filled them with
data in the article. If it is not a required field, can you forget it?

<img
src="https://docs.joomla.org/images/thumb/6/66/Sql_field_frontend-en.png/800px-Sql_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/66/Sql_field_frontend-en.png/1200px-Sql_field_frontend-en.png 1.5x, https://docs.joomla.org/images/6/66/Sql_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Sql field frontend-en.png" />
