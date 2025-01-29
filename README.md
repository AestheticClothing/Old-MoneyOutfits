@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap');

body {
    font-family: 'Playfair Display', serif;
    background-color: #f5f5dc;
    color: #2c2c2c;
    text-align: center;
    padding: 20px;
    animation: fadeIn 2s ease-in-out;
}

header {
    margin-bottom: 40px;
}

h1 {
    font-size: 2.5em;
    color: #8B6A4F;
}

.outfit-gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.outfit {
    background: white;
    padding: 15px;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.outfit:hover {
    transform: scale(1.05);
}

img {
    width: 100%;
    border-radius: 10px;
}

.generator {
    margin-top: 50px;
}

input, button {
    padding: 10px;
    margin: 10px;
    font-size: 1em;
    border: none;
    border-radius: 5px;
}

input {
    width: 60%;
    border: 1px solid #8B6A4F;
}

button {
    background-color: #8B6A4F;
    color: white;
    cursor: pointer;
    transition: background 0.3s;
}

button:hover {
    background-color: #6b4a2b;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
}

.fade-in {
    animation: fadeIn 1.5s ease-in-out;
}
