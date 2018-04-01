# Config

Grafite CMS has a rather elaborate config with many options available. You can expand the core modules, enable / disable features, and configure so much more.

| Key | Description |
| ------ | ----- |
| analytics | Choose an analytics engine for the dashboard (internal or google) |
| pixabay | Your pixabay API code |
| db-prefix | Add a prefix to the Grafite CMS content tables |
| live-preview | Preview your site in the editor view |
| frontend-namespace | Sets the default namespace for the frontend code |
| frontend-theme | The theme for the frontend |
| load-modules | Do you want to load the external modules |
| module-directory | Directory for custom Grafite CMS modules |
| active-core-modules | Which core Grafite CMS modules are active |
| rss | A set of attributes which can be set for the RSS feed |
| site-mapped-modules | The module urls and their repositories that build the site map XML |
| auto-translate | Automatically translate your content to other languages with Google Translate |
| default-language | Your website's default language |
| languages | Languages available in your website (enables their tabs in the editor) |
| storage-location | Storage for files/ images (s3 or local) |
| max-file-upload-size | The maximum file size for upload (Must also be set in php.ini) |
| preview-image-size | When uploading images we cache clones at a smaller size (default: 800) |
| cloudfront | Set a cloudfront URL to swap for the S3 bucket link |
| backend-title | A title for the CMS (default: cms) |
| backend-route-prefix | The route prefix for the backend of the CMS (default: cms) |
| backend-theme | Theme for the backend (standard|dark) |
| registration-available | Enable or disable registration |
| pagination | Results per pack in backend |
| api-key | Api Key for the Redactor photo and file injection |
| api-token | Api Token for the Redactor photo and file injection, and the general external API calls |
| forms | Forms config for core modules |
