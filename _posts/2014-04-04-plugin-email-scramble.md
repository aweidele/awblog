---
ID: 26
post_title: 'Plugin: Email Scramble'
author: aaron
post_excerpt: ""
layout: post
permalink: >
  http://blog.aaronweidele.com/plugin-email-scramble/
published: true
post_date: 2014-04-04 18:12:02
---
I thought I'd get my blog started with a simple Wordpress plugin I developed, the <a href="http://blog.aaronweidele.com/wp-content/uploads/2014/04/anw-email-scramble.zip">Email Scramble</a> plugin. The adds a shortcode which allows you to insert your email address into a post, but avoid spammers grabbing your address. The plugin causes the address to appear scrambled within the post, and adds Javascript to unscramble it back to a visible address for a human user, complete with a <strong>mailto:</strong> link.

<strong>Default:</strong> display the Admin Email inside Wordpress settings.
&#91;email&#93;
[email to="john@doe.com"]
(Appears as "|k+pdcn%"zkhsei*qipy~mic/viz"=qipy~mic/viz|}k=" in the HTML output.)

<strong>Specify an email address:</strong>
&#91;email to="john@doe.com"&#93;
[email to="john@doe.com"]

<strong>Specify a label:</strong>
&#91;email label="Click here to email me!"&#93;
[email to="john@doe.com" label="Click here to email me!"]

Download it <a href="http://blog.aaronweidele.com/wp-content/uploads/2014/04/anw-email-scramble.zip">here</a>.

<small><strong>Disclaimer:</strong> I developed this plugin for my own use, and am making it available to download for anyone who wants to use it. I make no guarantees as to how well this plugin will work, nor do I offer support or accept any liability for any damage it may cause.</small>