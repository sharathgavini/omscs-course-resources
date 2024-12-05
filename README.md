# OMSCS Course Resources Contribution Guide

Thank you for contributing to the OMSCS Course Resources repository! This guide explains the rules and structure for adding new courses and their resources. Please follow these instructions carefully to maintain consistency across the repository.

To make resources easily accessible, we will use `README.md` files in each course folder. GitHub automatically previews `README.md` files when a folder is opened, allowing quick and convenient access to the course resources.

---

## Folder Naming Rules

Each course should have its own folder with the following naming format:
CS[Course Number] [Course Name]

### Examples:

- `CS7641 Machine Learning`
- `CS6200 Introduction to Operating Systems`

---

## Required Files in Each Course Folder

Each course folder must contain a single file:

- **`README.md`**: A structured list of resources for the course. This ensures the content is automatically displayed when the folder is opened on GitHub.

### Optional:

- `other_files/`: A subfolder for additional materials like datasets, notes, or sample code.

---

## File Content Requirements

### `README.md`

The `README.md` file should provide a categorized list of resources related to the course. Use the following format:

#### File Structure:

```markdown
# CS[Course Number]: [Course Name] Resources

## Lecture Videos:

1. [Lecture 1: Topic Name](https://link-to-video.com)
2. [Lecture 2: Topic Name](https://link-to-video.com)

## Books:

- [Book Title by Author](https://link-to-book.com)

## Articles:

- [Article Title](https://link-to-article.com)

## Tools:

- [Tool Name (e.g., Scikit-learn)](https://tool-link.com)

## Other Resources:

- [Resource Title](https://link-to-resource.com)
  Example README.md:

# CS7641: Machine Learning Resources

## Lecture Videos:

1. [Lecture 1: Introduction to Machine Learning](https://example.com/lecture1)
2. [Lecture 2: Supervised Learning](https://example.com/lecture2)

## Books:

- [Pattern Recognition and Machine Learning by Christopher Bishop](https://example.com/book1)

## Articles:

- [Understanding Machine Learning Basics](https://example.com/article1)

## Tools:

- [Scikit-learn Documentation](https://scikit-learn.org)

## Other Resources:

- [GitHub Repository with Course Notes](https://example.com/github-repo)
```

## Optional: other_files/

If you have additional materials, create a folder named other_files/ within the course folder and add your files there. Examples:
Sample datasets
Lecture notes
Source code or Jupyter notebooks
Contribution Steps

## Contribution Steps

### Check Existing Folders:

- Before creating a new folder, check if the course folder already exists.

### Create a New Folder:

- Use the naming format `CS[Course Number] [Course Name]`.

### Add the Required File:

- Add a `README.md` file as described above.
- **Optional**: Include an `other_files/` folder for additional materials.

### Commit Your Changes:

- Use meaningful commit messages. Example:
  `Added resources for CS7641 Machine Learning`

### Submit a Pull Request:

- Push your changes to a new branch and open a pull request.
- Provide a description of your changes and ensure they follow the guidelines.

# General Rules for Contributors

## Be Consistent:

Follow the naming conventions and structure outlined above.

## Share High-Quality Resources:

Ensure that resources are relevant, accurate, and helpful.

## Provide Attribution:

Always credit the source of external materials by linking to the original content.

## Collaborate Respectfully:

Be respectful and constructive when discussing or reviewing contributions.

# Example Repository Structure

Here’s an example of how the repository should look:

```
OMSCS-course-resources/
├── CS7641 Machine Learning/
│   ├── README.md
│   └── other_files/
│       └── example_dataset.csv
├── CS6200 Introduction to Operating Systems/
│   ├── README.md
│   └── other_files/
└── template.md
```

Thank you for contributing to the OMSCS Course Resources repository. Your work helps create a valuable resource for students and professionals alike. Happy contributing!
