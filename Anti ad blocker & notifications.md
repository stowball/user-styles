```
/* ==UserStyle==
@name           Anti ad blocker & notifications
@namespace      github.com/openstyles/stylus
@version        1.0.0
@description    Removes as many anti-ad blocker, ads and notification nag dialogs as possible, and tries to prevent sites that have explicitly disabled scrolling 
@author         Matt Stow
==/UserStyle== */
```

```
metering-modal,
.fc-ab-root.fc-ab-root.fc-ab-root,
[class*="sp_veil"][class*="sp_veil"][class*="sp_veil"],
[class*="sp_message_container"][class*="sp_message_container"][class*="sp_message_container"],
[id*="__vliadb"][id*="__vliadb"][id*="__vliadb"],
.ml-webforms-popup-overlay,
webpushrpromptconatiner,
[class*="popupally"],
#onesignal-slidedown-container,
.pushowl-optin,
.martech-modal-component-overlay,
body.mol-fe-ab-dialog iframe ~ * [class*="overlay-"],
body.mol-fe-ab-dialog iframe ~ * [class*="wrapper-"],
.airship-html-prompt-shadow,
[class*="pe-optin"],
.tp-modal,
.tp-backdrop,
[style*="z-index: 21474"]:not([data-radix-portal]):not([id*="eventbrite-widget-modal-"]),
.single-article .overlay,
.blocking-ads-modal,
#_evidon-barrier-wrapper,
.gu-overlay,
#onetrust-consent-sdk,
.pushly_popover,
.ua-opt-in,
.wp-optin-dialog-container,
[class*="pushcrew-"],
[class*="_hj_survey_"],
[class*="Playground__InnerBackdrop"],
[class*="Playground__InnerDialog"],
.grow_modal.grow_modal,
iframe[src*="btloader.com"],
[id*="google_ads_iframe"],
[class*="frontend-components-SubscribePrompt-module__subscribeDialog"],
[class*="frontend-components-SubscribePrompt-module__background"],
[class*="pushengage-opt-in"],
ytd-engagement-panel-section-list-renderer:not([shorts-panel]),
.html5-video-player.ad-showing:has(> .video-ads) video,
.ytp-ad-player-overlay-flyout-cta,
.cc-banner,
div[class]:has(a[href*="getadmiral"]),
div[class]:has(img[src*="getadmiral.com"]),
[data-google-query-id]:has(iframe),
[data-google-query-id][style]:has(iframe),
.mol-controls-overlay-panel,
amp-consent.i-amphtml-consent-ui-iframe-active.i-amphtml-consent-ui-in,
.i-amphtml-consent-ui-mask,
#bt-softwall,
ytd-in-feed-ad-layout-renderer,
.pencraft, .pencraft + [style],
.dailymotion-player-root,
.hu-iframe-overlay,
.zephr-ad-block-detected-backdrop,
.fuse-ad,
.adblock,
[data-name="exitInterstitial"],
div[id][style]:has(> div[data-report*="Report Ad"]),
[id*="push-notification-subscription" i], 
[id*="ad" i]:not([class*="braintree"], [class*="admin"], [class*="sqs-layout"], [data-qa-block="true"], [id*="#"], [id*=":"], [id*="_ad"], [id*="aD"], [id*="-ad"], [id*="ad0" i], [id*="ad1" i], [id*="ad2" i], [id*="ad3" i], [id*="ad4" i], [id*="ad5" i], [id*="ad6" i], [id*="ad7" i], [id*="ad8" i], [id*="ad9" i], [id*="add" i], [id*="ade" i], [id*="adjust" i], [id*="admin" i], [id*="admincontainer" i], [id*="adobe-analytics" i], [id*="adv" i], [id*="badg" i], [id*="cad" i], [id*="collapsing-side-bar"], [id*="diff-" i], [id*="ead" i], [id*="grad" i], [id*="keypad"], [id*="metadata" i], [id*="oad" i], [id*="QuestionId_" i], [id*="rad" i], [id*="row-" i], [id*="shadow" i], [id*="adult" i], [id*="widget" i], [name="codepen" i], .pluginRoot, .question):is(div, iframe, span) {
    display: none !important;
}

.sp-message-open.sp-message-open.sp-message-open {
    margin-top: 0 !important;
    overflow: auto !important;
    position: static !important;
}

html[style*="overflow: hidden"],
html[style*="overflow-y: hidden"],
body[style*="overflow: hidden"]:not([jstcache]),
body[style*="overflow-y: hidden"],
.martech-overlay-not-visible,
body.mol-fe-ab-dialog,
.tp-modal-open,
body.noscroll,
#i-amphtml-wrapper.i-amphtml-scroll-disabled,
.i-amphtml-scroll-disabled,
.bt-sw-overflow,
html.force--consent.show--consent,
html.zephr-modal-open
{
    height: auto !important;
    overflow-y: auto !important;
}

div[data-adunit-name], iframe[src*="https://ads."] {
    opacity: 0 !important;
}


body:has(.adblock:open) {
    overflow: auto
}
```
