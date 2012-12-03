openumea-theme
==============

Theme for openumea.se

Setup
=====
	cd $(dirname path-to-development.ini)
	git clone git://github.com/openumea/openumea-theme.git

	ckan.site_title = OpenUmea
	ckan.site_description = Open data from the municipality of Umea
	ckan.favicon = /images/icons/UmeaKommun.ico
	ckan.site_logo = /images/UmeaKommun.png
	ckan.locales_offered = en sv
	extra_template_paths = %(here)s/openumea-theme/templates
	extra_public_paths = %(here)s/openumea-theme/public
