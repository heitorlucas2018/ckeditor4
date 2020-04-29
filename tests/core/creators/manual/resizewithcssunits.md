@bender-tags: bug, 4.14.1, 1883
@bender-ui: collapsed
@bender-ckeditor-plugins: toolbar, wysiwygarea, table

1. Open browser developer tools.

1. In console paste: `CKEDITOR.instances[ 'editor' ].resize( '20em', '10em' )`

## Expected

Editor changes its size.

## Unexpected

Editor is not resized.
