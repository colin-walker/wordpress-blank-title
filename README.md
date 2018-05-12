# wordpress-blank-title
Replace blank WordPress post title with the date/time

The Micro.blog service leaves post titles blank as they are not needed, this can be frustrating when self-hosting as wp-admin lists posts as (no title) with no way to distinguish them.

The function simply checks the post title pre-save and changes it if empty.

To account for BST/DST uncomment the line with `date_default_timezone_set` and add your time zone, e.g. "Europe/London"
