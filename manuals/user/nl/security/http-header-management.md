<!-- Filename: J4.x:Http_Header_Management / Display title: Http header beheer -->

Joomla!  4.0 Handleiding  
Hoe het nieuwe HTTP header beheer gebruiken in Joomla 4.0

  
Vanaf Joomla 4.0, heeft Joomla een HTTP Header beheersysteem ingevoerd.
Dit systeem is ontworpen om eigenaren van websites te helpen de HTTP
Security Headers vanuit het beheergedeelte in te stellen.

In deze handleiding vind je informatie hoe dit nieuwe systeem in te
stellen op je website.

## Plugin

### Systeem - HTTP Headers (plg_system_httpheaders)

Navigeer naar **Systeem **→** Plugins **→** Systeem - HTTP Headers** om
bij de instellingen van de plugin te komen.

#### Plugin instelling

Vanuit deze pagina kun je er voor kiezen om in te schakelen dat de
headers weggeschreven worden naar de server instellingen bestanden
(.htaccess en web.config) en instellen of de volgende http headers
ingeschakeld zijn.

- <a
  href="https://scotthelme.co.uk/hardening-your-http-response-headers/#x-frame-options"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">X-Frame-Options</a>
- <a
  href="https://scotthelme.co.uk/a-new-security-header-referrer-policy/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Referrer-Policy</a>
- <a href="https://www.chromestatus.com/feature/5432089535053824"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Cross-Origin-Opener-Policy</a>

Met het formulier "Force Header" kunt u ook de volgende headers forceren
met de bijbehorende waarden:

- <a href="https://scotthelme.co.uk/hsts-the-missing-link-in-tls/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Strict-Transport-Security</a>
- <a
  href="https://scotthelme.co.uk/content-security-policy-an-introduction/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Content-Security-Policy</a>
- <a
  href="https://scotthelme.co.uk/content-security-policy-an-introduction/#testingapolicy"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Content-Security-Policy-Report-Only</a>
- <a href="https://scotthelme.co.uk/a-new-security-header-expect-ct/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Expect-CT</a>
- <a href="https://scotthelme.co.uk/a-new-security-header-feature-policy/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Feature-Policy &amp;
  Permissions-Policy</a>
- <a
  href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/report-to"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Report-to</a>

<img
src="https://docs.joomla.org/images/thumb/9/93/Plg-system-httpheaders-options-nl.png/800px-Plg-system-httpheaders-options-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/93/Plg-system-httpheaders-options-nl.png/1200px-Plg-system-httpheaders-options-nl.png 1.5x, https://docs.joomla.org/images/9/93/Plg-system-httpheaders-options-nl.png 2x"
data-file-width="1283" data-file-height="886" width="800" height="552"
alt="Plg-system-httpheaders-options-nl.png" />

### Strict-Transport-Security (HSTS) instellingen

Vanaf deze pagina kun je er voor kiezen dat de Strict-Transport-Security
(HSTS) header ingeschakeld is evenals het instellen van de max-age
waarde, of subdomeinen opgenomen moeten worden en of het toegevoegd moet
worden aan de preload-lijst van de browser.

<img
src="https://docs.joomla.org/images/thumb/6/65/Plg-system-httpheaders-options-hsts-nl.png/800px-Plg-system-httpheaders-options-hsts-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/65/Plg-system-httpheaders-options-hsts-nl.png/1200px-Plg-system-httpheaders-options-hsts-nl.png 1.5x, https://docs.joomla.org/images/6/65/Plg-system-httpheaders-options-hsts-nl.png 2x"
data-file-width="1297" data-file-height="775" width="800" height="478"
alt="Plg-system-httpheaders-options-hsts-nl.png" />

### Content-Security-Policy (CSP) Configuration

From this page you can choose to enable and configure the
Content-Security-Policy (CSP) header set by the plugin.

<img
src="https://docs.joomla.org/images/thumb/c/cb/Plg-system-httpheaders-options-csp-en.png/800px-Plg-system-httpheaders-options-csp-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/cb/Plg-system-httpheaders-options-csp-en.png/1200px-Plg-system-httpheaders-options-csp-en.png 1.5x, https://docs.joomla.org/images/thumb/c/cb/Plg-system-httpheaders-options-csp-en.png/1600px-Plg-system-httpheaders-options-csp-en.png 2x"
data-file-width="1802" data-file-height="1846" width="800" height="820"
alt="Plg-system-httpheaders-options-csp-en.png" />

Once enabled you can set the client where you want to enforce the
configured CSP on, allowing you to set set "site", "administrator" or
"both".

