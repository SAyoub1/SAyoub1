<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafe Business Overview</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section class="business-overview">
        <h1>Business Overview</h1>
        <img src="Moonlit Mocha logo.png" alt="Moonlit Mocha Logo" style="display: block; margin: 0 auto; width: 150px;">
        <div class="about-us">
            <h2>About Us</h2>
            <p><strong>History:</strong> Founded in 2025, our Cafe was born out of a love for both coffee and storytelling. The cafe quickly gained a loyal customer base due to its unique atmosphere and high-quality offerings.</p>
            <p><strong>Vision:</strong> To be a place where every visit feels like a magical escape, offering customers not just coffee, but an experience.</p>
        </div>
        <div class="team">
            <h2>Team</h2>
            <p><strong>Clara Mendel:</strong> Owner and Manager - Brings over 10 years of experience in the hospitality industry and a passion for creating magical experiences.</p>
            <p><strong> Julian Reyes :</strong> Head Barista - Known for her creative coffee concoctions and warm customer service.</p>
            <p><strong> Maya Thompson & Theo Kim :</strong> Baristas - Maintains a positive and efficient workflow while delivering high-quality beverages with precision.</p>
        </div>
        <div class="market-analysis">
            <h2>Market Analysis</h2>
            <p>Our target market includes young professionals, students, and families who appreciate high-quality coffee and a welcoming environment. We also aim to attract tourists looking for a memorable and delightful cafe experience.</p>
        </div>
        <div class="future-plans">
            <h2>Future Plans</h2>
            <ul>
                <li><strong>Expansion:</strong> Opening additional locations in other parts of the city and potentially other cities.</li>
                <li><strong>New Offerings:</strong> Introducing a line of branded merchandise and expanding the menu to include more vegan and gluten-free options.</li>
                <li><strong>Community Engagement:</strong> Partnering with local artists and authors to create a vibrant, creative hub.</li>
            </ul>
        </div>
    </section>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9; /* Light background for a clean look */
    color: #333; /* Neutral text color for readability */
}

.business-overview {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffff; /* White background for contrast */
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

.business-overview h1 {
    text-align: center;
    color: #2c3e50; /* Deep blue for a professional header */
    font-size: 2rem;
    margin-bottom: 20px;
}

.business-overview h2 {
    color: #16a085; /* Vibrant teal for section headers */
    border-bottom: 2px solid #1abc9c; /* Matching border for consistency */
    padding-bottom: 5px;
    margin-bottom: 15px;
}

.business-overview p, .business-overview ul {
    line-height: 1.6;
    margin-bottom: 15px;
    color: #555; /* Slightly darker text for better contrast */
}

.business-overview ul {
    padding-left: 20px;
}

.business-overview ul li {
    margin-bottom: 10px;
    color: #34495e; /* Darker blue-gray for list items */
}

strong {
    color: #e74c3c; /* Vibrant red for emphasis */
}

a {
    color: #3498db; /* Bright blue for links */
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

