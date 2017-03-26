# operation-failed polymer custom element

[![Greenkeeper badge](https://badges.greenkeeper.io/vajahath/operation-failed.svg)](https://greenkeeper.io/)
A UI element that can be used to indicate that the operation was unsuccessful.

![demo](https://lh3.googleusercontent.com/Oje7iXFY5S4N48s_lWOIoCrHNSxT3s5q6ahqIHqno0hnlix-Kf27BgbeB40Qfi5qoedzblTk6TN3J-uq9sYhsvSkshPTJjaXOZKzDvxQXI8u_DOjAn6QDBH0wMwpH6TLQwUFDHFPufGIyoJVHXf0UooHxtCRH5nVRqp2sbECKb1BHbXAb8fEd3r6HKLZwFtlvQ99GbfXFa9fofpc53adWEN3uh_NhI-MA0b7-Ginl5uuZ4H1Ws2OFm4jc2SBMxbg9yKw_6wumb0t1GMMgZY8zlbPtzN6_rAjdbbVQG97l28a53Aw-frL96tbCNcARfQvilzHtYrmkP7Aog6ho_hoW0wR205xy2pED0K2xj5Q_a1eulm8u8x4RnR_sTs78v3fgSDPNf1ciZiVYXVtQsqyFwMxHeFPlJSlSiR93Rwmk1-dV_mysp73YzImT9m0wQxigPJ-vPW0qwob7R4SJmVF7KT4GqnEPDiVYubajFkEyYqIqIsQM5bkw1If79ptRmzN88fzb0CxEEYRnecG7Gv5sjun6QcH4dWgBgDps2pqXoF6hp9efkd_foY_-G3YPb4JXffCuR_KOp4Zn9-dWt8C_1ULFPv3XSFF=w702-h250-no "<operation-failed> element")

Just use
```html
<operation-failed></operation-failed>
```
to show up the above element.

## Setup Polymer and Bootstrap.

You need Polymer base files to use this component.

1. Install Bower if you don't have : `sudo npm install -g bower`.
2. Download Polymer using bower: `bower install Polymer/polymer`.

You also need [Bootstrap](http://getbootstrap.com/getting-started/#download) v3.3.6 or higher to work this component correctly.

## Install this package

`npm install --save operation-failed`

## Dependency Locations

_Verify your directory structure. (if necessary)_ 
```
|
|-- operation-failed
|   |-- operation-failed.html (this file)
|-- bower_components
    |-- polymer
    |   |-- polymer.html
    |-- webcomponentsjs
        |-- webcomponents-lite.min.js
```

# Usage

```html
<head>
    <!-- Bootstrap minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
    ...
    <!-- import webcomponents-lite.min.js -->
    <script src="/path/to/bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ...
    <!-- import the file -->
    <link rel="import" href="/path/to/operation-failed.html">
    ...
</head>
<body>
    ...
    <operation-failed attribute1="value1" attribute2="value2"></operation-failed>
    ...

    <!-- Bootstrap minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" integrity="sha384-0mSbJDEHialfmuBBQP6A4Qrprq5OVfW37PRR3j5ELqxss1yVqOtnepnHVP9aJ7xS" crossorigin="anonymous"></script>
</body>

```


## Attributes

By default `<operation-failed></operation-failed>` tag will output the default values.

Attributes      | Type        | Default value            | Description                               
--------------- | ----------- | ------------------------ | ------------------------------------------
`header`        | String      | `We're sorry,`           | `header = "15th June 2016"` will output the string at the top of the element.
`title`         | String      | `Something went wrong !` | `title = "Upload Failed"` will output the string title of the element.
`info_bold`     | String      | `Failed`                 | `info_bold = "bolded! "` will output the string as a strong info.
`info`          | String      | `File upload`            | `info = "hello-world"` will output the string as a normal info.
`button_name`   | String      | ` Retry`                 | `button_name = "bye"` will output the string on the button.
`button_href`   | String (url)| `http://www.google.com`  | `button_href = "https://twitter.com"`: when you click on the button, you will be directred to the provided link.

## Example 

```html
<head>
    ...
    <!-- Bootstrap minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
    ...
    <!-- import webcomponents-lite.min.js -->
    <script src="/path/to/bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ...
    <!-- import the file -->
    <link rel="import" href="/path/to/operation-failed.html">
    ...
</head>
<body>
    ...
    <!-- default usage -->
    <operation-failed></operation-failed>

    <!-- customized usage (recommended) -->
    <operation-failed header="I am a header" title="I am the Title"></operation-failed>
    ...       

    <!-- Bootstrap minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" integrity="sha384-0mSbJDEHialfmuBBQP6A4Qrprq5OVfW37PRR3j5ELqxss1yVqOtnepnHVP9aJ7xS" crossorigin="anonymous"></script>
 
</body>

```


## Questions ?

Feel free to ping me on Skype at `vajuinside`.

If you found any issues, [file an issue on Github](https://github.com/vajahath/operation-failed/issues).

visit my [profile](https://www.npmjs.com/~vaju) to see other elements.

bye..


## Change Log
*1.0.2*
* Anonymous documentation update.

*1.0.1*
* New image in the documentation.

*1.0.0*
* Initial release.

