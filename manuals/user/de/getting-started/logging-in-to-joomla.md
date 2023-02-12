<!-- Filename: J4.x:Logging_in_to_Joomla / Display title: Einloggen in Joomla -->

<span id="main-portal-heading">**Tutorial**  
An- und Abmelden bei Joomla!</span> Joomla!  4.0

## Einführung

Eine der großartigen Eigenschaften von Joomla! ist, dass es die
Flexibilität bietet, Aufgaben entweder über das Administrator-Dashboard
(oft als Backend bezeichnet) oder, falls aktiviert, direkt vom Frontend
(dem öffentlich zugänglichen Teil der Website) aus zu erledigen.

Der Frontend-Zugang ist eine einfache und effiziente Methode, die es
Autoren ermöglicht, Artikel schnell hinzuzufügen oder zu bearbeiten,
ohne das Administrator-Dashboard aufrufen zu müssen.

Das Joomla-Login ist so konfiguriert, dass man kontrollieren kann, was
zu sehen ist und was man tun kann (oder nicht tun kann), indem der
Joomla-Benutzermanager und die leistungsstarken Zugriffssteuerungsebenen
(ACL) verwendet werden. Das bedeutet, dass eine Joomla-Website Benutzer
haben kann, die nur das Backend oder nur das Frontend oder beides
nutzen.

Im Folgenden wird die An- und Abmeldung sowohl vom Backend als auch vom
Frontend Ihrer Joomla-Website behandelt.

**Hinweis:** Der Joomla-Administrator hat möglicherweise den
Frontend-Zugang deaktiviert, so dass alle Aufgaben über das
Backend-Administrator-Dashboard ausgeführt werden müssen.

Die Schritte, die in diesem Tutorial behandelt werden, basieren auf
einer Standard-Joomla!-Installation.

## An- und Abmeldung beim Backend-Administrator Dashboard

### Anmelden

Die Login-Seite für den Administrationsbereich kann durch Eingabe der
Webadresse mit der Endung /administrator, z. B.
meine-joomla-website.de/administrator, aufgerufen werden.

Die Anmeldeseite für den Administrationsbereich:

\[\[Image:j4x\_\_administrator_login_en.png\|border\|800px\]\]

1.  Add your **Username**.
2.  Add your **Password**.

Click the **Log in** button and you will be taken to the Joomla! Home
Dashboard.

**Note:**

1.  Joomla provides you with the option to set up and use Web
    Authentication - this is not within the scope of this tutorial.
2.  If the website has other languages installed you will be able to
    select the relevant language from a dropdown list before logging in.

===Logging Out=== To log out click the **User Menu** then **Log out**.

\[\[Image:j4x\_\_administrator_logout_en.png\|border\|800px\]\]

==Log in and out from the frontend of the website== ===Logging In===

If frontend access is enabled, a login form will have been added to the
website. Joomla allows a number of ways to do this. A standard
installation includes a login form in the sidebar of the website but you
may find a link has been added to the website menu, or perhaps in the
footer. In some cases a *Create Page* link may exist. The design of the
website will dictate where you access the login form.

In this example we use a login form on the website that is located in
the sidebar.

\[\[Image:j4x\_\_front_end_login_en.png\|border\|800px\]\]

In the **Login Form**:

1.  Add your **Username**.
2.  Add your **Password**.

Click the **Log in** button.

When logging in from the frontend of the website, you will be kept on
the same page that you logged in on. You will notice the login form will
also be replaced with a **Log out** button.

===Logging Out===

\[\[Image:j4x\_\_front_end_logout_en.png\|border\|800px\]\]

To logout go to the position you logged in then click the **Log out**
button.

  
==Quick Tips==

- Some Joomla website administrators install extensions that hide or
  restrict access to the backend Administrator Dashboard. You may have
  to take additional steps or visit an alternative login URL.
- If you are making edits using the frontend login, save time by logging
  in on the page you wish to edit.
