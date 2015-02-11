#Default Wordpress project with composer

#Installation

## Create project

```

composer create-project distilleries/wordpress

```

## Composer
Run

```

 composer install

```

##Environment
Create a file `.env and put the configuration for the database en environment

```

DB_NAME=wordpress
DB_USER=root
DB_PASSWORD=root
DB_HOST=localhost

WP_ENV=development
WP_HOME=http://wordpress.dev
WP_SITEURL=http://wordpress.dev/wp

```

You can define `WP_ENV` and create a new file in `config/environments` with the name of the environment.
It's use to create a specific configuration by env, like the init of `WP_DEBUG`.

##Folders

By default you have a folder `app`. on this one you can find your folder `my-plugin` to put your default plugin.
On the folder `theme`, put your different themes use.
ON the folder `plugins`put all external plugins.

