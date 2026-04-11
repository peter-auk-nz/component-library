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

<!-- Search Box 2: Bold & Colorful -->
+------+
| HTML |
+------+
<div class="component-card">
    <h3>Search Box 2: Bold & Colorful</h3>
    <div class="component-demo">
        <input type="text" class="search-bold" placeholder="Search...">
        <button class="btn-bold">Search</button>
    </div>
</div>

+-----+
| CSS |
+-----+

/* Search Box 2: Bold & Colorful */
.search-bold {
    padding: 0.75rem 1rem;
    border: 3px solid #ff6b6b;
    border-radius: 4px;
    font-size: 1rem;
    font-weight: bold;
    width: 300px;
    outline: none;
    color: #333;
    transition: border-color 0.3s;
}

.search-bold:focus {
    border-color: #ff9f43;
}

.btn-bold {
    padding: 0.75rem 1.5rem;
    background: linear-gradient(135deg, #ff6b6b, #ff9f43);
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 1rem;
    font-weight: bold;
    cursor: pointer;
    transition: opacity 0.3s;
}

.btn-bold:hover {
    opacity: 0.85;
}

+------+
| HTML |
+------+
<!-- Search Box 3: Rounded & Soft -->
<div class="component-card">
    <h3>Search Box 3: Rounded & Soft</h3>
    <div class="component-demo">
        <input type="text" class="search-rounded" placeholder="Search...">
        <button class="btn-rounded">Search</button>
    </div>
</div>

+-----+
| CSS | 
+-----+
/* Search Box 3: Rounded & Soft */
.search-rounded {
    padding: 0.75rem 1.25rem;
    border: 2px solid #e0c3fc;
    border-radius: 50px;  /* Fully rounded. The key thing making this one feel "soft */
    font-size: 1rem;
    width: 300px;
    outline: none;
    background: #fdf6ff;
    color: #555;
    transition: border-color 0.3s, box-shadow 0.3s;
}

.search-rounded:focus {
    border-color: #b388ff;
    box-shadow: 0 0 0 4px rgba(179, 136, 255, 0.15);
}

.btn-rounded {
    padding: 0.75rem 1.5rem;
    background: #ce93d8;
    color: white;
    border: none;
    border-radius: 50px;
    font-size: 1rem;
    cursor: pointer;
    transition: background 0.3s;
}

.btn-rounded:hover {
    background: #ab47bc;
}

+------+
| HTML |
+------+
<!-- Search Box 4: Dark Mode -->
<div class="component-card">
    <h3>Search Box 4: Dark Mode</h3>
    <div class="component-demo demo-dark">
        <input type="text" class="search-dark" placeholder="Search...">
        <button class="btn-dark">Search</button>
    </div>
</div>

+-----+
| CSS | 
+-----+
/* Search Box 4: Dark Mode */
.demo-dark {
    background: #1a1a2e;
    border-radius: 8px;
}

.search-dark {
    padding: 0.75rem 1.25rem;
    border: 2px solid #444;
    border-radius: 8px;
    font-size: 1rem;
    width: 300px;
    outline: none;
    background: #16213e;
    color: #e0e0e0;
    transition: border-color 0.3s;
}

.search-dark::placeholder { /* new CSS selector! Style the placeholder text separately! Important with dark mode */ 
    color: #888;
}

.search-dark:focus {
    border-color: #00d4ff;
}

.btn-dark {
    padding: 0.75rem 1.5rem;
    background: #00d4ff;
    color: #1a1a2e;
    border: none;
    border-radius: 8px;
    font-size: 1rem;
    font-weight: bold;
    cursor: pointer;
    transition: background 0.3s;
}

.btn-dark:hover {
    background: #00b8d9;
}

+------+
| HTML |
+------+
<!-- Search Box 5: Glass Effect -->
<div class="component-card">
    <h3>Search Box 5: Glass Effect</h3>
    <div class="component-demo demo-glass">
        <input type="text" class="search-glass" placeholder="Search...">
        <button class="btn-glass">Search</button>
    </div>
</div>

+-----+
| CSS | 
+-----+
* Search Box 5: Glass Effect */
.demo-glass {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    border-radius: 8px;
}

.search-glass {
    padding: 0.75rem 1.25rem;
    border: 1px solid rgba(255, 255, 255, 0.4);
    border-radius: 50px;
    font-size: 1rem;
    width: 300px;
    outline: none;
    background: rgba(255, 255, 255, 0.15);
    color: white;
    backdrop-filter: blur(10px);
    transition: border-color 0.3s, background 0.3s;
}

.search-glass::placeholder {
    color: rgba(255, 255, 255, 0.7);
}

.search-glass:focus {
    background: rgba(255, 255, 255, 0.25);
    border-color: rgba(255, 255, 255, 0.8);
}

.btn-glass {
    padding: 0.75rem 1.5rem;
    background: rgba(255, 255, 255, 0.2);
    color: white;
    border: 1px solid rgba(255, 255, 255, 0.4); /* rgba */
    border-radius: 50px;
    font-size: 1rem;
    cursor: pointer;
    backdrop-filter: blur(10px); /* The glass effect and rgba colours with transparency — creates the frosted glass look. ✨ */
    transition: background 0.3s;
}

.btn-glass:hover {
    background: rgba(255, 255, 255, 0.35);
}