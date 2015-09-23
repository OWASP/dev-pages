---
title: OWASP General Security - Persistence
layout: default
---

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          <a id="forkme_banner" href="https://github.com/OWASP/dev-pages">View on GitHub</a>

          <h1 id="project_title">Java  Developers @ OWASP</h1>
          <h2 id="project_tagline">Java  Developer Focused Application Security Pages</h2>

            <section id="quick-links">

            <!--
              Use this for something?

              <a class="spring_link" href="./spring/index.html">Spring</a> |
              <a class="struts_link" href="./struts/index.html">Struts</a> | 
              <a class="android_link" href="./android/index.html">Android</a> 
            --> 
            </section>

        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        <h3>
<a id="welcome-to-owasp-dev-pages" class="anchor" href="#welcome-to-owasp-dev-pages" aria-hidden="true"><span class="octicon octicon-link"></span></a>General Java Application Security</h3>

<p>Interestingly, Java gets a bad rap in the security world even though in many ways Java based applications encourage
a number of important security improvements.  The bad rap comes from vulnerabilities in the JVM, and the extent to which
attackers can use malicious java to run arbitrary code through browsers.  This is a reason to give a second thought to
web based rich application delivery (applets).</p>

<p>Java is compiled to bytecode and then run in a JVM.  Running the code this way generally prevents buffer overflows and 
memory allocation issues, a very important class of vulnerability that is common in C and C++ programs.  Specifically, 
Java developers rarely have to consciously use or free memory - it is done automatically through garbage collection.
</p>

<p>Java is a very rich langauge.  This can mean that simple programs create large amounts of objects and use surprising
amounts of memory.  This is something to watch out for during development as it can result in performance and denial of 
service issues with an application.</p>

<p>Java applications often use a large number of open source libraries.  Since vulnerabilities in the libraries can 
cause issues, it is important when working in Java to use a tool like OWASP Dependency Check to identify security issues
in dependent libraries.</p>

<p>Although Java is compiled to bytecode, it is possible to decompile bytecode to readable Java code.  This means that
distributing .jar, .war, .ear or .apk files with compiled code is effectively sharing source code for an application.
</p>

<p>Java offers very advanced multithreading capabilities.  When in doubt, use the concurrrent packages to avoid writing
code that isn't threadsafe.
</p>

<h3>
<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true"><span class="octicon octicon-link"></span></a>Resources</h3>
<!--  Provide detailed links to Spring security sections based on capabilities.  -->
<ul>
<li><a href="http://owasp.org">OWASP Top 10</a></li>
</ul>

<h3>
<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true"><span class="octicon octicon-link"></span></a>Support or Contact</h3>

<p>Having trouble with the developer pages? Help us update them or <a href="mailto:matt.konda@owasp.org">matt.konda@owasp.org</a> and we’ll help you sort it out.  See something wrong?  Get involved and help us fix it!</p>
      </section>
    </div>

    

  </body>
</html>
