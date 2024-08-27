# rcmuthaconfigserver
<br>
Dependency : 
<br>
https://github.com/Roshanmutha/rcmutha-configclient <br>
https://github.com/Roshanmutha/rcmuthaconfigserver <br>
https://github.com/Roshanmutha/Configuration <br>


hit : http://localhost:8888/a-bootiful-client/default

Returns on config server. 
 { 
 "name": "a-bootiful-client",
  "profiles": [
    "default"
  ],
  "label": null,
  "version": "4ec5084564e38aea1fedf9d705bb090f6e466fd5",
  "state": null,
  "propertySources": [
    {
      "name": "https://github.com/Roshanmutha/Configuration/a-bootiful-client.properties",
      "source": {
        "message": "Hello world",
        "auther.name": "Roshankumar Mutha",
        "auther.country": "India"
      }
    }
  ]
}
