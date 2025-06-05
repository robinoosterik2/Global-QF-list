# 🌍 Global Qualification Frameworks (QFs)

This repository is a curated reference of **national and regional qualifications frameworks** from around the world. It includes level breakdowns, mappings to major frameworks like the **European Qualifications Framework (EQF)** or **UNESCO ISCED**, and alignment notes where available.

The goal is to provide a **centralized, open-source knowledge base** for understanding how educational and vocational qualifications compare globally.

---

## 📘 What’s Included

- ✅ Descriptions of qualification frameworks from multiple countries/regions
- ✅ Level-by-level breakdowns (e.g., Level 1–8/12/etc.)
- ✅ Crosswalks to EQF or ISCED where applicable
- ✅ Coverage of both **academic** and **vocational/technical** routes
- ✅ Source references to official agencies or frameworks (UNESCO, CEDEFOP, SCQF, etc.)

---

## 🌐 Frameworks Covered

Examples include:

- 🇪🇺 [European Qualifications Framework (EQF)](https://europa.eu/europass/en/description-eight-eqf-levels)
- 🇬🇧 [Regulated Qualifications Framework (RQF, UK)]
- 🏴 [Scottish Credit and Qualifications Framework (SCQF)](https://scqf.org.uk/)
- 🇨🇦 [Canadian Qualification Framework (CICIC)]
- 🇯🇲 [Caribbean Qualifications Framework (CQF, CARICOM)]
- 🌍 [UNESCO ISCED](http://uis.unesco.org/en/topic/international-standard-classification-education-isced)

> For the full list, see the `data/` directory.

---

## 📂 Structure

```text
/
├── README.md
├── LICENSE
├── data/
│   ├── eqf.md
│   ├── scqf.md
│   ├── cqf.md
│   ├── [country_code]_[framework].md
│   └── ...
└── sources/
    └── references.md
```

## 🤝 How to Contribute

We welcome contributions from anyone who has access to information about national and regional qualifications frameworks. If you have information about a framework that is not included in this repository, please submit a pull request.

As right now this project is being maintained by me, it is very welcome to help, as I am not an any where near an export on this topic.

### 🛠️ Steps to Contribute

1. Fork the repository
2. Create a new branch
country specific branch name: 
```bash
git checkout -b add-[framework]-[country]
```

framework specific branch name: 
```bash
git checkout -b add-[framework]
```

1. Add the new framework to the `data/` directory
2. Link official sources (e.g., UNESCO, CEDEFOP, SCQF, etc.) in the `sources/` directory
3. Update the `list.md` file
4. Submit a pull request

## 📬 Contact

Feel free to open an issue or discussion if you have questions, suggestions, or frameworks you'd like us to include.