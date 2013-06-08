<h2>DP_Debug</h2>

<ul>	<li>Author: Jim Davis, the Depressed Press</li>
	<li>Created: September 20, 2006</li>
	<li><b>Documentation</b>: http://depressedpress.com/javascript-extensions/dp_debug/</li>
	<li>Contact: http://depressedpress.com/about/contact-me/</li>
	<li>Other Components: http://depressedpress.com/javascript-extensions/</li>
</ul>

<p>The DP_Debug utility script extends JavaScript with (we think) useful debugging methods.  The following methods are made available:</p>
<ul><li>dump(): Converts JavaScript objects (their properties, values and relationships) to an HTML representation and displays this in the console for review.  It supports objects with circular/recursive references.  It's similar to the insanely useful CFDUMP tag in ColdFusion.</li>
	<li>dumpCookies(): A convenience method which dumps all available browser cookies to the console.</li>
	<li>dumpQueryString(): A convenience method which dumps all available query-string names and values to the console.</li>
	<li>logger(): A method for logging messages to the console using either custom or predefined types.  logInfo(), logWarning() and logError() are all shortcut methods for logging specific types of messages easily.</li>
	<li>timer(): A method for timing blocks of code.</li>
	<li>getType(): Provides more advanced Object type-recognition than the native "typeof" operator.</li>
</ul>
<p>The extension is self-contained and present an extremely small footprint.  Only a single global object, "DP_Debug", is created.</p>
<p>This component requires a JavaScript (ECMAScript) 1.3 (or better) development environment and has been tested successfully on Internet Explorer 6+, Firefox 1+ and Opera 9+.</p>

<blockquote style="background: #dedede;">
Copyright (c) 1996-2013, The Depressed Press (depressedpress.com)
<br />
All rights reserved.
<br />
Covered under the BSD Open Source License (included in the code).  Full legal information here: http://depressedpress.com/about/source-code-policy/
</blockquote>