# SKAdNetworks

This site was created by Fyber Marketplace in order to support our Fairbid and Marketplace publishers in adopting Apple's new SKAdNetwork specification for programmatic ad buying. To participate in install validation for [Apple's SKAdNetwork](https://developer.apple.com/documentation/storekit/skadnetwork/configuring_the_participating_apps) the source app must include the ad network’s ID in its Info.plist.

Programmatic ad buying uses the following framework for SKAdNetwork:
* Fyber's publishers are source apps
* Fyber's Demand Partners register and receive ad network IDs from Apple. Each Demand Partner running app install validation on Fyber Marketplace will have at least one SKAdNetwork ad network ID

Fyber's recommended list of SKAdNetwork ad network IDs can be found [here](https://fyber-engineering.github.io/SKAdNetworks/). Feel free to either clone or fork this repository. Alternatively, you directly download or CURL the JSON file containing the mentoined data.  

Please do not create pull requests into this project as they will be ignored. The data will be updated periodically by Fyber's engineering team. 
