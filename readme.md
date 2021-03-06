## Laravento Application

Layout, Element(Block) and Admin system like Magento, based on Laravel Framework.

### Installation

Clone git repository:

    git clone git@github.com:violetbrick/laravento-dev.git
  
Init git submodules:

    cd laravento-dev
    git submodule init
    git submodule update
  
Install dependencies:

    composer install

Apply database migrations:

    php artisan migrate

### Development

#### Anotations

Route and Event anotation already included, see official documentation for details http://laravelcollective.com/docs/5.0/annotations

#### Themes and layouts

*note: by default and for fallback will be used base/default directory*

All layout elements described in:

    config/layout.php

Theme settings defined in:

    config/theme.php

All layout files will be included automatically from:

    resources/design/{your_package}/{your_theme}/layout

Templates should be placed to:

    resources/design/{your_package}/{your_theme}/template

Assets must be placed to:

    public/design/{your_package}/{your_theme}
