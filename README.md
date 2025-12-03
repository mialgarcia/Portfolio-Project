# Mia Garcia — Portfolio


**Mia Garcia**

Finance Major at the University of South Florida

Hi! I'm Mia. I enjoy learning how financial systems work and developing skills that will help me in corporate finance and investment analysis. This repository is part of my "Launching Your Digital Brand" project, where I'm building a professional online presence and getting comfortable using GitHub.

---

## Project Reflection

GitHub Copilot helped me jump-start multiple functions in my data cleaning script, especially load_data(), clean_column_names(), and parts of handle_missing_values(). By providing Copilot with clear comments and partial code prompts, I was able to get useful starter code that followed standard Python practices. For example, when I wrote a comment describing the need to standardize column names, Copilot generated a function using .str.lower() and .str.replace() that I could then refine to fit my dataset.

While Copilot’s suggestions were useful, I made several modifications to ensure the code met my requirements. In clean_column_names(), I added a step to strip whitespace from column names and ensured that all spaces were replaced with underscores for consistent formatting. For handle_missing_values(), Copilot initially suggested dropping rows with missing values entirely, but I decided to fill numeric columns with zeros and trim whitespace from text columns instead, which preserved more usable data. In remove_invalid_rows(), I added checks for negative prices and quantities to ensure the dataset was accurate and realistic.

Through this project, I learned how essential clean and well-organized data is in Python. Using pandas, I gained hands-on experience standardizing column names, managing missing data, and removing invalid rows. I also learned how to write clear comments that explain both what and why certain cleaning steps are necessary, which makes code more understandable for others and for myself in the future. This project taught me how to use Copilot as a tool rather than a crutch. Its ability to quickly generate boilerplate code is a huge time-saver, but I learned that I still need to carefully review and modify its suggestions. For instance, Copilot suggested dropping all rows with missing data in handle_missing_values(), which would have caused the loss of important information. Adjusting that logic taught me the importance of human judgment in data cleaning.

---

## Contact

- **Email:** mialauragarcia@usf.edu
- **GitHub:** https://github.com/mialgarcia/Portfolio-Project

---

## Projects

- **Launching Your Digital Brand** — A portfolio README and simple static site to present projects and professional background.

