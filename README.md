Overview

AI Folder Creator is an intelligent automation tool that generates structured folders and files based on input images, diagrams, or manual descriptions. Using advanced AI techniques like OCR, CNNs, NLP, and Graph Processing, it interprets logical structures and creates relevant directory hierarchies and code files automatically.

Features

Image/Diagram Processing: Converts hand-drawn sketches, flowcharts, and system logic diagrams into structured file systems.

AI-Powered Recognition: Uses OCR (Tesseract, Google Vision API) and CNN-based Object Detection (YOLO, Faster R-CNN) for text and object extraction.

Graph Structure Mapping: Parses hierarchical relationships and dependencies from input data.

Automated Folder & File Generation: Creates meaningful file and folder structures instead of placeholders.

Programming Language Support: Generates structured code files in multiple languages (Python, JavaScript, etc.).

Interactive Previews: Displays a tree structure and a visual flowchart before file generation.

User-Defined Customization: Allows manual modifications before finalizing the output.

Local Deployment Support: Can be run on a local machine or integrated into an existing workflow.

Versioning & Rollback: (Upcoming Feature) Supports version control using Git.

Installation

Prerequisites

Python 3.8+

pip (Python package manager)

Required Libraries:

pip install opencv-python numpy pytesseract transformers torch torchvision networkx flask django

Clone the Repository

git clone https://github.com/yourusername/AI-Folder-Creator.git
cd AI-Folder-Creator

Usage

Running the Application

python main.py --input <image_path> --output <output_directory>

Example Usage

python main.py --input diagrams/flowchart.png --output generated_folders

Configurations

Modify config.json to customize settings:

{
  "default_folder": "AI_Generated",
  "file_naming": "structured"
}

Folder Structure

AI-Folder-Creator/
│── main.py       # Core script for folder generation
│── config.json   # Configuration file
│── README.md     # Documentation
│── samples/      # Sample images/diagrams
└── generated/    # Auto-generated folders & files

Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

License

MIT License

Contact

For queries or support, reach out via arvindvijay09@gmail.com or GitHub Issues.
