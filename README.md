# mzebib_captcha_v2

<b>
  <h1>Oracle Apex Plugin for google reCaptcha Version 2</h1>
  <p>by Mohamed Zebib (mzebib@gmail.com)</p>
  <h2><i>Description:</i></h2>
</b>
<p>Protect your website from spam and abuse.</p>
<p>Easy to use Google noCaptcha reCaptcha v2 plugin. Just create a new item using the plugin inside your login page. The use of this plugin will give you a mean to verify that the user connecting to your application is not a robot. This is essentially useful for admin access or regular access to an application with sensitive data. This plugin supports multiple language applications. The zip file contains the plugin in APEX version 4.2 and APEX 5.0. Choose the version that suits your APEX installation.
Special Requirements
Just import the plugin and see detailed description in the Help Section of the plugin.</p>
<p>Mainly, you will need to :
1- get google public and private keys available at https://www.google.com/recaptcha/admin/create. The one provided in the plugin is a test key and will always pass. You can use it for your own testing.
2- You will also need to setup an Oracle Wallets in order to access the google service in https mode from Oracle 11g or 12c. A good reference can be found on https://oracle-base.com/articles/misc/utl_http-and-ssl.
3- You will need to grant the right ACL access to you APEX schema APEX04_0200 or APEX05_0000.See https://oracle-base.com/articles/misc/utl_http-and-ssl#acl
</p>
<p>For an APEX 5.0 demo see : https://apex.oracle.com/pls/apex/f?p=11169</p>
