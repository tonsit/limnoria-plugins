Old version of plugin. Return the latest Coronavirus (COVID-19) statistics. Uses JHU data.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=T8E56M6SP9JH2)

`config plugins.coronalight.template` - Configure the template for replies

Template default: `\x02$location: \x0307$confirmed\x03 infected, \x0304$dead\x03 dead ($ratio), \x0309$recovered\x03 recovered. (Last update: $updated)`

`config plugins.coronalight.countryFirst` - Country name abbreviations take precedence over USA state name abbreviations when `True`

countryFirst default: `False`

`config plugins.coronalight.cacheLifetime` - Time in seconds to cache API results. Default: `600`
