---
layout: docs_page
title: Okta API Release Notes
excerpt: Summary of changes to the Okta API since Release 2017.50
---

## Okta API Release Notes for Release 2017.52

These release notes summarize the changes since 2017.49. Dates for preview and production release are the earliest possible release date. Always check your org to verify the release version.

### New and Enhanced Feature

#### Strict Policy Enforcement for Password Changes

Added `strict` optional parameter to the following operations:

* [Update User](https://developer.okta.com/docs/api/resources/users.html#update-user)
* [Change Password](https://developer.okta.com/docs/api/resources/users.html#change-password)

This parameter allows you to force the validation of the password policy’s `minAge` and `passwordHistory` requirements when an updated password is sent. This will be Generally Available in preview orgs starting on Dec 13, 2017 and in production orgs starting on Dec 19, 2017.
<!-- OKTA-148151 -->

### API Bug Fix

The following bug fixes will be available on preview orgs starting Dec 13, 2017, and will be available on production orgs starting December 19, 2017:

* When using the [Zones API](https://developer.okta.com/docs/api/resources/zones.html#update-an-ip-zone), erasing all IP addresses in the Default IP Blacklist zone caused an error. (OKTA-145602)


### Does Your Org Have This Change Yet?

To verify the current release for an org, check the footer of the Dashboard page. If necessary, click the **Admin** button to navigate to your dashboard.

{% img release_notes/version_footer.png alt:"Release Number in Footer" %}

### Looking for Something Else?

* [Platform Release Note Index for 2016](platform-release-notes2016-index.html)
* [Platform Release Note Index for 2017](platform-release-notes2017-index.html)
* For changes outside the Okta platform, see the [Product Release Notes](https://help.okta.com/en/prev/Content/Topics/ReleaseNotes/okta-relnotes.htm).