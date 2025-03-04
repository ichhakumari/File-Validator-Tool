<h1>File Validator Tool</h1>

<h3>🚀 A robust file validation tool for bioinformatics and scientific datasets</h3>
<h5> live here  https://filecheckertool.netlify.app/</h5>
<h3>📌 Overview </h3>

The File Validator Tool is designed to validate CSV, PDB, and TXT files, ensuring data consistency, correctness, and format adherence. It automates the process of checking file structures, data types, and missing values, making it ideal for scientists, researchers, and bioinformatics professionals working with protein-ligand interactions, docking simulations, and molecular datasets.
<h3>✨ Features</h3>
<h3>📂 File Upload & Display</h3>

    ✅ Supports CSV, PDB, and TXT file uploads
    ✅ Displays uploaded files on the right panel
    ✅ Uses radio buttons to toggle between multiple files
    ✅ Accepts only valid file types (e.g., CSV for tabular data, PDB for protein structures)

<h3>🔍 CSV File Validation </h3>

    📌 Ensures the uploaded CSV file contains required columns as per user input
    📌 Supports more than 3 columns, but required ones must exist
    📌 Checks for missing values and datatype mismatches
        SMILES Column → Only string values
        Protein Sequence Column → Only string values
        Activity Column → Only integer or float values
    📌 Clear and structured error messages
        "Missing required column: Activity"
        "Invalid data type in Protein column - Rows: 3, 5, 7"
        "Null values found in SMILES column - Rows: 4, 6, 10"

<h3>🔬 PDB File Validation (Protein & Ligand)</h3>

    📌 Accepts only .pdb files for protein and ligand validation
    📌 Ensures structure correctness
        Protein files must contain only "ATOM" records
        Ligand files can contain both "ATOM" & "HETATM"
        Ligand files must have at least one column with "LIG"
    📌 Users can switch between uploaded files with radio buttons for easy viewing

<h3>📜 TXT File Validation</h3>

    📌 Ensures TXT files have exactly 3 columns
        2 String Columns (alphanumeric names, molecule names, etc.)
        1 Integer/Boolean Column (true/false, 1/0)
    📌 Provides real-time validation with instant feedback

<h3>🎨 UI/UX Enhancements</h3>

    ✅ Modern & Responsive Design for desktop & mobile
    ✅ Card-based layout with clear navigation
    ✅ Home & Docking links added outside the main card for quick access
    ✅ Styled error messages for better readability
    ✅ Interactive buttons & hover effects for an engaging experience

<h3>⚡ Validation Button Fixes</h3>

    ✅ Fixed issues where validation wasn’t triggering correctly
    ✅ Applied all validation conditions across different button methods

<h3>🛠 Project Evolution</h3>

The File Validator Tool has undergone multiple iterations, continuously improving accuracy, performance, and user experience.
<h4>💡 Challenges Solved</h4>
🔹 CSV Validation Improvements

    Early Issues: Data type checks were inconsistent for small datasets (<5 errors)
    Now: Each row is validated, and datatype mismatches are reported clearly

🔹 Better Error Messages

Before: "Invalid data type detected in multiple rows."
Now:

    "Invalid data type in Activity column (expected float/int) - Rows: 3, 5, 7"
    "Protein column cannot contain numbers - Rows: 8, 9"

🔹 PDB Validation Enhancements

    Previously, the tool wasn't fully checking ligand files for both ATOM & HETATM
    Now, ligand files are properly validated, ensuring scientific accuracy

🔹 Validation Button Fixes

    Before, the Validate button wasn’t executing checks on all uploaded files
    Now, it validates all files properly, including multiple uploads

🔹 UI Improvements

    Buttons arranged in a single line for a cleaner look
    Card-based layout ensures aesthetic appeal & ease of use
    Radio buttons to switch between files for better usability

<h3>📌 Final Functionalities</h3>

✅ Complete File Validation Workflow<br>
✅ CSV File Validation (SMILES, Protein, Activity Columns)<br>
✅ PDB File Validation (Protein: ATOM only, Ligand: ATOM/HETATM & LIG presence)<br>
✅ TXT File Validation (2 String + 1 Boolean Column)<br>
✅ UI Enhancements (Cards, Alignment, Hover Effects, Links, Responsiveness)<br>
✅ Error Handling (Missing Columns, Datatype Errors, Null Values)<br>
✅ Toggle View (Radio buttons for different file views)<br>
<h3>💡 Future Improvements</h3>

🔹 Drag & Drop File Uploads for easier interaction<br>
🔹 Downloadable Error Reports for external validation<br>
🔹 Support for Additional File Types (JSON, SDF, MOL2, etc.)<br>
🔹 Progress Indicators & File Previews
<h4>🌟 Why This Project Stands Out</h4>

✅ Solves a real-world problem for bioinformatics & data validation<br>
✅ Multiple validation mechanisms make it robust & reliable<br>
✅ Scalable for larger datasets & complex file structures<br>
✅ Clean UI/UX ensures easy usability for researchers<br>
✅ Extensive error handling ensures data integrity
<h4>👨‍💻 Tech Stack</h4>

    Frontend: HTML, CSS, JavaScript
    Backend: Django (for future scalability)
    Validation: JavaScript for client-side file validation
    UI Frameworks: Bootstrap (for styling & responsiveness)


<h3>📜 License</h3>

This project is licensed under the MIT License.
<h3>📢 Connect with Me</h3>

💡 If you're looking for a developer who can build intelligent tools, solve complex data challenges, and improve user experience, let’s connect! 😊🚀

<h2> Due to company integrity, I haven't uploaded the code. However, feel free to reach out if you'd like to know more about this tool.

<br>You can contact me on LinkedIn(https://www.linkedin.com/in/ichha-kumari) or via email (ichha2111@gmail.com).</h2>
