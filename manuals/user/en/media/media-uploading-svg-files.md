<!-- Filename: J4.x:Media:_Uploading_SVG_files / Display title: Media: Uploading SVG files -->

## Introduction

SVG (Scalable Vector Graphics) files are not supported in Joomla by
default. A few steps are necessary to allow the Media Manager to support
them.

## How to Add Support to SVG files

In the Joomla Administrator interface, you need to access the global
configurations settings of the Media Manager.

### How to Access the Media Settings

There are several ways to access the Media Manager settings:

- From the Media Manager click on **Options**.
- From the Home Dashboard click on **Global Configuration**, then go to
  the **Media** section.

### What Media Settings Should Be Modified

There are 3 areas in the settings where changes should be applied (the
last 2 are necessary only if uploads are restricted):

- In *Legal Image Extensions*, add at the end of the already available
  value: `,svg`.
- In *Allowed Extensions*, add at the end of the already available
  value: `,svg`.
- In *Legal MIME Types*, add at the end of the already available value:
  `,image/svg+xml`.

From now on, you should be able to upload SVG files into the Media
Manager.

## Why is Joomla preventing me from uploading SVG files still?

SVG is not a raster image format (like PNG files, which contain pixels),
it is written in XML (Extensible Markup Language). It is text-based,
usable directly inside the DOM (Document Object Model), CSS can change
properties and JavaScript can add interactivity.

As such, SVG files are susceptible to all XML related attack patterns:

- Cross-site scripting – or XSS (through its `<script>` tag and events).
- HTML injections (through the `<foreignObject>` element – foreignObject allows you to include elements from a different XML namespace).
- Denial of service (if the `<xlink:href>` element is misused).

Starting with Joomla 4.1, a sanitizer tool is used to check the content of any SVG file uploaded through the Media Manager. The rules are strict and ensure files cannot harm the site. Therefore, some files may need to be **cleaned** manually (remember, SVG files are text files and can be edited in a text editor) or through an outside tool before they can be uploaded successfully.

Tip: Opening a SVG file in a text editor and in a separate graphical interface (such as _Inkscape_, a free open source editor) simultaneously will help prevent you from removing necessary code from the original file. 

## Further Information

In this series of tutorials:

- [Managing
  Media](https://docs.joomla.org/J4.x:Managing_Media "J4.x:Managing Media")
- [Media: Upload Delete
  Rename](https://docs.joomla.org/J4.x:Media:_Upload_Delete_Rename "J4.x:Media: Upload Delete Rename")
- [Media: Image Crop Resize
  Rotate](https://docs.joomla.org/J4.x:Media:_Image_Crop_Resize_Rotate "J4.x:Media: Image Crop Resize Rotate")
- [Media:
  Options](https://docs.joomla.org/J4.x:Media:_Options "J4.x:Media: Options")

