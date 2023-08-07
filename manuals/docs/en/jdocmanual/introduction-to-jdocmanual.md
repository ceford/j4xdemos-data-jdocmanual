# Introduction to Jdocmanual

Jdocmanual is a Joomla component designed to display articles organised for convenience with an Index to all articles at the left, the selected article content in the centre and a list of headings in the article to the right. Each collection of articles constitutes a Manual, of which there can be any number. The content of each article is stored in Markdown format. Three Joomla Manuals are available for demonstration purposes: ***The Joomla 4 User Manual***, ***The Joomla 4 Developer Manual*** and the ***Joomla 4 Help Screens***. The content of the articles came from the Joomla Documentation site. The articles can be displayed in any language for which a translation is available. 

## The Manual View

Jdocmanual has a default Manual view for the Administrator and a Site view using the same code. This is the Administrator view:

<img src="/jdocmanual2/images/manuals/docs/en/jdocmanual/jdocmanual.png" class="screenshot" alt="manual view" title="The Jdocmanual Manual View" width=1440 height=728>

### Manual and Language Selection 

**Select Manual:** The list of manuals available is kept in a databse table with standard list and edit views. Todo: Provision for Title translation.

**Index Language:** The index to the left can be displayed in a different language from the content to the right. This is useful for problem solving and checking on the translation status of articles. It does not require a Multilingual site!

**Page Language:** If the article is NOT available in the selected language it will be displayed in English. The index title link will be in English. At the moment there are 8 languages available but few articles have been translated.

**Actions:** There is an option to hide the left Administrator menu so the full screen width can be used for article display. There is also an option to update the HTML of the current page from the Markdown source. That is related to how data is processed and stored for delivery to the end user.

Try it: https://jdocmanual.org/

## The Source Data

The article data used by Jdocmanual are stored in a git repository in GitHub Flavoured Markdown format (GFM). They could be on GitHub but don't have to be. It could even be a disadvantage to use GitHub. Ancillary data used for importing the data into Jdocmanual are stored in txt or ini files. The repository structure is as follows:

```
/manuals
    /developer
    /help
    /user
        /de
            /articles
            /banners
            ...
            menu-headings.ini
        /en
        /es
        ...
        articles-index.txt
        menu-index.txt
```

The data originally came from the Joomla Documentation Mediwiki site. The conversion process was rather tortuous and not so easily repeated! An important feature of the conversion is that the links to article images, mostly Joomla screenshots, have been retained in the GFM files. So Jdocmanual is using images delivered by MediaWiki. In due course that may change. The data are on GitHub:

```
https://github.com/ceford/j4xdemos-data-jdocmanual
```

## Updating an Article

We need to make it really easy to update an article source file. In Jdocmanual that is done by creating a personal **stash** copy of the article. The following screenshot shows the first page of a list of all articles in a Manual. The list is based on the English original. If English is selected as the language then the **Translated** column is not displayed.

Image: Screenshot of the Article Stashes list

The stash copy is stored in the database until it is deleted or committed and merged into the git source.

### The Stash Edit Form

The Article Edit form has a number of tabs. The `Details` tab is mostly **read only** data. However, the `Display Title` can be changed. On creating a new stash in German the Display Title will be in English. If a translation already exists it will be whatever the previous translator set it to.

Image: Screenshot of the Article Edit form Details tab

The `Stash` tab shows the original English text and German text side by side. If the selected language is English the tab shows just the English text. Note the first line is an HTML comment. This is actually used to set the Article title when building the database. There is no H1 in the Mediawiki articles. The display title is stored separately there.

Image: Screenshot of the Article Edit form Stash tab English and German side by side

The `English diff` tab shows the difference between the last two committed English versions. This is intended to help the translator see what has changed in the English source. This tab is not displayed if the selected language is English.

The `Source` tab shows a **read only** view of the source markdown file.

The `Diff` tab shows the difference between the Stash and the Source. So before any changes are made this tab is empty - but there is an `Identical` message.

The `Preview` tab show a HTML conversion of the stash showing what the end users will see.

The `Comments` tab has a field to enter a `Commit Message` and a field to enter `Comments`. These fields can be filled in by either the user who created the stash or whoever commits the stash. In some cases a committer may decline to commit until some correction is made. That can be indicated here.

## Commit a Stash

In a communal environment it is expected that there will be two User Groups, one allowed to create stashes and another allowed to commit stashes. Of course an individual user may belong to both groups.

When a stash owner is satisfied with the text, a pull request is made by selecting the `Pull Request` button in the Toolbar. Up to that point a Committer is not aware of a stash created by another user. After that point the Pull Request appears in the list in the Pull Requests tab of the list form.

From time to time a Committer will consult the list of Pull Requests and open the Edit Stash form. It is the same form seen by the stash owner except that it has a `Commit` button in the Toolbar. If the Committer is satisfied with the stash, a click on the button causes creation of a git branch