# wordpress-blank-title
Replace blank WordPress post title with the date/time

The Micro.blog service leaves post titles blank as they are not needed, this can be frustrating when self-hosting as wp-admin lists posts as (no title) with no way to distinguish them.

The function simply checks the post title pre-save and changes it if empty.
