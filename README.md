# operation-failed polymer custom element
A UI element that can be used to indicate that the operation was unsuccessful.

![demo](https://lh3.googleusercontent.com/awXnDr2q1RZuJ_Xbr9IVK4UBQkuMlzP4dlc_PxP8qkRoQK8pkMkZ4Wem93d_v0OF6ewPrYTXFW3Nc_2XylaXhJrGS5aIdBZ26v_WJO6xWKsjAmNb6G6O54w-vzLic4hyEvsYs9RLcW-R_8X5P2-glyg7K-_y-dnqBXr91SoEuBQUZ_B45Su_V9SKueyQEY9pTXF7v19X-cFhpzmb_Sdy_m296-rVZHMnN0tijjMUQjhGB1vpurBAtL7DRXsq00eZ-v15kIhe9DKqwTwTiTgEu2nyK4nEto7Bx_aAgTkmqM1bcaE4wCzYoXclwDZZFOIEtnlW7bnU0NUE3t52xkZOvKn51iXlaj5tZbIfYTAm9_3PXiixHSjveXZb6zkww-weA_Kjo0_dT2O-DnydLXrfvQFO6rDWWMn3h3ZvdPD7TKzGRIYmGiwUwpkMQcnt4E2GY4OF4Y7NgZJ37hHY6mBPx7hhBZQCftNyfCbPulGvE4CU0elR8dGoksDLXtjbU_I8fIxkYM-58klaKP0fn962Tfpx5J47892eysWtifMmReB6gY_k2kZHoH6oFGU7SSTQ6QHlJD2uzTtFJYbPwB_0M-vWIHpl7NTq=w702-h250-no "<operation-failed> element")

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

visit my [profile](https://www.npmjs.com/~vaju) to see other elements.

bye..


## Change Log

*1.0.0*
* Initial release.

