===BP Group Documents  ===
Contributors: Lena Stergatu (http://lenasterg.wordpress.com) since version 0.4 with additional bug fixes by Keeble Smith Ltd (http://keeblesmith.com) and Anton Andreasson work for BP 1.7. Initial plugin author Peter Anselmo
Tags: wpms, buddypress, group, document, plugin, file, media, storage, upload, widget
Requires at least: WP 3.5, BuddyPress 1.7
Tested up to: 3.6, BuddyPress 1.8
Stable tag: 1.0 (Requires at least: WP 3.5, BuddyPress 1.7)
License: GNU General Public License 3.0 or newer (GPL) http://www.gnu.org/licenses/gpl.html
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Q4VCLDW4BFW6L 

This allows members of BuddyPress groups to upload and store files and documents that are relevant to the group.

== Description ==
Group Documents creates a page within each BuddyPress group to upload and any type of file or document. 
Documents can be edited and deleted either by the document owner or by the group administrator.
Categories can be used to organize documents. 
Activity is logged in the main activity stream, and is also tied to the user and group activity streams.
The site administrator can set filters on file extensions, set display options, and upload files via FTP.
Group members and moderators can receive email notifications at their option. 
The group administrator can decide if all members or only admins/moderators can upload documents (Since v0.5)
User verification for Downloads: when a document is downloaded, a redirect page checks is the user is member of the group (in case of a private  or hidden groups) and only then the user can download the file.(Since v0.5)
3 Widgets: "User's groups documents" (since v0.5) ,"Recent Uploads" , "Popular Downloads"  can be used to show activity at a glance.


PLEASE: If you have any issues or it doesn't work for you, contact Lena on http://lenasterg.wordpress.com. Reporting bugs is the only way for them to be fixed.  It doesn't help anyone to mark "broken" without asking around.  Thanks!  

NOTE: For Buddypress v1.5, use the plugin's version 0.4.3.3. available in http://lenasterg.wordpress.com/2012/04/17/buddypress-group-documents-for-bp-1-5-and-wp-3-3/

== Installation ==

Make sure Wordpress and BuddyPress are installed and active.

Copy the plugin folder buddypress-group-documents/ into /wp-content/plugins/

Browse to the plugin administration screen and activate the plugin.

There will now be a "Group Documents" menu item under the "Settings" menu.  Here you will find a list of all file extensions allowed for uploaded files along with other settings.

== Upgrade Notice == 
If you upgrade from older version you must also add a  your .htaccess in order 
to ensure that requests to the old URLs are redirected to the new, hardened URL
That line is: 
RewriteRule ^wp\-content/blogs\.dir/1/files/group\-documents/(.*) /?get_group_doc=$1 [R,L]


== Frequently Asked Questions ==
 1. If you run a windows server and you get errors about mb_convert_case  function which is a default php function (see http://php.net/manual/en/function.mb-convert-case.php), you must uncomment the line with php_mbstring.dll in your php.ini
 2. If you are a plugin developer and want to use the upload file form you can link to /group_slug/bpgroupdocuments_slug/add to access the upload document form

== Screenshots ==
Need to be made
1. Admin settings page
2. Documents settings page on group creation
3. Upload document form
4. Document list tab
5. Ties into site activity stream (for public groups only)
6. Group admin document's settings tab, allow category's edit, addition 
7. User options for email notifications
8. Widget Recent Documents from your groups  and Widget Popular Group Documents
9. Message when non member of a private or hidden group tries to access a group document


==Changelog==
See history.txt for version changelog

Aplogies for the frequent updates, this plugin is under active development!

== Notes ==

Roadmap.txt - contains ideas proposed and the (approximate) order of implementation

History.txt - contains all the changes since version .1

License.txt - contains the licensing details for this component.

== Feedback ==

Please leave a comment  with any bugs, improvements, or comments at http://lenasterg.wordpress.com


== Donate ==
You can  say "Thank You" via my Amazon wish list
http://www.amazon.co.uk/registry/wishlist/7HYK62UCVCDI
or donate at paypal https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Q4VCLDW4BFW6L 