# Students-class-10th-
This is amazing name students class 10th 
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 10th Notes Hub</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Class 10th Notes Portal</h1>
        <p>Padhai ki duniya, ab aapke haath mein!</p>
    </header>

    <main>
        <section class="subjects">
            <h2>Subjects</h2>
            <div class="grid-container">
                <div class="card">Maths</div>
                <div class="card">Science</div>
                <div class="card">SST</div>
                <div class="card">Hindi/English</div>
            </div>
        </section>

        <section class="upload-section">
            <h3>Naye Notes Upload Karein</h3>
            <form id="uploadForm">
                <input type="text" placeholder="Chapter ka Naam" required>
                <select>
                    <option>Maths</option>
                    <option>Science</option>
                    <option>SST</option>
                    <option>English</option>
                </select>
                <input type="file" id="fileInput" accept=".pdf,.doc,.jpg" required>
                <button type="submit">Upload karein</button>
            </form>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    background-color: #f4f7f6;
    color: #333;
    text-align: center;
}

header {
    background-color: #2c3e50;
    color: white;
    padding: 2rem 0;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    padding: 20px;
    max-width: 800px;
    margin: auto;
}

.card {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
}

.card:hover {
    background-color: #3498db;
    color: white;
}

.upload-section {
    background: #fff;
    margin: 30px auto;
    padding: 20px;
    max-width: 500px;
    border-radius: 8px;
}

input, select, button {
    display: block;
    width: 100%;
    margin: 10px 0;
    padding: 10px;
    box-sizing: border-box;
}

button {
    background-color: #27ae60;
    color: white;
    border: none;
    cursor: pointer;
}
