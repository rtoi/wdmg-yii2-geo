# Yii2 GEO Module
Geo module with countries and cities

# Installation
To install the module, run the following command in the console:

`$ composer require "wdmg/yii2-geo" --dev`

# Migrations
To execute the migration and create the initial data, run the following command in the console:

`$ yii migrate --migrationPath=@vendor/wdmg/yii2-geo/migrations`

# Configure
To add a module to the project, add the following data in your configuration file:

    'modules' => [
        ...
        'tasks' => [
            'class' => 'wdmg\geo\Module',
        ],
        ...
    ],

# Status and version
v.1.0.0 - Module in progress development.