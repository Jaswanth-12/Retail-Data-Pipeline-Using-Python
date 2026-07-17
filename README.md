# Retail Data Pipeline

A simple, modular data engineering project that processes retail sales data by combining database records with external files.

---

## 📌 Features

* **Multi-Source Data:** Combines PostgreSQL database records with external Parquet files.
* **Modular Design:** Clear code structure separating database, ETL, and transformation functions.
* **Logging:** Output logged to `logs/pipeline.log` for easy tracking.
* **Testing:** Automated tests using `pytest`.

---

## 📂 Project Structure

```text
retail-data-pipeline/
├── config/
│   └── settings.py          # Database & path configurations
├── data/
│   ├── input/               # Raw input files (extra_data.parquet)
│   └── output/              # Final processed data
├── logs/
│   └── pipeline.log         # Execution logs
├── pipeline/
│   ├── database.py          # Database operations
│   ├── etl.py               # Main ETL flow
│   ├── file_handler.py      # File reading/writing logic
│   └── transformations.py   # Business logic & data cleaning
├── tests/                   # Unit tests
```

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and build upon this project for your own learning or professional portfolio work.

---

## 👤 About Me

Hi, I'm **Jaswanth Sai Grandhisila**! I am an **Assistant System Engineer (ASE) at TCS**, specializing in data infrastructure and modern data engineering methodologies. I have a strong passion for transforming raw, unorganized datasets into clean, optimized production environments that power analytics and data-driven decision-making.

Let's connect and talk data engineering!
* **GitHub:** [https://github.com/Jaswanth-12](https://github.com/Jaswanth-12)
* **LinkedIn:** [https://www.linkedin.com/in/jaswanth-sai-grandhisila-1798b2260/](https://www.linkedin.com/in/jaswanth-sai-grandhisila-1798b2260/)
