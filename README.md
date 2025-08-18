# Projeto-Cat-logo-de-V-deos
body {
    margin: 0;
    font-family: 'Chakra Petch', sans-serif;
    background-color: #111;
    color: white;
}

header {
    background-color: #B71C1C;
    padding: 20px;
    text-align: center;
    font-size: 36px;
    font-weight: bold;
    letter-spacing: 2px;
}

.chamada {
    padding: 40px 20px;
    text-align: center;
    background-color: #1E1E1E;
}

.chamada-texto h1 {
    font-size: 32px;
    margin-bottom: 10px;
    color: #E53935;
}

.chamada-texto p {
    font-size: 18px;
    color: #ccc;
}

.video-container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    max-width: 100%;
    margin-top: 20px;
}

.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.categoria {
    padding: 40px 20px;
}

.categoria h2 {
    text-align: center;
    font-size: 28px;
    margin-bottom: 20px;
}

.categoria-videos {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.categoria-videos img {
    width: 100%;
    max-width: 300px;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.categoria-videos img:hover {
    transform: scale(1.05);
}