The following settings need a bit more explanation, thats also the
reason there are additional descriptions on all of them.

The final option called "Add Directive" allows you to configure the
allowlist per directive as you need them. For example the directive
"script-src" where the option "Value" you enter the origins you want to
allow to load scripts from.

## Notes

When you have configured some HTTP Security Headers directly on the
server, then our tooling might create double entries.

Check the output of your HTTP Headers after configuring in the browser
console. In Google Chrome: Inspect \> Network \> the output under
Headers). You can than disable the headers that cause double entries.
Also check the console of your browser for possible errors.

## Extension Developers

As you might know the big security advantage concerning Content Security
Policy jumps in when we can use the Header to block all inline
JavaScript and inline CSS affecting for example JavaScript event
handlers via HTML attributes. So with this browser protection enabled we
will block inline JavaScript and inline CSS usage also for your
extensions. That protection is not enabled by default but can be enabled
by your users.

For 4.0 it would be recommended to get the frontend of your extension
running with strict Content Security Policy enabled. For 4.1
compatibility it would be recommended that this also applies to your
backend.

We know that it is still a requirement to have inline JavaScript and
CSS, for that reason we have implemented nonce and hash support into our
Document APIs when you use them the core will make sure they are
whitelisted but we will still block any malicious to protect our sites.

### Important notes for Extension Developers

Starting with Joomla 4.0 Content Security Policy:

- is shipped by the core
- is disabled by default
- can be enabled by your users
- it is strongly recommended that your extension frontend works by 4.0
  with Content Security Policy enabled
- it is recommended that your extension backend works by 4.1 with
  Content Security Policy enabled

With strict Content Security Policy enabled the following features will
be blocked:

- the execution of JavaScript via the HTML event handlers (onXXX
  handlers like onClick and similar)
- the execution of in-page JavaScript not passed to the page via the
  Document API
- the execution of JavaScript code injected into DOM APIs such as eval()
- the usage of inline in-page CSS not passed to the page via the
  Document API
- the usage of inline CSS using the HTML style attribute

To get your extensions work even with strict Content Security Policy
enabled, the easiest way is to use the Document API to apply your inline
JavaScript and CSS, please check the examples below.

### Adding JavaScript using the Joomla API

    use Joomla\CMS\Factory;

    /** @var Joomla\CMS\WebAsset\WebAssetManager $wa */
    $wa = Factory::getApplication()->getDocument()->getWebAssetManager();

    // Add JavaScript from URL
    $wa->registerAndUseScript('com_example.sample', 'https://example.org/sample.js', [], ['defer' => true]);

    // Add inline JavaScript
    $wa->addInlineScript('
        document.addEventListener("DOMContentLoaded", function(event) {
            alert("An inline JavaScript Declaration");
        });
    ');

### Adding CSS using the Joomla API

    use Joomla\CMS\Factory;

    /** @var Joomla\CMS\WebAsset\WebAssetManager $wa */
    $wa = Factory::getApplication()->getDocument()->getWebAssetManager();

    // Add Style from URL
    $wa->registerAndUseStyle('com_example.sample', 'https://example.org/sample.css');

    // Add inline Style
    $wa->addInlineStyle('
        body {
            background: #00ff00;
            color: rgb(0,0,255);
        }
    ');

More details can be found here:[Adding JavaScript and CSS to the
page](https://docs.joomla.org/J3.x:Adding_JavaScript_and_CSS_to_the_page "Special:MyLanguage/J3.x:Adding JavaScript and CSS to the page")

## Additional resources about Content Security Policy and HTTP Headers

- <a href="https://scotthelme.co.uk/csp-cheat-sheet/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CSP Cheat Sheet</a>
- <a
  href="https://scotthelme.co.uk/content-security-policy-an-introduction/"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Content Security Policy - An
  Introduction</a>
- <a href="https://securityheaders.com/%7C" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">SecurityHeaders.com
  (by Scott Helme)</a>
- <a href="https://csp-evaluator.withgoogle.com/%7C" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">CSP Evaluator</a>
- <a href="https://developers.google.com/web/fundamentals/security/csp%7C"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Web Fundamentals Content Security
  Policy</a>
- <a href="https://csp.withgoogle.com/docs/index.html%7C"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Google's CSP Documentation</a>
- <a href="https://research.google/pubs/pub45542/%7C"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CSP Is Dead, Long Live CSP! On the
  Insecurity of Whitelists and the Future of Content Security Policy</a>
- <a href="https://web.dev/tags/security/%7C" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">web.dev tag
  Security</a>
