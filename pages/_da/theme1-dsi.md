---
banner: /assets/images/dsi-theme.png
title: Nintendo DSi-tema
---

<div id="button-controls" class="section-title">Knapfunktioner</div>
<div class="section-body">
    <div class="button-action-group">
        <p class="button-action button">&#xE079;</p>
        <p class="button-action-text">Flyt punkt<br>(Sorteringsmetoden skal være sat til "tilpasset")</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action button">&#xE07E;</p>
        <p class="button-action-text">Forrige/næste punkt</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action"><span class="button">&#xE000; /</span> START</p>
        <p class="button-action-text">Start det valgte program</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action button">&#xE001;</p>
        <p class="button-action-text">Gå et mappeniveau op</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action button">&#xE002;</p>
        <p class="button-action-text">Slet/skjul punkt</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action button">&#xE003;</p>
        <p class="button-action-text">Åbn indstillinger for spillet</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action">SELECT</p>
        <p class="button-action-text">Åbn SELECT-menuen eller den klassiske DS-menu</p>
    </div>
</div>

<div id="touch-controls" class="section-title">Touch-funktioner</div>
<div class="section-body">
    <div class="button-action-group">
        <p class="button-action"><img src="/assets/images/left-right.png"></p>
        <p class="button-action-text">Rul gennem listen</p>
    </div>
    <hr>
    <div class="button-action-group">
        <p class="button-action"><img src="/assets/images/tap.png"></p>
        <p class="button-action-text">Start det valgte program</p>
    </div>
    <!-- <hr>
    <div>
        <p>
            If the Sort Method is set to "Custom", you can drag the icon up to move it.
        </p>
    </div> -->
</div>

<div id="page-system" class="section-title">Sidesystemet</div>
<div class="section-body">
    <p>
        Nintendo DSI-temaet opdeler elementer i sider med højst 40 elementer pr. side. Du kan navigere gennem siderne ved at trykke på &#xE004;- og &#xE005;-knapperne.
    </p>
    <ul>
        <li><p>Hvis du trykker på &#xE004; på den første side, vil det første punkt på siden blive markeret</p></li>
        <li><p>Hvis du trykker på &#xE005; på den sidste side, vil det sidste punkt på siden blive markeret</p></li>
    </ul>
    <p>
        Rullebjælken nederst viser alle punkter på en side, du kan trykke på den for hurtigt at flytte til et bestemt punkt på siden.
    </p>
    <p>
        Hvis dine skulderknapper ikke virker, kan du i stedet trykke SELECT +&#xE07E;.
    </p>
</div>

<div id="custom-top-screen-image" class="section-title">Tilpasset billede på øverste skærm</div>
<div class="section-body">
    <div style="text-align: center;"><img style="border-color: black; border-width: 1px; border-style: dashed;" src="https://raw.githubusercontent.com/DS-Homebrew/TWiLightMenu/master/romsel_dsimenutheme/nitrofiles/languages/{{ page.collection }}/photo_default.png"></div>
    <p>TWiLight Menu++ understøtter visning af dine egne billeder på den øverste skærm, ligesom den officielle Nintendo DSi-menu. Dog i stedet for at hente dem fra programmet Nintendo DSi-kamera, vil ethvert PNG-billede placeret i <code class="language-plaintext wrap">sd:/_nds/TWiLightMenu/dsimenu/photos</code> blive brugt</p>
    <ul>
        <li>Maksimal bredde: 200 pixels</li>
        <li>Maksimal højde: 156 pixels</li>
    </ul>
    <p>Hvis billedets størrelse er mindre end det maksimale, vil det blive centreret med sorte rammer.</p>
</div>

<div id="select-menu" class="section-title">SELECT-menuen</div>
<div class="section-body">
    <p>
        Ved at trykke SELECT i Nintendo DSi-temaet vil den klassiske DS-menu blive vist som standard. Men i TWiLight Menu++-indstillingerne kan du ændre det til i stedet at starte SELECT-menuen, en miniaturemenu indbygget i temaet selv. Her er mulighederne i SELECT-menuen.
    </p>
    <ul>
        <li><strong>HOME-menu:</strong> På Nintendo DSi- og 3DS-konsoller vil et punkt til at gå tilbage til HOME-menuen blive vist</li>
        <li><strong>Indstillinger:</strong> Dette punkt starter en menu, der kan bruges til at ændre indstillingerne for TWiLight Menu++ og diverse spilstartere</li>
        <li><strong>Kort-indstillinger:</strong> På en original DS eller DS lite kan du starte din Slot-2 enhed herfra. På en Nintendo DSi eller Nintendo 3DS med menuen kørende fra SD-kortet, kan du enten køre dit Slot-1 kort eller med visse flashcarts skifte hvilket SD-kort TWiLight Menu++ navigerer</li>
        <li><strong>Manual</strong>: Dette vil starte manualen til TWiLight Menu++, det er den du kigger på lige nu :P</li>
    </ul>
</div>
