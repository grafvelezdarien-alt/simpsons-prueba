* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html,
body {
    width: 100%;
    height: 100%;
    overflow: hidden;
    font-family: Arial, Helvetica, sans-serif;
    background: #111;
}

#game-container {
    position: relative;
    width: 100vw;
    height: 100vh;
    overflow: hidden;
}

canvas {
    position: absolute;
    left: 0;
    top: 0;

    width: 100%;
    height: 100%;

    display: block;

    background: #6ca84a;
}

/* =========================
   HUD
========================= */

#hud {
    position: absolute;
    inset: 0;

    pointer-events: none;

    color: white;
    text-shadow:
        2px 2px 0 #000,
        -1px -1px 0 #000;
}

.hud-top {
    position: absolute;

    top: 20px;
    left: 20px;
    right: 20px;

    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}

.money {
    background: rgba(0,0,0,.65);

    padding: 10px 18px;

    border-radius: 8px;

    font-size: 25px;
    font-weight: bold;
}

.wanted {
    background: rgba(0,0,0,.65);

    padding: 8px 15px;

    border-radius: 8px;

    text-align: center;
}

#wanted-label {
    font-size: 12px;
    font-weight: bold;
}

#wanted-stars {
    font-size: 25px;
    letter-spacing: 3px;
}

/* =========================
   MISIÓN
========================= */

#mission-box {
    position: absolute;

    top: 90px;
    left: 20px;

    width: 280px;

    background: rgba(0,0,0,.72);

    border-left: 6px solid #ffd900;

    padding: 12px 15px;

    border-radius: 5px;
}

.mission-title {
    color: #ffd900;

    font-size: 13px;
    font-weight: bold;

    margin-bottom: 5px;
}

#mission-text {
    font-size: 16px;
    line-height: 1.3;
}

/* =========================
   VELOCÍMETRO
========================= */

#speedometer {
    position: absolute;

    right: 20px;
    bottom: 20px;

    width: 120px;
    height: 70px;

    background: rgba(0,0,0,.7);

    border-radius: 10px;

    display: flex;
    flex-direction: column;

    align-items: center;
    justify-content: center;

    font-size: 30px;
    font-weight: bold;
}

#speedometer small {
    font-size: 11px;
}

/* =========================
   MENSAJES
========================= */

#message {
    position: absolute;

    top: 45%;
    left: 50%;

    transform: translate(-50%, -50%);

    background: rgba(0,0,0,.75);

    padding: 15px 25px;

    border-radius: 8px;

    font-size: 20px;
    font-weight: bold;

    opacity: 0;

    transition: opacity .2s;

    pointer-events: none;

    color: white;
}

/* =========================
   CONTROLES MÓVILES
========================= */

#controls {
    position: absolute;

    left: 20px;
    bottom: 20px;

    display: none;

    user-select: none;
}

.control-row {
    display: flex;

    justify-content: center;
}

#controls button {
    width: 55px;
    height: 55px;

    margin: 3px;

    border: none;

    border-radius: 10px;

    background: rgba(0,0,0,.65);

    color: white;

    font-size: 22px;

    touch-action: none;
}

#controls button:active {
    background: rgba(255,255,255,.4);
}

.action-buttons {
    margin-top: 8px;
    text-align: center;
}

#action-button {
    width: 110px !important;
    font-size: 13px !important;
}

/* =========================
   PANTALLA INICIO
========================= */

#start-screen {
    position: absolute;

    inset: 0;

    display: flex;

    flex-direction: column;

    align-items: center;
    justify-content: center;

    text-align: center;

    background:
        linear-gradient(
            rgba(0,0,0,.55),
            rgba(0,0,0,.75)
        );

    color: white;

    z-index: 20;
}

#start-screen h1 {
    font-size: clamp(35px, 7vw, 80px);

    color: #ffd900;

    text-shadow:
        4px 4px 0 #000,
        -2px -2px 0 #000;

    margin-bottom: 20px;
}

#start-screen p {
    max-width: 500px;

    line-height: 1.5;

    margin-bottom: 20px;
}

#start-button {
    border: none;

    padding: 15px 45px;

    font-size: 22px;
    font-weight: bold;

    background: #ffd900;

    border-radius: 8px;

    cursor: pointer;

    box-shadow: 0 5px 0 #8d7600;
}

#start-button:hover {
    transform: translateY(-2px);
}

#start-button:active {
    transform: translateY(4px);

    box-shadow: none;
}

.instructions {
    margin-top: 30px;

    font-size: 14px;

    opacity: .8;
}

.instructions p {
    margin: 4px;
}

/* =========================
   MÓVILES
========================= */

@media (max-width: 800px) {

    #controls {
        display: block;
    }

    #mission-box {
        width: 220px;

        top: 80px;
    }

    .money {
        font-size: 18px;
    }

    #wanted-stars {
        font-size: 19px;
    }

    #speedometer {
        width: 90px;
        height: 60px;

        font-size: 22px;
    }
}