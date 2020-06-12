<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/sssolutiontec/open-source-catalog/actions?query=workflow%3A%22Master+branch+CI%22"><img src="https://github.com/sssolutiontec/open-source-catalog/workflows/Master%20branch%20CI/badge.svg" alt="Build status"></a>
</p>
<br><br>

# Open Source Catalog

Aim is to catalog as many open source as possible with the help of community.

<strong><a href="https://opensourcecatalog.com">Find in catalog!</a></strong>
<br><br><br>

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/sssolutiontec/open-source-catalog. 
This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

### Add/Update entry
If you have account on github use [Add new entry](https://github.com/sssolutiontec/open-source-catalog/issues/new?assignees=&labels=&template=aNewEntry.md&title=Add+new+entry) 
or [Update existing entry](https://github.com/sssolutiontec/open-source-catalog/issues/new?assignees=&labels=&template=aUpdateEntry.md&title=Update+existing+entry)
to request add/update entry.

### Send us email
You can send email on (info at sssolutiontec dot com) subject should include OSC init. e-g Add entry OSC or update entry OSC

For new entry, your email should contain following
```
Please note title, description, website, source code, technologies and categories are mandatory.

*Title:
Name of open source product. This will appear on top of page.

*Description:
A clear and concise description of what this is about.

*Website(s):
A Online demo or website about the product for more/detail information.

*Source code(s):
Location of source code. Can be multiple repos. More detail better it will be. e-g frontend repo & backend repo etc

*Technologies:
Technologies used to create this product e-g Java, mysql, solr, php etc

*Categories:
General category, under which we should put this product. In case of multiple categories, please specify the main catagory
under which we should place this product. e-g biology(main), education

Blog(s):
Where from you came to know about this product or if any blog explaining about this product

Tags:
Tags to help additional search keywords

Products:
Other product offer by same vendor which might interest readers.

Others:
Any other field you would like to include in this page. e-g fieldname:value
```

For update, your email should contain following
```
*Category:
Category in which we can find entry. 

*Title:
Name of Entry which you want to change.

Details
Provide all the details in following format which you want to update.

FieldName:Value
```

### Add/Update pull request
You can fork code and add/update doc folder pages accordingly and submit PR.

### Submitting code changes:

- Open a [Pull Request](https://github.com/sssolutiontec/open-source-catalog/pulls)
- Ensure all CI tests pass
- Await code review
- Bump the version number in `open-source-catalog.gemspec` and `package.json` according to [semantic versioning](https://semver.org/).

## Development

This catalog Build upon <a href="https://pmarsceill.github.io/just-the-docs/" target="_blank">Just the Docs</a> on <a href="https://github.com/pmarsceill/just-the-docs" target="_blank">github</a>, using Jekyll.

To set up your environment to develop this theme, run `bundle install`.

Your site is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When this is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
