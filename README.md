<!DOCTYPE html>
<html>
<head>
    <title>Responsive Card Layout</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<style>
    .card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.card {
    width: 300px;
    height: 400px;
    border: 1px solid #ccc;
    border-radius: 8px;
    overflow: hidden;
    margin-bottom: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.card:hover {
    background-color: #f5f5f5;
    transform: scale(1.05);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card-content {
    padding: 20px;
}

@media (max-width: 768px) {
    .card {
        width: 100%;}
    }
</style>
<body>
    <div class="card-container">
        <div class="card">
            <img src="images/62d1163f1995ab9ab99e29b1451e1e10.jpg" alt="Card Image">
            <div class="card-content">
                <h2>Card 1</h2>
                <p>This is a good picture that is taken by google.</p>
            </div>
        </div>
        <div class="card">
            <img src="images/shallow.depth_.of_.field_.mishra.wildflower.webp" alt="Card Image">
            <div class="card-content">
                <h2>Card 2</h2>
                <p>This is the picture of the shallow deth of field.</p>
            </div>
        </div>
        <div class="card">
            <img src="images/untitled-2791.webp" alt="Card Image">
            <div class="card-content">
                <h2>Card 3</h2>
                <p>This is a picture of player that playing his game.</p>
            </div>
        </div>
    </div>
</body>
</html>
