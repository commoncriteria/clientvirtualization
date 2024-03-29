PP-Module for Client Virtualization 
============

[cols="1,1,1,1,1,1,1,1"]
|===
8+|clientvirtualization 
| https://github.com/commoncriteria/clientvirtualization/tree/master[master] 
a| https://commoncriteria.github.io/clientvirtualization/master/clientvirtualization-release.html[📄]
a|[link=https://github.com/commoncriteria/clientvirtualization/blob/gh-pages/master/ValidationReport.txt]
image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/validation.svg[Validation]
a|[link=https://github.com/commoncriteria/clientvirtualization/blob/gh-pages/master/SanityChecksOutput.md]
image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/warnings.svg[SanityChecks]
a|[link=https://github.com/commoncriteria/clientvirtualization/blob/gh-pages/master/SpellCheckReport.txt]
image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/spell-badge.svg[SpellCheck]
a|[link=https://github.com/commoncriteria/clientvirtualization/blob/gh-pages/master/TDValidationReport.txt]
image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/tds.svg[TDs]
a|image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/transforms.svg[transforms,150]
a| [link=https://github.com/commoncriteria/clientvirtualization/blob/gh-pages/master/HTMLs.adoc]
image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/html_count.svg[HTML Count]
[link=https://github.com/commoncriteria/clientvirtualization/blob/gh-pages/master/PDFs.adoc]
image::https://raw.githubusercontent.com/commoncriteria/clientvirtualization/gh-pages/master/pdf_count.svg[PDF Count]
|===


[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/clientvirtualization.svg?maxAge=2592000)](https://github.com/commoncriteria/clientvirtualization/issues) 


This repository hosts the draft version of the PP-Module for Client Virtualization based on the 
[Essential Security Requirements (ESR)](https://commoncriteria.github.io/pp/clientvirtualization/clientvirtualization-esr.html) for this technology class of 
products. This repository is used to facilitate collaboration and development on the draft document. 
See the [release](#Release-Version) section if you are looking for the officially released version for evaluations. 
A list of products that have passed evaluation against this PP-Module can be found [here](https://www.niap-ccevs.org/Profile/Info.cfm?id=409).

## Draft Version

* [PP-Module for Client Virtualization](https://commoncriteria.github.io/pp/clientvirtualization/clientvirtualization-release.html) (html)
* [PP-Module for Client Virtualization](https://commoncriteria.github.io/pp/clientvirtualization/clientvirtualization-release.pdf) (pdf)
* [Supporting Documents for Client Virtualization](https://commoncriteria.github.io/pp/clientvirtualization/clientvirtualization-sd.html) (html)
* [Supporting Documents for Client Virtualization](https://commoncriteria.github.io/pp/clientvirtualization/clientvirtualization-sd.pdf) (pdf)


## Release Version
* [Extended Package for Client Virtualization](https://www.niap-ccevs.org/Profile/Info.cfm?id=409)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/clientvirtualization/issues)


## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/clientvirtualization.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License

See [License](./LICENSE)
