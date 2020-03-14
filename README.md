## README ##

### Names & SID: ###
Ruifeng Zhang 915275849
Zhongquan Chen 913875678

### Compliation and Execution steps ###

We use IntelliJ IDEA IDE for this project, hence we can simply setup "-deprecation" command line parameters in the settings. Press the green triangle button inside the IDE to run the proxy.

### Testing process(Windows 10) ###

1. Clear the browsing history of the browser.
2. Go to the Setting of Windows 10, then go to Network and Internet->Proxy->Manual proxy setup.
3. Enter "localhost" into the address field and a desired port number
4. Try to access the webpage: http://gaia.cs.umass.edu/, if you get the error, that means the brwoser is talking to the proxy.
5. Start the proxy with previously entered port number.
6. Try to access the webpage: http://gaia.cs.umass.edu/ again
7. The page now display correctly
8. Test completed