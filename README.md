@import url("https://fonts.googleapis.com/css?family=Changa One");
@import url("https://fonts.googleapis.com/css?family=Imprima");

body {
  overflow: hidden;
  background-color: rgba(0,0,0,0);
}
yt-live-chat-renderer {
  background-color: transparent !important;
}
yt-live-chat-text-message-renderer,
yt-live-chat-text-message-renderer[is-highlighted],
yt-live-chat-text-message-renderer[author-type="owner"],
yt-live-chat-text-message-renderer[author-type="owner"][is-highlighted],
yt-live-chat-text-message-renderer[author-type="moderator"],
yt-live-chat-text-message-renderer[author-type="moderator"][is-highlighted],
yt-live-chat-text-message-renderer[author-type="member"],
yt-live-chat-text-message-renderer[author-type="member"][is-highlighted] {
  background-color: transparent !important;
}
yt-live-chat-author-chip #author-name {
  background-color: transparent !important;
}

yt-live-chat-renderer * {
  text-shadow: -2px -2px #000000,-2px -1px #000000,-2px 0px #000000,-2px 1px #000000,-2px 2px #000000,-1px -2px #000000,-1px -1px #000000,-1px 0px #000000,-1px 1px #000000,-1px 2px #000000,0px -2px #000000,0px -1px #000000,0px 0px #000000,0px 1px #000000,0px 2px #000000,1px -2px #000000,1px -1px #000000,1px 0px #000000,1px 1px #000000,1px 2px #000000,2px -2px #000000,2px -1px #000000,2px 0px #000000,2px 1px #000000,2px 2px #000000;
  font-family: "Imprima";
  font-size: 16px !important;
  line-height: normal !important;
}

yt-live-chat-text-message-renderer #content,
yt-live-chat-legacy-paid-message-renderer #content {
  overflow: initial !important;
}

yt-live-chat-item-list-renderer #items,
yt-live-chat-item-list-renderer #item-scroller {
  overflow: hidden !important;
}

yt-live-chat-header-renderer,
yt-live-chat-message-input-renderer,
yt-upsell-dialog-renderer,
yt-live-chat-restricted-participation-renderer,
yt-live-chat-signin-renderer,
#input-panel,
#action-panel,
yt-live-chat-renderer > div:last-child {
  display: none !important;
}

yt-live-chat-text-message-renderer #author-photo,
yt-live-chat-paid-message-renderer #author-photo,
yt-live-chat-legacy-paid-message-renderer #author-photo {
  display: none !important;
}

yt-live-chat-text-message-renderer #author-badges {
  display: none !important;
}
yt-live-chat-text-message-renderer #timestamp {
  display: none !important;
}

yt-live-chat-text-message-renderer #author-name[type="owner"],
yt-live-chat-text-message-renderer #author-name.owner,
yt-live-chat-text-message-renderer yt-live-chat-author-badge-renderer[type="owner"] {
  color: #ffd600 !important;
}
yt-live-chat-text-message-renderer #author-name[type="moderator"],
yt-live-chat-text-message-renderer #author-name.moderator,
yt-live-chat-text-message-renderer yt-live-chat-author-badge-renderer[type="moderator"] {
  color: #5e84f1 !important;
}
yt-live-chat-text-message-renderer #author-name[type="member"],
yt-live-chat-text-message-renderer #author-name.member,
yt-live-chat-text-message-renderer yt-live-chat-author-badge-renderer[type="member"] {
  color: #0f9d58 !important;
}

yt-live-chat-text-message-renderer #author-name {
  color: #cccccc !important;
  font-family: "Changa One";
  font-size: 16px !important;
  line-height: 12px !important;
}
yt-live-chat-text-message-renderer #author-name::after {
  content: ":";
  margin-left: 2px;
}

yt-live-chat-text-message-renderer #message,
yt-live-chat-text-message-renderer #message * {
  color: #ffffff !important;
  font-family: "Imprima";
  font-size: 16px !important;
  line-height: normal !important;
  letter-spacing: normal !important;
}

yt-live-chat-text-message-renderer {
  background-image: url('https://raw.githubusercontent.com/yuwutspxl-cloud/Jiro-Jirowr/main/BUBBLE%20CHAT.png') !important;
  background-repeat: no-repeat !important;
  background-size: 100% 100% !important;
  background-position: center !important;
  border: none !important;
  min-height: 120px !important;
  height: auto !important;
  margin: 2px 0 !important;
  padding: 40px 40px 20px 50px !important;
  box-sizing: border-box !important;
  border-radius: 0 !important;
}

yt-live-chat-moderation-message-renderer { display: none !important; }
yt-live-chat-paid-message-renderer { margin: 4px 0 !important; }
yt-live-chat-legacy-paid-message-renderer {
  background-color: #0f9d58 !important;
  margin: 4px 0 !important;
}

yt-live-chat-text-message-renderer a,
yt-live-chat-legacy-paid-message-renderer a { text-decoration: none !important; }

yt-live-chat-text-message-renderer[is-deleted],
yt-live-chat-legacy-paid-message-renderer[is-deleted] { display: none !important; }

yt-live-chat-ticker-renderer {
  background-color: transparent !important;
  box-shadow: none !important;
  display: none !important;
}

yt-live-chat-mode-change-message-renderer,
yt-live-chat-viewer-engagement-message-renderer,
yt-live-chat-restricted-participation-renderer { display: none !important; }

yt-live-chat-banner-manager { display: none !important; }

yt-live-chat-text-message-renderer,
yt-live-chat-legacy-paid-message-renderer {
  opacity: 1 !important;
  animation: none !important;
}

yt-live-chat-action-panel-renderer,
yt-live-chat-renderer #action-panel { display: none !important; }
yt-reaction-control-panel-overlay,
yt-reaction-control-panel-overlay-view-model,
yt-reaction-control-panel-view-model { display: none !important; }
yt-live-chat-viewer-engagement-message-renderer { display: none !important; }
