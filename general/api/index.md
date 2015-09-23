---
title: OWASP API Developer Pages
layout: default
---

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          <a id="forkme_banner" href="https://github.com/OWASP/dev-pages">View on GitHub</a>

          <h1 id="project_title">API Security @ OWASP</h1>
          <h2 id="project_tagline">API Security Focused Application Security Pages</h2>

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
<a id="welcome-to-owasp-dev-pages" class="anchor" href="#welcome-to-owasp-dev-pages" aria-hidden="true"><span class="octicon octicon-link"></span></a>API Application Security</h3>

<p>API security is really just a subset of web application security.  There are a few specific things we need to 
think about in the contect of API's.</p>

<p>API's generally authenticate users using a secret.  It is critical that the secret be tied to a user or subject.  
A good way to think about it is that you want to have a "user" and a "password".  These would come from "API KEY" and 
"Secret".  This allows us to tie requests to a user and change the password.
</p>

<p>API's sometimes seem invisible.  They are not.  Authorization is critical in API's.  Additionally, rate limiting 
can be an important consideration.  Metrics can be extremely helpful in identifying patterns of misuse.
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
