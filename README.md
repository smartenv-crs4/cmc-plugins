# cmc-plugins
This is the repository of all the plugins supported by CMC microservices

## Usage

### Install

1) All plugins are grouped by service, so look for the microservice 
you want to enrich with some extra features
2) Inside each plugin folder, you will find a file called <code>extend.js</code>. 
Simply copy it inside the <code>plugin</code> folder of the service
3) If your service has already one or more plugins installed, 
<code>extend.js</code> will be already there. 
You need to add to the <code>plugin</code> array only the array element containing the code of the new plugin
4) Restart your service and enjoy the plugin!