D3BulletCharts - QlikView Extension
===

D3BulletCharts is a QlikView object extension based on the famous [D3 JavaScript charting](http://d3js.org/) library.


Motivation
---------------
If you install QlikView you'll find an extension example called "Bullet Chart" with a basic implementation to integrate bullet charts in QlikView.

While this kind of visualization (based on a concept created by Stephen Few) is quite famous this extension here offers some more functionality based on a piece of code I have found on [bl.ocks.org](http://bl.ocks.org/mbostock/4061961).

Screenshots
---------------

**Adding the object:**

![](https://raw.github.com/stefanwalther/QlikView-Extension-D3BulletCharts/master/Images/D3BulletCharts_ExtensionObject.png)


**The final result:**

![](https://raw.github.com/stefanwalther/QlikView-Extension-D3BulletCharts/master/Images/D3BulletCharts_Example.png)

**Configuration:**

![](https://raw.github.com/stefanwalther/QlikView-Extension-D3BulletCharts/master/Images/D3BulletCharts_Configuration.png)

Sample Application
---------------
A QlikView sample application using this extension is published in the "Demo" directory


## Further Information

### Compatiblity
This QlikView Object Extension is only developed and tested with QlikView 11 SR2 or higher.

### Change Log
* v1.0.1 (11/19/2913) - Added support for selecting one of 22 predefined color schemas
* v1.0.0 (11/18/2013) - Initial version

### Known Issues

- If you do not like the colors, change the `style.css` located in the folder `lib/css/`

### Possible Improvements
Some improvements I could imagine:

* <del>Offering a possibility to select a color scheme</del>
* Implementing an option to change between horizontal and vertical layout (see [http://www.jasondavies.com/bullet/](http://www.jasondavies.com/bullet/))
* Additional layout properties for
 * font-sizes for "Title", "SubTitle" & "Scale"
 * color for "Title", "SubTitle", "Scale" 


### License
The software is made available "AS IS" without any warranty of any kind under the MIT License (MIT).
Since this is a private project QlikTech support aggreement does not cover support for this software.

### Credits

* All credits go to [Mike Bostok](https://github.com/mbostock) and his fabulous work on the [D3 library](http://d3js.org).
* Icon set(s) used for this solution:
 * "Batch Icons" by Adam Whitcroft (http://adamwhitcroft.com/batch/)



### Resources

* Code: `git clone git://github.com/stefanwalther/qlikview-extension-d3bulletcharts.git`
* QlikView Extension (.qar file): download here
* Instructions on [installing and deploying QlikView Extensions](http://www.qlikblog.at/1597/qliktip-40-installingdeploying-qlikview-extensions/)
* Issues: [https://github.com/stefanwalther/QlikView-Extension-D3BulletCharts/issues](https://github.com/stefanwalther/QlikView-Extension-D3BulletCharts/issues)
