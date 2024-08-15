<p align="center">
  
![Header-Image-crop-1024x559](https://github.com/user-attachments/assets/97ac4111-9bd6-4404-bf6e-279ff4bf9be0)

</p>
<p align="center">
    <h1 align="center">BIOINNOVATE</h1>
</p>
<p align="center">
    <em><code>Gene expression analysis and classification using XGBoost and Differential Expression Analysis (DES)</code></em>
</p>
<p>
<p align="center">
		<em>Developed with Jupyter Notebook.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter">
</p>
<hr>

## 🔗 Quick Links

> - [📍 Overview](#-overview)
> - [📦 Features](#-features)
> - [📂 Repository Structure](#-repository-structure)
> - [🚀 Getting Started](#-getting-started)
>   - [⚙️ Installation](#️-installation)
>   - [🤖 Running Bioinnovate](#-running-bioinnovate)
> - [🤝 Contributing](#-contributing)
> - [📄 License](#-license)
> - [👏 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

<code>BioInnovate performs gene expression analysis and classification using XGBoost. It includes Differential Expression Analysis (DES) to identify significant gene changes and evaluate model performance.
</code>

---

## 📦 Features

<code>XGBoost Classification: Utilizes XGBoost for gene expression classification
Differential Expression Analysis (DES): Identifies differentially expressed genes
Visualization: Includes feature importance and correlation heatmaps</code>

---

## 📂 Repository Structure

```sh
└── BioInnovate/
    ├── GSE250323.csv
    ├── README.md
    ├── Visuals.ipynb
    └── Modeling.ipynb
```

---

## 🧩 Files

<details open><summary>.</summary>

| File                                                                                                    | Summary                         |
| ---                                                                                                     | ---                             |
| [Visuals.ipynb](https://github.com/Saherpathan/BioInnovate/blob/master/Visuals.ipynb)                   | <code>Implements Differential Expression Analysis and visualizations |
| [Modeling.ipynb](https://github.com/Saherpathan/BioInnovate/blob/master/iitj_bioinnovate.ipynb) | <code>Trains and evaluates XGBoost classifier, analyzes feature importance</code> |

</details>

---

## 🚀 Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **JupyterNotebook**: `version v6`

### ⚙️ Installation

1. Clone the BioInnovate repository:

```sh
git clone https://github.com/Saherpathan/BioInnovate
```

2. Change to the project directory:

```sh
cd BioInnovate
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

### 🤖 Running BioInnovate

Use the following command to run BioInnovate:

```sh
jupyter nbconvert --execute Visuals.ipynb
jupyter nbconvert --execute Modeling.ipynb
```


---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Saherpathan/BioInnovate/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Saherpathan/BioInnovate/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Saherpathan/BioInnovate/issues)**: Submit bugs found or log feature requests for Bioinnovate.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/Saherpathan/BioInnovate
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License

This project is protected under the MIT License. 

---

## 👏 Acknowledgments

- Data: Gene expression data from GSE250323.
- Libraries: XGBoost, Jupyter Notebook, and Seaborn for analysis and visualization.

---

## 👥 Contributors
- **Saher Pathan** - [GitHub Profile](https://github.com/Saherpathan)  
- **Khushi Mohurle** - [GitHub Profile]()
- **Sayali Warkade** - [GitHub Profile]()

[**Return**](#-quick-links)

---
