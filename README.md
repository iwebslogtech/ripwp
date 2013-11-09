<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<title>RipWP &#8250; ReadMe</title>
	<link rel="stylesheet" href="wp-admin/css/install.css?ver=20100228" type="text/css" />
</head>
<body>
<h1 id="logo">
	<a href="http://www.ripwp.com/">
    <img alt="RipWp" src="wp-admin/images/wordpress-logo.png" width="274" height="63" /></a>
	<br /> Version 1.0
</h1>
<p style="text-align: center">Semantic Online Publishing Platform</p>

<h1>First Things First</h1>
<p>Welcome. RipWP is a very special project to me. RipWP is a collection of some 
of the best plugins and themes from the open source world of WordPress and other 
applications. It makes it easy to install and run your website or blog in few 
minutes. We&#8217;re dedicated to making it better every day. Thank you for making it 
a part of your world.</p>
<p style="text-align: right">&#8212; Rajesh</p>

<h1>Installation: Famous 5-minute install</h1>
<ol>
	<li>Unzip the package in an empty directory and upload everything.</li>
	<li>Open <span class="file"><a href="wp-admin/install.php">wp-admin/install.php</a></span> in your browser. It will take you through the process to set up a <code>wp-config.php</code> file with your database connection details.
		<ol>
			<li>If for some reason this doesn&#8217;t work, don&#8217;t worry. It doesn&#8217;t work on all web hosts. Open up <code>wp-config-sample.php</code> with a text editor like WordPad or similar and fill in your database connection details.</li>
			<li>Save the file as <code>wp-config.php</code> and upload it.</li>
			<li>Open <span class="file"><a href="wp-admin/install.php">wp-admin/install.php</a></span> in your browser.</li>
		</ol>
	</li>
	<li>Once the configuration file is set up, the installer will set up the tables needed for your blog. If there is an error, double check your <code>wp-config.php</code> file, and try again. If it fails again, please go to the
    <a title="WordPress support" href="http://www.ripwp.com/support/">support forums</a> with as much data as you can gather.</li>
	<li><strong>If you did not enter a password, note the password given to you.</strong> If you did not provide a username, it will be <code>admin</code>.</li>
	<li>The installer should then send you to the <a href="wp-login.php">login page</a>. Sign in with the username and password you chose during the installation. If a password was generated for you, you can then click on &#8220;Profile&#8221; to change the password.</li>
</ol>

<h1>Updating</h1>
<h2>Using the Automatic Updater</h2>
<p>If you are updating from version 2.7 or higher, you can use the automatic updater:</p>
<ol>
	<li>Open <span class="file"><a href="wp-admin/update-core.php">wp-admin/update-core.php</a></span> in your browser and follow the instructions.</li>
	<li>You wanted more, perhaps? That&#8217;s it!</li>
</ol>

<h2>Updating Manually</h2>
<ol>
	<li>Before you update anything, make sure you have backup copies of any files you may have modified such as <code>index.php</code>.</li>
	<li>Delete your old RipWP files, saving ones you&#8217;ve modified.</li>
	<li>Upload the new files.</li>
	<li>Point your browser to <span class="file"><a href="wp-admin/upgrade.php">/wp-admin/upgrade.php</a>.</span></li>
</ol>

<h1>Migrating from other systems</h1>
<p>RipWP can import from a number of systems. First you need to get 
RipWP installed and working as described above, before using <a href="wp-admin/import.php" title="Import to WordPress">our import tools</a>.</p>

<h1>System Requirements</h1>
<ul>
	<li><a href="http://php.net/">PHP</a> version <strong>5.2.4</strong> or higher.</li>
	<li><a href="http://www.mysql.com/">MySQL</a> version <strong>5.0</strong> or higher.</li>
</ul>

<h2>System Recommendations</h2>
<ul>
	<li>The <a href="http://httpd.apache.org/docs/2.2/mod/mod_rewrite.html">mod_rewrite</a> Apache module.</li>
	<li>A link to <a href="http://www.ripwp.com/">http://www.ripwp.com</a> on your site.</li>
</ul>

<h1>Online Resources</h1>
<p>If you have any questions that aren&#8217;t addressed in this document, please take advantage of 
RipWP&#8217; numerous online resources:</p>
<dl>
	<dt><a href="http://codex.wordpress.org/">The WordPress Codex</a></dt>
		<dd>The Codex is the encyclopedia of all things RipWP. It is the most comprehensive source of information for 
        RipWP available.</dd>
	<dt><a href="http://wordpress.org/news/">The WordPress Blog</a></dt>
		<dd>This is where you&#8217;ll find the latest updates and news related to 
        RipWP. Recent RipWP news appears in your administrative dashboard by default.</dd>
	<dt><a href="http://planet.wordpress.org/">WordPress Planet</a></dt>
		<dd>The RipWP Planet is a news aggregator that brings together posts from 
        RipWP blogs around the web.</dd>
	<dt><a href="http://wordpress.org/support/">WordPress Support Forums</a></dt>
		<dd>If you&#8217;ve looked everywhere and still can&#8217;t find an answer, the support forums are very active and have a large community ready to help. To help them help you be sure to use a descriptive thread title and describe your question in as much detail as possible.</dd>
	<dt> <abbr title="Internet Relay Chat"><a href="http://codex.wordpress.org/IRC">
    WordPress IRC</a></abbr><a href="http://codex.wordpress.org/IRC"> Channel</a></dt>
		<dd>There is an online chat channel that is used for discussion among people who use 
        RipWP and occasionally support topics. The above wiki page should point you in the right direction. (<a href="irc://irc.freenode.net/wordpress">irc.freenode.net 
        #wordpress</a>)</dd>
</dl>

<h1>Final Notes</h1>
<ul>
	<li>If you have any suggestions, ideas, or comments, or if you (gasp!) found a bug, join us in the
    <a href="http://www.ripwp.com/support/">Support Forums</a>.</li>
	<li>RipWP has a robust plugin <abbr title="application programming interface">API</abbr> that makes extending the code easy. If you are a developer interested in utilizing this, see the <a href="http://codex.wordpress.org/Plugin_API" title="WordPress plugin API">plugin documentation in the Codex</a>. You shouldn&#8217;t modify any of the core code.</li>
</ul>

<h1>Share the Love</h1>
<p>RipWP has no multi-million dollar marketing campaign or celebrity sponsors, but we do have something even better&#8212;you. If you enjoy 
RipWP please consider telling a friend, setting it up for someone less knowledgable than yourself, or writing the author of a media article that overlooks us.</p>

<p>RipWP is a mix of best open source projects available online. The work has been 
followed at twitter @RipWP. Currently we are not accepting any donations, 
however you can donate to the open source projects here -
<a title="Donate to WordPress" href="http://wordpress.org/donate/">Donate</a>.</p>

<h1>License</h1>
<p>RipWP is free software, and is released under the terms of the <abbr title="GNU General Public License">GPL</abbr> version 2 or (at your option) any later version. See <a href="license.txt">license.txt</a>.</p>

</body>
</html>
