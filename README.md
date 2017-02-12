# Topic Image Preview

## Installation

Copy the extension to phpBB/ext/vse/TopicImagePreview

Go to "ACP" > "Customise" > "Extensions" and enable the "Topic Image Preview" extension.

## Tests and Continuous Integration

We use Travis-CI as a continuous integration server and phpunit for our unit testing. See more information on the [phpBB Developer Docs](https://area51.phpbb.com/docs/dev/31x/testing/index.html).
To run the tests locally, you need to install phpBB from its Git repository. Afterwards run the following command from the phpBB Git repository's root:

Windows:

    phpBB\vendor\bin\phpunit.bat -c phpBB\ext\vse\TopicImagePreview\phpunit.xml.dist

others:

    phpBB/vendor/bin/phpunit -c phpBB/ext/vse/TopicImagePreview/phpunit.xml.dist

[![Build Status](https://travis-ci.org/VSEphpbb/TopicImagePreview.svg?branch=master)](https://travis-ci.org/VSEphpbb/TopicImagePreview)

## License

[GPLv2](license.txt)
