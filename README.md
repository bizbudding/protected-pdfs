# Protected PDFs
Attach PDFs to pages/posts/cpts that can only be viewed from the pages they are attached to (via PDF.js). Requires Genesis for file display and ACF Pro for the files metabox.

Use `apply_filters( 'wampum_protected_media_post_types', $post_types );` to filter which post types support Protected PDFs.
Use `apply_filters( 'wampum_protected_media_image_size', $image_size );` to change the image size used for display.
