# MBNOG.ca website (Now in hugo!)

## to work on the site

*	fork the repo and make a branch for what you would like to commit
*	make your changes to that branch
*	use Github to make a pull request for your branch
	*	you may be requested to sync your branch (see github's [configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/) and [syncing a fork](https://help.github.com/articles/syncing-a-fork/) documentation for help with that)

## Build the site locally

Get a copy of hugo, releases are available from the [Github Repo](https://github.com/gohugoio/hugo/releases)

### To develop the site:

	hugo server --disableFastRender 
	open http://localhost:1313/

### To publish the site:

	hugo

The site will then be in the `public` directory (or wherever configured in `config.toml`)

