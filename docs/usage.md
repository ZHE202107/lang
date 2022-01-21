# Basic Usage

## Copy files


> When installing the package this way, you will need to manually copy the files from the `vendor/laravel-lang/lang` folder into your application.
>
> If you want to automate the process, then use one of the [publishers](installation/managers.md).

After adding the dependency using composer (as described above) to your application you can find the language files under the directory `vendor/laravel-lang/lang`.

Copy the folders of languages that you want, in `resources/lang` or `lang` directory of your Laravel application.


## Translation managers

You can also use one of the translation managers to automate the file update process:

* [Lang Publisher](https://github.com/Laravel-Lang/publisher) by [*@Laravel-Lang/laravel-lang*](https://github.com/Laravel-Lang/publisher) - Easy installation and update of
  translation files for your project.
* [LaravelLang](https://github.com/ARCANEDEV/LaravelLang) by [*@arcanedev-maroc*](https://github.com/ARCANEDEV) - Translations manager and checker for Laravel.
* [Laravel-lang](https://github.com/overtrue/laravel-lang) by [*@overtrue*](https://github.com/overtrue) - Command to add languages in your project.