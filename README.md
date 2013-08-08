nkProgressHUD
=============

nkProgressHUD is a responsive web HUD that preoccupies users during server-side tasks.

![nkProgressHUD](http://naoufal.com/assets/img/nkprogresshud.png)

Demo
----------
### Try the demo [here](http://naoufal.com/projects/nkprogresshud/).

Requirements
----------
jQuery & Modernizr (csstransforms3d)

How to use
----------

To get started, include the files in the `head` section of your HTML document.  Make sure you're loading the jQuery library before nkProgressHUD.

    <head>
        <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>
        <script src="lib/modernizr.custom.21716.js"></script>   
        <link rel="stylesheet" href="http://naoufal.com/projects/nkprogresshud/nkProgressHUD.css" type="text/css" media="screen"/>
        <script type="text/javascript" src="http://naoufal.com/projects/nkprogresshud/nkProgressHUD.js"></script>
    </head>

### Display the HUD

You can display the HUD by initializing nkProgressHUD like this:

    nkProgressHUD.show(loaderString);

You can display whatever text you want by replacing `loaderString' with whatever you want to display to the user.

    nkProgressHUD.show('Text to Display');

### Changing the HUD Text

You can change the dispalyed text at any point during your script with the following:

    nkProgressHUD.change('New Text');

###Dismissing the HUD

You can dismiss the HUD by adding the following to the end of your script:

    nkProgressHUD.dismiss();


## Credits

nkProgressHUD is brought to you by [Naoufal Kadhom](https://twitter.com/naoufal). The spinner icon was generated over at [Preloaders](http://preloaders.net/). nkProgressHUD is inspired by [Sam Vermette](http://samvermette.com)'s [SVProgressBar](https://github.com/samvermette/SVProgressHUD).
