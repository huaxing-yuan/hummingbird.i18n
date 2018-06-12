# hummingbird.i18n
i18n project for Hummingbird, aimed to help users run hummingbird application with their native languages.

## TextResource.xaml
This file is the orginal and by-default language resources used in Hummingbird application.

## TextResource.xx.xaml or TextResource.xx-xx.XAML
These are the localized language resources files which synchronizes with the original resources in English.
while xx is the ISO 639-1 language code, with two letters in lowercase, for example
es for Spanish, or ja for Japanese.
These resources are for language only, but not country specific and does not take account the differences in culture like decimal point and date time format 


When xx-XX is used, it combines a ISO 639-1 language code and ISO 3166-1 country code. it is a country specifique resource.
for example:
fr-FR and fr-CA are both in french language, but short date time format, currency symbol are different.

