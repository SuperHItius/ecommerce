# This is simple way to make static site with Webpack with no worries :)

**Launch project ways**

* npm run start - start dev server on the 8080 port of localhost
* npm run build - build bandle files for prod

**Dinamic import html-layouts**

* <%= _.template(require('./../includes/views.html').default)(data) %> 

**Dinamic import scss-styles**

* @import './way/style.scss'

*The template is open to experimentation and can work with yarn and bower :)*