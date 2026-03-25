+-------------------+
|COMPONONENT LIBRARY|
+-------------------+
+------------------+
|4:43 pm 25/03/2026|
+------------------+

+--------------------------+
|  A  |  B   |  C   |  D   |
+--------------------------+

README.md

# Component Library

A collection of reusable UI components for web projects.

## Components

### Search Boxes
- Search Box 1: Minimal & Clean
- More designs coming soon...

## Purpose
This is a sandbox for experimenting with different component designs and styles. Each component can be copied and used in other projects.

Created: 2026-03-25
+------+
| HTML |
+------+
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Component Library</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Component Library</h1>
        <p>A collection of reusable UI components</p>
    </header>

    <main>
        <section class="component-section">
            <h2>Search Boxes</h2>
            
            <!-- Search Box 1: Minimal & Clean -->
            <div class="component-card">
                <h3>Search Box 1: Minimal & Clean</h3>
                <div class="component-demo">
                    <input type="text" class="search-minimal" placeholder="Search...">
                    <button class="btn-minimal">Search</button>
                </div>
            </div>

        </section>
    </main>
</body>
</html>

+-----+
| CSS |
+-----+
/* ===================================
   COMPONENT LIBRARY STYLES
   =================================== */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    min-height: 100vh;
    padding: 2rem;
}

header {
    text-align: center;
    color: white;
    margin-bottom: 3rem;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 0.5rem;
}

header p {
    font-size: 1.2rem;
    opacity: 0.9;
}

main {
    max-width: 1200px;
    margin: 0 auto;
}

.component-section {
    margin-bottom: 3rem;
}

.component-section h2 {
    color: white;
    font-size: 2rem;
    margin-bottom: 2rem;
}

.component-card {
    background: white;
    border-radius: 12px;
    padding: 2rem;
    margin-bottom: 2rem;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.component-card h3 {
    color: #333;
    margin-bottom: 1.5rem;
    font-size: 1.3rem;
}

.component-demo {
    display: flex;
    gap: 1rem;
    padding: 2rem;
    background: #f8f9fa;
    border-radius: 8px;
    justify-content: center;
    align-items: center;
}

/* Search Box 1: Minimal & Clean */
.search-minimal {
    padding: 0.75rem 1rem;
    border: 2px solid #ddd;
    border-radius: 4px;
    font-size: 1rem;
    width: 300px;
    outline: none;
    transition: border-color 0.3s;
}

.search-minimal:focus {
    border-color: #667eea;
}

.btn-minimal {
    padding: 0.75rem 1.5rem;
    background: #667eea;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 1rem;
    cursor: pointer;
    transition: background 0.3s;
}

.btn-minimal:hover {
    background: #5568d3;
}