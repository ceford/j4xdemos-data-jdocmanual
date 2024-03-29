<!-- Filename: J3.x:Adding_custom_fields/Multilingual_Sites / Display title: Adding custom fields/Multilingual Sites -->

## Multilingual Sites

If you have a multilingual site then you can display the labels and
descriptions of custom fields and field groups in the user's language.
To do this:

1.  Define the Title and Description of your custom field group as
    language constants
2.  Define the Label and Description of your custom field as language
    constants
3.  Set up those language constants as overrides for each of your
    languages

In the following example we set up a Contact custom field group and
custom field. We define a custom field group relating to the contact's
personal preferences called Favourites. And inside the Favourites field
group we add a custom field for Car.

We define the above attributes as language constants, and then define
text for these language constants in English and German. The result is
that the custom field group and custom field are shown in both the
administrator and site areas in the user's language.

(To use these features it's assumed you have your site set up to be
multilingual, as described in the [Setup a Multilingual
Site](https://docs.joomla.org/J3.x:Setup_a_Multilingual_Site "J3.x:Setup a Multilingual Site")
tutorial.)

## Defining the Custom Field Group

Within the Contacts areas define a new custom field group as shown
below. (Note that it's best to choose a language constant that doesn't
start with one of the Joomla components etc, to avoid possible future
clashes with newer versions of Joomla).

<img
src="https://docs.joomla.org/images/d/d1/Multilanguage-custom-field-goup-en.jpg"
decoding="async" data-file-width="787" data-file-height="399"
width="787" height="399" alt="Multilanguage-custom-field-goup-en.jpg" />

## Defining the Custom Field

Then define a new custom field and assign it to the above field group:

<img
src="https://docs.joomla.org/images/4/4e/Multilanguage-custom-field-en.jpg"
decoding="async" data-file-width="700" data-file-height="473"
width="700" height="473" alt="Multilanguage-custom-field-en.jpg" />

## Edit a Contact (before strings translated)

When you now edit a contact record you should see the new custom field
within a tab for the Favourites. At this stage the language constant
strings we entered will be displayed.

<img
src="https://docs.joomla.org/images/a/ac/Multilanguage-custom-field-edit-en.jpg"
decoding="async" data-file-width="800" data-file-height="305"
width="800" height="305" alt="Multilanguage-custom-field-edit-en.jpg" />

## Defining the Overrides

Now go into Extensions / Languages / Overrides. Select the English
Administrator in the drop-down box, and create overrides for each of the
language constants. Select For Both Locations so that the language
constant is used on the front-end as well.

<img
src="https://docs.joomla.org/images/8/8c/Multilanguage-custom-field-override-en.jpg"
decoding="async" data-file-width="800" data-file-height="479"
width="800" height="479"
alt="Multilanguage-custom-field-override-en.jpg" />

After you have entered overrides for the 4 English language constants
you should end up with:

<img
src="https://docs.joomla.org/images/0/06/Multilanguage-custom-field-overrides-gb-en.jpg"
decoding="async" data-file-width="800" data-file-height="341"
width="800" height="341"
alt="Multilanguage-custom-field-overrides-gb-en.jpg" />

Now select German Administrator and add German translations for each,
ending up with:

<img
src="https://docs.joomla.org/images/8/8c/Multilanguage-custom-field-overrides-de-en.jpg"
decoding="async" data-file-width="800" data-file-height="329"
width="800" height="329"
alt="Multilanguage-custom-field-overrides-de-en.jpg" />

## Edit a Contact

Now when a Contact is edited in the back-end the custom field and field
group are displayed in the administrator's language:

<img
src="https://docs.joomla.org/images/1/1e/Multilanguage-custom-field-edit-gb-en.jpg"
decoding="async" data-file-width="2410" data-file-height="876"
width="2410" height="876"
alt="Multilanguage-custom-field-edit-gb-en.jpg" />

<img
src="https://docs.joomla.org/images/7/78/Multilanguage-custom-field-edit-de-en.jpg"
decoding="async" data-file-width="2410" data-file-height="789"
width="2410" height="789"
alt="Multilanguage-custom-field-edit-de-en.jpg" />

## Display a Contact

If you display a contact on the front-end then the custom fields are
displayed with the language-specific label.

<img
src="https://docs.joomla.org/images/b/b6/Multilanguage-custom-field-site-gb-en.jpg"
decoding="async" data-file-width="2410" data-file-height="1346"
width="2410" height="1346"
alt="Multilanguage-custom-field-site-gb-en.jpg" />

<img
src="https://docs.joomla.org/images/3/3d/Multilanguage-custom-field-site-de-en.jpg"
decoding="async" data-file-width="2410" data-file-height="1328"
width="2410" height="1328"
alt="Multilanguage-custom-field-site-de-en.jpg" />
