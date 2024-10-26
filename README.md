<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>

<h1>📊 Welcome to the Pandas Project</h1>
<p>This project showcases various functionalities of the <code>Pandas</code> library using Python. It covers creating DataFrames, exporting to CSV, accessing rows and columns, and performing data analysis tasks.</p>

<h2>🔧 Libraries Used</h2>
<ul>
    <li><code>numpy</code> 🧮</li>
    <li><code>pandas</code> 📈</li>
</ul>

<h2>👨‍👩‍👧‍👦 Dataset 1: Family Information</h2>
<p>The following dictionary was converted into a DataFrame:</p>
<pre><code>dict1 = {
    "name": ['ramesh', 'laxmi', 'bhuvan', 'shubh'],
    "marks": [92, 98, 98, 96],
    "city": ['Hyderabad', 'Mumbai', 'Rajasthan', 'Assam']
}</code></pre>

<h3>💾 Exporting Data to CSV</h3>
<p>The DataFrame was saved as <code>family.csv</code> and <code>family_index.csv</code> (without row indices).</p>

<h2>🚆 Dataset 2: Train Details</h2>
<p>This dataset contains information about trains, including their number, speed, and city of origin:</p>
<pre><code>dict2 = {
    "Train No.": ['1233', '1456', '7812', '9034'],
    "Speed": [123, 345, 567, 789],
    "City": ['Jaipur', 'Raipur', 'Hyderabad', 'Nizamabad']
}</code></pre>

<h3>🔄 Modifying Data</h3>
<p>The value in the <code>Speed</code> column for Train No. <code>7812</code> was changed to <code>50</code>.</p>

<h2>📋 Creating Series and DataFrames</h2>
<p>A <code>Series</code> and a larger <code>DataFrame</code> were created with random values to demonstrate statistical analysis and manipulation.</p>

<h3>💻 Example Code</h3>
<pre><code># Creating a Series with 34 random values
ser = pd.Series(np.random.rand(34))

# Creating a DataFrame with random values
newdf = pd.DataFrame(np.random.rand(334, 5), index=np.arange(334))</code></pre>

<h2>🛠 Changing Index and Data Types</h2>
<p>The <code>newdf</code> DataFrame was modified by:</p>
<ul>
    <li>Changing specific cell values (with warnings displayed).</li>
    <li>Updating the index labels and viewing data types.</li>
</ul>

<h2>📈 Statistical Analysis</h2>
<p>The <code>describe()</code> method was used to generate statistics for numerical columns:</p>
<pre><code>newdf.describe()</code></pre>

<h2>🔍 Data Sample</h2>
<p>A snapshot of the first few rows in the DataFrame:</p>
<pre><code>newdf.head()</code></pre>

<h2>📚 Resources</h2>
<ul>
    <li><a href="https://pandas.pydata.org/pandas-docs/stable/index.html" target="_blank">Pandas Documentation</a> 📖</li>
    <li><a href="https://numpy.org/doc/" target="_blank">NumPy Documentation</a> 📚</li>
</ul>

</body>
</html>
