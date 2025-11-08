Site: youtube.com

```
/* ==UserStyle==
@name           youtube.com
@namespace      github.com/openstyles/stylus
@version        1.0.0
@description    A new userstyle
@author         Me
==/UserStyle== */
@-moz-document url-prefix("https://www.youtube.com/watch") {
    .ytp-panel {
        overscroll-behavior: none;
    }

    .ytp-miniplayer-button,
    .ytp-settings-menu .ytp-menuitem-with-footer {
        display: none !important;
    }

    .ytp-remote-button {
        display: inline-block !important;
    }

    .html5-video-player.ad-showing:has(> .video-ads) video,
    .ytp-ad-player-overlay-flyout-cta/*, #player-ads*/
    {
        display: none !important;
    }

    yt-playability-error-supported-renderers,
    ytd-enforcement-message-view-model[in-player] {
        display: none !important;
    }

    ytd-watch-flexy[player-unavailable] #player-container-outer.ytd-watch-flexy {
        visibility: visible;
    }

    #player-ads {
        height: 0 !important;
        overflow: hidden !important;
    }

    .ytp-hide-controls .ytp-chrome-bottom {
        display: block !important;
    }
}
```
