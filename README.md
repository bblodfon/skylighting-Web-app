# skylighting-Web-app
My thesis code for AUEB (Athen Univercity of Economics and Business - Computer Science Program)

<b>Abstract</b>

In this thesis we study and briefly examine different skylight models that have been proposed by the scientific community and we analyze a more recent one which provides an analytic model for full-Spectral Sky-Dome Radiance. This model is used to implement a web-based application which takes input from the user and draws a scene on a canvas element using the JavaScript 3D library three.js. This scene includes a basic 3D-model, a ground plane, the sky Dome, the Sun and the light sources that represent the radiance of the sky. A full explanation is provided for the source code and the functionality of each component of the Web-application as well as some screenshots of the scene, showing different instances of the sky dome and the 3D-model while changing the turbidity, the ground albedo value as well as the solar elevation.

To run the application, just put the skymodel folder inside a web-server (e.g. inside pathToXAMPP/htdocs/ for windows, or in /var/www for Linux) and go to http://localhost/skymodel/skydome.html.

If you want to compile the dome_points.c do: gcc -std=c99 dome_points.c ArHosekSkyModel.c -o dome_points.exe
