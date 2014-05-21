Clone to your Sublime Text 3 User Packages Folder:

For Mac: '/Users/username/Library/Application Support/Sublime Text 3/Packages/User/'

Then, move the /images folder to reside within your project folder.*


Contained Snippets:

template  : An HTML email template with tab stops for campaign customization
tbl       : An HTML table, with styling for email
gatags    : Google analytics tags for links (company-specific)
bnr       : A linked image that is centered inside its parent
horz      : A horizontal spacer for use in tables (a <td> for spacing)
vert      : A vertical spacer for use in tables (a <tr> & <td> for spacing)
img       : An image, ready for HTML email (Might override img snippet)
lnk       : A linked image, ready for HTML email
sans      : A set of sans-serif styling, ideally applied on <td> elements
serif     : A set of serif styling, ideally applied on <td> elements


Snippet Variables:

ORGANIZATION_NAME   : Your company name string (no spaces)
IMG_NAME            : Image filename (no spaces, no extension)
EXT                 : The image file’s extension
PROJECT_NAME        : Your email project name (no spaces)
PROJECT_TITLE       : The email project’s title, visible to the user in inbox and tab
PROJECT_URL         : The absolute URL to your project folder (including final /)
LINK_TARGET         : The click-through target URL for the link
ALT_TEXT            : The image’s alternate text

*Don’t forget to upload all your email’s images to a web-public location. Local testing is great, but email recipients won’t be able to see images in your testing environment.