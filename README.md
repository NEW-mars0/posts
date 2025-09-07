{
  "catwebConfig": {
    "admin": {
      "username": "admin",
      "permissions": {
        "canPost": true,
        "canDelete": true,
        "canFeature": true,
        "canBanUsers": true
      },
      "accessLevel": "full"
    },
    "uiTheme": {
      "themeName": "Catweb Neon",
      "colors": {
        "primary": "#FF69B4",
        "secondary": "#00FFFF",
        "background": "#1A1A1A",
        "text": "#FFFFFF"
      },
      "fonts": {
        "header": "Orbitron",
        "body": "Inter"
      },
      "animations": {
        "buttonHover": "pulse",
        "popupOpen": "fadeInUp"
      }
    },
    "featureFlags": {
      "enableArcadeHub": true,
      "enableEmojiReactions": true,
      "enablePopupPostCreation": true,
      "enableFloatingButtons": true
    },
    "posts": [
      {
        "id": "001",
        "author": "admin",
        "visibility": "public",
        "title": "Catweb Arcade Launches!",
        "body": "Pixel Pounce and Whisker Dash are now live. Tap the floating button to play.",
        "media": ["arcade-banner.png"],
        "reactionsEnabled": true,
        "commentsEnabled": false,
        "timestamp": "2025-09-06T20:00:00Z"
      }
    ],
    "archetypes": [
      {
        "id": "pixel-nomad",
        "title": "Pixel Nomad",
        "description": "Wanders through digital cities, leaving trails of neon and curiosity.",
        "badge": "🌐",
        "style": {
          "background": "gradient-neon",
          "textColor": "#ffffff"
        }
      }
    ],
    "addressGenerator": {
      "theme": "Tokyo-inspired",
      "locked": true,
      "output": "Whisker Way, Echo District, TK-01"
    },
    "arcadeHub": {
      "entryPoint": "floatingButton",
      "style": "retroTiles",
      "games": [
        {
          "title": "Whisker Dash",
          "launch": "adminOnly",
          "icon": "🐾"
        },
        {
          "title": "Pixel Pounce",
          "launch": "adminOnly",
          "icon": "🎮"
        }
      ]
    }
  }
}
