<p align="center"><img src ="/screenshot.png" style="max-width: 200px;"/></p>

A customization of the [Keene](http://keene-demo.squarespace.com) Squarespace template for [rodrigues.ink](http://rodrigues.ink).
In __Developer Mode__ this template can be uploaded to a Squarespace GIT repo.

### Resources
- See the [Wells Squarespace Guide](https://support.squarespace.com/hc/en-us/articles/206545647-Using-the-Wells-template) for base features and functions.
- For more information about the Squarespace Developer Platform see [developers.squarespace.com](http://developers.squarespace.com).
- See the [Developer Getting Started](https://developers.squarespace.com/getting-started) page for an step-by-step guide for getting started with the Squaresapce Developer Platform.

## About Squarespace templates
Squarespace templates contain regular web files like CSS and JavaScript. In addition, Squarespace recognizes a few special file types:

#### JSON-T Template Files

Squarespace template files are written in [JSON Template](https://developers.squarespace.com/what-is-json-t), also known as JSON-T. It is a simple yet expressive template language. JSON-T files have different extensions depending on the type of file, for example `.list`, `.item`, and `.region`.

#### LESS Files

Template LESS files (.less) are processed through the [LESS](http://lesscss.org/) preprocessor. LESS extends CSS with dynamic behavior such as variables, mixins, operations and functions.

### Template Folder Structure

Squarespace template files are organized using the following folder structure at the root of your site:

- **assets**: design assets — example: images, fonts and icons
- **blocks**: reusable blocks of JSON-T (AKA partials) — ex: navigation.block
- **collections**: collection files — [collection].list, [collection].item, [collection].conf
- **scripts**: Javascript files — site.js
- **styles**: stylesheet files — styles.css, styles.less
- [**root**]: sitewide files — site.region, template.conf

### Essential Files

At the very minimum, your template needs a `.region` file and a `template.conf`.

#### /site.region

Typically this file is used as the global site template – containing the site header, footer, and sidebars. This is like the `index.html` of your site. Every template must have at least one `.region` file. Simple templates will have a single `.region`, more advanced templates will have multiple `.region` files describing header, body, and footer variants. Regions files live in the root directory of a template.

See the [Layouts & Regions documentation](https://developers.squarespace.com/layouts-regions/) for more details.

#### /template.conf

Contains the configuration settings for the template. This is where you can name your template, specify layouts, add navigation sections, specify stylesheets, and other general site options. Template configuration files must live in the root directory of a template.

See the [Template Configuration documentation](https://developers.squarespace.com/template-configuration/) for more details.

### Further Reading

For further reading please consult the [Squarespace Template Overview](https://developers.squarespace.com/template-overview/) and other documentation on the Squarespace developers website.
