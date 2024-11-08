<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Dark Side of Social Media</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Body styling */
        body {
            background-color: #1a1a2e;
            color: #e5e5e5;
            line-height: 1.6;
            padding: 20px;
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: #16213e;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.6);
        }

        /* Title */
        h1 {
            text-align: center;
            color: #e94560;
            margin-bottom: 20px;
            font-size: 2em;
        }

        /* Subtitle */
        p.subtitle {
            text-align: center;
            font-size: 1.1em;
            color: #a6a6a6;
            margin-bottom: 30px;
        }

        /* List styling */
        .disadvantages-list {
            list-style: none;
            padding: 0;
        }

        .disadvantages-list li {
            background-color: #0f3460;
            margin: 10px 0;
            padding: 20px;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        /* Hover effect for list items */
        .disadvantages-list li:hover {
            transform: translateY(-5px);
            background-color: #533483;
        }

        /* Number style for items */
        .disadvantages-list li::before {
            content: counter(item) ". ";
            counter-increment: item;
            font-weight: bold;
            color: #e94560;
            font-size: 1.2em;
            margin-right: 8px;
        }

        /* Content inside list items */
        .disadvantages-list li h3 {
            color: #e5e5e5;
            font-size: 1.3em;
            margin-bottom: 10px;
        }

        .disadvantages-list li p {
            color: #c7c7c7;
            font-size: 1em;
        }
    </style>
</head>
<body>

    <!-- Container for content -->
    <div class="container">
        <h1>The Dark Side of Social Media</h1>
        <p class="subtitle">While social media offers many advantages, it's crucial to acknowledge its potential downsides.</p>

        <!-- Disadvantages list -->
        <ul class="disadvantages-list">
            <li>
                <h3>Cyberbullying and Harassment</h3>
                <p>The anonymity and vast reach of social media can embolden individuals to engage in cyberbullying and harassment. This can have devastating consequences for victims, causing emotional distress, reputational damage, and even physical harm.</p>
            </li>
            <li>
                <h3>Misinformation and Fake News</h3>
                <p>The rapid spread of information on social media can lead to the amplification of misinformation and fake news. This can have serious consequences, impacting public opinion, political discourse, and even public health.</p>
            </li>
            <li>
                <h3>Privacy Concerns</h3>
                <p>Social media platforms collect vast amounts of personal data, raising concerns about privacy and data security. This information can be used for targeted advertising, profiling, and even unauthorized access by third parties.</p>
            </li>
            <li>
                <h3>Social Comparison and Negative Self-Image</h3>
                <p>The curated and often idealized content on social media can lead to social comparison and feelings of inadequacy. Individuals may feel pressure to present a perfect image, leading to anxiety, depression, and low self-esteem.</p>
            </li>
            <li>
                <h3>Addiction and Time Wasting</h3>
                <p>The constant stream of notifications, updates, and engaging content can be highly addictive, leading to excessive screen time and neglecting other important activities. This can impact productivity, relationships, and overall well-being.</p>
            </li>
        </ul>
    </div>

</body>
</html>
