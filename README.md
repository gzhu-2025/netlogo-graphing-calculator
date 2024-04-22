# Netlogo-Simulation

This program graphs a 7th degree function(septic function) and graphs its Taylor polynomial approximation. This program is written entirely in NetLogo and can be imported and run at NetLogo Web.  

Background - While learning calculus in school, the topic of Taylor series and Taylor approximations came up. I wanted to see a visualization of the way Taylor polynomials approximate functions about a certain x value(in this case 0). I wrote this program in NetLogo in order to create a model that could graph a function and the corresponding Taylor polynomial, while still being able to easily modify and change the specified function. 

Download - There are two code files in the [repository](https://github.com/gzhu-2025/netlogo-simulation). Either can be downloaded and imported into NetLogo Web or the NetLogo desktop app to run the model. 

Requirements - There are no extra requirements required to run the code, only access to internet and a browser that can run [NetLogo Web](https://www.netlogoweb.org). The code can also be run in the NetLogo desktop app, which can be found at NetLogo Web and has its own requirements for download and installation. Both NetLogo Web and the desktop app can modify and save the code on your device. 

Execution - Once the program is imported into your NetLogo of choice, the function can be specified with the sliders labeled constant, x1-coefficient, x2-coefficient, x3-coefficient... and so on. These represent the constant term and the coefficients of the powers of x in the septic function. The 'degree' slider changes the degree of the Taylor polynomial, which affects how closely it models the original function. The Taylor polynomial graph can either be graphed statically by pressing 'Setup' or graphed dynamically by pressing 'Go', which graphs the function and with its Taylor approximation with a gradually increasing degree, starting from the set degree and then ending and resetting once the degree reaches 7.

Troubleshooting - If importing the model does not work with one file type, try downloading and importing the other file type. If there is a compilation error, try redownloading the file from the repository or downloading the other file type. 

Authors - Geoffrey Zhu
