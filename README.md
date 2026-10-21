# Brilliant Chess — public pages

Home, privacy policy and account-deletion pages, served by GitHub Pages so they stay up when the game
server is down. The game server serves the same two legal pages at `/chess/api/legal/*`
(`Chess-backend/src/main/resources/static/`): change both copies together. The deletion form posts to the
game server (`API` in `delete-account.html`) — update it when the server URL changes.
