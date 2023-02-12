<!-- Filename: J4.x:Scheduling_the_publication_of_an_article / Display title: Het plannen van de publicatie van een artikel -->

<span id="main-portal-heading">**Handleiding**  
Hoe de publicatie van een artikel plannen</span> Joomla!  4.0

## Inleiding

A key part of a Content Management System (CMS), is its ability to do
just that - manage content. Joomla! provides an easy way for you to
deliver your content to who you want to, when you want to.

This Tutorial looks specifically at scheduling the publication of
articles, either from a specific date or between dates.

Joomla allows you to set publishing start and finish dates and times for
your articles.

Scheduling can be used in two ways:

1.  Set a date and time when an article will published.
2.  Set a date and time when an article will be published and a date and
    time when it will be unpublished.

Joomla! 4 additionally allows you to set times and dates for featured
articles. If your website is using featured articles this new feature
provides a way to set the article to be featured on the home page (or
other featured articles page) for a pre-defined time period whilst also
available at a different page. For example you could create an article
about a type of dog that is available via the dogs link in your menu and
set the article as featured to appear on your home page for a set period
of time.

==How Scheduling Works==

By default articles are set at **Published** as soon as they are saved.
The initial saving of the article creates the **Created Date** and
**Start Publishing** timestamps.

Scheduling an article involves manually setting a **Start Publishing**
date and time to delay publishing. You can also set dates and times to
**Start Publishing** and **Finish Publishing**.

**Note:** For scheduling to work the article **Status** must be set to
**Published**.

Scheduling works by setting articles as **Pending** prior to the publish
date and **Expired** after the date and time an article has been set to
finish. Despite the article itself being set to published, Joomla uses
the start and finish settings to override the default published state.

==Scheduling the Publishing of an Article==

If you are scheduling an existing article:

- Log in to the Administrator Home Dashboard. More on this here:
  [Logging in or out of the Administrator
  Dashboard](https://docs.joomla.org/J4.x:Logging_in_to_Joomla "Special:MyLanguage/J4.x:Logging in to Joomla").

\*From the Home Dashboard Site Panel click on Articles or from the
Sidebar Menu navigate to **Content** then **Articles** to open the
Articles List. \*Find the article you want to schedule and click it's
title to open it.

Under most circumstances you would normally schedule an article when you
create it.

Click on the article's **Publishing** tab.

\[\[File:j4x_article_scheduling_tab-en.png\|border\|left\|300px\]\]

To schedule the article there are four options:

**Start Publishing:** Use this field to schedule a future publishing
date and time of your choosing. If you only set this field the article
will be published on the date you set and then remain published.

**Finish Publishing:** Use this field to schedule a date to unpublish
(expire) the article. Note that in the **Article List** the article will
show as **Expired** but if you opened the article from the Article List
it's status would still show as published - this is normal.

**Start Featured:** Use this field to schedule a date and time for an
article to appear as a featured one. Note that the article **must** be
set as a featured article to use this field.

**Finish Featured:** Setting a date and time in this field will remove
(expire) it as a featured article. Note that in the Article List the
article will show as **Expired** in the Featured Column when the date
and time is reached.

In the following screenshot we set a future publishing date for the
article:

\[\[File:j4x_article_scheduling_start-en.png\|border\|left\|300px\]\]

At the end of the *Start Publishing* field click the calendar icon.

The calendar lets you move between months and years using forward or
backward arrows. Go to the month you require.

Click on the date you require.

Set the time using the drop down boxes.

The **Clear** button clears the date and time.

The **Today** button sets the current date.

When you have set the date and time, click **Close**.

To set the **Finish Publishing** field the process is the same.

The **Start Featured** and **Finished Featured** fields work the same
but to use these fields the article **must** be set to **Featured**
using the toggle in the article settings because if not, when you save
the article, the dates you entered will be cleared.

Once you have scheduled the article as required click **Save&Close** via
the top toolbar.

\[\[File:j4x_article_scheduled-en.png\|border\|800px\]\]

In the Article List you will see that the article you have scheduled
shows an exclamation mark (!) in the **Status** column. If you hover
over the exclamation mark the scheduling details will be displayed
showing the article is **Pending**. When the scheduled date and time is
reached, the exclamation mark will be replaced with a tick showing the
article is **Published** and **Current**.

If an article has been scheduled to finish, when it does the
**Published** and **Current** the tick will be replaced with the
**Expired** icon as below.

\[\[File:j4x_article_expired-en.png\|border\|800px\]\]

Featured articles will show as pending or expired in the Featured
column.

==Quick Tips==

\*You can schedule the publishing of articles from the front end too.
\*It is also possible to schedule via the menu item for the article.
\*Scheduling is also available for Contacts and Modules.
