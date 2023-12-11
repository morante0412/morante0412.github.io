<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Country Information</title>
    <style>
        body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #333;
}

header, main, footer {
    padding: 20px;
    background-color: #333;
    color: #fff;
}

header {
    text-align: center;
}

main {
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
}

footer {
    text-align: left;
    position: fixed;
    bottom: 0;
    width: 25%;
}

label {
    display: block;
    margin-bottom: 10px;
    font-size: 1.2em;
}

input, button {
    margin: 10px;
    padding: 8px;
    font-size: 1em;
}

img {
    max-width: 100%;
    max-height: 300px;
    height: auto;
    margin-bottom: 10px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #BA7BA1;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 1em;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #C087AA;
}

    </style>
</head>
<body>
    <header>
        <h1>Country Information</h1>
    </header>
    <main>
        <label for="countryInput">Search for a Country:</label>
        <input type="text" id="countryInput" placeholder="Enter a country name">
        <button onclick="searchCountry()">Search</button>

        <div id="countryInfo"></div>
        <div id="countryImages"></div>

        <button id="viewArticlesBtn" onclick="navigateToArticlesPage()" style="display: none;">View Articles</button>
    </main>
    <footer>
        <p>ITP 207 FINAL PROJECT 2023</p>
    </footer>
    <script>
        function searchCountry() {
            const countryInput = document.getElementById('countryInput').value;

            // Fetch country information from REST Countries API
            fetch(`https://restcountries.com/v3.1/name/${countryInput}`)
                .then(response => response.json())
                .then(data => {
                    const countryInfoContainer = document.getElementById('countryInfo');
                    countryInfoContainer.innerHTML = '';

                    if (data.length > 0) {
                        const country = data[0];
                        const countryElement = document.createElement('div');
                        countryElement.innerHTML = `
                            <h2>${country.name.common}</h2>
                            <p>Capital: ${country.capital}</p>
                            <p>Region: ${country.region}</p>
                            <p>Subregion: ${country.subregion}</p>
                            <p>Population: ${country.population}</p>
                            <p>Area: ${country.area} km<sup>2</sup></p>
                        `;
                        countryInfoContainer.appendChild(countryElement);

                        // Show the "View Articles" button
                        document.getElementById('viewArticlesBtn').style.display = 'block';
                    } else {
                        countryInfoContainer.innerHTML = '<p>Country not found</p>';
                        // Hide the "View Articles" button if country is not found
                        document.getElementById('viewArticlesBtn').style.display = 'none';
                    }
                })
                .catch(error => console.error('Error fetching country information:', error));

            // Fetch country images from Unsplash API
            fetch(`https://api.unsplash.com/photos/random/?query=${countryInput}&client_id=yCT9C_o1z0L-n7VafhZ0hrLHfQ1c13H8U9Toe6zH5p8`)
                .then(response => response.json())
                .then(data => {
                    const countryImagesContainer = document.getElementById('countryImages');
                    countryImagesContainer.innerHTML = '';

                    if (data.urls) {
                        const imageElement = document.createElement('img');
                        imageElement.src = data.urls.regular;
                        imageElement.alt = 'Country Image';
                        countryImagesContainer.appendChild(imageElement);
                    } else {
                        countryImagesContainer.innerHTML = '<p>No images found</p>';
                    }
                })
                .catch(error => console.error('Error fetching images:', error));
        }

        function navigateToArticlesPage() {
            const countryInput = document.getElementById('countryInput').value;
            window.location.href = `articles.html?country=${countryInput}`;
        }
    </script>
</body>
</html>
