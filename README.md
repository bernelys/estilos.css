# estilos.css
body {
    background-color: #f5f0e6;
    font-family: Arial, sans-serif;
    margin: 20px;
    color: #333;
}

h1 {
    text-align: center;
}

#malla {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
}

.caja {
    background: #fff8f0;
    border: 2px solid #c2b280;
    padding: 10px;
    width: 220px;
    min-height: 100px;
    text-align: center;
    box-shadow: 0 3px 5px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.2s, background 0.3s;
}

.caja:hover {
    transform: scale(1.05);
}

.caja.aprobada {
    background: #c5e1c5;
    border-color: #6da86d;
}

.caja.bloqueada {
    opacity: 0.5;
    cursor: not-allowed;
}
