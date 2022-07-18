# CMS | CORE | Creating a Custom Theme in Wordpress
## User Story 1
*As a Developer, I want to create a theme directory and setup a minimum of required files, so that I can see and select the theme in the WordPress backend.*

### Acceptance Criteria
- The theme directory has been created
- The theme is setup as block theme (index.php only exists for legacy reasons)
- The theme is selectable in the backend
- The index.html has been filled with demo HTML so the preview of pages will show a demonstration text

## User Story 2
*As a Developer, I want to create a theme.json for my custom theme, so that I can setup the basic styles.*

### Acceptance Criteria
- The theme.json with directive to use version 2 exists within the custom theme directory
- The theme.json can be based on the one of the Twenty Twenty-Two theme
- At least one custom font is implemented, which is different than the ones in Twenty Twenty-Two
- At least 2 elements use the custom font
- The developer only uses directives in theme.json which are relevant to the sites style and can explain them

## User Story 3
*As a Developer, I want to load my own stylesheet for the theme, so that I can add additional CSS rules*

### Acceptance Criteria
- The stylesheet is loaded with the theme

## User Story 4
*As a Developer, I want to provide a standard header and footer for all pages, so that the user has a site navigation and legal information available on each webpage.*

### Acceptance Criteria
- One header which is automatically selected for the index template is available
- The header features the website logo (A click on the logo in the header directs to the index of the website)
- The header features a navigation for the website
- One footer which is automatically selected for the index template is available
- The footer features a copyright
- The footer features a link to the Imprint page 
- The theme is selectable in the backend
- The index.html has been filled with demo HTML so the preview of pages will show a demonstration text

## User Story 5
*As a Developer, I want to copy and alter the HTML markup from the Twenty Twenty-Two standard block theme to my own index template, so that I can create a basic template layout quickly"

### Acceptance Criteria
- The index template features 11 posts per page, the user is able to overwrite this default setting via the WordPress backend
- The index shows the featured image along with each post
- The index features a pagination
- The index features a footer

## User Story 6
*As a Developer, I want to create a "Quote with photo" block pattern, so that editors can easily add a photo of the person quoting.*

### Acceptance Criteria
- A block pattern "Quote with photo" is available for the theme
- The block pattern is used in at least 2 posts

## User Story 7
*As a Developer, I want to have my custom theme feature a preview screenshot and a title in the theme selection screen.*

### Acceptance Criteria
- The theme features a screenshot of itself in the selection screen
- The theme features a title that is not the folder name in the selection screen

#### Links
SkillSet: https://my.skilldisplay.eu/en/skillset/509
