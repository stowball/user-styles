Site: kickstarter.com

```
#content-wrap video:first-of-type::-webkit-media-controls {
    display: revert !important;
}

#content-wrap video:first-of-type::-webkit-media-controls-panel {
    display: revert !important;
    -webkit-appearance: revert !important;
}

#content-wrap video:first-of-type + div > .h7.w100p.max-w200.bg-black.flex.items-center.transition-all.relative.z2,
.player_controls.absolute-bottom.mb3.radius2px.white.bg-green-dark.forces-video-controls_hide {
    background: transparent !important;
    height: 3rem !important;
    opacity: 0.5 !important;
    transition: none !important;
    width: 3rem !important;
}

#content-wrap video:first-of-type + div > .h7.w100p.max-w200.bg-black.flex.items-center.transition-all.relative.z2 :not(:first-child),
.player_controls.absolute-bottom.mb3.radius2px.white.bg-green-dark.forces-video-controls_hide .time,
.player_controls.absolute-bottom.mb3.radius2px.white.bg-green-dark.forces-video-controls_hide .right,
.player_controls.absolute-bottom.mb3.radius2px.white.bg-green-dark.forces-video-controls_hide .progress_container {
    display: none;
}

#content-wrap video:first-of-type + div > button {
    display: none;
}

.hide-rewards-sidebar {
    display: block !important;
}

.w100p.h60.mb8 {
    height: auto !important;
    margin-bottom: 18px;
}

.project-card-root {
    position: relative !important;
}

.expandable-background {
    inset: 0;
    zbox-shadow: 0px 6px 16px 0px rgba(0,0,0,0.12);
    border: 1px solid #e0e0e0;
    opacity: 1;
}

.project-card-root__extra-info-container {
    max-height: 9999px;
    opacity: 1;
    pointer-events: all;
    transform: translateY(0);
    transition-delay: 0s;
    visibility: visible;
}

.load_more {
    position: relative;
    z-index: 10;
}

textarea {
    resize: both;
}

.kds-chip[href*="/games/tabletop"] { 
    background: #FFFF8F;
}


.kds-chip[href*="/games/playing"] { 
    background: #FFF4E7;
}
```
