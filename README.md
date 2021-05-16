# WorkingTwitchAdBlockers

This repo/readme aims to provide a list and explanation of only working Twitch ad blockers. These ad blockers, will not interrupt the stream.

First of all, do not mix Twitch specific ad-blockers, doing this will cause issues. If using an extension, remove Twitch specfic userscripts if installed via TamperMonkey, UBlock Origin or other userscript managers. If you are unsure how to remove old UBlock Origin userscripts, reset UBlock Origin to factory settings or uninstall/reinstall UBlock Origin.

All of these extensions should be used with UBlock Origin or other major ad blockers, this will prevent overlay type ads also.

M3U8 Proxies:

Pros: Full quality ad-free streams.
Cons: Higher latency and chance of buffering due to streaming from countries such as Russia.

- `TTV.LOL` - [chrome](https://chrome.google.com/webstore/detail/ttv-lol/ofbbahodfeppoklmgjiokgfdgcndngjm) / [firefox](https://addons.mozilla.org/en-US/firefox/addon/ttv-lol/) / [code](https://github.com/TTV-LOL/extensions)

TTV.LOL:
Pros: Seems reliable with a large amount of traffic.
Cons: Passes Twitch userID with personal IP to their server. Although unlikely, this information could be linked together to get a users home address (If their IP address is linked to an address, such as business internet). Server code is not opensource.

- `Purple AdBlock` - [chrome](https://chrome.google.com/webstore/detail/purple-adblock/lkgcfobnmghhbhgekffaadadhmeoindg) / [firefox](https://addons.mozilla.org/en-US/firefox/addon/purpleadblock/) / [code](https://github.com/arthurbolsoni/Purple-adblock/)

Purple AdBlock:
Pros: Passes no personal information to their server except IP. Server code is opensource.
Cons: Their proxy can sometimes struggle with current traffic requirements.


Local Code:

- `Video Ad-Block for Twitch` - [chrome](https://chrome.google.com/webstore/detail/video-ad-block-for-twitch/kgeglempfkhalebjlogemlmeakondflc) / [firefox](https://addons.mozilla.org/en-US/firefox/addon/video-ad-block-for-twitch/) / [code](https://github.com/saucettv/VideoAdBlockForTwitch)

Video Ad-Block for Twitch:
Pros: Fully opensource code. Runs locally, no proxies, VPN's or third party websites.
Cons: Ads are blocked by switching the stream to an ad-free version that can be between 1080p and 480p, however quality is returned to source quality upon ads ending.
