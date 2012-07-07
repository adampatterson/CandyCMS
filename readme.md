# Candy
Candy is an easy to use CMS written in PHP.

Take a look at [this screencast](https://vimeo.com/45358208) to see Candy in action.

## Requirements
* PHP 5.3 or greater
* cURL (for updating)
* MySQL or other database (DB driver will need to be edited if not using MySQL)
* Ability to write htaccess file for apache mod_rewrite

## Installation

* Upload CandyCMS to the directory of your choice.
* Navigate to the installation in your browser. 
* Follow the instructions.
* Done!

## Troubleshooting

If you encounter an issues with the path and files not working remove the `$_SERVER['DOCUMENT_ROOT']` from the core/config.php CMS_PATH constant.

## Documentation
See [http://www.candycms.org/docs](http://www.candycms.org/docs)

## Issues
Please log any issues found in the Github repo or tweet them at [@steve228uk](http://www.twitter.com/steve228uk)

## License
Candy is released under the GPLv2 License