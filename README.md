# Responsive Dashboard

## Description
Web responsive dashboard developed with html, css, bootstrapp and javascript libraries dc, gridstack and dc.leaflet.

The dashboard is web responsive wich means it can render on mobile and desktop screens on a web browser. It offers a great experience trought interactive and fast responsive charts. It consists on different interactive charts including an interactive map, in wich you can click in any of the items to filter the dashboard, as well you can select and filter by toggling the menu items in blue.

For checking it out the live dashboard please click <a target='_blank' target="_blank" href='https://adrianrodriguez-io.github.io/responsive-dashboard/'>here</a>.

## Challengues

### FIrst challengue
While developing this project for getting a web responsive dashboard I started by searching javascript libraries wich allow to develop interactive graphs. After investigating and searching on the web
I found dc and crossfilter javascript libraries wich in combination allow to create data visualization of connected charts that offers a great experience trought interactive and responsive charts.

### Second challengue
The second challengue was to find a way of doing the set of charts responsive, this is, I wanted the charts to render and change the size according to mobile or desktop screens. After investigating 
I found gridstack javascript library wich allow to create different widgets that adjust the size and layout depending on the screen device. 

### Third challengue
I was very interested on ploting a map, so i found dc.leaflet wich is a javascript library in combination with dc js that works as another dc chart. The challengue is
to find a geojson to use in the map. I managed to find xml files with coordinates for the given data used, wich I parsed into a geojson having to develop a PHP script wich converted the xml into a json.

Links:
Dc.js Dimensional chart library <a href='https://dc-js.github.io/dc.js/'>https://dc-js.github.io/dc.js/</a>
<br>
Gridstack.js web <a href='https://gridstackjs.com/'>https://gridstackjs.com/</a>

### Next step
A step further is to place the crossfilter engine in a nodejs app so it is not needed to filter the raw data in the client. The node js app works on the server side offering a REST service. A crossfilter engine in the server side can filter and aggreate the results and send the response to the client. For this purpose the configuration of the dc charts would be different as shared in this repository. 

Note: 2022-09-28. This is something I have already done but not sure if it does make sense to create a new one with the nodejs app, because in github it is not possible to allocate nodejs apps so it would be needed to place the a node js app in another provider. Currently different existing providers offer a free service of this kind, from November 2022 Heroku wich is the provider I used the most for allocating node js apps will not be free anymore. Another free nodejs app service doesnt offer inmediate response less than 30s while in iddle status. So in my opinion an example of that wouldnt be very useful for its purpose, or at least I can create the repository and you can clone the project and adjust the parameters and test in your local machine. Just ping me if you want me to create a responsive-node-dashboard repository. 

## Dashboard developed

Here you can find a screenshoot of the dashboard developed. For checking it out the live dashboard please click <a target='_blank' href='https://adrianrodriguez-io.github.io/responsive-dashboard/'>here</a>.

<img src='https://github.com/adrianrodriguez-io/responsive-dashboard/blob/main/images/dashboard%20screenshoot.png'></img>
