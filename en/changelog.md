# Revision history

## September 2021

### yfm-docs

#### 1.13.0

* YFM2 is used

### yfm-transform

#### 2.0

* YFM can be used on the client.
* The plug-in connection scheme has been changed.
* The [markdown-it-attrs](https://www.npmjs.com/package/markdown-it-attrs) plugin is always connected.
* The [highlight.js](https://www.npmjs.com/package/highlight.js) package must be installed independently.

## July 2021

### yfm-docs

#### 1.12.0

* The experimental YFM linter was disabled.

### yfm-transform

#### 1.9.0

* Added the ability to enable support for GitHub compatible anchors (GFM).

## June 2021

### yfm-docs

#### 1.11.0

* An experimental YFM linter was enabled.

#### 1.10.0

* Now you can configure redirects using a special file. Static builds are not supported.

#### 1.9.0

* Added support for sections accessible only by direct link.

### yfm-transform

#### 1.8.0

* Added experimental linter support

## April 2021

### yfm-docs

#### 1.8.0

* Added the option to add file contributors to metadata. Only GitHub is supported out-of-the-box. It isn't displayed visually in any way, but can be used by a custom viewer.

## March 2021

### yfm-docs

#### 1.7.0

* Added complete disabling of variables: conditions are not calculated and values are not substituted.

### yfm-transform

#### 1.7.0

* Added complete disabling of variables: conditions are not calculated and values are not substituted.

## January 2021

### yfm-docs

#### 1.6.0

* Now you can build a document as a single HTML file.

#### 1.5.0

* Refactoring and bug fixes

#### 1.4.0

* Added disabling the calculation of conditions with variables.

### yfm-transform

#### 1.6.0

* Added support for loops, filters, and functions

#### 1.5.0

* Added a feature to use the `not_var` flag for variables that don't need to be substituted with values. For example, `not_var{{ variable_name }}`.

## October 2020

### yfm-docs

#### 1.3.0

* Added the ability to display built files on S3.

## August 2020

### yfm-docs

#### 1.2.0

* Now the documentation interface allows the user to change the font size, turn on the dark theme, and hide the table of contents.

### yfm-transform

#### 1.4.0

* Added an option to use '|' in variables.

## July 2020

### yfm-transform

#### 1.3.0

* Basic element styles have been updated.

#### 1.2.0

* Added support for inserting videos.

#### 1.1.0

* Added support for multiple custom anchors per header.

## June 2020

### yfm-docs

#### 1.1.0

* Added silent mode without outputting build logs.

