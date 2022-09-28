# Responsive Dashboard

## Description
Web responsive dashboard developed with html, css, bootstrapp and javascript libraries dc, gridstack and dc.leaflet. It renders accordingly to mobile or desktop screens. 

The dashboard is web responsive wich means it can render on mobile and desktop screens on a web browser. It offers a great experience trought interactive and fast responsive charts. It consists on different interactive charts including an interactive map, in wich you can click in any of the items to filter the dashboard, as well you can select and filter by toggling the menu items in blue.

For checking it out the live dashboard please click <a target='_blank' target='_blank' href='https://adrianrodriguez-io.github.io/responsive-dashboard/'>here</a>.

## Challengues

While developing this project for getting a web responsive dashboard I started by searching javascript libraries wich allow to develop interactive graphs. After investigating and searching on the web
I found dc and crossfilter javascript libraries wich in combination allow to create data visualization of connected charts that offers a great experience trought interactive and responsive charts.

The second challengue was to find a way of doing the set of charts responsive, this is, I wanted the charts to render and change the size according to mobile or desktop screens. After investigating 
I found gridstack javascript library wich allow to create different widgets that adjust the size and layout depending on the screen device. 

I was very interested on ploting a map, so i found dc.leaflet wich is a javascript library in combination with dc js that works as another dc chart. The challengue is
to find a geojson to use in the map. I managed to find xml files with coordinates for the given data used, wich I parsed into a geojson having to develop a PHP script wich converted the xml into a json.

Links:
Dc.js Dimensional chart library <a href='https://dc-js.github.io/dc.js/'>https://dc-js.github.io/dc.js/</a>
<br>
Gridstack.js web <a href='https://gridstackjs.com/'>https://gridstackjs.com/</a>

A step further is to place the crossfilter engine on a nodejs app so it is not needed to filter the raw data in the client. 

## Dashboard developed

Here you can find a screenshoot of the dashboard developed. For checking it out the live dashboard please click <a target='_blank' href='https://adrianrodriguez-io.github.io/responsive-dashboard/'>here</a>.

<img src='https://github.com/adrianrodriguez-io/responsive-dashboard/blob/main/images/dashboard%20screenshoot.png'></img>
