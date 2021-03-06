This site fetches github statistics to rank cryptocoins by developer activity.

Because I wish people paid more attention to altcoin fundementals, like how much work the developers are doing. 

One disclaimer, these stats should just be a broad guide to which coin is developing or not. As reddit user u/Alonski said:  "I'm not sure open issues is a very valid indication of success if people don't understand it. Some projects use issues as task management and not just bug tracking. Other than that this looks really cool"

Any problems, feel free to submit a PR.

### to update the list navigate to yourdomain.com/fetch and use the list generated there in the data/example_data.js file

The [live site is here](https://wassname.github.io/compare_altcoin_development/src/) but there's a snapshot below.

# Snapshot 2017-11-29

| coin           | commits per week | watchers | open issues | created    | updated    | contributor |
|---|---|---|---|---|---|---|
|Cardano|203|477|47|2016-10-14|2017-11-29|45|
|Lisk|173|1861|342|2017-05-08|2017-11-27|580|
|Augur|165|824|32|2016-05-27|2017-11-20|134|
|LBRY Credits|118|4065|355|2017-03-28|2017-11-26|629|
|Storj|109|1248|344|2017-06-21|2017-11-28|224|
|Steem|96|1258|678|2017-06-10|2017-11-27|141|
|Monero|90|2231|502|2014-08-31|2017-11-11|370|
|Ethereum Classic|85|560|239|2017-06-07|2017-11-22|253|
|Waves|75|485|75|2016-04-29|2017-10-02|50|
|Ethereum|73|36658|4241|2016-08-08|2017-11-03|1884|
|Status|73|2201|785|2017-10-19|2017-11-27|779|
|Iota|72|1653|618|2017-08-16|2017-11-29|162|
|Bitcoin|66|21425|811|2014-08-26|2017-11-13|559|
|Maidsafe|50|1624|182|2017-01-04|2017-11-27|323|
|Factom|50|419|23|2016-03-26|2017-10-24|110|
|BitcoinGold|50|403|55|2017-07-23|2017-11-28|394|
|Stratis|50|453|117|2017-07-13|2017-11-03|351|
|Litecoin|49|2239|50|2016-11-06|2017-11-28|1186|
|EOS|46|2212|143|2017-08-16|2017-11-01|74|
|Sia|45|2126|229|2017-02-21|2017-11-16|58|
|Golem|44|1864|330|2017-04-12|2017-10-29|48|
|Gnosis|37|226|49|2017-10-09|2017-11-24|33|
|Qtum|37|397|6|2017-03-03|2017-11-29|392|
|Bitshares|32|1021|429|2017-01-19|2017-11-14|334|
|Stellar Lumens|29|1922|610|2017-02-21|2017-11-18|362|
|Dash|28|885|175|2017-02-04|2017-11-26|601|
|Vertcoin|23|321|23|2017-09-22|2017-11-19|763|
|PIVX|17|147|61|2016-01-30|2017-11-28|293|
|ZCash|16|3208|761|2016-11-12|2017-11-16|388|
|BitcoinUnlimited|14|273|69|2016-09-06|2017-11-22|383|
|Ripple|13|4033|260|2016-03-09|2017-11-29|361|
|NEM|13|361|350|2016-10-29|2017-11-28|54|
|OmiseGO|11|400|49|2016-12-01|2017-11-23|99|
|NEO|9|1623|93|2017-08-23|2017-11-27|125|
|Syscoin|8|96|164|2017-05-09|2017-11-22|347|
|VCash|5|65|25|2016-12-02|2017-11-20|10|
|BitcoinCash|4|17|4|2017-09-17|2017-11-20|15|
|Blocknet|3|34|0|2014-10-21|2017-11-08|6|
|DigixDAO|2|309|28|2017-02-06|2017-09-03|14|
|Bitcoinclassic|0|510|25|2016-09-20|2017-11-21|371|
|Qora|0|35|21|2015-03-15|2017-08-26|6|
|Dogecoin|0|1463|94|2015-04-11|2017-11-10|359|
|Nxt|0|2|1|2017-07-29T15:28:59+00:00|2017-11-18T09:32:31+00:00||
|Burstcoin|0|60|13|2014-08-13|2017-10-08|3|
|Ardor|0|5|1|2017-04-02T10:08:50+00:00|2017-08-24T12:00:55+00:00||


# Screenshot

![](docs/img/2017-24-11-29-17_Selection_001.png)

TODO:

- [x] bitbucket
- [x] github organisations
- [x] progbar
- [x] user input
- [ ] detect data from forks?
- [ ] finer stats, e.g. total contributions, change in lines of code etc
