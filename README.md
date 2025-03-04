File Validator Tool

🚀 A robust file validation tool for bioinformatics and scientific datasets
📌 Overview

The File Validator Tool is designed to validate CSV, PDB, and TXT files, ensuring data consistency, correctness, and format adherence. It automates the process of checking file structures, data types, and missing values, making it ideal for scientists, researchers, and bioinformatics professionals working with protein-ligand interactions, docking simulations, and molecular datasets.
✨ Features
📂 File Upload & Display

    ✅ Supports CSV, PDB, and TXT file uploads
    ✅ Displays uploaded files on the right panel
    ✅ Uses radio buttons to toggle between multiple files
    ✅ Accepts only valid file types (e.g., CSV for tabular data, PDB for protein structures)

🔍 CSV File Validation

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

🔬 PDB File Validation (Protein & Ligand)

    📌 Accepts only .pdb files for protein and ligand validation
    📌 Ensures structure correctness
        Protein files must contain only "ATOM" records
        Ligand files can contain both "ATOM" & "HETATM"
        Ligand files must have at least one column with "LIG"
    📌 Users can switch between uploaded files with radio buttons for easy viewing

📜 TXT File Validation

    📌 Ensures TXT files have exactly 3 columns
        2 String Columns (alphanumeric names, molecule names, etc.)
        1 Integer/Boolean Column (true/false, 1/0)
    📌 Provides real-time validation with instant feedback

🎨 UI/UX Enhancements

    ✅ Modern & Responsive Design for desktop & mobile
    ✅ Card-based layout with clear navigation
    ✅ Home & Docking links added outside the main card for quick access
    ✅ Styled error messages for better readability
    ✅ Interactive buttons & hover effects for an engaging experience

⚡ Validation Button Fixes

    ✅ Fixed issues where validation wasn’t triggering correctly
    ✅ Applied all validation conditions across different button methods

🛠 Project Evolution

The File Validator Tool has undergone multiple iterations, continuously improving accuracy, performance, and user experience.
💡 Challenges Solved
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

📌 Final Functionalities

✅ Complete File Validation Workflow
✅ CSV File Validation (SMILES, Protein, Activity Columns)
✅ PDB File Validation (Protein: ATOM only, Ligand: ATOM/HETATM & LIG presence)
✅ TXT File Validation (2 String + 1 Boolean Column)
✅ UI Enhancements (Cards, Alignment, Hover Effects, Links, Responsiveness)
✅ Error Handling (Missing Columns, Datatype Errors, Null Values)
✅ Toggle View (Radio buttons for different file views)
💡 Future Improvements

🔹 Drag & Drop File Uploads for easier interaction
🔹 Downloadable Error Reports for external validation
🔹 Support for Additional File Types (JSON, SDF, MOL2, etc.)
🔹 Progress Indicators & File Previews
🌟 Why This Project Stands Out

✅ Solves a real-world problem for bioinformatics & data validation
✅ Multiple validation mechanisms make it robust & reliable
✅ Scalable for larger datasets & complex file structures
✅ Clean UI/UX ensures easy usability for researchers
✅ Extensive error handling ensures data integrity
👨‍💻 Tech Stack

    Frontend: HTML, CSS, JavaScript
    Backend: Django (for future scalability)
    Validation: JavaScript for client-side file validation
    UI Frameworks: Bootstrap (for styling & responsiveness)

🚀 Getting Started
🔹 Clone the Repository

git clone https://github.com/your-username/file-validator-tool.git
cd file-validator-tool

🔹 Run the Web App

    Install Dependencies

pip install -r requirements.txt

    Run Django Server

python manage.py runserver

    Open in Browser
    Navigate to http://127.0.0.1:8000/

📝 Contribution Guidelines

Feel free to contribute!

    Fork the Repository
    Create a Feature Branch

git checkout -b feature-new-validation

    Commit Changes

git commit -m "Added new validation logic"

    Push to GitHub & Open a PR

git push origin feature-new-validation

📜 License

This project is licensed under the MIT License.
📢 Connect with Me

💡 If you're looking for a developer who can build intelligent tools, solve complex data challenges, and improve user experience, let’s connect! 😊🚀
