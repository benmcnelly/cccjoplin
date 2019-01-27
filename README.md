# cccjoplin
Central Christian Center, Joplin MO

This project will contain the development branch, static templates, live site, Branding Guide and downloads.

Layout order rough draft:

- redesign site presentation to move away from bootstrap
- move CSS to SASS for portability
- jQuery to cover browser compatibility and time constraints
- move content to new site map, emphasize app approach vs deprecated static info site model
- post layout and content fixes, subdomain setup optimization
- Amazon Route 53 for DNS
- Digital Ocean Droplet's
- Container
- Database
- Git Repo
- Craft CMS | craft.cccjoplin.com/admin (currently inactive)
- Static Resources

Layout within webserver (without disclosing complete server paths):

## Website Templates
	/admin/expressionengine/templates/default_site/website.group/[dev.html]
## CSS
	/admin/expressionengine/templates/default_site/website.group/[cccjoplinjs.js]
## JS
	/admin/expressionengine/templates/default_site/website.group/[cccjoplincss.css]
## Fonts
	/fonts
## Images
	/images/site

### App with three sections:

- lead content
  * greeting (page lead)
  * web app features
    - video content
    - audio content
    - online giving
    - current event organization
  * greeting (text, maybe video?)

- ministries
  * Life Groups
  	- about life groups
  	- life group listing
  * Woven
  	- about
  	- social media
  * Royal Rangers
  	- about
  	- social media
  * Saturday Night Live
  	- about
  	- social media
  * Bright Futures
  	- about
  	- social media
  * Food Pantry

- about
	* church
		- beliefs
		- history
		- staff
		- about the building
	* location
		- contact
  		* address
  		* phone number
  		* directions
  		* social media
  		* service times

- footer  		
	* development
  * licensing
