Runfile: batch
==================================================

Run commands in batch with parameters from a config file.

Prerequisites:
--------------------------------------------------

    $ gem install runfile


Usage
--------------------------------------------------

Copy the `sample.yml` file as `config.yml`, and edit the file to your needs, 
then run:

    $ run batch config.yml --dry

The `script` configuration should be an array, each with the `:value` token.

The `values` configuration should be an array of values that will be replaced
at runtime.
