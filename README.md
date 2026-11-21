# idle-powerwash-board
Global Top Washers list for the Idle Powerwash VRChat world.

`top.txt` is copied from the world's Supabase function every 10 minutes by `.github/workflows/mirror-top.yml`, and
GitHub Pages serves it at https://silentstudioshq.github.io/idle-powerwash-board/top.txt, an address VRChat trusts.

Format: first line `ipw1 TAB total TAB total with a Grand Reopening TAB unix time`, then one washer a line:
`name TAB Shine earned TAB XP TAB Washer Rank TAB items found TAB shiny finds TAB Reopening stars`.
