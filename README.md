# -Invision-Community-Suite-v4.7.18

Additional Information

Core

Added new prune setting for failed requests in API logs.
Improved the efficiency of unread content streams when using MySQL 8.
Improved performance when replying to a content item or create a content item.
Fixed possible error when using the DataLayer with PII as well as Single Sign on.
Fixed issue with deleting secondary group using the REST API.
Fixed an issue where Censor Block may allow HTML tags to be used in the preview even though they are not stored in the database.
Fixed an issue where group promotion may move the member back to the default group if MySQL is temporarily unavailable.
Fixed an issue where the results count was always 0 for Hidden Content in the ModCP
Fixed an issue where certain saved charts were not showing.
Fixed an issue where broken modlog data could break the topic view page.
Fixed an issue where it was possible to toggle online status without multi-factor authentication.
Fixed an issue where OAuth PKCE values may not persist in some situations.
Fixed an issue where some very old topics would not show the "I posted in this" star.
Fixed an issue with notifications on comments that did not account for anonymous posting.
Fixed an error on the Manage Promoted Items page when an application is disabled.
Fixed an issue which happened while warning a member.
Fixed an issue where the content widget was showing the tags option for all content types, even if they weren't implementing tags.
Fixed an issue where a service worker may not work if your site is not accessible to guests.
Fixed an issue where deleted an application wouldn't remove the data from the core_javascript db table.
Fixed an issue on the moderators permission page.
Fixed an issue where the REST API (with API key) would not return a last activity date for anonymous members.
Fixed an issue on Cloud where large Member CSV imports would inadvertently trigger human verification.
Removed CommunityHive integration.
Removed ability for pending-validation registrations changing their email address to avoid a race condition.
Forums

Improved performance when rebuilding statistical data for forum topics.
Commerce

Added a new prune settings for Commerce related member history.
Fixed an issue where upgrading subscriptions did not always update the expiration date.
Fixed an issue where support request URLs would be sent to IndexNow.
Fixed an issue where some support requests were not properly linked to a member account.
Fixed an issue where some billing agreements were not properly linked to purchases.
Fixed an issue where changing the club owner could fail for paid clubs.
Courses

Fixed an error that could occur when viewing badges that had been assigned for completing a course.
Calendar

Fixe dan issue in the upcoming events widget where club events would be shown even if they shouldn't.
Pages

Fixed an issue with the RSS Feed widget, where the cache expiration time would be overwriten by the custom rss widget cache time.
Platform

Removed the 'Popular Now' widget, use 'Trending Content' instead.
Changes affecting third-party developers and designers

Added new _setLastComment() method to nodes.
Added new \IPS\Node\DelayedCount trait.
Other performance improvements included related to search index and content statistics.
