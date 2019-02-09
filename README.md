# Bene Promo Redirect
A Bene Feature module.

## Description
The Bene Promo Redirect tool is a intended for special, short-term campaigns
such as end-of-year giving pushes, to redirect site visitors to a specific page
or external site when they visit your website. It uses no cookies, and instead
decides whether or not to redirect users based on how they arrived at your site:
if they arrived from the promoted page that you redirect them _to_, for example,
it will not redirect them again. Similarly, if they are already on your site and
click an internal link, it will not redirect them because they are coming from
inside your site.

The Promo Redirect tool supports redirecting from any number of specified pages,
but never allows redirects from admin pages or from "user" pages, such as the
login page. The most common usage is to redirect only the homepage, which is
specified by adding "/" in the configuration screen.

## Strategic Use
Bene Promo Redirect should be used sparingly, for moments when you want all of
your interested constituents to receive exactly one message: something important
needs their attention _right now_. Over-using this behavior may wear on your
constituents, and make its usage less impactful.

Think of this feature as a loudhorn: useful but also mildly annoying! People
will listen to an important announcement on a loudhorn, but not more.

## How To
To configure the Promo Redirect feature, log in as a user with the "Configure
Bene Feature" permission (this is usually associated with the Staff Admin role).
Go to Configure -> Bene Features and find Promo Redirect. If necessary, click
Enable to enable it, then you can click Configure. (Note: when you are done with
your promotional period, you can come back here and Disable the Promo Redirect
feature until the next time you need it.)

On the configuration screen, complete the desired fields. To redirect your home
page, put "/" as one of the redirect pages.

Be sure to visit your redirect "Destination" page and verify that any links on
that page that go back to your website use the exact "protocol" and "domain"
that appear when you are on your site. For example, if your site loads with
"https://", make sure your page doesn't link using "http://". The same is true
for including "www." before your domain: make sure they match. A mismatch breaks
the feature's ability to identify where people are coming from and make an
appropriate decision about redirecting them.
