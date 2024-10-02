body {
    font-family: 'Arial', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: linear-gradient(135deg, #71b7e6, #9b59b6);
    margin: 0;
    background-size: cover; /* Ensure the background image covers the entire body */
    background-position: center; /* Center the background image */
    background-repeat: no-repeat; /* Prevent the background image from repeating */
}


.container {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 300px;
}

h1 {
    margin-bottom: 20px;
}

.search-box {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

input {
    padding: 10px;
    width: 70%;
    border: 1px solid #ddd;
    border-radius: 5px 0 0 5px;
}

button {
    padding: 10px;
    width: 30%;
    border: 1px solid #ddd;
    border-left: none;
    background: #3498db;
    color: white;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
}

button:hover {
    background: #2980b9;
}

.loading-spinner {
    font-size: 24px;
    margin: 20px 0;
}

.weather-info {
    display: none;
    text-align: left;
}

.weather-info h2 {
    margin: 0;
}

.weather-info p {
    margin: 5px 0;
}

.error-message {
    color: red;
    margin-top: 20px;
}
