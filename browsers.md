# Web Browsers - Your portal to the internet.

I've yet to figure out how to make Chrome telemetry free.

I have not yet had a chance to play around with Safari or other Apple browsers, but Apple is generally much more privacy friendly than Google.

Startpage offers their Chromium-based browser, which is allegedly tracker free.

Alternatively, if you use Firefox, you can enter "about:config" in the toolbar, accept the warning, and change the settings below in order to shut off telemetry and other triangulation-friendly services.

TOR is built on the Firefox browser, and has the same permissions. TOR is centered around the concept of making all users appear identical, however it is also much slower.

There is an automatic way to do this on desktop computers, using a user.js file. We'll include that momentarily.

Until then, here's the list of advanced settings. If a setting doesn't exist on your platform, that's fine too. You don't need to add it manually unless you're paranoid (we won't judge):

# Firefox addons

Noscript: This one can prevent Cross-Site Scripting (XSS) attacks by simply blocking the javascript from unnecessary domains. The downside is that you need to whitelist every page you visit.

Ublock Origin: This addon blocks ads that load in-page, which can also be common ways for bad actors to acquire your IP Address.

# Firefox about:config policies

"" is a blank string, it means to delete the line and then leave it empty

-------------------------------------------------------

beacon.enabled: false

browser.casting.enabled: false

browser.contentanalysis.enabled: false

browser.discovery.enabled: false

browser.ml.modelHubRootUrl: ""

browser.newtabpage.activity-stream.enabled: false

browser.newtabpage.activity-stream.telemetry: false

browser.newtabpage.activity-stream.feeds.telemetry: false

browser.newtabpage.activity-stream.telemetry.ut.events: false

browser.newtabpage.activity-stream.feeds.recommendationprovider: false

browser.newtabpage.activity-stream.discoverystream.merino-provider.endpoint: ""

browser.newtabpage.activity-stream.telemetry.structuredIngestion.endpoint: ""

browser.newtabpage.activity-stream.showWeather: false

browser.newtabpage.activity-stream.system.showWeather: false

browser.newtabpage.activity-stream.weather.locationSearchEnabled: false

browser.partnerlink.attributionURL: ""

browser.pagethumbnails.capturing_disabled: false

browser.search.serpEventTelemetry.enabled: false

browser.region.network.url: ""

browser.search.geoip.url: ""

browser.shell.checkDefaultBrowser: false

browser.shopping.experience2023.ads.enabled: false

browser.shopping.experience2023.ads.exposure: false

browser.shopping.experience2023.ads.userEnabled: false

browser.tabs.crashReporting.sendReport: false

browser.topsites.contile.enabled: false

browser.topsites.contile.endpoint: ""

browser.urlbar.autocomplete.enabled: false

browser.urlbar.contextualSearch.enabled: false

browser.urlbar.merino.endpointURL: ""

browser.urlbar.pocket.featureGate: false

browser.urlbar.quicksuggest.allowPositionInSuggestions: false

browser.urlbar.quicksuggest.dataCollection.enabled: false

browser.urlbar.speculativeConnect.enabled: false

browser.urlbar.suggest.pocket: false

browser.urlbar.suggest.quicksuggest.sponsored: false

browser.urlbar.suggest.remotetab: false

browser.urlbar.suggest.topsites: false

browser.urlbar.suggest.trending: false

browser.urlbar.suggest.weather: false

browser.urlbar.suggest.yelp: false

browser.urlbar.weather.ignoreVPN: false

browser.urlbar.yelp.featureGate: false

camera.control.face_detection.enabled: false

clipboard.autocopy: false

datareporting.healthreport.service.enabled: false

device.sensors.enabled: false

device.sensors.ambientLight.enabled: false

device.sensors.motion.enabled: false

device.sensors.orientation.enabled: false

device.sensors.proximity.enabled: false

devtools.browserconsole.enableNetworkMonitoring: false

dom.network.enabled: false

dom.reporting.enabled: false

dom.reporting.featurePolicy.enabled: false

dom.reporting.testing.enabled: false

dom.telephony.enabled: false

dom.text-recognition.enabled: false

experiments.enabled: false

geo.enabled: false

geo.provider.ms-windows-location: false

geo.provider.network.url: ""

geo.provider.use_geoclue: false

geo.provider.use_gpsd: false

geo.wifi.logging.enabled: false

geo.wifi.uri: ""

identity.fxaccounts.toolbar.pxiToolbarEnabled.monitorEnabled: false

identity.mobilepromo.android: ""

keyword.enabled: false

media.aboutwebrtc.auto_refresh.peerconnection_section: false

media.aboutwebrtc.auto_refresh.user_modified_config_section: false

media.devices.enumerate.legacy.enabled: false

media.getusermedia.screensharing.enabled: false

media.gmp-manager.allowLocalSources: false

media.gmp-provider.enabled: false

media.navigator.enabled: false

media.navigator.permission.disabled: true

media.peerconnection.allow_old_setParameters: false

media.peerconnection.enabled: false

media.peerconnection.ice.no_host: true

media.peerconnection.ice.stun_client_maximum_transmits: 0

media.peerconnection.mtransport_process: false

media.peerconnection.scripttransform.enabled: false

media.peerconnection.turn.disable: true

media.peerconnection.video.use_rtx: false

media.webrtc.capture.allow-pipewire: false

media.webspeech.recognition.enable: false

messaging-system.rsexperimentloader.enabled: false

media.video_stats.enabled: false

network.allow-experiments: false

network.http.referer.spoofSource: true

network.predictor.enabled: false

network.prefetch-next: false

network.proxy.enable_wpad_over_dhcp: false

network.proxy.system_wpad: false

network.proxy.system_wpad.allowed: false

network.traffic_analyzer.enabled: false

network.trr.confirmation_telemetry_enabled: false

pdfjs.enableScripting: false

places.history.enabled: false

privacy.donottrackheader.enabled: true

privacy.fingerprintingProtection: true

security.certerrors.recordEventTelemetry: false

security.protectionspopup.recordEventTelemetry: false

security.ssl.errorReporting.automatic: false

services.sync.prefs.sync.browser.discovery.enabled: false

services.sync.prefs.sync.browser.newtabpage.activity-stream.section.highlights.includePocket: false

services.sync.prefs.sync.browser.newtabpage.activity-stream.showSponsored: false

services.sync.prefs.sync.browser.newtabpage.activity-stream.showSponsoredTopSites: false

services.sync.prefs.sync.privacy.donottrackheader.enabled: true

toolkit.telemetry.bhrPing.enabled: false

toolkit.telemetry.cachedClientID: ""

toolkit.telemetry.cachedProfileGroupID: ""

toolkit.telemetry.dap_helper: ""

toolkit.telemetry.dap_leader: ""

toolkit.telemetry.enabled: false

toolkit.telemetry.archive.enabled: false

toolkit.telemetry.rejected: true

toolkit.telemetry.server: ""

toolkit.telemetry.unified: false

toolkit.telemetry.unifiedIsOptIn: false

toolkit.telemetry.updatePing.enabled: false

# Full paranoia mode:
browser.safebrowsing.enabled: false

media.getusermedia.audiocapture.enabled: false

media.gmp-gmpopenh264.enabled: false

webgl.disabled: true
