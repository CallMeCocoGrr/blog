---
layout: page
title: Game Portfolio

---

## Featured Games

<script>
function loadGame(containerId, gameId) {
    const button = document.getElementById('button-' + containerId);
    const frame = document.getElementById(containerId);
    button.style.display = 'none';
    frame.src = `https://itch.io/embed-upload/${gameId}?color=000000`;
    frame.style.display = 'block';
}
</script>

### [Sanctum]
<div class="game-container">
    <button id="button-sanctum" class="load-button" onclick="loadGame('sanctum', '13665764')">Run Game</button>
    <iframe id="sanctum" class="game-frame" frameborder="0" 
            allowfullscreen="">
        <a href="https://trev3lyan.itch.io/sanctum">Play Sanctum on itch.io</a>
    </iframe>
</div>

> The cathedral was built on your sacred ground, its stones laid over ancient altars, its hymns drowning out the old rites. 
>
> Writhing inside are only, divine parasites that twisted the very air.
>
> Now the Last Penitent comes, a blind zealot armed with the very corruption they call faith. Let them try to stop you from reclaiming your land. 
>
> Their god is just another beast to slay.

---

### [Breach Zero]
<div class="game-container">
    <button id="button-breachzero" class="load-button" onclick="loadGame('breachzero', '12810672')">Run Game</button>
    <iframe id="breachzero" class="game-frame" frameborder="0" 
            allowfullscreen="">
        <a href="https://finbox-entertainment.itch.io/breach-zero">Play Breach Zero on itch.io</a>
    </iframe>
</div>

> You wake up in a top secret underground bio weapon laboratory, the alarm is blaring.
>
> There is blood and death everywhere, and the experiment containment tubes are shattered!
>
> Time is ticking relentlessly and the fate of the world might depend on you as you discover the dark secret lurking inside.

---