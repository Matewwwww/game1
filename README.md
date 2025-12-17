
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Programming Language Quiz</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            min-height: -webkit-fill-available;
            padding: 0;
            overflow-x: hidden;
        }

        html {
            height: -webkit-fill-available;
        }

        .container {
            width: 100%;
            max-width: 100%;
            margin: 0 auto;
            padding: 0;
            background: white;
            min-height: 100vh;
            min-height: -webkit-fill-available;
            position: relative;
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 100%);
            color: white;
            padding: clamp(20px, 5vw, 30px);
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .header h1 {
            font-size: clamp(1.5rem, 6vw, 2.2rem);
            margin-bottom: 8px;
            font-weight: 700;
            line-height: 1.2;
        }

        .header p {
            font-size: clamp(0.9rem, 4vw, 1.1rem);
            opacity: 0.95;
            line-height: 1.4;
        }
